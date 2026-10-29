# **Notatka**

## **Ćw a)**

##### **Dsadd – służy do tworzenia kont użytkowników z poziomu wiersza poleceń.**

dsadd user – tworzenie konta użytkownika.

CN – nazwa obiektu.

OU – jednostka organizacyjna.

DC – składnik nazwy domeny.

\-samid – nazwa logowania użytkownika.

\-pwd – hasło użytkownika.

\-mustchpwd – wymuszenie zmiany hasła przy następnym logowaniu.

\-hmdir – ścieżka do katalogu domowego.

\-hmdrv – litera dysku katalogu domowego.



##### **CSVDE – importuje wielu użytkowników z pliku tekstowego.**

csvde – narzędzie do importowania i eksportowania danych Active Directory.

\-i – tryb importowania.

\-f – wskazanie pliku.

\-k – pomijanie niektórych błędów podczas importu.

DN – unikalna nazwa obiektu w katalogu.

objectClass – typ obiektu.

sAMAccountName – nazwa konta użytkownika.

givenName – imię użytkownika.

sn – nazwisko użytkownika.

userPrincipalName – pełna nazwa logowania użytkownika.



##### **LDIFDE – importuje i eksportuje obiekty Active Directory.**

ldifde – narzędzie do importowania i eksportowania obiektów Active Directory.

\-i – tryb importowania.

\-f – wskazanie pliku.

\-k – pomijanie niektórych błędów podczas importu.

\-d – wskazanie obiektu lub punktu początkowego wyszukiwania.

\-s – wskazanie serwera.

DN – unikalna nazwa obiektu.

changetype – określa rodzaj zmiany, np. add oznacza dodanie obiektu.

objectClass – typ obiektu.

userAccountControl – określa stan konta i jego ustawienia.



## **Ćw b)**

##### **PowerShell – umożliwia tworzenie użytkowników za pomocą poleceń.**

ADSI – umożliwia dostęp do obiektów Active Directory.

LDAP – protokół dostępu do katalogu.

Create() – tworzy nowy obiekt.

Put() – ustawia wartość atrybutu.

SetInfo() – zapisuje zmiany w Active Directory.

sAMAccountName – nazwa logowania użytkownika.

distinguishedName – pełna, unikalna nazwa obiektu.

Get-Member – wyświetla właściwości i metody obiektu.

Set-ExecutionPolicy – ustawia zasady uruchamiania skryptów.

RemoteSigned – pozwala uruchamiać skrypty lokalne i wymaga podpisu od skryptów pobranych z internetu.

Import-Csv – wczytuje dane z pliku CSV.

ForEach-Object – wykonuje operacje dla każdego elementu.



##### **VBScript – tworzy użytkowników za pomocą skryptów.**

Set – przypisuje obiekt do zmiennej.

GetObject() – uzyskuje dostęp do istniejącego obiektu.

Put – ustawia wartość atrybutu.

userAccountControl – określa stan konta i jego ustawienia.

AccountDisabled – określa, czy konto jest wyłączone.

cscript.exe – uruchamia skrypt VBScript w konsoli.





# 

# **Wnioski**



1\. Automatyzacja tworzenia kont za pomocą Dsadd

Dowiedziałem się, jak tworzyć konta użytkowników w Active Directory za pomocą polecenia Dsadd oraz jak ustawiać ich podstawowe dane, hasła i katalogi domowe.



2\. Importowanie użytkowników za pomocą CSVDE i LDIFDE

Dowiedziałem się, jak importować wielu użytkowników z plików tekstowych oraz czym różnią się formaty CSV i LDIF.



3\. Tworzenie użytkownika za pomocą PowerShell

Dowiedziałem się, jak tworzyć użytkowników w Active Directory za pomocą poleceń PowerShell.



4\. Tworzenie użytkownika za pomocą skryptu PowerShell

Dowiedziałem się, jak tworzyć skrypty automatyzujące zakładanie kont oraz jak korzystać z ADSI.



5\. Tworzenie użytkownika za pomocą VBScript

Dowiedziałem się, jak tworzyć konta użytkowników za pomocą VBScript i ustawiać ich dane przy użyciu skryptu.



6\. Tworzenie wielu użytkowników z pliku CSV za pomocą PowerShell

Dowiedziałem się, jak wczytywać dane z pliku CSV i automatycznie tworzyć na ich podstawie wiele kont użytkowników.

