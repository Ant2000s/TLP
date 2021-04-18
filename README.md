![Alt text](https://g.gravizo.com/source/svg/c1?https%3A%2F%2Fraw.githubusercontent.com%2FAnt2000s%2FTLP%2Fmain%2FREADME.md)
<details> 
<summary></summary>
c1
  digraph G {
    END -> C;
    C -> S [label="\s"];  
    C -> B [label="A-Z, a-z, 0-9"];
    B -> A [label="A-Z, a-z, 0-9"];
    A -> A [label="A-Z, a-z, 0-9"];
    A -> S [label="A-Z, a-z, _"];
  }
c1
</details>
