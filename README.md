[![SOURCES.LIST » Wikipedia offline in veste elegante con BytePac](https://tse1.mm.bing.net/th/id/OIP.AbllkI9stlwQAjsAGCGn-AHaFH?pid=Api)](https://www.sourceslist.eu/blog/wikipedia-offline-in-veste-elegante-con-bytepac/?utm_source=chatgpt.com)

Oczywiście! Oto zaktualizowana specyfikacja projektu **Bielik AI Hub** z uwzględnieniem edukacyjnej paczki danych offline oraz integracji z urządzeniami IoT.

---

## 🎯 Cel projektu

Stworzenie **kompleksowego, bezpiecznego i zgodnego z RODO** środowiska edukacyjnego i biurowego, działającego **w trybie offline**, które obejmuje:

* **Chat AI** oparty na lokalnym LLM.
* **Edukacyjną paczkę danych offline** zawierającą zasoby z Wikipedii, Khan Academy, MIT OpenCourseWare, Coursera, edX.
* **Integrację z urządzeniami IoT**.
* **Moduły zgodności z AI Act, cyberbezpieczeństwa i dostępności cyfrowej**.

---

## 📦 Zasoby edukacyjne offline

### 1. Wikipedia

* **Źródło**: Pełne zrzuty bazy danych Wikipedii dostępne są na stronie [Wikipedia:Database download](https://en.wikipedia.org/wiki/Wikipedia:Database_download).
* **Format**: XML, HTML, JSON.
* **Rozmiar**: Około 20–30 GB dla wersji angielskiej bez multimediów.
* **Narzędzia do przeglądania**: WikiTaxi, Kiwix.

### 2. Khan Academy

* **Źródło**: Aplikacja mobilna Khan Academy umożliwia pobieranie materiałów do nauki offline.
* **Instrukcja**: Szczegóły dotyczące pobierania materiałów offline dostępne są na stronie [Khan Academy Support](https://support.khanacademy.org/hc/en-us/articles/202487370-How-can-I-use-Khan-Academy-without-an-internet-connection).

### 3. MIT OpenCourseWare

* **Źródło**: Materiały kursów MIT dostępne są na stronie [MIT OpenCourseWare](https://ocw.mit.edu/).
* **Format**: Materiały w formacie PDF, wideo, HTML.
* **Instrukcja**: Pobieranie kursów możliwe jest bezpośrednio ze strony kursu lub za pomocą narzędzi takich jak `ocwd` (OpenCourseWare Downloader).

### 4. Coursera

* **Źródło**: Aplikacja mobilna Coursera pozwala na pobieranie materiałów kursów do oglądania offline.
* **Instrukcja**: Szczegóły dotyczące pobierania materiałów offline dostępne są na stronie [Coursera Support](https://www.coursera.support/s/article/learner-000001476).

### 5. edX

* **Źródło**: Aplikacja mobilna edX umożliwia pobieranie wideo kursów do oglądania offline.
* **Instrukcja**: Szczegóły dotyczące pobierania materiałów offline dostępne są na stronie [edX Support](https://help.edx.org/edxlearner/s/article/Downloading-videos-in-the-edX-App).

---

## 🧩 Architektura systemu

```
+---------------------------+
|     Urządzenia IoT        |
|  (czujniki, kamery, itp.) |
+-----------+---------------+
            |
            v
+---------------------------+
|    Serwer Bielik AI Hub   |
|  (LLM, baza offline, IoT) |
+-----------+---------------+
            |
            v
+---------------------------+
|       Interfejs Webowy     |
|  (chat, edukacja, IoT)    |
+---------------------------+
```

* **Serwer Bielik AI Hub**: Hostuje lokalny model językowy (LLM), bazę danych offline oraz integrację z urządzeniami IoT.
* **Interfejs Webowy**: Dostępny przez przeglądarkę, umożliwia interakcję z systemem.

---

## 🔐 Bezpieczeństwo i zgodność z regulacjami

* **RODO**: Dane użytkowników są przechowywane lokalnie, bez przesyłania do chmury.
* **AI Act**: System zapewnia zgodność z przepisami dotyczącymi sztucznej inteligencji.
* **NIS2**: Implementacja standardów cyberbezpieczeństwa zgodnych z dyrektywą NIS2.
* **Dostępność cyfrowa**: Interfejs zgodny z WCAG 2.1, zapewniający dostępność dla osób z niepełnosprawnościami.

---

## 💼 Model biznesowy

| Pakiet         | Zawartość                                       | Cena (PLN) |
| -------------- | ----------------------------------------------- | ---------- |
| Edu Start      | Chat AI, podstawowa paczka offline (~1 TB)      | 5 000      |
| Edu Pro        | Chat AI, pełna paczka offline (3–5 TB), IoT     | 12 000     |
| Edu Enterprise | Wszystko z Edu Pro + audyty compliance + granty | 25 000     |

* **Subskrypcja aktualizacji**: Możliwość subskrypcji rocznej na aktualizacje paczki edukacyjnej.
* **Dodatki**: Możliwość dokupienia dodatkowych kursów, materiałów edukacyjnych czy urządzeń IoT.

---

Jeśli potrzebujesz dodatkowych informacji lub wsparcia w implementacji, daj znać!
