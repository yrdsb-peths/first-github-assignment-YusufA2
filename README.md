public String teenTalk(String sentence)
{
    String result = "";
    for (int i = 0; i < text.length(); i++)
    {
        String letter = ""+text.charAt(i);
        if (!letter.equals("2"))
        {
            result += text.charAt(i);
        }
        else
        {
            result += "to";
        }
    }
    return result;

}
