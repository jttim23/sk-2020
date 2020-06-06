# Podział i agregacja sieci

Dysponująć siecią o adresie ``80.90.100.96/27`` dokonaj podziału na 4 równe podsieci

| Parametr | wartość | komentarz(opcionalny) |
| ------------- |:-------------:| -----:|
| Adres sieci do podziału | 80.90.100.96 | | 
| Maska sieci  | 255.255.255.224 | |
| Maska binarnie  | 11111111.11111111.11111111.11100000 | |


2^n >= 4
2^3 >= 4
n = 3

| Podsiec   | Adres podsieci | Host min     | Host max      | Adres rozgłoszeniowy |
| -------------     |:-------------: | -----:       | -----:        | -----:    |
| 1         | 80.90.100.96 | 80.90.100.97| 80.90.100.126 | 80.90.100.127 |
| 2         | 80.90.100.128 | 80.90.100.129 | 80.90.100.158 | 80.90.100.159 |
| 3         | 80.90.100.160 | 80.90.100.161 | 80.90.100.190 | 80.90.100.191 |
| 4         | 80.90.100.192 | 80.90.100.193 | 80.90.100.222 | 80.90.100.223 |
