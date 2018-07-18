# Rozpoznawanie czy na zdjęciu jest  pies czy kot

Program uczący się ze zbioru testowego plików .jpg ze zdjęciami zwierząt z informacją czy na zdjęciu jest pies czy kot oraz potrafiący na podstawie wyuczonych wartości rozpoznawać zwierze na zdjęciach testowych.

### Zastosowany algorytm
Za pomocą biblioteki tesorflow do uczenia maszynowego w pythonie oraz nakładki keras, która ułatwia w znacznym stopniu budowanie sieci neuronowych można w prosty sposób binarnie wyszkolic program do rozpoznawania przedmiotów na zdjęciu. Keras ułatwia budowanie konwolucyjnych sieci neuronowych do procesowania zdjęć.

### Wymagane środowisko i biblioteki
 - Python 3.6 (najlepiej Anaconda)
 - numpy
 - keras
 - tensorflow

### Korzystanie

Skrypty umieszczone muszą być w folderze razem z folderem zawierającym pliki treningowe.

Aby rozpocząć trenowanie należy wywołać w folderze zawierającym:
```sh
python main.py
```

Aby rozpocząć testowanie należy wywowałać w folderze zawierającym:
```sh
python predict.py
```
Aby zmienić plik, na którym jest testowany algorytm należyw pliku predict.py podmienić ścieżkę, z której jest pobierane zdjęcie.