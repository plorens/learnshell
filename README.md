# learnshell

Ważne skróty klawiszowe
CTRL+D lub CTRL+C - przerwanie wykonywania aktualnie działającej aplikacji
Kursór do góry (strzałka) - poprzednia komenda
Kursór w dół (strzałka) - następna komenda
SHIFT + PageUP - przewinięcie ekranu konsoli do góry
SHIFT + PageDown - przewinięcie ekranu konsoli w dół
Podstawowe komendy

```sh
$ ls
$ ls -la
$ ls --help
```

ls
wylistowanie zawartości obecnego folderu
ls -la
wylistowanie zawartości obecnego folderu ze szczegółami i ukrytymi plikami
ls --help
wyświetlenie skróconej pomocy dla np. programu ls
man ls
wyświetlenie dokumentacji dla programu ls. Oczywiście ls możesz zastąpić inną nazwą aplikacji
mkdir nazwa
utworzenie katalogu o nazwie "nazwa"
cd nazwa
zmiana katalogu - przejście do katalogu o nazwie "nazwa"
cd ..
powrót do nadrzędnego katalogu
cp zrodlowy.txt cel.txt
utworzenie kopii pliku zrodlowy.txt pod nazwą cel.txt
mv zrodlowy.txt katalog/
przeniesienie pliku zrodlowy.txt do folderu katalog/
touch plik.txt
utworzenie pustego pliku o nazwie plik.txt
wget http:// adres-serwera.pl/plik.zip
pobranie pliku z sieci i zapisanie go w bierzącym folderze
rm plik.txt
usunięcie pliku plik.txt
du -hs katalog/
wyświetlenie powierzchni zajmowanej przez folder katalog i wszystkie pliki w num umieszczone
date
aktualna data i czas
uptime
wyświetla w kolejności: aktualną godzinę, uptime serwera, liczba zalogowanych użytkowników oraz za load average; średnie obciążenie w ciągu ostatniej minuty, 5 minut, 15 minut
free -m
informacje o wykorzystaniu pamięci w megabajtach, pierwsza linia (Mem:) odnośi się do pamięci RAM, druga (Swap:) informuje o pamięci wymiany zainstalowanej na dysku twardym.
total - zainstalowana pamięć
used - wykorzystana pamięć
free - dostępna pamięć
ps
liczba uruchomionych procesów, bardziej szczegółowe informację, program zwróci po dodaniu parametru aux czyli ps aux
hostname -i
akutualna nazwa hosta oraz adres IP
uname -a architektura systemu
