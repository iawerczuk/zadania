#WZORCE PROJEKTOWE

#Wzorce projektowe to schematy rozwiazywania typowych problemów podczas projektowania oprogramowania. Ułatwiają tworzenie elastycznych, skalowalnych aplikacji, które są łatwe w użytkowaniu. 
Są szczególnie przydatne do zarzadzania zależnościami, organizacji kodu, zwiększania używalności. 

#Przykładowe wzorce:

#•	Kompozyt
Wzorzec strukturalny pozwalający na organizowanie obiektów w struktury drzewiaste, gdzie obiekty mogą być kompozycjami lub pojedynczymi obiektami. Dzięki temu można je traktować jednolicie. Kluczowymi elementami są 
o	komponent (Component), który definiuje interfejsy,
o	liść(Leaf)-reprezentujący pojedyncze elementy bez elementów podrzędnych
o	 kompozyt(Composite)- reprezentujący pojedyncze elementy z  elementami podrzędnymi lub bez(liście lub inne). 
Ma zastosowanie w budowie hierarchii graficznych, struktur danych, operacjach na grupach obiektów.
Zapewnia jednolitość operacji, elastyczność, reużywalność. 

#•	Obserwator
Wzorzec behawioralny, reprezentujący podejście „jeden do wielu”. Kiedy obserwowany (obiekt) zmienia swój stan, obserwatorzy (obiekty zależne) zostają aktualizowane.  Kluczowymi elementami są:
o	Obserwator (Observer)- definiuje interfejs, który musi być implementowany przez wszystkich obserwatorów
o	Obserwowany(Subject)-przechowuje informacje o stanie i  posiada mechanizm dodawania, usuwania i informowania obserwatorów
o	Obiekty- implementują interfejsy obserwującego i obserwatora
Może być używany we wzorcach MVC (kontroler jako obserwator, widoki -obserwatorzy), Eventy i delegaty- obsługa zdarzeń, delegaty w .NET jako obserwatorzy, powiadomieniach- powiadamianie w czasie rzeczywistym (czaty, systemy powiadomień).
Zapewnia niezależność, skalowalność, reużywalność. \

#•	Strategia
Wzorzec behawioralny, pozwala na definiowanie algorytmów, umieszczanie ich w oddzielnych klasach i wymiany podczas działania aplikacji. Algorytmy mogą być selekcjonowane w czasie działania.  Kluczowymi elementami są:
o	Strategia (Strategy)- wspólny interfejs
o	Konkretny algorytm (Concrete strategy)-klasy implementujące algorytmy
o	Kontekst (Context)- używa Strategy do wykonania zadania
Ma zastosowanie w obsłudze różnych formatów (JSON, XML, CSV).różnych metodach płatności w ecommerce, algorytmach sortowania.
Zaletami są łatwość zmiany algorytmów, ograniczenie złożoności i testowalność.

#•	Metoda wytwórcza
Wzorzec kreacyjny, dostarcza interfejsu do tworzenia obiektów w klasie bazowej i pozwala podklasom zmieniać twej i pozwala podklasom zmieniać typy obiektów. Deleguje tworzenie obiektów do podklas, pozwala na tworzenie elastycznych instancji. .  Kluczowymi elementami są:	
o	Produkt (Product)- interfejs lub klasa bazowa dla obiektów
o	Konkretne produkty (Concrete products)- implementacje Product
o	Twórca (Creator)- podklasy Creator nadpisujące metodę wytwórczą, by zwrócić implementację Product
Używana do tworzenia obiektów zależnych od kontekstu, opóźnionego tworzenia obiektów i łatwego dodawania nowych typów obiektu.

#•	Dekorator
Wzorzec strukturalny, pozwala na dynamiczne dodawanie funkcjonalności bez modyfikowania kodu obiektów. Ułatwia to rozszerzanie możliwości klasy bardziej niż dziedziczenie. .  Kluczowymi elementami są:
o	Komponent (Component)- definiuje wspólny interfejs na dynamicznie rozszerzalnych obiektów
o	Konkretny komponent (Concrete component)- implementuje interfejs I może być dekorowany
o	Dekorator (Decorator)- klasa abstrakcyjna, zawiera referencje do komponentu i implementuje interfejs. Deleguje operacje do obiektu komponentu
o	Konkretny dekorator (Concrete decorator)- rozszerza funkcjonalność komponentu, daje nowe zachowania przed lub po delegowaniu operacji
Może służyć do rozszerzania funkcjonalności, wzbogacania logiki biznesowej, do interfejsu użytkowania. 


