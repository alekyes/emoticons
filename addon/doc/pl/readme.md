# Emotikony / Emoticons #

* Autorzy: Chris Leo, Noelia Ruiz Martínez, Mesar Hameed, Francisco Javier
  Estrada Martínez
* Pobierz [wersja stabilna][1]
* Pobierz [wersja rozwojowa][2]

Przy użyciu tego dodatku, wypowiadany tekst zawierający znaki emotikonów
zostanie zastąpiony przez bardziej przyjazne opisy.

Dla przykładu: ":)" zostanie odczytane jako "Buzia uśmiech", albo emoji
będzie przeczytany w odpowiedni sposób, zrozumiały dla użytkownika.

Możesz wykorzystać następujące funkcje:

## Wstaw uśmieszek ##

W niektórych sytuacjach, obraz jest warty 1000 słów: użyj nowego emoji, aby
ożywić twoje wiadomości błyskawicznei żeby pokazać swoim przyjacielom, jak
się czujesz.

Jeśli nie jesteś pewien znaku dla określonego uśmiechu, ten dodatek pozwala
oznaczyć i dodać smajliki .

Naciśnij NVDA+I, oraz z mini ustawień -> zarządzaj emotikonami -> wstaw emotykon, aby otworzyć dialog z dostępnymi emotikonami lub emoji.

Ten dialog umożliwia wybór emotikonu i przegląd emotikonów interesujących
cie:

*	An editable field allows you to filter the search for the desired emoticon
  among the emoticons available.
*	Poprzez przyciski opcji, można wybrać tylko emoji (alt+E) albo standardowe
  emotykony (alt+s) oraz wszystkie emotykony (alt+A).
*	Na liście emotikonów (alt+L) wyświetlane są trzy kolumny: nazwa emotikonu,
  typ emotikonu (emotikon standardowy lub emoji), i odpowiedni znaczek.

Po naciśnięciu "ok", znaczki dla wybranego emotikonu będą skopiowane do
schowka, już gotowe do wklejenia.

## Dostosuj emotikony ##

Z pozycji meni NVDA, Ustawienia -> Zarządzaj emotikonami -> dostosuj emotikony, można otworzyć okno dialogowe, w którym można edytować istniejące, lub dodawać nowe emotykony.

Ten dialog umożliwia zochowanie słownika wymowy dla emotikonów z
dostosowaniami.

Naciśnij przycisk "Zapisz i eksportuj słownik", plik słownika o nazwie
emoticons.dic zostanie zapisany w twoim folderze konfiguracji użytkownika,
podfolderze speechDicts.

## Ustawienia aktywacji ##

Możesz ustawić aktywowanie wypowiadania emotikon po starcie NVDA. Domyślnie jest wyłączone.

Możliwe jest zachowywanie wyboru dla tego ustawienia.

## Skróty klawiszowe: ##

To są domyślnie dostępne skróty klawiszowe, można ich zmienić, albo dodać
nowy skrót do wywołania dialogu aktywacji lub słownika emotikonów:

* NVDA+E: przełącza między odczytem tekstu tak jak jest napisany, albo z
  emotikonami zastąpionymi przez opisy.
* NVDA+I: wyświetla okno dialogowe wyboru uśmieszku do skopiowania.


## Zmiany dla wersji 5.0 ##

* Dodane wsparcie dla emoji.
* Usprawnienia dla okna dialogowego wstaw emotikonyy z polem do filtrowania
  i i przyciskami opcji do wyboru wyświetlanych emotek.
* Używanie guiHelper do aktywacji okna dialogowego ustawień i okna
  dialogowego dla wstawiania emotek: wymaga NVDA 2016.4 lub nowsze wersje

## Zmiany dla wersji 4.0 ##

* Jeżeli jest otwarty dialog do wstawiania emotek, gdy się próbuje otworzyć
  inny dialog ustawień, NVDA wyświetli odpowiednią wiadomość o błędzie.


## Zmiany dla wersji 3.0 ##

* W oknie konfiguracji dodatku, , można teraz określić, że wzorzec powinien
  pasować tylko, jeśli jest całym słowem, zgodnie ze słownikami mowy NVDA
  2014.4.


## Zmiany dla wersji 2.0 ##

* Pomoc dodatku dostępna w managerze dodatków.


## Zmiany dla wersji 1.1 ##

* Usunięty powielony emotikon.
* Dodano kilka buź.

## Zmiany dla wersji 1.0 ##

* Pierwsza wersja.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=emo

[2]: https://addons.nvda-project.org/files/get.php?file=emo-dev
