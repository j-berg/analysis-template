# analysis-template
Template for analysis projects.    
You will need to start by modifying the following files and some of their default settings:
- `.github/ISSUE_TEMPLATE/*.md` -> change "Asignee" to your Github handle
- `.gitignore` -> The default file is for a Python project, but you should modify as needed
- `CITATION.cff` -> Modify project and author information as appropriate
- `LICENSE` -> This project defaults to an Apache 2.0 license, but you should modify this file if you wish to use another license for your work.
- `requirements.yml` -> change the project name and dependencies

## Description
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
$ conda activate xpresspipe
```

## Operating system
If there are any specifics for running the analysis, outline them here. For instance, a key dependency of the analysis may only be available on Windows, or may only work on an Intel chip.

## Running the analyses
Outline the steps to reproduce the analyses. For example:
1. Preprocess data: Run the `notebooks/preprocess.ipynb` file
2. Generate Figure 1 images: Run the `notebooks/figure1.ipynb` file
3. ...

## Getting help
You can provide information on how to contact you, or submit an issue on Github. For example, this template includes template issue forms for `bugs` and `feature requests`. You can provide details on how a user might go about handling this.

## Licensing
Include any licensing terms, or copy and paste the details of the license like so:
```
                                 Apache License
                           Version 2.0, January 2004
                        http://www.apache.org/licenses/

   TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION

   1. Definitions.

      "License" shall mean the terms and conditions for use, reproduction,
      ...
```
