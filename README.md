# resume

An unnecessarily complicated resume generator.

## Basics

On commit, this repository uses the `resume.tex` LaTeX file to build the resume into a PDF, image for the README, and webpage for GitHub pages.

## Development

Install your favorite LaTex distribution (I recommend [TeX Live](https://www.tug.org/texlive/)) and run `latexmk` to generate a PDF of the resume. Watch with `latexmk -pvc`.

Once installed, you can also leverage tools like the LaTeX Workshop extension in VSCode. (Don't forget to update your path!)

## Result

![A photo of a resume](dist/resume.jpg)

Check out the [PDF](dist/resume.pdf) and [page](https://tneely.github.io/resume/) too!
