# BarteKasiAdam

## Rozwiązywany problem:
Problem: Klienci banku rezygnują z usług związanych z kartami kredytowymi. Chcemy zbadać, którzy klienci mogą być chętni do odejścia od tej usługi (customer churn).

Dane: Dane Credit Card dostępne są na kaggle: https://www.kaggle.com/sakshigoyal7/credit-card-customers
Zbiór danych zawiera 10 tyś. obserwacji, 18 zmiennych objaśniających.

W celu przygotowania modeli związanych z predykcją przepływu klinetów należy odtworzyć notebook: https://www.kaggle.com/alpertml/credit-card-customers-eda-ml-97-5-accuracy

W ramach projektu można również wytrenować swoje modele do porównania.

## Notatki:
1. Wczytaliśmy dane za pomocą kodu z kaggle. Okazało się, że Notebook ten jest błędny - autor twierdzi, że niema braków danych, a w rzeczywistości są 2 kolumny - "Income_Category" oraz "Education_Level" - posiadające kolejno 11% oraz 15% braków danych. Stworzyliśmy więc nową kolumnę informującą o tym, czy był to brak, a oryginalne kolumny zaimputowaliśmy ich modą. W przyszłym tygodniu będziemy pracować nad wstępną analizą modelu i rozpoczniemy jego wyjaśnianie.
2. 