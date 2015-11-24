public class Magpie2
{
    public String getGreeting()
    {
        return "Hi I'm Carchbot \nDid you see that last Penn State game?";
    }
    public String getGreetingResp(String state)
    {
        String response = "";
        if(response.equalsIgnoreCase(yes)) ||
          (response.equalsIgnoreCase(yeah)) ||
          (response.equalsIgnoreCase(yup)) ||
          (response.equalsIgnoreCase(Sadly)) ||
          (response.equalsIgnoreCase(It was a great game)))
        {
            return "Cool, I love football";
        }
        else{ return "Oh, nevermind";}
    }
    
        
    public String getResponse(String statement)
    {
        String response = "";
        if (statement.indexOf(" no ") >= 0)
        {
            response = sayNo();
        }
        else if (statement.indexOf("mother") >= 0
                || statement.indexOf("father") >= 0
                || statement.indexOf("sister") >= 0
                || statement.indexOf("brother") >= 0
                || statement.indexOf("mom") >= 0
                || statement.indexOf("dad") >= 0
                || statement.indexOf("aunt") >= 0
                || statement.indexOf("uncle") >= 0
                || statement.indexOf("cousin") >= 0
                || statement.indexOf("grandma") >= 0
                || statement.indexOf("grandpa") >= 0
                || statement.indexOf("daughter") >= 0
                || statement.indexOf("son") >= 0
        {
            response = "Tell me more about your family.";
        }
        else if (statement.indexOf("win") >= 0) { response = "There are winners and there are non-winners";}
        else if (statement.indexOf("work") >= 0) { response = "Do your work";}
        else
        {
            response = getRandomResponse();
        }
        return response;
    }
    
    private String sayNo(){
        int whichNoResp = (int)(Math.random() * 4);
        String response = "";
        if (whichNoResp == 0) {response = "Why so negative?";}
        else if (whichNoResp == 1) {response = "Calm down";}
        else if (whichNoResp == 2) {response = "Settle down my little trooper";}
        else if (whichNoResp == 3) {response = "Rellaaxxxx";}

        return response;
       }
    private String getRandomResponse()
    {
        double r = Math.random();
        int whichResponse = (int)(r * 4);
        String response = "";
        
        if (whichResponse == 0)
        {
            response = "Nice";
        }
        else if (whichResponse == 1)
        {
            response = "Hmmm.";
        }
        else if (whichResponse == 2)
        {
            response = "Do you really think so?";
        }
        else if (whichResponse == 3)
        {
            response = "You don't say.";
        }
        else if (whichResponse == 4)
        {
            response = "It's Ryder or it's wrong";
        }
        return response;
    }
}
