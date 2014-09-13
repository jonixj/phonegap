Phonegap
========  
För att komma på banan med phonegap på osx (förutsätter homebrew):  
### Installation
brew install node  
brew install android-sdk ( kör sedan android - ett gui öppnar som hjälper en att tanka hem androidreleaser och lite annat mög)  
sudo npm install -g phonegap  
### Skapa och testkör en app  
phonegap create hello-world  
cd hello-world  
phonegap run android  
##### Disclaimer  
Antagligen kommer det inte funka - läs isf felmeddelandet och fixa problemet (Kanske får du "Please install Android target X", skriv isf android i terminalen och installera version X)
