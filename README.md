# LaTeX template for TUM theses

This is a LaTeX template created according to the guidelines for TUM informatics theses in WS 2022. **Always check the [current formatting guidelines][thesis-guidelines] before you hand in.** See [`build/main.pdf`][sample-pdf] for an example PDF created with this template.

Comments & contributions are welcome!

## Quickstart

 * [Download][template-download] and extract the template, or upload it to an online editor such as [Overleaf][overleaf] or [TUM ShareLaTeX][tum-sharelatex]. If you prefer to use Git, just clone/fork the repository.
If your editor supports compiling LaTeX, set it up to use `pdflatex` and `biber`. Set the master document to `main.tex`. Alternatively, you can use the provided Makefile to generate a PDF in the `build` directory (requires `latexmk`).
 * To use Visual Studio Code install the [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) extension. Then, as soon as you click on "Save," it automatically compiles your thesis without you having to configure anything.
 * Look for `TODO` comments in the provided files. Start at `main.tex`.

If you are new to LaTeX, the [Overleaf Documentation][overleaf-learn] or the [LaTeX Wikibook][latex-wikibook] might help.

If you still have problems with the template, feel free to [create an issue][issue]. For general LaTeX questions, use [TeX StackExchange][tex-se].

## License

[![Creative Commons License][license-image]][license]

This template is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License][license], meaning that:

 * You can share (copy, redistribute) and adapt (remix, transform, build upon) this template for any purpose, even commercially.
 * If you share the template or a modified (derived) version of it, you must attribute the template to the original authors ([Florian Walch and contributors][template-authors]) by providing a [link to the original template][template-url] and indicate if changes were made.
 * Any derived template has to use the [same][license] or a [compatible license][license-compatible].

The license **applies only to the template**; there are no restrictions on the resulting PDF file or the contents of your thesis.

[license-compatible]: https://creativecommons.org/compatiblelicenses
[license-image]: https://i.creativecommons.org/l/by-sa/4.0/88x31.png
[license]: https://creativecommons.org/licenses/by-sa/4.0/
[overleaf]: https://www.overleaf.com/
[overleaf-learn]: https://www.overleaf.com/learn
[tum-sharelatex]: https://sharelatex.tum.de/ldap/login
[template-authors]: https://github.com/TUM-Dev/tum-thesis-latex/graphs/contributors
[tex-se]: https://tex.stackexchange.com/
[thesis-guidelines]: https://www.cit.tum.de/en/cit/studies/students/thesis-completing-your-studies/informatics/
