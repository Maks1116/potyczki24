# zadanie 0
200 OK

# Zadanie 1
 - utworzyłem projekt
 - dodałem namespace nginx

# Zadanie 2 
- Environmment check zwraca brak kilku potrzebnych paczek (env check z dokumentacji Longhorn)
- Zainstalowalem potrzebne paczki oraz Longhorna za pomoca kubectl apply.
- Zauwazony blad:  	Containers with incomplete status: [wait-longhorn-manager]
- Manager crashuje sie z powodu braku open-iscsi

# Zadanie 3
 - dodałem repo o nazwie rodeo, kierujące do https://rancher.github.io/rodeo
 - zainstalowałem tetrisa ![](screenshots/1.png)

# Zadanie 4
 - Zainstalowałem neuvector ![](screenshots/2.png)
 - Zainstalowałem Extension Operator
 - zainstalowałem NeuVector UI Extension 
![very neuvector](screenshots/3.png)

# Zadanie 5
 - Włączyłem autoscan w neuvectorze
 - Dodałem dockerownię ![](screenshots/4.png)

# Zadanie 18
Pan Adrian użył złego obrazu. Nasze serwery nie są na architekturze arm64v8, tylko amd64.
![alt text](screenshots/5.png)
