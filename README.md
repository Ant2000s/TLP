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
    END -> E [label="-[1-9], 1-9"];
    END -> C [label="0-9"];
    END -> A [label="0-9"];
    END -> S [label="0-9"];
    H -> G [label="F, f, L, l"];
    G -> F [label="0-9"];
    G -> E [label="-[1-9], 1-9"];
    F -> F [label="0-9"];
    F -> E [label="-[1-9], 1-9"];
    E -> D [label="e, E"];
    D -> C [label="0-9"];
    D -> B [label="."];
    C -> C [label="0-9"];
    C -> B [label="."];
    B -> A [label="0-9"];
    B -> S [label="0, 1-9"];
    A -> A [label="0-9"];
    A -> S [label="1-9"];
    S -> H [label="space"];
  }
c2
</details>

![Alt text](https://g.gravizo.com/source/svg/c3?https%3A%2F%2Fraw.githubusercontent.com%2FAnt2000s%2FTLP%2Fmain%2FREADME.md)
<details> 
<summary></summary>
c3
  digraph A {
END -> H [label="space"];
    END -> G [label="F, f, L, l"];
    END -> F [label="0-9"];
    END -> E [label="-[1-9], 1-9"];
    END -> C [label="0-9"];
    END -> A [label="0-9"];
    END -> S [label="0-9"];
    H -> G [label="F, f, L, l"];
    G -> F [label="0-9"];
    G -> E [label="-[1-9], 1-9"];
    F -> F [label="0-9"];
    F -> E [label="-[1-9], 1-9"];
    E -> D [label="e, E"];
    D -> C [label="0-9"];
    D -> B [label="."];
    C -> C [label="0-9"];
    C -> B [label="."];
    B -> A [label="0-9"];
    B -> S [label="0, 1-9"];
    A -> A [label="0-9"];
    A -> S [label="1-9"];
    S -> H [label="space"];
    }
c3
</details>

![Alt text](https://g.gravizo.com/source/svg/c4?https%3A%2F%2Fraw.githubusercontent.com%2FAnt2000s%2FTLP%2Fmain%2FREADME.md)
<details> 
<summary></summary>
c4
  digraph AA {
"  store i32 0, i32* %1, align 4" -> "  %1 = alloca i32, align 4";
    }
c4
</details>

