## rust-harjoitukset
Täytellään Rust harjoituksia projects/ kansion alle.

## Docker jutut
- cd rust-docker-setup
- docker system prune -f
- docker-compose up --build
- docker-compose run --rm rust 
- docker rmi <id> -f


### Muistiinpanot
- use std::io
    - io = input / output
    - std = standard library
- fn main() {} (Pääohjelma)
    - fn = function
    - () parametrit, jos ei arvoja = ei parametrejä
- println!, tulostetaan arvo
- let, tehdään muuttuja em. (let apples = 5;)
    - Oletuksena muuttujat on immutable.
    - let mut rimpsulla asetetaan muuttuja muutettavaksi
- // kommentointi
- & = viittaus
    - viittaukset ovat oletuksena immutable
- crate on laajennus rustin koodiin
    - Cargo.toml tiedostossa on laajennuksille oma osuutensa
- cargo.lock tiedosto ylläpitää alkuperäiset versiot millä koodi on kasattu. (Tärkeä viedä versiohallintaan)



### Muuttujat
String = UTF-8 encoded bit of text