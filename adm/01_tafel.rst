**********************************
Induktions-Axiom - 5. Peano Axiom
**********************************

| Jede Eigenschaft, die 0 hat und sich von n auf n' überträgt, haben alle natürlichen Zahlen.
| => garantiert, dass die natürlichen Zahlen, bis auf die definierten Zahlen keine weiteren Elemente enthalten.
|
| ℕ = { 0, 1, 2, 3, … }
|
| => Es garntiert weiter, dass es keine weiteren Stränge gibt.
|
    | a => a' => a'' ↯ (5)
    Durch das Induktions-Axiom kann es keinen Strang a geben, da 0 die Eigenschaft hat im ersten Strang zu liegen.
|
| m, n ∈ ℕ
| m ≤ n wenn man von 0 ausgehend entsprechend Nachfolger bildet.


Vollständige Induktion
======================

| P ist eine Eigenschaft

    P(n) bedeutet n hat die Eigenschaft P

| P gilt nur für die Zahl, die P besitzt. Hätte n die Eigenschaft (P) gerade zu sein, wäre das nicht auf n' übertragbar, da auf eine gerade Zahl eine ungerade folgt.
| ∀ (für alle) ∈ ℕ : P(n)
| **Annahmen:**
| 1. P(0), 0 hat die Eigenschaft P
| 2. Wenn n die Eigenschaft P hat dann auch n', P(n) => P(n + 1)
| P(0) ∧ (∀ n ∈ ℕ : P(n) => P(n + 1)) => ∀ n ∈ ℕ : P(n)
| 
| **Beipiel:**
| P(n) =  (n ∑ k = 0) k = n * (n + 1) / 2
| 1) P(0) = (0 = 0 * 1 / 2) -> *Induktionsanfang*
| 2) P(n + 1) = (n + 1 ∑ k = 0) k = (n + 1)(n + 2) / 2
|
| **Beweis:**
| (n + 1 ∑ k = 0)


