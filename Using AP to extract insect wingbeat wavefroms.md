# Using AP to Extract Insect Wingbeat Waveforms

## Installation

* Install powershell
* Install SoX
* Install AP
    * ~/.local/share/AP

## Recording

The SoxX CLI can be used to record audio. For example, the following records a ten-minute mono wav file at 22050 Hz.
```
rec -c 1 -r 22050 testsox.wav trim 0 10:00
```

## Recognizer

A recognizer config file for insect wingbeat waveforms is included in this repo as **Ecosounds.GenericRecognizer.Moore.yml**. This recognizer is based upon 
* **~/.local/share/AP/ConfigFiles/RecognizerConfigFiles/Truskinger.PetaurusBreviceps.yml**.

The commandline to run AP with this recognizer is:

```
AP audio2csv test.wav Ecosounds.GenericRecognizer.Moore.yml ./myoutput
```


