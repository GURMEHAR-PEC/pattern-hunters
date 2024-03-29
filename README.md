# Pattern Hunters

Pattern Hunters is a browser extension designed to identify dark patterns on websites. This project includes a browser extension, a web scraper, and an NLP model trained to recognize dark patterns in website content.

## Table of Contents

- [Introduction](#introduction)
- [Directory Structure](#directory-structure)
- [Getting Started](#getting-started)
- [Contibutors](#contributors)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [Demonstration](#demonstration)

## Introduction

A dark pattern is a user interface carefully crafted to trick users into doing a certain action that they wouldn’t have done otherwise. Dark patterns are of many types such as forced action, nagging, confirm shaming, interface interference, false urgency, and basket sneaking to name a few. We aim to solve this problem by providing a solution that can detect dark patterns on various e-commerce digital platforms to keep our consumers safe through a browser extension by highlighting the dark patterns and providing the users with knowledge about them. It would help protect users from the malicious intentions of developers who aim to increase their profits through these malpractices. We aim to create a transparent digital world.

![proposed-workflow](https://github.com/ItsPranavz/pattern-hunters/blob/main/proposed-workflow.png?raw=true)

## Directory structure
```bash
├── Dark Pattern
│   ├── Augmentation --> This module contains code for data augmentation using contextualized word embeddings.
|   |
│   ├── Dataset --> Holds the dataset in TSV format used for training the NLP model.
|   |
│   ├── Extention --> HTML, CSS, and JavaScript files of the browser extension.
│   │   
│   ├── Models --> Contains pickled (.pkl) files of the trained NLP model.
|   |
│   ├── Backend
│   |    ├──DPBHscrapper --> Contains files for the web scraper extracting text from webpages
|   |    ├──app.py --> File to to run extention on local machine.
|   |
│   ├── Training --> Code files used to train the NLP model.
```

## Installation

To get started with Pattern Hunter, follow these steps:

1. Clone the repository: `git clone https://github.com/ItsPranavz/pattern-hunters.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Change working directory `cd backend`
4. Run backend server `python app.py`
5. Load `extension` folder in your browser.
6. Active the extension on your browser.

## Contributors

- [Pranav Sharma](https://github.com/ItsPranavz)
- [Akanksha Narula](https://github.com/AkankshaNarula)
- [Arnav Singh](https://github.com/astra1503)
- [Gurmehar Singh](https://github.com/GURMEHAR-PEC)
- [Gaurav Gupta](https://github.com/GauravGupta993)


## Documentation

(https://github.com/ItsPranavz/pattern-hunters/edit/main/documentation)

## Demonstration
[View video demonstration of the project.](https://drive.google.com/file/d/1OIGqgTj8utMk471UxyuvoNg_nASMuEMF/view?usp=sharing)
