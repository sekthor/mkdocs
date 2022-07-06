# Features

This page is to test some of the features of `mkdocs` and the `material` theme.

## Syntax Highlighting

For example the syntax highlighting of code snippets.
A code snippet looks like this:

```go hl_lines="6" linenums="1"
package main

import "fmt"

func main() {
    fmt.Println("Hello World")
}
```

## Equations

Using MathJax we can use `Tex`-like math mode.

$$
\operatorname{ker} f=\{g\in G:f(g)=e_{H}\}{\mbox{.}}
$$

## Mermaid Diagrams

``` mermaid
graph LR
  A[Start] --> B{Error?};
  B -->|Yes| C[Hmm...];
  C --> D[Debug];
  D --> B;
  B ---->|No| E[Yay!];
```

## Footnotes

This is a text that has footnotes[^1].
At the end of the page there will be a footnote providing details to the previous sentence.

[^1]: In this footnote, there is some extra info

Some more text.

