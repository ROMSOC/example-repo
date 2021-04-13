# Example of a ROMSOC repository

## Summary
This is a typical example of a public repository with the minimal elements required to have a well documented and functional structure open source project hosted in GitHub.

## Description
The minimal structure of the repository should contain at least three elements: i) the source code, ii) a variety of benchmarks (or test-case scenarios), and iii) a documentation information (with installation and running instructions, which could be included also in the ``README.md`` file). No specific requirements are established regarding programing languages, the internal structure of the subfolders, type of license, file formats, or additional contents required for each particular repository.

## Directory structure
All the repositories should include at least the ``README.md`` (markdown file) and  ``LICENSE`` files with the general description and information about the code available in the repository. A possible folder structure of the repository could be desiged as follows:
```
.
├── source
│   └── source files (and subfolders if any)
├── benchmarks
    ├── data files (input)
    ├── result files (output)
│   └── source files (and subfolders if any)
├── documentation
│   └── source files (and subfolders if any)
├── LICENSE
├── README.md
└── .gitignore
```

## Acknowledgments
<img src="/images/EU_Flag.png" alt="EU Flag"  width="150" height="100" />
The ROMSOC project has received funding from the European Union’s Horizon 2020 research and innovation programme under the Marie Skłodowska-Curie Grant Agreement No. 765374.
This repository reflects the views of the author(s) and does not necessarily reflect the views or policy of the European Commission. The REA cannot be held responsible for any use that may be made of the information this repository contains.
