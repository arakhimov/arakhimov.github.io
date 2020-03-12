# validation inputs: name, url, telephone, site
---
<<<<<<< HEAD

## Версия v0.0.3
=======
## (https://arakhimov.github.io/form-validation/)
---
### Версия v0.0.3
>>>>>>> develop
---

#### pattern for name: "[А-ЯЁ][а-яё]+(-[А-ЯЁ][а-яё]+)*"

#### pattern for url: "[a-z\-\._\d]+@[a-z\-\._\d]+\.[a-z]{2,4}"

#### pattern for telephone: "(\+7|8)\s?\(?\d{3}\)?\s?\d{3}-?\d{2}-?\d{2}"

<<<<<<< HEAD
#### pattern for site consider: 
##### pattern for IPv4: (([1-9]?\d|1\d\d|(2([0-4]\d|5[0-5])))(\.(?!$)|$)){4}
##### pattern for domain name: (?<!\-)([a-zA-Zа-яёА-ЯЁ\d](\-)?)*(?!\-)\.[a-zа-я]{2,4}
=======
#### pattern for site: "^https?:\/\/(www\.)?((([1-9]?\d|1\d\d|(2[0-4]\d|25[0-5]))(\.(?!$)|$)){4}|(([\wа-яёА-ЯЁ]-?)+(?<!-|www)\.[a-zа-я]{2,4})+):?(\d{2,5})?(\/[\w\-]*\/*)*#?$"
#### pattern for site consider: 
#### pattern for IPv4: "(([1-9]?\d|1\d\d|(2[0-4]\d|25[0-5]))(\.(?!$)|$)){4}"
#### pattern for domain name: "(([\wа-яёА-ЯЁ]-?)+(?<!-|www)\.[a-zа-я]{2,4})+)"
>>>>>>> develop
