# Basic template for group papers

Using the `achemso` class and allowing cross-references between the main text and supporting information.

## Usage

- To compile: run `latexmk article`
- This will produce `article.pdf`, and the supporting info will be compiled into `output-subdoc/supporting.pdf`
- To remove all generated files, run `latexmk -C article` (or `latexmk -c article` to keep the PDF)
