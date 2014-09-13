Phonegap
========  
För att komma på banan med phonegap på osx (förutsätter homebrew):  
### Installation
````
brew install node  
brew install android-sdk
android #installera saker via guit som kommer upp  
sudo npm install -g phonegap  
````
### Skapa och testkör en app  
````
phonegap create hello-world  
cd hello-world  
phonegap run android  
```
Om man har tur så startar appen på den inkopplade android telefonen, har man otur så öppnas den istället i en seg emulator. 
  För att kolla vilka enheter som finns anslutna så kan man köra  
  ```adb devices```  
  finns den inte med där så testa att koppla ur och koppla in telefonen på nytt

##### Disclaimer  
Antagligen kommer det inte funka första gången phonegap run körs - läs isf felmeddelandet och fixa problemet (Kanske får du "Please install Android target X", skriv isf android i terminalen och installera version X)
