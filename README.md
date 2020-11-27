[![Marketplace Version](https://vsmarketplacebadge.apphb.com/version/vscode-javacc21.svg "Current Release")](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-javacc21)

# JavaCC 21 Tools for Visual Studio Code

## Description

This Visual Studio Code extension provides support for [JavaCC 21](https://github.com/javacc21/javacc21) development.

Today only [JavaCC 21](https://github.com/javacc21/javacc21) `syntax coloration` is available:

 * for Java Legacy like options, PARSER_BEGIN:

![PARSER_BEGIN syntax coloration](doc/images/parser-begin-syntax-coloration.png)


 * for JavaCC 21 INJECT:

![INJECT syntax coloration](doc/images/inject-syntax-coloration.png)

But once [JavaCC 21](https://github.com/javacc21/javacc21) will support fault tolerant parsing, it will open the door to provide advanced features like validation, completion, hover, navigation by consuming a Language Server which will use the fault tolerant JavaCC grammar AST to support those features.