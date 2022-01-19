# cun

public static void main(String[] args){<br>
    Cun cun=new Cun("word=hello world;");<br>
    System.out.print(cun.get("word"));<br>
}<br>
out hello world<br>
public static void main(String[] args){<br>
    Cun cun=new Cun("word=hello world;function(){return 0;}");<br>
    System.out.print(cun.get("function()"));<br>
}<br>
out: return 0<br>

