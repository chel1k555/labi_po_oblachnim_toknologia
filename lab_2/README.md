# Отчет

## Что такое Docker :raised_eyebrow: :thinking:

Про докер до этой лабы я ничего не знал, и в основном слышал либо в рекламах на ютубе, либо в тик-токе на записи собесов. Сначала я решительно зашел в ютуб
![photo](./images/youtube.png)

Там я нашел много видосов и часть из них были реально хорошими, там же ссылку на хабр (вроде полезную). Вот **https://habr.com/ru/companies/kokocgroup/articles/802039/**.

Чтоб все закрепить закинул запрос в гпт и прочитал там все то же самое, что слышал в других источниках и приступил к работе.

## Работа

Сначала написал простой код который буду использовать в задании.
```
#include <iostream>
#include <vector>

int main() {

    int a = 326;
    int b = 25266;
    std::vector<int> arr;

    arr.push_back(a * b);
    arr.push_back(a + b);
    arr.push_back(a - b);
    arr.push_back(a);

    for (int i : arr) {
        std::cout << "result" << arr[i] << '\n';
    }
    
    
    return 0;
}
```

