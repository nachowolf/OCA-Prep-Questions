### Given the bits of code below, which of the following fields won't be accessible by the Accessed Class? Choose all that apply. (2)


```
package ocaQuest.mainQuest;

public class AccessLevels {
    public String a = "A";
    protected String b = "B";
    String c = "C";
    private String d = "D";
}


package ocaQuest;

import ocaQuest.mainQuest.AccessLevels;

public class Accessed extends AccessLevels {
    public static void main(String[] args) {
        Accessed level = new Accessed();
        System.out.println(level.a);
        System.out.println(level.b);
        System.out.println(level.c);
        System.out.println(level.d);
    }
}
```


