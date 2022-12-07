# Kochetov Alexander
***
## Contacts
* **E-mail**: sahamain23@gmail.com
* **Telegram**: @nuwyint
* **GitHub**: nuwyint
* **Discord**: nuwyint
*****
## About me
I am 18 years old, I am studying at the university in the direction of software engineering. I am currently working on python courses for children.

*****
## Skills
* HTML 5
* Python
* C++

*****
## Education
Tambov State Technical University, Information and Computer Engineering (2022-present)

*****
## Code example
*the algorithm of perfix sums* solution from codewars 
```f = open('f.txt')
n = int(f.readline())
mas = [int(f.readline()) for i in range(n)] * 2
prefix = [0] * n * 2
prefix[0] = mas[0]
for i in range(1, 2 * n):
    prefix[i] = prefix[i - 1] + mas[i]
price = mas[1]
for i in range((n - 2) // 2):
    price += mas[i + 2] * (i + 2) + mas[-i - 1] * (i + 1)
minsum = price
for i in range(1, n):
    minus = prefix[i + n // 2 - 1] - prefix[i]
    plus = prefix[i + (n // 2 - 1) * 2] - prefix[i + n // 2 - 1]
    price = price - mas[i] + mas[i - 1] + plus - minus
    minsum = min(minsum, price)
print(minsum)
```

******
## Special skills 
* Language
    + English - C1