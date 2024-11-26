# Завдання 7. Симуляція кидання двох кубиків методом Монте-Карло
## Аналітичні та емпіричні ймовірності

| Сума | Аналітична ймовірність | Ймовірність (Монте-Карло) |
|------|-------------------------|---------------------------|
| 2    | 2.78%                   | 2.77%                     |
| 3    | 5.56%                   | 5.53%                     |
| 4    | 8.33%                   | 8.28%                     |
| 5    | 11.11%                  | 11.13%                    |
| 6    | 13.89%                  | 13.88%                    |
| 7    | 16.67%                  | 16.74%                    |
| 8    | 13.89%                  | 13.89%                    |
| 9    | 11.11%                  | 11.13%                    |
| 10   | 8.33%                   | 8.31%                     |
| 11   | 5.56%                   | 5.56%                     |
| 12   | 2.78%                   | 2.78%                     |

## Висновки

- **Відхилення:** Різниця між аналітичними ймовірностями та результатами Монте-Карло мінімальна, що свідчить про високу точність симуляції.
- **Точність методу Монте-Карло:** Завдяки великій кількості кидків (1,000,000) емпіричні ймовірності дуже добре наближаються до теоретичних значень. Усі відхилення знаходяться в межах допустимої похибки, що є очікуваним для методу Монте-Карло.
- **Збільшення точності:** У разі необхідності досягнення ще більшої точності можна збільшити кількість кидків, але результати вже є досить точними для загального аналізу.