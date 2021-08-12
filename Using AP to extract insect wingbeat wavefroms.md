# Using AP to Extract Insect Wingbeat Waveforms

## Installation

* Install powershell
* Install SoX
* Install AP
    * ~/.local/share/AP

## Recognizer

* **~/.local/share/AP/ConfigFiles/RecognizerConfigFiles/Truskinger.PetaurusBreviceps.yml** provides a good starting point because it uses **!harmonics**

```
AP audio2csv test.wav Truskinger.PetaurusBreviceps.yml ./myoutput
```


