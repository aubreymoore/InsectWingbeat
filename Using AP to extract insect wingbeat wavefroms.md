# Using AP to Extract Insect Wingbeat Waveforms

## Installation

* Install powershell
* Install SoX
* Install AP
    * ~/.local/share/AP

## Recognizer

A recognizer config file for insect wingbeat waveforms is included in this repo as **Ecosounds.GenericRecognizer.Moore.yml**. This recognizer is based upon 
* **~/.local/share/AP/ConfigFiles/RecognizerConfigFiles/Truskinger.PetaurusBreviceps.yml**.

The commandline to run AP with this recognizer is:

```
AP audio2csv test.wav Ecosounds.GenericRecognizer.Moore.yml ./myoutput
```


