# hello-world
pomysły i nauka zmiana tekstu
  
<h1>
GITHUB :  </h1>
- Utwórz repozytorium z projektem lub wybierz istniejące repozytorium np hello-world
- Wejdź w ustawienia repozytorium menu -> settings
- Przewiń na dół do sekcji GitHub Pages
- Wybierz Source – master branch
- Zapisz zamiany - Kliknij przycisk SAVE. <br>
Po odświeżeniu zobaczysz swój adres strony https://m-woryna.github.io/hello-world/<br>
Twoja strona została opublikowana po tym adresem. Tekst w pliku README.md<br>
Aby przejść do pliku README.md trzeba wybrać z menu -> code<br>
Wybrać plik i nacisnąć ołówek w prawym górnym rogu w celu Edit <br>
Po wrowadzeniu zmian nacinąć Commit i przejść do Sttings aby zobaczyć zmiany. <br>
Zmiana Theme - efekt może być widoczny ze znacznym poślizgiem.<br>
Aby zobaczyć ostatnie zmiany trzeba przejśc przez Settings -> GitHub Pages ->Source - Master branch  i odświeżyć stronę.
<br>Choć niekoniecznie :/<br><br>
<IMG SRC="ogrodnik_zima1.jpg" BORDER="0"  ALT="obrazek zimowy">
  <b>graficzny przerywnik dla relaksu - w sumie fajne narzędzie</b> <BR>
 <br>
  pomocna strona : https://www.flynerd.pl/2018/02/opublikowac-strone-internetowa-github-pages-krok-kroku.html
  <br>
  https://www.flynerd.pl/2018/02/github-dla-zielonych-pierwsze-repozytorium.html
  <br>
  jutro zainstalowac program git na kompie, spróbujemy plik z turystyki przerobić ;) i nasac tekst do fikusa sprężystego ....<br><br>
  
GitHub flow to lekki, oparty na oddziałach przepływ pracy, który wspiera zespoły i projekty, w których wdrażanie odbywa się regularnie. W tym przewodniku wyjaśniono, jak i dlaczego działa przepływ GitHub.<br>

<h3> zmiana nazwy repozytorium </h3>
-  wybierz repozytorium a następnie spo prawej stronie wybierz Settings --> Rename zmienn nazwię i potwierdż.
<h3> usuń plik z repozytorium </h3>
wybierz plik z repozytorium, naciśnij ikonę edycji (ołówek w pawym górnym rogu) i naciśnji usuń (ikona kosza w parwym górnym rogu)
  
<h3> Utwórz branch</h3>

Kiedy pracujesz nad projektem, będziesz mieć mnóstwo różnych funkcji lub pomysłów w toku w danym momencie - niektóre z nich są gotowe, a inne nie. Branch istnieje, aby pomóc Ci zarządzać tym przepływem pracy. <br>

<h3>ProTip</h3>

Branch jest podstawową koncepcją w Git i na nim opiera się cały przepływ GitHub. Jest tylko jedna zasada: wszystko w gałęzi master jest zawsze możliwe do wdrożenia.<br>
Z tego powodu niezwykle ważne jest, aby twoja nowa branch została utworzona jako master podczas pracy nad funkcją lub poprawką. Nazwa branch powinna mieć charakter opisowy (np. Uwierzytelnianie refaktora, klucz pamięci podręcznej treści użytkownika, make-retina-avatary), aby inni mogli zobaczyć, nad czym pracuje.<br><br>

<h3>Add commits</h3>
Po utworzeniu branch czas zacząć wprowadzać zmiany. Ilekroć dodajesz, edytujesz lub usuwasz plik, dokonujesz zatwierdzenia i dodajesz go do swojego branch. Ten proces dodawania zatwierdzeń śledzi Twoje postępy podczas pracy nad gałęzią funkcji.
Zatwierdzenia tworzą również przejrzystą historię twojej pracy, którą inni mogą śledzić, aby zrozumieć, co zrobiłeś i dlaczego. Każdemu zatwierdzeniu towarzyszy powiązany komunikat zatwierdzenia, który jest opisem wyjaśniającym, dlaczego wprowadzono określoną zmianę. Ponadto każde zatwierdzenie jest traktowane jako oddzielna jednostka zmiany. Pozwala to wycofać zmiany, jeśli błąd zostanie znaleziony lub jeśli zdecydujesz się pójść w innym kierunku.

<h3>ProTip</h3>

Komunikaty zatwierdzania są ważne, zwłaszcza że Git śledzi zmiany, a następnie wyświetla je jako zatwierdzenia po przekazaniu ich na serwer. Pisząc jasne komunikaty zatwierdzania, możesz ułatwić innym osobom śledzenie i przesyłanie opinii.

<h3>Open a Pull Request</h3>
Pull Requests inicjuje dyskusję o twoich zobowiązaniach. Ponieważ są ściśle zintegrowane z bazowym repozytorium Git, każdy może zobaczyć, jakie zmiany zostałyby scalone, gdyby zaakceptował twoje żądanie.
Możesz otworzyć Pull ReQuest w dowolnym momencie procesu programowania: gdy masz mało kodu lub nie masz go, ale chcesz udostępnić zrzuty ekranu lub ogólne pomysły, gdy utkniesz i potrzebujesz pomocy lub porady, lub gdy jesteś gotowy na kogoś przejrzeć swoją pracę. Korzystając z systemu @mention GitHub w komunikacie Pull Request, możesz poprosić o informacje zwrotne od konkretnych osób lub zespołów, niezależnie od tego, czy są na dole korytarza, czy w dziesięciu strefach czasowych.

<h3>ProTip</h3>

Pull Request są przydatne do przyczyniania się do projektów typu open source i zarządzania zmianami w udostępnianych repozytoriach. Jeśli korzystasz z modelu Fork & Pull, żądania ściągnięcia zapewniają sposób powiadamiania opiekunów projektu o zmianach, które chcesz rozważyć. Jeśli korzystasz z modelu współdzielonego repozytorium, żądania ściągania pomagają rozpocząć przegląd kodu i rozmowę na temat proponowanych zmian przed ich scaleniem w gałęzi głównej.

<h3>Omów i przejrzyj swój kod</h3>

Po otwarciu Pull Request osoba lub zespół przeglądający twoje zmiany mogą mieć pytania lub komentarze. 
Być może styl kodowania nie jest zgodny z wytycznymi projektu, w zmianie brakuje testów jednostkowych, a może wszystko wygląda świetnie, a rekwizyty są w porządku. Pull Request mają na celu zachęcanie i przechwytywanie tego typu konwersacji.

Możesz także nadal naciskać na swój branch w świetle dyskusji i informacji zwrotnych na temat swoich zobowiązań. Jeśli ktoś komentuje, że zapomniałeś coś zrobić lub jeśli w kodzie jest błąd, możesz to naprawić w swoim branch i przyspieszyć zmianę. GitHub pokaże twoje nowe zobowiązania i wszelkie dodatkowe informacje zwrotne, które możesz otrzymać w ujednoliconym widoku Pull Request.

<h3>ProTip</h3>

Komentarze Pull Request są zapisywane w Markdown, więc możesz osadzać obrazy i emoji, używać wstępnie sformatowanych bloków tekstowych i innych lekkich formatowań.

<h3>Rozmieścić</h3>

Dzięki GitHub możesz wdrożyć z Branch do końcowego testowania w produkcji przed połączeniem z głównym.

Po sprawdzeniu Pull Request i przejściu testów przez Branch można wdrożyć zmiany, aby zweryfikować je w środowisku produkcyjnym. Jeśli twoja Branch powoduje problemy, możesz ją wycofać, wdrażając istniejący wzorzec do produkcji.

<h3>Merge</h3>

Teraz, gdy zmiany zostały zweryfikowane w produkcji, nadszedł czas, aby scalić kod w master branch.
Po Merge Pull Request zachowują zapis historycznych zmian w kodzie. Ponieważ można je przeszukiwać, pozwalają każdemu cofnąć się w czasie, aby zrozumieć, dlaczego i jak podjęto decyzję.

<h3>ProTip</h3>
Umieszczając określone słowa kluczowe w tekście Pull Request, możesz powiązać problemy z kodem. Po Merge Pull Request powiązane problemy również zostają zamknięte. Na przykład wpisanie frazy Zamknięcie # 32 spowoduje zamknięcie numeru sprawy 32 w repozytorium. Aby uzyskać więcej informacji, zapoznaj się z naszym artykułem pomocy.

<h1>
SYMFONY :  </h1>

Symfony to zestaw komponentów PHP wielokrotnego użytku ...<br>
Standardowa podstawa, na której budowane są najlepsze aplikacje PHP. Wybierz jeden z 50 samodzielnych komponentów dostępnych dla własnych aplikacji.<br>
... i framework PHP dla projektów internetowych<br>
rzyspiesz tworzenie i utrzymanie aplikacji internetowych PHP. Zakończ powtarzające się zadania kodowania i ciesz się mocą kontrolowania swojego kodu.
<br><br>

Rozpoczęcie pracy z Symfony<br>
stnieją setki starannie napisanych stron dokumentacji obejmujących wszystkie funkcje Symfony, które są DARMOWE i posiadają licencję typu open source!<br>
<br>

<h2>Instalowanie i konfigurowanie środowiska Symfony</h2>

<h3>Wymagania techniczne</h3>

Przed utworzeniem pierwszej aplikacji Symfony musisz:<br>

- Zainstaluj PHP 7.2.5 lub nowszy i te rozszerzenia PHP (które są instalowane i włączane domyślnie w większości instalacji PHP 7): Ctype, iconv, JSON, PCRE, Session, SimpleXML i Tokenizer;<br>
- Zainstaluj Composer, który służy do instalowania pakietów PHP;<br>
- Zainstaluj Symfony, który tworzy na komputerze plik binarny o nazwie symfony, który zapewnia wszystkie narzędzia potrzebne do lokalnego tworzenia aplikacji.
<br>
<br>
Plik <b>symfony binary</b> zapewnia narzędzie do sprawdzenia, czy komputer spełnia te wymagania. Otwórz terminal konsoli i uruchom następującą komendę:<br>
$  symfony check:requirements
<br><br>
ze strony https://symfony.com/download <br>
$ wget https://get.symfony.com/cli/installer -O - | bash
<br>
