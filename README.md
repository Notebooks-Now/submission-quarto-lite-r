# Notebooks Now! Submission Template

This submission template is for a markdown-based publication using R code cells, as well as supporting data, bibliography, and Quarto build configuration. It is based upon a new type of project in Quarto, Manuscripts. 

Get started with Quarto and Manuscript projects here: <https://quarto.org/docs/manuscripts/>.

## Source file

The primary source file for this template is a Quarto markdown article. This file uses inline code cells to produce specific figures within the document. The HTML version of the article hides any inline code used to generate the article, but will include links that allow readers to see the code behind any computations.

## Supporting material

### Bibliography

Bibliography entries may be specific in the document as described in the [Quarto documentation](https://quarto.org/docs/authoring/footnotes-and-citations.html#bibliography-files). 

## Quarto configuration

Configuration for the example is provided by a YAML block that appears in the document (index.qmd) front matter. In addition, there is a `_quarto.yml` file which provides project level configuration.

## Building output artfiacts

To build PDF/JATS output from your source data, you must have the Quarto CLI installed - you can download or learn about installation at <https://quarto.org/docs/download/>

Then render the article using

```
quarto render
```
