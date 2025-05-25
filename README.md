# Podstawy Programowania - Meta Skille 

Zbiór informacji o programowaniu w języku Polskim. 

Mimo, że starałem się pisać jak najwięcej sam, dzieląc się własnymi przemyśleniami i starać się zachować szczery i spójny styl, część treści jest pisane i redagowane z pomocą AI, ale ze źródłami i sprawdzeniem informacji. 

Jak znajdziesz błąd, zrób PR :) Dzięki!

W tym przewodniku będę się skłaniał bardziej do angielskich nazw, niż polskich (w końcu programowanie jest bardziej międzynarodowe), każdy programista powinien język angielski znać i umieć się w nim odnaleźć. Szukanie informacji w internecie na dany temat jest też prostsze używając angielskich fraz, niż używanie polskich odpowiedników. 

# Wstęp

Każdy język programowania rządzi się swoimi własnymi prawami. 

W jednym definiujemy jako wstęp programu "public static void main", w innym przypadku nie musimy nic robić i wpisanie "print("Hello World")" w zupełności wystarczy.

Jednakże istnieje wiele umiejętności w programowaniu, których można się nauczyć i wykorzystywać niezależnie od języka programowania. 
Do takich podstawowych należą SOLID, Patterny (Wzorce Projektowe), Architektura, ale i też zarządzanie danymi. ich stanem, asynchroniczność w aplikacjach, czy testowanie. Znajdziesz również trochę inforamcji o polepszaniu performance (wydajności) aplikacji, ich bezpieczeństwu, Clean Code oraz DDD. 

## Kiedy byłem małym chłopcem

https://www.youtube.com/watch?v=lWXSUuosxtk

Myślałem, że programowanie jest o wiele prostsze. Jeżeli Mark Zuckerberg stworzył Facebooka, Bill Gates Windowsa, a Steve Jobs iPhone'a, to mi się też z pewnością to uda. Muszę tylko przeczytać 1 czy 2 książki, trochę napisać tego magicznego kodu i cyk, biznes działa i zarabia. 

Jakież było moje zdziwienie, gdy w 2007 roku tworząc moją pierwszą strone na PHP-Fusion, nie byłem nawet sam w stanie nawet zaimplementować filmików na YouTube, bądź Google Video na mojej stronie. Sfrustrowany tym faktem, postanowiłem zadać pytanie w moim łamanym angielskim na dedykowanym forum. Jakież było moje zdziwienie, gdy niecałe 15 minut później, ktoś postanowił się podzielić ze mną swoim skryptem PHP.

Po implementacji skryptu, wszystko zaczęło działać. To była moja pierwsza lekcja. 

### Komunikacja i umiejętność zadawania pytań

Jeżeli nauczycie się opisywać swój problem i będziecie wiedzieli, gdzie zadać pytanie i w jaki sposób, aby otrzymać na nie odpowiedź, to nikt nie będzie was w stanie prześcignąć.

Oczywiście przed zadaniem pytania powinniście sami najpierw trochę dać z siebie wysiłku i spróbować rozwiązać problem (czy to z Google, czy z ChatGPT) i dopiero jako ostatnią deskę ratunku użyć pytania do przyjaciela (Forum, Q&A, Discord, Github Issues, ChatGPT). Społeczności programistyczne są bardzo pomocne, jeżeli macie trochę kultury i nie zadajecie głupich pytań w stylu "od czego zacząć naukę programowania". 

## Strony internetowe to nie wszystko

W 2008 roku miałem już stworzone kilka stron internetowych (słabej jakości, ale od czegoś trzeba było zacząć). Jedna o piłce nożnej, druga o grach komputerowych, trzecia o trikach z piłką (Freestyle Football). Jednakże statyczne przekazywanie treści ze strony serwera do klienta bardzo szybko zaczęło mnie nudzić. Cięcie szablonów w photoshopie i klejenie stron używając "src=" w co drugim divie nie należało w tamtych czasach do najprzyjemniejszych. 

Jako że Facebook nabierał na popularności i strona ta była o wiele bardziej dynamiczniejsza postanowiłem poszerzyć swoją wiedzę. 
W nadzieji, że może nowy język i nauka od podstaw programowania coś zmieni, pożyczyłem wtedy książkę od znajomego. Prawdopodobnie kultową dziś już "Symfonię C++" Jerzego Grębosza. 

Nauka od początku nie należała do najprzyjemniejszych, bo jednak kopiowanie skryptów z tutoriala, czy z różnego rodzaju forum było łatwiejsze, niż faktyczna próba zrozumienia materiału. Przerabiałem też materiały w internecie jak https://cpp0x.pl/ Ale moja umiejętność programowania nie stawała się lepsza.
Poza zrozumieniem kilku funkcji i umiejętności nauczenia się jak działa pętla, wciąż nie umiałem nic sam stworzyć od podstaw. Dałem sobie wtedy spokój z programowaniem w nadzieji, że może w technikum informatycznym nauczyciele mnie wszystkiego nauczą. 

### 2011 rok

W technikum nie nauczyłem się więcej, niż sam umiałem. Turbo Pascal, C++, Java, C... Niby umiałem coraz to więcej składni, ale poza prostymi programami, nie byłem w stanie stworzyć niczego własnego. 

Próbowałem wtedy się motywować na różnego rodzaju sposoby. Czytałem wtedy nowo-wydaną biografię Steva Jobsa, kolejne źródła i zakładki w przeglądarce stawały się coraz większe. Tutorial za tutorialem przerabiałem jak tworzyć gry. Zaczynając od GameMakera, na Unity i CryEngine kończąc.

Niby pisałem kod, ale nie rozumiałem jak on działa i co się dzieje pod maską. Im więcej wiedziałem, tym miałem wrażenie, że umiem coraz mniej.

Na studiach byłem w stanie pisać jakieś proste programy, ale logika i jak ze sobą komponenty współgrają były dla mnie czarną magią. 

#### 2017 Rok, olśnienie

Do tego czasu miałem naprawdę dużo problemów na studiach. Pisanie coraz to bardziej skomplikowanych programów sprawiały mi taki problem, że byłem zmuszony te studia rzucić, a próba pracy w firmach często kończyła się ze względu posiadanych przeze mnie kwalifikacji zwolnieniem. 

##### Czy ja naprawdę się do tego nie nadaję? Czy powinienem rzucić programowanie i poszukać czegoś innego?

Dopiero jakoś w 2017 roku książka: "Think Like a Programmer: An Introduction to Creative Problem Solving", która była w Humble Bundle pozwoliła mi zrozumieć programowanie. Brzmi to trochę irocznie, ale do tego czasu tak dużo się naczytałem o programowaniu, ale nie byłem w stanie napisać sam programu.

Czemu?

### Bo nie wiedziałem jak myśleć jak programista.

Programowanie to nie tylko pisanie kodu... czy tam cyferek i literek. To sposób myślenia, łączenia funkcji, analizy działania i flow informacji.

Żeby zrozumieć programowanie, nie można się porywać z motyką na słońce. Sparzycie się. Trzeba zacząć od podstaw. Żeby móc używać funckji, trzeba najpierw zrozumieć zasadę ich działania. Co robi dana funkcja? Czy może się ona łączyć z innymi funkcjami? Czy posiada ona specjalne właściwości?

Jako że Java na studiach była językiem, który jako tako rozumiałem to postanowiłem zrozumieć co dokładnie robią dane funkcje. Nie z książek, a przez eksperymenty. 
Sam doświadczyć co się stanie, jak wywołamy funkcję, to co pojawi się na ekranie?

## Nauka przez eksperymenty

Zdecydowałem wtedy przeznaczyć 1 godzinę dzienne na naukę programowania (a dokładniej rzecz mówiąc na eksperymenty).

Jako że nie wiedziałem co zbytnio wtedy programować postanowiłem brać pomysły z tej listy:
https://github.com/G-Anon/Challenge-info

Zainstalowałem Eclipse i postanowiłem zakosić rękawy i wziąć się do działania. 
Pierwszym zadaniem było stworzyć "Name Generator" (Generator Imion). Jako że kilka lat wcześniej byłem zapalonym tibijczykiem, to pamiętałem o tym wątku na forun tibia.pl : https://forum.tibia.pl/showthread.php?t=109721

Autor tego poradnika przedstawił pewnego rodzaju algorytm, w jaki sposób można by było tworzyć imiona dla postaci w zależności od profesji. 
Aby nasza postać możliwie jak najlepiej wpasowała się w klimat gry, lepiej nazwać naszego Rycerza w stylu jakiegoś wojownika jak "Braveheart", niż "Great Ferumbras". Ale po co kleić imiona na kartce papieru i myśleć co by najlepiej pasowało, jak można by stworzyć program, który wygeneruje to nasze imię za nas?

Motywacją było z pewnością to, że program, który piszę przydałby się nie tylko mi, ale i innym graczom. A nawet by można było ten algorytm wykorzystać w grze, jeżeli bym tworzy w przyszłości grę RPG. Możliwości jego wykorzystania było wiele. 

Tak więc zainstalowałem ponownie Eclipse i stworzyłem nowy projekt:

<img width="788" alt="image" src="https://github.com/user-attachments/assets/152ee30a-5c83-4394-b591-01276c2df2eb" />

Następnie w Eclipse prawy przycisk na folder "src" i stworzyłem nową klasę o nazwie: "NameGenerator"
<img width="600" alt="image" src="https://github.com/user-attachments/assets/eeb1cba3-4620-4e07-b7b1-9dc79ab6c00e" />

Dodałem naszego legendarnego public static void main'a, a w nim funkcję printowania (wyświetlania teksty w konsoli).

```
package nameGenerator;

public class NameGenerator {
	public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

Skompilowałem... i sukces. 

<img width="947" alt="image" src="https://github.com/user-attachments/assets/5147caa6-d718-44f7-b75c-cde377d5bd53" />

Program działa i się kompiluje.

Skonfigurowanie środowiska w taki sposób, aby działało jest jednym z ważniejszych umiejętności jako programista. 

Jeżeli macie problemy, bo jesteście na innym systemie, bądź wasz komputer sprawia problemy, to musicie wiedzieć co zrobić, aby wasz program poprawnie kompilował to co do niego wprowadziliście. Google, ChatGPT, spytanie się Discordzie może często pomóc w takich problemach. To jest jedno z tych pytań, o które warto czasem poprosić o pomoc :)

#### Przykład jak rozwiązywać problemy. 

Pomyliliście się i zapomnieliście na końcu waszej funkcji napisać średnika (;) 

Dostajecie taki Error (bład):
```
Exception in thread "main" java.lang.Error: Unresolved compilation problem: 
	Syntax error, insert ";" to complete BlockStatements

	at nameGenerator/nameGenerator.NameGenerator.main(NameGenerator.java:5)
```

Kopiujecie jedynie górną część, czyli sam błąd: 
"Exception in thread "main" java.lang.Error: Unresolved compilation problem: 
	Syntax error, insert ";" to complete BlockStatements" i wrzucacie w Google.

 Jako, że Google nie zawsze znajduje to co potrzeba, pmocne może być skopiowanie źródła problemu: "Syntax error, insert ";" to complete BlockStatements"
 Tu  macie przykładową odpowiedź na pytanie:
 
 https://www.reddit.com/r/javahelp/comments/ifqdqq/help_with_syntax_error_insert_to_complete/

Zapomnieliśmy gdzieś w naszym programie użyć średnika. 
IDE będzie starało wam się podpowiedzieć czerwonym kolorem, gdzie moglibyście popełnić błąd:

<img width="785" alt="image" src="https://github.com/user-attachments/assets/edafe0cd-b235-4f29-ada0-2ecd8ab61c57" />

Dodanie średnika powinno rozwiązać wasz przykładowy problem. 

Teraz wiecie, że w przyszłości, jeżeli znowu pojawi się wasz błąd, że gdzieś zapomnieliście użyć średnika w waszym programie.

### Programowanie to nauka na błędach

Im więcej tych błędów popełnicie, tym większa będzie wasza wiedza jak te błędy rozwiązać. 
Z każdym błędem i każdym ich rozwiązaniem, będziecie stawać się coraz to lepszymi programistami. 

Ale chwila... Niby spoko, mamy naszego Hello Worlda, ale co robi faktycznie nasz blok: "System.out.println("Hello, World!");"?
Moja ciekawość stawała się coraz większa. Miałem wewnętrzną potrzebę zrozumienia co się dzieje pod maską języka.

W tym przypadku pomocne było odniesienie się do dokumentacji i czytania odpowiedzi bardziej doświadczonych osób na StackOverflow:
https://docs.oracle.com/javase/8/docs/api/java/lang/System.html

```bash
public final class System
extends Object
The System class contains several useful class fields and methods. It cannot be instantiated.
Among the facilities provided by the System class are standard input, standard output, and error output streams; access to externally defined properties and environment variables; a means of loading files and libraries; and a utility method for quickly copying a portion of an array.
```

Jak widzimy z oficjalnej dokumentacji, Klasa System posiada kilka funkcji, które umożliwiają pokazywanie przez was treści, ale i też ich wprowadzanie. 

Poza "out" istnieje jeszcze "in" oraz "err".
Jest użyty tak zwany "PrintStream" (Strumieniowanie drukowania) https://docs.oracle.com/javase/8/docs/api/java/io/PrintStream.html

A jedną z jego metod które możemy użyć jest "println"

Jak się dowiadujemy z dokumentacji, nie tylko same stringi mogą być przekazane, ale też i liczby i wartości boolean (prawda/fałsz).

Oraz, że poza samym "println" istnieje jeszcze "print", który nie posiada na końcu znaku nowej linii (enter) ("\n")

```
public void println()
Terminates the current line by writing the line separator string. The line separator string is defined by the system property line.separator, and is not necessarily a single newline character ('\n').
```

https://docs.oracle.com/javase/8/docs/api/java/io/PrintStream.html#println--

Czasem odpowiedzi w dokumentacji mogą brzmieć zbyt skomplikowanie, bądź sucho, wtedy czasem warto zajrzeć na Reddita przez google wpisując na przykład:
"what does "System.out.println" do?"

Wtedy dostaniecie bardziej luźne odpowiedzi jak tutaj:

https://www.reddit.com/r/learnjava/comments/xqa2i2/in_systemoutprintln_what_is_what_exactly/
https://stackoverflow.com/questions/61168525/why-does-system-out-println-in-java-print-to-the-console

W moim doświadczeniu odpowiedzi na StackOverflow są lepsze, gdyż są bardziej techniczne i więcej się można z nich nauczyć. Natomiast odpowedzi na Reddicie dobrze wprowadzają do tematu, bądź dzielą się innymi źródłami, które próbują rozwiązać problem autora. 

### Tworzenie Konceptu 

No spoko, mamy nasze działające IDE (środowisko programistyczne), co dalej?

Naturą byłoby spytać się ChatGPT o wygenerowanie kodu. Co w sumie byłoby prostym sposobem na podejście do problemu... ale przez to się niczego nie nauczymy. 
Na początku nauki jest ważne nauczyć się tego myślenia, a nie oddawać myślenie maszynie. 

Przeanalizujmy w takim razie wcześniej wspominany przeze mnie artykuł na forum: https://forum.tibia.pl/showthread.php?t=109721

Naszym pierwszym zadaniem jest stworzyć coś działajacego. Cokolwiek. Potem możemy nasz koncept polepszyć. 

W artykule na forum mamy bardzo prosty przykład:

```
Nazwisko rodowe wojownika, powinno składać się z dwóch członów, i obrazować najważniejszą cechę naszego przyszłego bohatera.
Przypuśćmy, że będziemy chcieli wpakować dużo czasu i pracy w rozwój siły fizycznej oraz używać w walce tylko młotów. Wyszukujemy więć wszelkie słowa klucze, które mogły by nam się przydać, np:
hammer - młot
stone - kamień
rock - skała
fist - pięść
strength - siła
itp.

Następnie wybieramy dwa z nich i łączymy w parę. Tak uzyskujemy kilka nazwisk:
Stonehammer - Kamienny Młot
Stonefist - Kamienna Pięść
Hammerstrenght - Siła Młota
Hammerrock - Młocia Skała
```

Tutaj jak widzimy, z połączenia dwóch słów i powiększenia pierwszej litery orzymamy przykładowe imię dla postaci.
Czyli naszym zadaniem jest:
1. Znaleźć sposób, funkcję, która umożliwi nam połączenie dwóch wyrazów w jeden
2. Znaleźć funkcję, która zamieni naszą pierwszą literę wyrazu na wielką literę.
   
Aby to zrobić musimy najpierw pomyśleć, jak możemy zapisać jakąś wartość w naszym programie. 
Jeżeli nie masz kompletnie żadnej wiedzy o programowaniu, to przydałaby się jednak jakiś książka, bądź nawet film wprowadzający i tłumaczący podstawowe zagadnienia i koncepty o programowaniu. Szukanie w Googole po frazach jak: "how to save a text value in java" może was skierować na złe wyniki, bo jednak nikt nie pyta się "podstaw, podstaw".

W naszym przypadku potrzebujemy zmiennej (variable), która posiada wartosć tekstową i posiada typ "tekstowy", bądź jak to niektórzy mówią "łańcuch znaków". 
Więc zapisujemy naszą pierwszą wartość: "stone" do zmiennej.

```
String name1 = "stone";
```

Jeżeli chcecie sprawdzić, czy dobrze zdefiniwaliście  waszą wartość to możecie sobie ją pokazać w konsoli:
```
String name1 = "stone";
System.out.print(name1);
```













