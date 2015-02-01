# MTA-ToastyRPG
Niedokończony gamemode pisany prawie rok temu na potrzeby serwera "Serwer Polskiego Życia". W repozytorium są wszystkie skrypty ukończone, zaczęte i niedokończone oraz te ukończone i niewprowadzone.

# Instalacja
Instalacja jest bardzo prosta i przyjemna, wystarczy podmienić plik acl.xml z istniejcym, albo podmienić skrawek kodu odpowiadający za prawa dla skryptów i grup.

# Komendy i bindy
Komend nie ma prawie wcale, wszystko starałem się robić w GUI, dla każdej frakcji panel jest pod klawiszem F1, trzeba być w odpowiednim teamie. Aby do niego dołączyć, wystarczy wpisać /joinwork.

Komendy:


/towar - sprawdza towar danego gracza (elementData ustawione na gracza o kluczu "towar") (Policja)


/dowod - otwiera dowód osobisty


/ulecz - leczy gracza znajdującego się do 20m od nas (Pogotowie)


/score - sprawdza score


/ascore - dodaje punkty score (Administrator)


/cywil - "wylogowujemy" się z frakcji (przechodzimy do teamu Cywile)


/czat - czyści czat (Administrator)


/lpanel - otwiera panel lidera frakcji


/takceptuj - akceptuje tankowanie (elementData "fuel")

# Frakcje
Aby można było otworzyć panel lidera frakcji, gracz musi mieć ustawioną odpowiednią elementDatę. Dla poszczególnych frakcji są to:

Pomoc Drogowa: lider:pd


Policja: lider:policja


Pogotowie: lider:pogotowie


Urząd: lider:urzad


Taxi: lider:taxi


# Braki w skryptach

Jest ich kilka, nie ma np. panelu dla administratora do przydzielania liderów frakcji dla graczy.
Brak też jakiejkolwiek pracy dorywczej, jedyna jaka była - pochodziła z internetu i postanowiłem nie dołączać jej do publicznej wersji tego skryptu. Zbugowany jest także skrypt na ID graczy (po restarcie skryptu ID się dublują), zalecam użycie skryptu na ID z XyzzyRP https://github.com/lpiob/MTA-XyzzyRP/blob/master/resources/%5BXyzzyRP%5D/lss-core/id_graczy.lua (wystarzy podmienić kod).

# Autorzy
Tostuch - skrypty
