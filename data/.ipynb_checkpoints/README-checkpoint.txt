Oba pliki CSV z danymi mają identyczny format. Ważniejsze uwagi:
- Pola "Kod" i "Nazwa" opisują jednostkę terytorialną, której dotyczą zagregowane dane.
- W polu "Kod" znajduje się tzw. kod TERYT, zwracam uwagę, że koduje on województwo, powiat, gminę oraz rozróżnienie miasto/wieś. (Szczegóły - w internecie).
- Pola "Kategoria" oraz "Zmienna" opisują *łącznie*, jakiej wartości dotyczy dany wiersz.
  (Pole "Kategoria" zostało dodane przeze mnie, żeby połączyć w jednym pliku CSV różne GUS-owskie tabele)
- Pole "Atrybut" jest niemal zawsze puste; mogą je Państwo zignorować.

Wskazówka dla użytkowników Pythona (w szczególności biblioteki pandas): polecam uwadze funkcję pivot().

