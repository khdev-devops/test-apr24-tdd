# Övning: TDD

## Uppgift

Implementera klassen `BankAccount` med följande metoder:

- `deposit(amount: int)`
- `withdraw(amount: int)`
- `get_balance() -> int`

Du får **endast skriva kod för en funktionalitet efter att du skrivit ett test** för den.

Tänk på TDD-loopen:
1. **Red** – Skriv ett test som misslyckas
2. **Green** – Implementera precis tillräckligt för att testet ska gå igenom
3. **Refactor** – Förbättra koden utan att ändra funktion

## Körinstruktioner

1. Installera beroenden:

```bash
pip install -r requirements.txt
```

2. Kör testerna
```bash
pytest
```

# Länkar
- [Martin Fowler: TDD](https://martinfowler.com/bliki/TestDrivenDevelopment.html)
- [Software Development Tutorial - What is test-driven development (TDD)? (5 min video)](https://www.youtube.com/watch?v=QCif_-r8eK4)
- [Is TDD dead? (30 min video)](https://www.youtube.com/watch?v=z9quxZsLcfo)
