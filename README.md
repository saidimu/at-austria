# Austria (Österreich)

## What's `football.db`?

A free open public domain football (soccer) database & schema
for use in any (programming) language
(e.g. uses plain text fixtures/data sets).
More [`football.db` Project Site »](http://openfootball.github.io)

## Intro

Free open public domain football data for Austria (Österreich) / Europe. Events include:

| Level |                                  |               |
| ----- | -------------------------------- | ------------- |
| I     |  Österr. Bundesliga              |  10 Clubs     |
| II    |  Erste Liga (1. Liga)            |  10 Clubs     |
| III   |  Regionalliga Ost, Mitte, West   |  3 x 16 Clubs |
|       |
| Cup   |  ÖFB (Austrian) Cup |


Example:

~~~
### Österr. Bundesliga Teams

austria,     FK Austria Wien|Austria Wien,                   AUS,  city:wien
salzburg,    FC RB Salzburg|RB Salzburg|Red Bull Salzburg,   RBS,  city:salzburg
...
~~~

~~~
### Österr. Bundesliga 2013/14

1. Runde  //  Sa+So 20.+21. Jul 2013

Sa, 20.07.2013 16.30  Austria Wien         FC Admira Wacker
Sa, 20.07.2013 19.00  SC Wiener Neustadt   RB Salzburg
...
~~~


## Build Your Own `football.db` Copy

To build your own `football.db` copy from the plain text fixtures
use the sportdb command line tool. Example:

Step 1:  Get a copy of the `world.db` fixtures

    $ git clone git://github.com/geraldb/world.db.git

Step 2:  Get a copy the `at-austria` fixtures

    $ git clone git://github.com/openfootball/at-austria.git

Step 3:  Let's build the `football.db`

    $ sportdb setup --include ./at-austria --worldinclude ./world.db

That's it. For more
see the [`sportdb` command line tool project](https://github.com/geraldb/sport.db.ruby).



## Links

### Web Admin App

Try the `football.db` Web Admin app running on Heroku
[`footballdb.herokuapp.com/at`](http://footballdb.herokuapp.com/at).

### Österreichische (Austrian) Bundesliga

Official Site - [`bundesliga.at` (de)](http://bundesliga.at)

- Teams: 10
- Matches: 180  (=36 (9x4) rounds x 5 matches)
- Rounds: 36 (=9x4 - each 5 matches)

| Level |                     |                |     |
| ----- | ------------------- | -------------- | --- |
|   I   | Österr. Bundesliga  | 10 Clubs       |
|       |   ↓↑ 1 club                          |
|   II  | Erste Liga          | 10 Clubs       |
|       |   ↓↑ 1-2 clubs                       |
|       |   ↑ 0-1 club                |   ↑ 0-1 club                     |     ↑ 0-1 club                 |
|   III | Regionalliga Ost - 16 Clubs |   Regionalliga Mitte - 16 Clubs  |   Regionalliga West - 16 Clubs |
|       |   ↓ 2-5 clubs               |   ↓ 2-5 clubs                    |     ↓ 2-5 clubs                |
|       |
|   IV  | Landesliga Burgenland        | 16 clubs | ↑ 1 club |
|       | Landesliga Niederösterreich  | 16 clubs | ↑ 1 club |
|       | Wiener Stadtliga             | 16 clubs | ↑ 1 club |
|       | 
|       | Landesliga Steiermark        | 16 clubs | ↑ 1 club |
|       | Landesliga Oberösterreich    | 14 clubs | ↑ 1 club |
|       | Landesliga Kärnten           | 16 clubs | ↑ 1 club |
|       | 
|       | Landesliga Salzburg          | 16 clubs | ↑ 1 club |
|       | Tiroler Liga                 | 16 clubs | ↑ 1 club |
|       | Landesliga Vorarlberg        | 14 clubs | ↑ 1 club |


#### Wikipedia

- [Österreichische_Fußballmeisterschaft_2013/14 (de)](http://de.wikipedia.org/wiki/Österreichische_Fußballmeisterschaft_2013/14)
- [Österreichische_Fußballmeisterschaft_2012/13 (de)](http://de.wikipedia.org/wiki/Österreichische_Fußballmeisterschaft_2012/13)
- [Österreichische_Fußballmeisterschaft_2011/12 (de)](http://de.wikipedia.org/wiki/Österreichische_Fußballmeisterschaft_2011/12)

### ÖFB Cup

- Teams: 64

ÖFB = Österreichischer Fußball-Bund (Austrian Football Association)


#### Wikipedia

- [Österreichischer_Fußball-Cup_2013/14 (de)](http://de.wikipedia.org/wiki/Österreichischer_Fußball-Cup_2013/14)
- [Österreichischer_Fußball-Cup_2012/13 (de)](http://de.wikipedia.org/wiki/Österreichischer_Fußball-Cup_2012/13)
- [Österreichischer_Fußball-Cup_2011/12 (de)](http://de.wikipedia.org/wiki/Österreichischer_Fußball-Cup_2011/12)


### Wikipedia

- [Football_in_Austria](http://en.wikipedia.org/wiki/Football_in_Austria)


### Sports Newspapers

- Sport Woche (1x week)
- Sport Zeitung (1x week)



## Questions? Comments?

Send them along to the
[Open Sports & Friends Forum/Mailing List](http://groups.google.com/group/opensport).
Thanks!