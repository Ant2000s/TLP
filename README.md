![Alt text](https://g.gravizo.com/source/svg/c1?https%3A%2F%2Fraw.githubusercontent.com%2FAnt2000s%2FTLP%2Fmain%2FREADME.md)
<details> 
<summary></summary>
c1
  digraph G {
    END -> B [label="space"];
    END -> A [label="A-Z, a-z, 0-9"];
    S -> B [label="space"];
    B -> A [label="A-Z, a-z, 0-9"];
    A -> A [label="A-Z, a-z, 0-9"];
    A -> S [label="A-Z, a-z, _"];
  }
c1
</details>

![Alt text](https://g.gravizo.com/source/svg/c2?https%3A%2F%2Fraw.githubusercontent.com%2FAnt2000s%2FTLP%2Fmain%2FREADME.md)
<details> 
<summary></summary>
c2
  digraph S {
    END -> H [label="space"];
    END -> G [label="F, f, L, l"];
    END -> F [label="0-9"];
  }
c2
</details>
