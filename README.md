# python-azure-ai-translate
2024-06-07-1  

Translate text using azure ai translate in python


You can use azure 12 months for free, then you have to pay $1 for 1000 images.  
You must move to pay as you go (basic supscription - $0) after first month.  
Be careful **not to go over free amount of units**. especially after 1st month  
More info here: https://github.com/dbojan/python-azure-ocr/  

## create azure resource "Translator"


    Create free azure account
    go to https://portal.azure.com/#home
    click on Translators on the left
    click on + to create new resource in "Translators"
        subscription: something like Azure subscription
        resource group: create new, something like: translator-test
        region: I selected North EU
        name: enter what ever you want
        pricing: select free f0 (S0 tier, 2 million characters per month)

## python
According to https://learn.microsoft.com/en-us/azure/ai-services/translator/quickstart-text-sdk?pivots=programming-language-python:  
pip install azure-ai-translation-text==1.0.0b1

download zip, start bat file. It will translate file 1.txt in the same dir.
You can edit .py file in notepad++



