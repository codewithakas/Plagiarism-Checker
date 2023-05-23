# Plagiarism-Checker

This repo consists of a source code of a Python script which detects plagiarism in a textual document using **cosine similarity**.

## How is it Done?

Plagiarism detection on textual data is a relatively straightforward task. Since computers excel at processing numerical data, we convert the raw text into vectors, which are numerical arrays. By leveraging basic vector operations, we can compute the similarity between two text documents.
This repository provides a simple example demonstrating how to perform such similarity calculations.
Feel free to modify and adapt the provided text to suit your needs.

## Getting Started

To get started with the code on this repo, you need to either *clone* or *download* this repo into your machine as shown below;

```bash
git clone https://github.com/Kalebu/Plagiarism-checker-Python
```

## Dependencies

Before you begin playing with the source code, you might need to install dependencies just as shown below;

```bash
pip3 install -r requirements.txt
```

## Running the App

In order to execute this code, ensure that your project directory contains the textual documents you want to analyze, and make sure they have the .txt extension. When you run the script, it will automatically load all the documents with that extension and proceed to calculate the similarities between them. The process is outlined below:

1.Load the textual documents from the project directory.

2.Convert the raw text data into vector representations.

3.Utilize vector operations to compute the similarities between the documents.

4.Generate a similarity matrix or other output to illustrate the relationships between the documents.

5.Remember to modify and adapt the code as needed to suit your specific requirements.
```bash
$-> cd Plagiarism-Checker
$ Plagiarism-Checker-> python3 app.py
('Chiradip.txt', 'juma.txt', 0.5465972177348937)
('Akash.txt', 'john.txt', 0.14806887549598566)
('Jhonny.txt', 'juma.txt', 0.18643448370323362)

```

## Pull Requests

If you have something to add, I welcome pull requests on improvement; your helpful contribution will be merged as soon as possible.

## Give it a Star

If you find this repo useful, give it a star so that many people can get to know it.


