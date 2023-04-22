#Lab Report 2
---

##Part 1: StringServer
Code:
```
import java.io.IOException;
import java.net.URI;

class Handler implements URLHandler {
    String statement = "";

    public String handleRequest(URI url) {
        if (url.getPath().equals("/")) {
            return String.format(statement);
        } else if (url.getPath().equals("/add-message")) {
            String[] parameters = url.getQuery().split("=");
            if (parameters[0].equals("s")) {
                statement += "\n" +parameters[1];
            }
            
            return String.format(statement);
        } else {
            return "404 Not Found!";
        }
    }
}

class StringServer {
    public static void main(String[] args) throws IOException {
        if(args.length == 0){
            System.out.println("Missing port number! Try any number between 1024 to 49151");
            return;
        }

        int port = Integer.parseInt(args[0]);

        Server.start(port, new Handler());
    }
}
```
![Image](Screenshot 2023-04-22 at 1.38.45 PM.png)
*Added the words "Words" and "Haribo"
![Image](Screenshot 2023-04-22 at 1.40.00 PM.png)
*Added the word "Chrome"

1. For both screenshots the main method was initailly called to start the server and both would call the handler method which would look for the path the user entered.
2. For both screenshots the relevant arguments for the main method is an argument the user passes which would be the port number and for handler would be the word the user would pass in the form add-message?s=[WORD]. The relevant fields are int port which hold the port number, String statement which holds the words the user passes in, and String[] parameters which holds the arguments the user passes in and s.
3. In the first screenshot the values of statement change with Haribo added onto it with a new line before and parameters would also include Haribo at parameters[1]. For the second screenshot the values of statement change with a new line added before the Chrome is added on the String and parameters would have Chrome at parameters[1].


##Part 2:
