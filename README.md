#Mahalo for Visual Studio Code
This package includes a syntax definition for [Mahalo](https://mahalo.github.io)
templates. If you follow the previous link you can find more information about
writing applications with the Mahalo framework.

## Features
Currently this extensions only declares the syntax for Mahalo's template language
to help developers by highlighting expressions. Apart from that it inherits from HTML.

If you want syntax highlighting inside HTML attributes you should use single
quotes to indicate that the value is a Mahalo expression. While at runtime
the Mahalo framework does not differentiate between the two this helps the highlighter
and gives developers the opportunity of choosing whether to highlight or not.