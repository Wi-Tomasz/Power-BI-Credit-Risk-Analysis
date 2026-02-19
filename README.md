# Power-BI-Credit-Risk-Analysis
Zaprojektowano i wdrożono kompleksowe ramy monitorowania ryzyka kredytowego, obejmujące quasi-score, analizę WOE/IV, monitorowanie stabilności PSI oraz panel zarządzania apetytem na ryzyko.

Projekt przedstawia kompleksowe ramy monitorowania ryzyka kredytowego, obejmujące analizę portfela, opracowanie quasi-score, ocenę stabilności modelu (PSI) oraz zarządzanie apetytem na ryzyko.

# Plik Power BI
Ze względu na ograniczenia rozmiaru pliku w serwisie GitHub, pełny plik Power BI (167 MB)
jest dostępny tutaj:

[Download PBIX file][(https://drive.google.com/file/d/1TztzSsUNDzYcHV3sGOxw_92TfwqV6Y3I/view?usp=drive_link)]

Rozwiązanie symuluje bankowe środowisko ryzyka kredytowego, w tym monitorowanie, system alertów i raportowanie zarządcze.

Zakres projektu:

- Analiza struktury portfela
- Identyfikacja czynników ryzyka (WOE / IV)
- Opracowanie quasi-logistycznej punktacji
- Segmentacja decylowa
- Monitorowanie stabilności (PSI)
- Porównanie liderów i pretendentów
- Struktura apetytu na ryzyko
- System alertów progowych

Metodologia:

1. Przygotowanie danych i inżynieria cech
- Flagi brakujących wartości
- Grupowanie DTI
- Identyfikacja plików o małej objętości
- Agregacja biurowa

2. Modelowanie ryzyka
- Transformacja WOE
- Wybór zmiennych oparty na IV
- Konstrukcja quasi-punktacji
- Analiza decylowa

3. Monitorowanie modelu
- Wskaźnik stabilności populacji (PSI)
- Macierz stabilności
- Migracja poziomów ryzyka

4. Warstwa zarządzania
- Progi apetytu na ryzyko
- Wskaźniki wczesnego ostrzegania
- Klasyfikacja alertów

Dostarczona wartość biznesowa:

- Zidentyfikowano kluczowe czynniki ryzyka (IV > 0,2)
- Stworzono strukturę segmentacji ryzyka
- Symulowano wpływ punktu odcięcia na DR portfela
- Wdrożono system wykrywania dryfu (PSI)
- Zaprojektowano panel oceny apetytu na ryzyko
- Stworzono system wczesnego ostrzegania
