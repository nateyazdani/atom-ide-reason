# ide-reason package

ReasonML/OCaml language support for Atom-IDE.

Using [ocaml-language-server](https://github.com/freebroccolo/ocaml-language-server) under the hood, the same as [vscode-reasonml](https://github.com/reasonml-editor/vscode-reasonml/).

Thanks for [@freebroccolo](https://github.com/freebroccolo) and all of [ocaml-language-server](https://github.com/freebroccolo/ocaml-language-server)'s contributors!

![](https://github.com/reasonml-editor/atom-ide-reason/blob/master/docs/capture.gif?raw=true)

## Requirements

* ocaml
* [merlin](https://github.com/ocaml/merlin)
* [atom-ide-ui](https://atom.io/packages/atom-ide-ui) or [nuclide](https://atom.io/packages/nuclide)
* language syntax package
  * [language-ocaml](https://atom.io/packages/language-ocaml) for ocaml
  * [language-reason](https://atom.io/packages/language-reason) for reason

## Custom configuration per project

You can add configuration per project by `.atom/ide-reason.json`, which could be generated by command `ide-reason:Generate Config`.
