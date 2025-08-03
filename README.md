# 🔍 LogSentinel

LogSentinel to narzędzie w Pythonie do **analizy logów, generowania statystyk i wykrywania anomalii** w danych aktywności użytkowników.

Projekt łączy **tryb terminalowy** z **interaktywnym dashboardem webowym** opartym o Streamlit, umożliwiając szybkie filtrowanie, wizualizację i eksport danych.

---

## 📌 Funkcje

- 📊 **Analiza i statystyki**
  - Liczba akcji, liczba dni aktywności
  - Średnia liczba akcji na dzień
  - Liczba unikalnych użytkowników
  - TOP 5 najczęstszych akcji

- 🚨 **Wykrywanie anomalii**
  - Działania poza godzinami pracy (6:00–23:00)
  - Logowania z publicznych IP
  - Korzystanie z rzadkich urządzeń (<1% wystąpień)
  - Nagłe skoki aktywności (statystyczne odchylenia)

- 📈 **Wizualizacje**
  - Wykres trendu aktywności dziennej
  - Wykres najczęstszych akcji

- 🌐 **Dashboard webowy**
  - Filtry po użytkowniku, akcji i zakresie dat
  - Wykrywanie anomalii w czasie rzeczywistym
  - Eksport danych do CSV

- 💻 **Tryb terminalowy**
  - Interaktywne menu z wyborem opcji
  - Filtrowanie, sortowanie, eksport CSV
  - Anomalie i agregacje dostępne z poziomu CLI

---

## 🛠 Technologie

- **Python 3**
- **SQLite**
- **Pandas**
- **Matplotlib**
- **Streamlit**
- **Rich** (kolorowe tabele w terminalu)

---

## 🚀 Uruchomienie

### 1. Klonowanie repozytorium
```bash
git clone https://github.com/twojnick/LogSentinel.git
cd LogSentinel
Dla web: python -m streamlit run dashboard_main.py
Dla terminala: python analyzer_off.py

Instalacja zależności
pip install -r requirements.txt




DEV BY BSOLECKI

