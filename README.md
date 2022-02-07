# cun
Cun类 是数据结构解释器，在 cun 数据结构解释器中，数据可以存在二种格式: 格式1 var=data; 格式2 var2{}
可以数据让更轻松地对象化是Cun解释器类存在的原因，同时也让数据变得更清晰，更省空间。

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

