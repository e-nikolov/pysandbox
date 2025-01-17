# PySandbox: Run Python in your Web Application

For installation and usage instructions see [user docs](https://bugzpodder.github.io/pysandbox)

## Introduction

PySandbox is a library that helps developers create client-side Python-powered web applications.  It is inspired by [PyScript](https://github.com/pyscript/pyscript) and built on top of [Pyodide](https://github.com/pyodide/pyodide) and [Polyscript](https://github.com/pyscript/polyscript).

The main features of PySandbox are:
  - Exports simple JS classes that can be used in any JS framework or html page.
  - Web Worker ready.  If your site is cross origin isolated, Web Workers can be used to execute python code.
  - Restricted mode.  Enabling this mode will disallow python scripts access to js.document.
  - Custom modules support.  You can define your own modules that are accessible in the codeblock.
  - Input/Output support.  You can easily pass data in and out of the python code blocks and display images and/or adding 3rd party JS integration.
  - Helper methods for formatting code, find imports and installing modules in Pyodide.


## Contributing

Project bootstraped with `tsup` and `esbuild`.  `Node.js 16.x/18.x` is recommended for development.

`yarn dev` to make changes and make development build

`yarn serve` to serve `/examples` for testing your changes

`yarn format` & `yarn format:py` to run code formatting

`/docs` contains documentation.  Run `yarn format` in docs to format changes.
