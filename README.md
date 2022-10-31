# analysis-template
Template for analysis projects.    

## Getting started
You will need to start by modifying the following files and some of their default settings:
- Change the repository name and description
- `.github/ISSUE_TEMPLATE/*.md` -> change "Asignee" to your Github handle
- `.gitignore` -> The default file is for a Python project, but you should modify as needed
- `CITATION.cff` -> Modify project and author information as appropriate
- `LICENSE` -> This project defaults to an MIT license, but you should modify this file if you wish to use another license for your work.
- `requirements.yml` -> change the project name and dependencies

## Project description
Provide a summary of your project here.

## Citing this work
This could include the same content as your CITATION.cff file, or you would include the citation for an associated publication.
```
Doe J, Doe J. (2001) My project title. Journal name. DOI.
```

## Installation
Include instructions on how to install the dependencies of the project.    
For example:
```
$ git clone https://github.com/j-berg/analysis-template.git
$ cd analysis-template
$ conda env create -f requirements.yml
$ conda activate analysis-template
```

## Operating system
If there are any specifics for running the analysis, outline them here. For instance, a key dependency of the analysis may only be available on Windows, or may only work on an Intel chip.

## Running the analyses
Outline the steps to reproduce the analyses. For example:
1. Preprocess data: Run the `notebooks/preprocess.ipynb` file
2. Generate Figure 1 images: Run the `notebooks/figure1.ipynb` file
3. ...

## Documentation
You may want to utilize the built-in "Wiki" in Github, or you wish to generate your own documentation. A starting directory for this is in `docs`. You can then mount this directory to Github Pages by `Settings` -> `Pages` -> Choose `Deploy from a branch` -> Choose `main` as your branch and `docs` as your directory.

## Getting help
You can provide information on how to contact you, or submit an issue on Github. For example, this template includes template issue forms for `bugs` and `feature requests`. You can provide details on how a user might go about handling this.

## Licensing
Include any licensing terms, or copy and paste the details of the license like so:
```
MIT License

Copyright (c) Author/Company/etc.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
