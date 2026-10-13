ćwiczenie 1

    joke- wyświetla losowy żart
    pong - uruchamia prostą grę w ponga w terminalu
    starwars - włącza film star wars w stylu ascii

dziś do wyświetlania używa się aplikacji przeglądarkowych

ćwiczenie 2 

    żądanie     metoda      ścieżka             kod                     3 nagłówki + co znaczą 
info.cern.ch    'GET'/-v       '/'                 '200 OK'                (Server)opisuje oprogramowanie serwera np.Apache (Content-Type) typ zwracanej wartości 
                                                                        (Last-Modified) data ostatniej modyfikacji
github.com      'HEAD'/-I      '/'                 '301 Moved Permanently' (Location) Adres, na który została zmieniona strona (Content-Length) Długość odpowiedzi 
                                                                        (Connection) Status połaczenia
nie-ma-takiej   'HEAD'/-I      '/nie-ma-takiej'    '404 Not Found'         (Content-Type) Typ zwracanego dokumentu (Date) Czas, w którym komputer odpowiedział 
                                                                        (Connection) Infromacja o stanie połączenia w tym wypadku zamknięcie

github inaczej niż cern odpowiada ponieważ automatycznie przekierowuje a cern dziala bezposrednio

ćwiczenie 3 

Pomiar              info.cern.ch     spacejam.com/1996   onet.pl
liczba żądań        4                   23                  299
Przesłane dane(kB)  3.1kB               67.1kB              3.6MB 
Czas ładowania      316ms               728ms               1.9s
Elementy DOM        16                  119                 1473
Najcięższy plik(typ) 1.7kB(document)              15.8kB(gif)              203kB(mp4/media)

Ilość przesłanych danych i czas ładowania mnie zaskoczył wynika to z ilości treści na stronie i użytej technologii. Na stronie onetu jest ti przesada też jeśli chodzi o elementy na stronie.