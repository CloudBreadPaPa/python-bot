# python-bot and QnA maker
Technical prep. project for bot framework and QnA maker

# Getting Started
TODO: Setup python 3.8+ environment and run python or notebook code

## Echo bot
1. Clone this repo.
2. Run dw-echo-bot directory python file

## QnA maker client SDK - automated provision to publish
1. Clone this repo.
2. Run client-sdk directory client.ipynb notebook file

## QnA maker evaluation
1. Clone this repo.
2. Follow [QnA maker guide paper](https://docs.microsoft.com/en-us/azure/cognitive-services/QnAMaker/how-to/test-knowledge-base)
3. Run batchtesting command
```
batchtesting.exe batch-test-data-1.tsv https://YOUR-RESOURCE-NAME.azurewebsites.net ENDPOINT-KEY out.tsv
```
4. Review evaluated - output tsv file result

# Build and Test
Compatible with Python 3.8