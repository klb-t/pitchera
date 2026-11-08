# Przepływ zgłaszania błędów (oparty na hierarchicznej liście funkcjonalności)

Użytkownik zgłasza buga.

System najpierw sprawdza, czy to rzeczywiście bug, czy po prostu brak pełnej implementacji.

Potem w osobnym drzewie błędów sprawdza, czy jest już taki zgłoszony.

- Jeśli tak — proponuje dołączenie do tego samego wątku, z danymi niepowtarzalnymi plus podbicie licznika, osobną obsługę i tak dalej.
- Kategoryzacja tylko dla systematyzacji.
- Jeśli nie — daje zgłoszenie do ręcznego sprawdzenia.

## Kontekst
Przepływ do testów (w tym beta z regulowanym poziomem eksperymentalności).
Opiera się na hierarchicznej liście funkcjonalności (ecosystem_spec).
