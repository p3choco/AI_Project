Wynik pokazuje że zdecydowanie nie poradził sobie liniowy SVM. Jest to spowodowane tym że dane nie są liniowo separowalne. Ma on wynik gorszy niż losowy. Metryka na którą tu będziemy głównie patrzeć to f1_score ponieważ klasy nie są podzielone róznomiernie. f1_score w większości modeli pokazuje wynik w okolicach 0.4 co jest dość dobrym wynikiem dla przewidywania 10 klas ( prawdopodobieństwo ślepego trafu rzędu 0.1).


Podsumowując długość nazwy gry, rok jej wydania w połączeniu z typem rozgrywki pozwalają w pewnym stopniu przewidzieć jej popularność. Nie jest to niestety przyszłościowa metoda ( moje modele osiągnęły słabe wyniki ). Prawdopodobnie duże znaczenie mają współczynniki nie zawarte w datasecie czyli marketing, grywalność czy platformy na których gra była dostępna.
