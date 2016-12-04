# SOI-Semaphores
Uwagi:
- należy korzystać tylko z semaforów POSIX, System V jest niedozwolone;
- wystąpienie zakleszczenia lub aktywnego oczekiwania daje 0 pkt za rozwiązanie;
- koncepcja powinna zawierać rozwiązanie w postaci pseudokodu i treść zadania;

Treść zadania:

Bufor n-elementowy FIFO. Trzech konsumentów i dwóch producentów. Producent A produkuje jedną literę, Producent B produkuje jednocześnie dwie litery. Element jest usuwany z bufora po odczytaniu przez obu konsumentów A i B. Konsument C może usunąć element z bufora jeżeli nie został ten element wcześniej przeczytany przez żadnego z pozostałych konsumentów. Dany element nie może być wielokrotnie czytany przez tego samego konsumenta.
