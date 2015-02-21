> *Uważaj na człowieka, którego nie interesują szczegóły.*
>
> — William Feather


## Architektura Serwisów Internetowych 14/15

Terminy rozliczenia się z projektów:

* ***zaliczenie***: **ISODate("2015-04-02T12:00:00.000Z")**<br>
  opóźnienie do 48h – ocena -1, więcej – ocena -2
* ***egzamin***: **ISODate("2015-05-22T12:00:00.000Z")**<br>
  opóźnienie do 48h – ocena -1, więcej – egzamin poprawkowy
  we wrześniu

Aplikacje tworzymy w repozytoriach Git.
Każda aplikacja powinna korzystać z aktualnej wersji Ruby
oraz Ruby on Rails (na dzień 04.02.2015 są to 2.2.0 i 4.2.0, odpowiednio)
oraz aktualnych wersji gemów.

W repozytoriach nie powinno być śmieci, np. plików backup edytora.
Aplikacje na egzamin umieszczamy w repozytoriach prywatnych.

W aplikacjach na „na zaliczenie”:

* strony aplikacji powinny być responsywne
* powinno być zaimplementowane wyszukiwanie i paginacja
* do bazy danych należy dodać sporo sensownych przykładowych rekordów;
  w tym celu należy użyć pliku *db/seeds.rb*


## Użyteczne linki

* [Ruby style guide](https://github.com/bbatsov/ruby-style-guide):
  - [rubocop](https://github.com/bbatsov/rubocop) – a Ruby static code analyzer,
    based on the community Ruby style guide
* [Code Guide by @mdo](http://mdo.github.io/code-guide/) – HTML & CSS
* Every Dog has one Blog.
  [Must Have Gems for Development Machine in Ruby on Rails](http://www.codebeerstartups.com/2013/04/must-have-gems-for-development-machine-in-ruby-on-rails)
