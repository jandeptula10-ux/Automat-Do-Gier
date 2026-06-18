# 🕹️ Repozytorium Dokumentacji Mechanicznej - Konsola Arcade

Witam w oficjalnym repozytorium projektu automatu do gier. Repozytorium zawiera posegregowane pliki źródłowe modeli CAD (`.IPT`), główny plik złożenia (`.IAM`) oraz plik projektu środowiska Autodesk Inventor (`.IPJ`).

---

> 💡 **Instrukcja nawigacji:** Po otwarciu poniższego linku, możesz swobodnie obracać model 3D całej maszyny. Użyj drzewa operacji po lewej stronie ekranu – **nakierowanie kursora myszy na dowolny element z listy podświetli go bezpośrednio na modelu.**

### 🔗 [KLIKNIJ TUTAJ, ABY OTWORZYĆ INTERAKTYWNY MODEL 3D W PRZEGLĄDARCE](https://viewer.autodesk.com/id/dXJuOmFkc2sub2JqZWN0czpvcy5vYmplY3Q6YTM2MHZpZXdlci1wcm90ZWN0ZWQvdDE3ODE3MTU0MzZfNmUxZGRkZTQtMzYxZi00NTI3LWJkZjktMTA5YzNlNmUwY2QxLmlwdA?sheetId=ZTk1MjU1NzMtMDU2MC00YTAyLTk5YjItODJmOTcyMzI3NDM4)

---

## 📂 Pliki Główne
W głównym katalogu repozytorium znajdują się pliki spajające cały projekt:
* 🛠️ **`konsola.iam`** - Główne złożenie maszyny.
* ⚙️ **`konsola.ipj`** - Plik projektu środowiska Inventor.

---

## 📌 Zestawienie Plików Źródłowych Inventor (`.IPT`)

Poniżej znajduje się wizualne zestawienie wszystkich zaprojektowanych elementów, zgodnie ze strukturą folderów w repozytorium.

### ⬅️ Przód Maszyny (Folder: `/Przod`)
| Podgląd | Pliki (URL) | Krótki Opis Elementu |
| :---: | :--- | :--- |
| <img src="img/K.png" width="100"> | [CUT PART K.ipt](./Przod/CUT%20PART%20K.ipt) <br> [CUT PART K-01.ipt](./Przod/CUT%20PART%20K-01.ipt) | **Panel sterowania:** Płyta, w której montowane są joysticki. |
| <img src="img/I.png" width="100"> | [CUT PART I.ipt](./Przod/CUT%20PART%20I.ipt) <br> [CUT PART I-01.ipt](./Przod/CUT%20PART%20I-01.ipt) | **Drzwi frontowe:** Duży przedni panel rewizyjny obudowy. |
| <img src="img/D.png" width="100"> | [CUT PART D.ipt](./Przod/CUT%20PART%20D.ipt) <br> [CUT PART D-01.ipt](./Przod/CUT%20PART%20D-01.ipt) | **Przód panelu:** Pionowa maskownica pod panelem głównym. |

---

### 📦 Korpus i Rama (Folder: `/korpus`)
| Podgląd | Pliki (URL) | Krótki Opis Elementu |
| :---: | :--- | :--- |
| <img src="img/A.png" width="100"> | [CUT PART A.ipt](./korpus/CUT%20PART%20A.ipt) <br> [CUT PART A-01.ipt](./korpus/CUT%20PART%20A-01.ipt) | **Panel boczny:** Profil stanowiący konstrukcję nośną szafy. |
| <img src="img/B.png" width="100"> | [CUT PART B.ipt](./korpus/CUT%20PART%20B.ipt) <br> [CUT PART B-01.ipt](./korpus/CUT%20PART%20B-01.ipt) | **Panel górny:** Sufit zamykający konstrukcję od góry. |
| <img src="img/C.png" width="100"> | [CUT PART C.ipt](./korpus/CUT%20PART%20C.ipt) <br> [CUT PART C-01.ipt](./korpus/CUT%20PART%20C-01.ipt) | **Spód szyldu:** Płyta zamykająca podświetlany baner od dołu. |
| <img src="img/H.png" width="100"> | [CUT PART H.ipt](./korpus/CUT%20PART%20H.ipt) <br> [CUT PART H-01.ipt](./korpus/CUT%20PART%20H-01.ipt) | **Panel głośników:** Płyta podtrzymująca system audio. |
| <img src="img/J.png" width="100"> | [CUT PART J.ipt](./korpus/CUT%20PART%20J.ipt) <br> [CUT PART J-01.ipt](./korpus/CUT%20PART%20J-01.ipt) | **Podłoga:** Dolny panel stanowiący podstawę automatu. |

---

### ➡️ Tył Maszyny (Folder: `/Tyl`)
| Podgląd | Pliki (URL) | Krótki Opis Elementu |
| :---: | :--- | :--- |
| <img src="img/G.png" width="100"> | [CUT PART G.ipt](./Tyl/CUT%20PART%20G.ipt) <br> [CUT PART G-01.ipt](./Tyl/CUT%20PART%20G-01.ipt) | **Dolny panel tylny:** Płyta zamykająca plecy automatu. |

---

### 🛠️ Elementy Dodatkowe (Folder: `/elementy_dodatkowe`)
| Podgląd | Pliki (URL) | Krótki Opis Elementu |
| :---: | :--- | :--- |
| <img src="img/monitor.png" width="100"> | [monitor.ipt](./elementy_dodatkowe/monitor.ipt) | Model 3D użytego monitora LCD (element referencyjny). |
| <img src="img/zawias-L.png" width="100"> | [zawias-lewy.ipt](./elementy_dodatkowe/zawias-lewy.ipt) | Lewy zawias drzwiczek frontowych. |
| <img src="img/zawias-P.png" width="100"> | [zawias-prawy.ipt](./elementy_dodatkowe/zawias-prawy.ipt) | Prawy zawias drzwiczek frontowych. |
| <img src="img/trzpien.png" width="100"> | [trzpien.ipt](./elementy_dodatkowe/trzpien.ipt) | Element mechanizmu zawiasu/zamka. |
| <img src="img/N.png" width="100"> | [CUT PART N.ipt](./elementy_dodatkowe/CUT%20PART%20N.ipt) <br> [CUT PART N-01.ipt](./elementy_dodatkowe/CUT%20PART%20N-01.ipt) | Wewnętrzny wspornik / element konstrukcyjny. |
| <img src="img/O.png" width="100"> | [CUT PART O.ipt](./elementy_dodatkowe/CUT%20PART%20O.ipt) <br> [CUT PART O-01.ipt](./elementy_dodatkowe/CUT%20PART%20O-01.ipt) | Wewnętrzny wspornik / element konstrukcyjny. |
| <img src="img/P.png" width="100"> | [CUT PART P.ipt](./elementy_dodatkowe/CUT%20PART%20P.ipt) <br> [CUT PART P-01.ipt](./elementy_dodatkowe/CUT%20PART%20P-01.ipt) | Wewnętrzny wspornik / element konstrukcyjny. |
| <img src="img/R.png" width="100"> | [CUT PART R.ipt](./elementy_dodatkowe/CUT%20PART%20R.ipt) <br> [CUT PART R-01.ipt](./elementy_dodatkowe/CUT%20PART%20R-01.ipt) | Wewnętrzny wspornik / element konstrukcyjny. |
