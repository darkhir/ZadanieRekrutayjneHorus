# ZadanieRekrutayjneHorus
Zostały zdefiniowane interfejsy Structure, Block i CompositeBlock (rozszerzający Block) określające strukturę i zachowanie bloków w ścianie.
Została zaimplementowana klasa CompositeBlockImpl jako konkretne wykonanie interfejsu CompositeBlock. Przechowuje informacje o kolorze, materiale i listę podbloków.
Została zaimplementowana klasa Wall, która przechowuje listę bloków i dostarcza metod dodawania, wyszukiwania według koloru i materiału oraz zliczania bloków.
W metodzie main został utworzony obiekt Wall, zostały dodane bloki do ściany oraz utworzono blok składający się z innych bloków.
Zostały wywołane różne metody na obiekcie Wall w celu wyszukiwania i zliczania bloków w ścianie.
