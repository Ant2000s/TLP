![Alt text](https://g.gravizo.com/source/svg/c1?https%3A%2F%2Fraw.githubusercontent.com%2FAnt2000s%2FTLP%2Fedit%2Fmaster%2FREADME.md)
<details> 
<summary></summary>
c1
  digraph G {
    size ="4,4";
    main [shape=box];
    main -> parse [weight=8];
    parse -> execute;
    main -> init [style=dotted];
    main -> cleanup;
    execute -> { make_string; printf};
    init -> make_string;
    edge [color=red];
    main -> printf [style=bold,label="100 times"];
    make_string [label="make a string"];
    node [shape=box,style=filled,color=".7 .3 1.0"];
    execute -> compare;
  }
c1
</details>
