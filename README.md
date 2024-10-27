# 🔒 Misia Cipher – Bezpieczne Szyfrowanie Plików

**Misia Cipher** to zaawansowane, a zarazem przyjazne użytkownikowi narzędzie do szyfrowania plików, stworzone z myślą o ochronie danych przy wykorzystaniu algorytmu AES-256. Dzięki intuicyjnemu interfejsowi graficznemu (GUI), Misia Cipher umożliwia łatwe i skuteczne zabezpieczanie zawartości plików przed nieautoryzowanym dostępem. 

## 📜 Funkcjonalność Misia Cipher

### 🔹 Algorytm AES-256 w Trybie CFB
Misia Cipher korzysta z algorytmu **AES (Advanced Encryption Standard)** o długości klucza 256-bitów w trybie **CFB (Cipher Feedback)**. Tryb CFB pozwala na szyfrowanie strumieniowe, co zapewnia, że każda część danych jest zaszyfrowana indywidualnie. Ta metoda eliminuje ryzyko nadpisania danych i gwarantuje ich integralność w trakcie szyfrowania.

### 🔹 Przyjazny Interfejs Graficzny
Narzędzie zostało zaprojektowane z myślą o intuicyjności – interfejs jest prosty, przejrzysty, a wszystkie funkcje są dostępne bezpośrednio z głównego ekranu aplikacji. Przez cały proces szyfrowania użytkownik jest prowadzony krok po kroku, a każda akcja jest opisana poprzez wyraźne komunikaty.

### 🔹 Bezpieczeństwo Kluczy i Wektora Inicjalizującego
Dla każdego pliku generowany jest losowy klucz szyfrujący oraz wektor inicjalizujący (IV). Dzięki temu każde szyfrowanie jest unikalne, co dodatkowo zabezpiecza dane przed możliwością odszyfrowania ich przy użyciu tej samej konfiguracji klucza.

### 🔹 Real-time Status Tracking
Każdy etap procesu szyfrowania jest szczegółowo wyjaśniany użytkownikowi poprzez komunikaty wyświetlane w interfejsie. Aplikacja informuje o statusie począwszy od wyboru pliku, przez przygotowanie, aż po zakończenie procesu szyfrowania.

---

## 🔧 Jak działa Misia Cipher?

### 1. Wybór Pliku do Szyfrowania
Użytkownik może szybko wybrać plik do zaszyfrowania za pomocą przycisku "Wybierz plik". Wybrany plik jest następnie analizowany i przygotowywany do procesu szyfrowania.

### 2. Generowanie Klucza i Wektora Inicjalizującego (IV)
Misia Cipher generuje unikalny, losowy klucz 256-bitowy oraz wektor inicjalizujący 128-bitowy. Oba te elementy są kodowane w zaszyfrowanej postaci, co zabezpiecza je przed dostępem osób trzecich.

### 3. Proces Szyfrowania
Zawartość pliku jest szyfrowana blok po bloku przy użyciu algorytmu AES-256 w trybie CFB. Proces ten zapewnia pełną integralność danych, zachowując jednocześnie wysoki poziom bezpieczeństwa.

### 4. Zapis Zaszyfrowanego Pliku
Po zakończeniu szyfrowania Misia Cipher zapisuje plik pod nową nazwą, np. `plik_zaszyfrowany.py`, aby odróżnić go od oryginału. Zaszyfrowany plik można bezpiecznie przechowywać lub udostępniać bez ryzyka, że ktoś niepowołany odczyta jego zawartość.

### 5. Powiadomienie o Zakończeniu
Po zakończeniu procesu aplikacja wyświetla powiadomienie informujące o pomyślnym szyfrowaniu pliku, wraz z lokalizacją, gdzie został zapisany zaszyfrowany plik.

---

## 📈 Dlaczego Warto Wybrać Misia Cipher?

### 🔐 Bezpieczeństwo i Prywatność
Zastosowanie AES-256 oraz unikalnych kluczy i IV dla każdego pliku sprawia, że Misia Cipher zapewnia najwyższy poziom ochrony danych.

### 🖱️ Prosta Obsługa
Intuicyjny interfejs graficzny pozwala na szyfrowanie plików nawet osobom bez wiedzy technicznej.

### ⚙️ Pełna Transparentność
Aplikacja informuje użytkownika na każdym etapie procesu szyfrowania, a także umożliwia przegląd statusu operacji w czasie rzeczywistym.

---

**Misia Cipher** to niezawodne narzędzie do ochrony danych, idealne zarówno dla osób prywatnych, jak i profesjonalistów, którzy cenią sobie prywatność i bezpieczeństwo swoich informacji.

> 🔗 **Pobierz i chroń swoje pliki już teraz!**
