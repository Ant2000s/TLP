![Alt text](https://g.gravizo.com/source/svg/c1?https%3A%2F%2Fraw.githubusercontent.com%2FAnt2000s%2FTLP%2Fmain%2FREADME.md)
<details> 
<summary></summary>
c1
  digraph G {
    main -> parse;
    parse -> execute;
    main -> init;
    execute -> { make_string; printf};
    init -> make_string;
    main -> printf;
    execute -> compare;
  }
c1
</details>
