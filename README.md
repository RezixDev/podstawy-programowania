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













