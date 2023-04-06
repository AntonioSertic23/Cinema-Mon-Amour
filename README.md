# Cinema Mon Amour

## Aplikacija za vođenje evidencije filmova

Mobilna aplikacija Cinema Mon Amour je nastala na faksu kao projekt za konstrukcijske vježbe za predmet **Programiranje mobilnih aplikacija**.

Aplikacija služi za vođenje evidencije filmova kako bi si korisnik mogao pratiti omiljene pogledane filmove.

---

### U aplikaciji je moguće:

- vidjeti listu filmova
- pregled detalja filmova (datum izlaska, imdb ocjenu i opis)
- dodavanje filmova u favorite uz dodjelu vlastite ocjene pojedinom filmu
- pregled favorita gdje se vide svi dodani filmovi
- uklanjanje filmova iz favorita

---

Projekt je rađen u Android Studiu, a za programski jezik izabrana je **Java**. Primjenjena su znanja korištenja: activitya, adaptera, fragmenta, listenera, izrade modela i služenja network-om.

[![My Skills](https://skills.thijs.gg/icons?i=androidstudio,java,sqlite)](https://skills.thijs.gg)

Kao baza podataka izabrana je lokalna baza podataka **Room**, a za dohvaćanje podataka o filmovima koristi se **Retrofit** koji se spaja na [TMDb API](https://www.themoviedb.org/documentation/api).

---

### Pokretanje projekta

Za pokretanje projekta potrebno je kreirati vlastiti _api key_ na službenoj stranici **TMDb API-a**, potom dobiveni _api key_ zalijepiti u `cinemamonamour/fragments/Pop_Movies_Fragment.java` unutar:

```sh
public static final String API_KEY = "";
```
