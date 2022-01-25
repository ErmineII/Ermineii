At https://codeberg.org/Wezl

Working on the Nib programming language.

> [<img src="https://proglangdesign.net/images/lang/nib.svg" width="20" alt="logo"></img> Nib](https://codeberg.org/Wezl/nib)
>
> A semi-concatenative that extends array language features such as tacit programming and scalar extension.

```d
`factorial example`
.(/ 1 while .[ .([ - 1 /:*) ]) .: fact-iter `loop (functionally) using a tuple (counter / factorial-accumulator)`
.(? ./ .(- 1 fact *:/) .(1))   .: fact-rec  `recursive definition`
.(downto 1 ^.* 1)              .: fact-array
`the product of the range 1..n (product is the multiplication * reduction ^ starting at 1)`
```
