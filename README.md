download-papers
======================
[![License](https://poser.pugx.org/badges/poser/license.svg)](./LICENSE)

This scripts downloads .pdf files from formatted .xlsx files, via DOI.

## Table of content

- [Pre-requisites](#pre-requisites)
    - [Python libraries](#python-libraries)
- [Installation](#installation)
    - [Clone](#clone)
    - [Download](#download)
- [Built With](#built-with)
- [How To Use](#how-to-use)
- [Author](#author)
- [Organization](#organization)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Pre-requisites

### Python libraries

```sh
  $ sudo apt install -y python3-pip
  $ sudo pip3 install --upgrade pip
```

```sh
  $ sudo pip3 install -U scidownl
  $ sudo pip3 install argparse
  $ sudo pip3 install openpyxl
  $ sudo pip3 install xlsxwriter
```

## Installation

### Clone

To clone and run this application, you'll need [Git](https://git-scm.com) installed on your computer. From your command line:

```bash
  # Clone this repository
  $ git clone https://github.com/glenjasper/download-papers.git

  # Go into the repository
  $ cd download-papers

  # Run the app
  $ python3 download_papers.py --help
```

### Download

You can [download](https://github.com/glenjasper/download-papers/archive/master.zip) the latest installable version of _download-papers_.

## Built With

* [SciDownl](https://github.com/Tishacy/SciDownl): Download pdfs from Scihub via DOI.

## How To Use

```sh  
  $ python3 download_papers.py --help
  usage: download_papers.py [-h] -i INPUT_FILE [-o OUTPUT] [--version]

  This scripts downloads .pdf files from formatted .xlsx files, via DOI.

  optional arguments:
    -h, --help            show this help message and exit
    -i INPUT_FILE, --input_file INPUT_FILE
                          .xlsx file that contains the DOIs
    -o OUTPUT, --output OUTPUT
                          Output folder
    --version             show program's version number and exit

  Thank you!
```

## Author

* [Glen Jasper](https://github.com/glenjasper)

## Organization
* [Molecular and Computational Biology of Fungi Laboratory](https://sites.icb.ufmg.br/lbmcf/index.html) (LBMCF, ICB - **UFMG**, Belo Horizonte, Brazil).

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.
