# Scitizia: 89 low poly rally cars in glTF/GLB with a retro 64-bit look

🇬🇧 English · **🇧🇷 [Leia em português](README.md)**

![Mosaic with the 89 low poly rally cars of the Scitizia fleet, in front three-quarter view: hatchbacks, coupes, sedans, wagons, minivans, prototypes, pickups and vans with made-up rally liveries](docs/frota-89-carros-rali-low-poly.jpg)

https://github.com/user-attachments/assets/331c06f0-8b64-4a61-bd34-ac46b8475eb9

▶️ **[Watch the video on YouTube](https://www.youtube.com/watch?v=G-UUvOGup1g)** · **[Download on itch.io](https://kkyqr.itch.io/scitizia-rally-fleet-64)** (free, optional donation)

**Scitizia: 64-bit fleet** is a free collection of 89 fictional low poly rally cars with the retro look of 64-bit consoles, ready for real-time games. There are 7 classes (C1 Rookie to C7 Off-road), from budget hatchbacks to cross-country rally pickups, with models from 1974 to 2010 and nine body types with their own silhouettes (hatchback, sedan, wagon, coupe, convertible, SUV, pickup, minivan, van). 12 of them are stock street cars from 4 made-up brands, with the proportions and physics of ordinary cars of each era. Each car is a binary glTF 2.0 file (`.glb`) of 152 to 230 KB, with 2,844 to 4,506 triangles, one 256×256 px texture for the body and one 128×64 px texture for the wheels (the street cars have one more, 128×40 px, for the license plates), separate wheels that can spin and steer, and a flat shadow. The cars were made for the game **Scitizia Rally Championship**; names, brands, shapes and liveries are made up, with no real manufacturer, model or sponsor.

## Summary

| | |
|---|---|
| Cars | 89 in 7 classes (C1 19, C2 15, C3 11, C4 11, C5 11, C6 11, C7 11) |
| Format | binary glTF 2.0 (`.glb`), textures also as PNG |
| Triangles per car | 2,844 to 4,506 |
| Textures | body 256×256 px, wheels 128×64 px, plates 128×40 px (street cars) |
| Scale and axes | meters, Y up, front facing +Z, left side at +X |
| Objects | `Carroceria`, doors (`Porta_E`, `Porta_D`, `Porta_TE`, `Porta_TD`), `Capo` and `Tampa` with the pivot at the hinge, `Farol`, `Lanterna`, `Interior`, four wheels (`Roda_DE`, `Roda_DD`, `Roda_TE`, `Roda_TD`), `Sombra` |
| Model years | 1974 to 2010 |
| Body types | Hatchback (31), Sedan (7), Wagon (8), Coupe (10), Convertible (6), SUV (7), Pickup (8), Minivan (7), Van (5) |
| Stock street cars | 12, from the made-up brands Ardena, Castrel, Nimbo, Vortan |
| Machine-readable catalog | [`catalogo.json`](catalogo.json) |

## Cars by class

The tables give the model year, body type, archetype, drive (FWD front-wheel drive, RWD rear-wheel drive, AWD all-wheel drive), power (cv, metric horsepower), mass and the ID, the game's Performance Index (100 to 999), calculated from each car's physics sheet. Within each class the cars follow the order of the years. The stock street cars show the made-up brand next to the archetype.

### C1 Rookie

Rally budget cars and stock street cars, all front-wheel drive and naturally aspirated. Body types: hatchback, coupe, wagon, pickup, minivan, van, sedan, convertible, SUV. 19 cars, ID from 312 to 386, power from 58 to 107 cv, mass from 800 to 1,180 kg.

| Preview | Car | Year | Body | Archetype | Drive | Power | Mass | ID |
|---|---|---|---|---|---|---|---|---|
| ![Bombom 1.3, low poly street car of class C1 Rookie](previas/bombom.jpg) | **Bombom 1.3** | 1974 | Hatchback | Small 3-door hatchback (street, Nimbo) | FWD | 61 cv | 820 kg | 319 |
| ![Dengo 1.6, low poly street car of class C1 Rookie](previas/dengo.jpg) | **Dengo 1.6** | 1977 | Coupe | Mid-size 2-door coupe (street, Castrel) | FWD | 80 cv | 920 kg | 343 |
| ![Rapadura 1.6, low poly street car of class C1 Rookie](previas/rapadura.jpg) | **Rapadura 1.6** | 1982 | Wagon | Mid-size wagon (street, Castrel) | FWD | 75 cv | 960 kg | 318 |
| ![Xodó 1.0, low poly rally car of class C1 Rookie](previas/xodo.jpg) | **Xodó 1.0** | 1991 | Hatchback | Budget compact hatchback | FWD | 87 cv | 930 kg | 361 |
| ![Cocada 1.0, low poly street car of class C1 Rookie](previas/cocada.jpg) | **Cocada 1.0** | 1992 | Hatchback | Budget hatchback with straight lines (street, Nimbo) | FWD | 58 cv | 800 kg | 318 |
| ![Miúdo 1.4, low poly rally car of class C1 Rookie](previas/miudo.jpg) | **Miúdo 1.4** | 1993 | Hatchback | Budget compact hatchback | FWD | 95 cv | 1,000 kg | 373 |
| ![Pipoca 1.3, low poly rally car of class C1 Rookie](previas/pipoca.jpg) | **Pipoca 1.3** | 1994 | Wagon | Budget compact wagon | FWD | 98 cv | 1,070 kg | 357 |
| ![Cuscuz 1.4, low poly rally car of class C1 Rookie](previas/cuscuz.jpg) | **Cuscuz 1.4** | 1996 | Pickup | Compact pickup | FWD | 97 cv | 990 kg | 354 |
| ![Pudim 1.6, low poly street car of class C1 Rookie](previas/pudim.jpg) | **Pudim 1.6** | 1996 | Minivan | Compact double-floor minivan (street, Ardena) | FWD | 100 cv | 1,120 kg | 362 |
| ![Pirulito 1.0, low poly street car of class C1 Rookie](previas/pirulito.jpg) | **Pirulito 1.0** | 1997 | Hatchback | Budget compact hatchback (street, Castrel) | FWD | 60 cv | 880 kg | 312 |
| ![Cafuné 1.0, low poly rally car of class C1 Rookie](previas/cafune.jpg) | **Cafuné 1.0** | 1998 | Van | Compact delivery van | FWD | 98 cv | 990 kg | 338 |
| ![Brigadeiro 1.8, low poly street car of class C1 Rookie](previas/brigadeiro.jpg) | **Brigadeiro 1.8** | 1999 | Hatchback | Mid-size hatchback with angular lines (street, Castrel) | FWD | 106 cv | 1,180 kg | 371 |
| ![Quindim 1.6, low poly rally car of class C1 Rookie](previas/quindim.jpg) | **Quindim 1.6** | 1999 | Sedan | Budget compact sedan | FWD | 101 cv | 1,090 kg | 372 |
| ![Canjica 1.6, low poly rally car of class C1 Rookie](previas/canjica.jpg) | **Canjica 1.6** | 2001 | Convertible | Compact convertible | FWD | 96 cv | 1,000 kg | 386 |
| ![Jujuba 1.0, low poly street car of class C1 Rookie](previas/jujuba.jpg) | **Jujuba 1.0** | 2002 | Hatchback | Subcompact with rounded lines (street, Castrel) | FWD | 65 cv | 900 kg | 327 |
| ![Paçoca 1.4, low poly rally car of class C1 Rookie](previas/pacoca.jpg) | **Paçoca 1.4** | 2002 | Minivan | Budget compact minivan | FWD | 97 cv | 1,070 kg | 364 |
| ![Guri 1.4, low poly rally car of class C1 Rookie](previas/guri.jpg) | **Guri 1.4** | 2003 | Hatchback | Budget compact hatchback | FWD | 96 cv | 1,020 kg | 368 |
| ![Pamonha 1.6, low poly rally car of class C1 Rookie](previas/pamonha.jpg) | **Pamonha 1.6** | 2007 | SUV | Compact SUV | FWD | 107 cv | 1,130 kg | 347 |
| ![Chuchu 1.6, low poly rally car of class C1 Rookie](previas/chuchu.jpg) | **Chuchu 1.6** | 2008 | Hatchback | Compact adventure hatchback | FWD | 102 cv | 1,080 kg | 368 |

### C2 Kit Car

Tuned sports cars (kit car) and stock sporty mid-size hatchbacks, front-wheel drive and naturally aspirated or turbo engines. Body types: hatchback, convertible, coupe, pickup, sedan, wagon, minivan. 15 cars, ID from 398 to 452, power from 100 to 129 cv, mass from 940 to 1,230 kg.

| Preview | Car | Year | Body | Archetype | Drive | Power | Mass | ID |
|---|---|---|---|---|---|---|---|---|
| ![Fósforo 16, low poly street car of class C2 Kit Car](previas/fosforo.jpg) | **Fósforo 16** | 1983 | Hatchback | Sporty 3-door hatchback (street, Castrel) | FWD | 100 cv | 950 kg | 398 |
| ![Rastilho 18, low poly street car of class C2 Kit Car](previas/rastilho.jpg) | **Rastilho 18** | 1984 | Hatchback | Sporty mid-size 3-door hatchback (street, Vortan) | FWD | 100 cv | 940 kg | 402 |
| ![Lampejo 20, low poly street car of class C2 Kit Car](previas/lampejo.jpg) | **Lampejo 20** | 1991 | Hatchback | Sporty mid-size hatchback (street, Vortan) | FWD | 124 cv | 1,150 kg | 419 |
| ![Fagulha 20, low poly rally car of class C2 Kit Car](previas/fagulha.jpg) | **Fagulha 20** | 1992 | Hatchback | Tuned sports hatchback (kit car) | FWD | 116 cv | 950 kg | 447 |
| ![Pirilampo 18, low poly rally car of class C2 Kit Car](previas/pirilampo.jpg) | **Pirilampo 18** | 1993 | Convertible | Tuned sports convertible (kit car) | FWD | 118 cv | 1,000 kg | 438 |
| ![Faísca KC, low poly rally car of class C2 Kit Car](previas/faisca.jpg) | **Faísca KC** | 1994 | Hatchback | Tuned sports hatchback (kit car) | FWD | 120 cv | 1,000 kg | 444 |
| ![Chispa 18, low poly rally car of class C2 Kit Car](previas/chispa.jpg) | **Chispa 18** | 1995 | Coupe | Tuned sports coupe (kit car) | FWD | 113 cv | 980 kg | 429 |
| ![Centelha 2.0, low poly rally car of class C2 Kit Car](previas/centelha.jpg) | **Centelha 2.0** | 1997 | Hatchback | Tuned sports hatchback (kit car) | FWD | 122 cv | 1,030 kg | 444 |
| ![Pólvora 18, low poly street car of class C2 Kit Car](previas/polvora.jpg) | **Pólvora 18** | 1998 | Hatchback | Sporty mid-size turbo hatchback (street, Vortan) | FWD | 126 cv | 1,230 kg | 411 |
| ![Isqueiro 18, low poly rally car of class C2 Kit Car](previas/isqueiro.jpg) | **Isqueiro 18** | 1999 | Pickup | Tuned compact sports pickup | FWD | 126 cv | 1,050 kg | 418 |
| ![Pavio 2.0, low poly rally car of class C2 Kit Car](previas/pavio.jpg) | **Pavio 2.0** | 2000 | Sedan | Tuned sports sedan (kit car) | FWD | 118 cv | 1,000 kg | 436 |
| ![Estopim 1.8, low poly rally car of class C2 Kit Car](previas/estopim.jpg) | **Estopim 1.8** | 2002 | Wagon | Tuned sports wagon (kit car) | FWD | 124 cv | 1,050 kg | 432 |
| ![Tocha 20, low poly rally car of class C2 Kit Car](previas/tocha.jpg) | **Tocha 20** | 2003 | Minivan | Tuned sports minivan | FWD | 128 cv | 1,080 kg | 410 |
| ![Labareda 2.0, low poly rally car of class C2 Kit Car](previas/labareda.jpg) | **Labareda 2.0** | 2004 | Hatchback | Tuned sports hatchback (kit car) | FWD | 126 cv | 1,050 kg | 449 |
| ![Rojão 2.0, low poly rally car of class C2 Kit Car](previas/rojao.jpg) | **Rojão 2.0** | 2009 | Hatchback | Tuned sports hatchback (kit car) | FWD | 129 cv | 1,060 kg | 452 |

### C3 Classic

Rear-wheel drive, naturally aspirated engines from 2.4 to 3.5. Body types: coupe, pickup, hatchback, wagon, convertible, van, sedan, SUV. 11 cars, ID from 486 to 547, power from 162 to 188 cv, mass from 1,000 to 1,180 kg.

| Preview | Car | Year | Body | Archetype | Drive | Power | Mass | ID |
|---|---|---|---|---|---|---|---|---|
| ![Brasa 24, low poly rally car of class C3 Classic](previas/brasa.jpg) | **Brasa 24** | 1986 | Coupe | Rear-wheel drive coupe | RWD | 170 cv | 1,050 kg | 529 |
| ![Braseiro 25, low poly rally car of class C3 Classic](previas/braseiro.jpg) | **Braseiro 25** | 1990 | Coupe | Rear-wheel drive coupe | RWD | 162 cv | 1,020 kg | 521 |
| ![Tição 30, low poly rally car of class C3 Classic](previas/ticao.jpg) | **Tição 30** | 1993 | Pickup | Rear-wheel drive sports pickup | RWD | 187 cv | 1,180 kg | 499 |
| ![Caldeira 28, low poly rally car of class C3 Classic](previas/caldeira.jpg) | **Caldeira 28** | 1995 | Hatchback | Rear-wheel drive hatchback | RWD | 167 cv | 1,000 kg | 542 |
| ![Forja 26, low poly rally car of class C3 Classic](previas/forja.jpg) | **Forja 26** | 1996 | Wagon | Rear-wheel drive wagon | RWD | 176 cv | 1,160 kg | 502 |
| ![Fornalha 28, low poly rally car of class C3 Classic](previas/fornalha.jpg) | **Fornalha 28** | 1998 | Convertible | Rear-wheel drive convertible | RWD | 172 cv | 1,030 kg | 547 |
| ![Borralho 30, low poly rally car of class C3 Classic](previas/borralho.jpg) | **Borralho 30** | 2000 | Van | Tuned rear-wheel drive van | RWD | 183 cv | 1,120 kg | 486 |
| ![Candeia 30, low poly rally car of class C3 Classic](previas/candeia.jpg) | **Candeia 30** | 2003 | Sedan | Rear-wheel drive sedan | RWD | 184 cv | 1,130 kg | 535 |
| ![Lampião 32, low poly rally car of class C3 Classic](previas/lampiao.jpg) | **Lampião 32** | 2005 | Coupe | Rear-wheel drive coupe | RWD | 188 cv | 1,150 kg | 541 |
| ![Rescaldo 32, low poly rally car of class C3 Classic](previas/rescaldo.jpg) | **Rescaldo 32** | 2006 | SUV | Rear-wheel drive SUV | RWD | 184 cv | 1,120 kg | 504 |
| ![Fogareiro 35, low poly rally car of class C3 Classic](previas/fogareiro.jpg) | **Fogareiro 35** | 2007 | Coupe | Rear-wheel drive coupe | RWD | 185 cv | 1,130 kg | 541 |

### C4 Production

Stock cars with all-wheel drive and turbo engines. Body types: sedan, wagon, coupe, pickup, convertible, minivan, SUV, hatchback, van. 11 cars, ID from 541 to 613, power from 190 to 229 cv, mass from 1,240 to 1,520 kg.

| Preview | Car | Year | Body | Archetype | Drive | Power | Mass | ID |
|---|---|---|---|---|---|---|---|---|
| ![Relâmpago 20, low poly rally car of class C4 Production](previas/relampago.jpg) | **Relâmpago 20** | 1991 | Sedan | Turbo 4x4 sedan | AWD | 190 cv | 1,240 kg | 599 |
| ![Trovão 4T, low poly rally car of class C4 Production](previas/trovao.jpg) | **Trovão 4T** | 1992 | Sedan | Stock turbo 4x4 sedan | AWD | 204 cv | 1,300 kg | 605 |
| ![Trovoada 22, low poly rally car of class C4 Production](previas/trovoada.jpg) | **Trovoada 22** | 1993 | Wagon | Turbo 4x4 wagon | AWD | 199 cv | 1,290 kg | 604 |
| ![Temporal 20, low poly rally car of class C4 Production](previas/temporal.jpg) | **Temporal 20** | 1997 | Coupe | Turbo 4x4 coupe | AWD | 203 cv | 1,270 kg | 613 |
| ![Granizo 22, low poly rally car of class C4 Production](previas/granizo.jpg) | **Granizo 22** | 1998 | Pickup | Turbo 4x4 double-cab pickup | AWD | 220 cv | 1,440 kg | 581 |
| ![Rajada 20, low poly rally car of class C4 Production](previas/rajada.jpg) | **Rajada 20** | 1999 | Convertible | Turbo 4x4 convertible | AWD | 200 cv | 1,250 kg | 610 |
| ![Tormenta 25, low poly rally car of class C4 Production](previas/tormenta.jpg) | **Tormenta 25** | 2002 | Wagon | Turbo 4x4 wagon | AWD | 215 cv | 1,390 kg | 602 |
| ![Aguaceiro 20, low poly rally car of class C4 Production](previas/aguaceiro.jpg) | **Aguaceiro 20** | 2003 | Minivan | Turbo 4x4 minivan | AWD | 216 cv | 1,440 kg | 558 |
| ![Borrasca 20, low poly rally car of class C4 Production](previas/borrasca.jpg) | **Borrasca 20** | 2004 | SUV | Turbo 4x4 SUV | AWD | 229 cv | 1,520 kg | 559 |
| ![Corisco 20, low poly rally car of class C4 Production](previas/corisco.jpg) | **Corisco 20** | 2007 | Hatchback | Turbo 4x4 hatchback | AWD | 203 cv | 1,270 kg | 605 |
| ![Chuvarada 25, low poly rally car of class C4 Production](previas/chuvarada.jpg) | **Chuvarada 25** | 2008 | Van | Turbo 4x4 van | AWD | 220 cv | 1,470 kg | 541 |

### C5 Elite

Rally prototypes, all-wheel drive and 1.6 turbo engine. Body types: hatchback, coupe, sedan, minivan, wagon, pickup, SUV. 11 cars, ID from 647 to 727, power from 218 to 242 cv, mass from NaN to NaN kg.

| Preview | Car | Year | Body | Archetype | Drive | Power | Mass | ID |
|---|---|---|---|---|---|---|---|---|
| ![Quartzo 16, low poly rally car of class C5 Elite](previas/quartzo.jpg) | **Quartzo 16** | 1992 | Hatchback | Rally prototype on a hatchback base | AWD | 218 cv | 1,090 kg | 702 |
| ![Basalto 16, low poly rally car of class C5 Elite](previas/basalto.jpg) | **Basalto 16** | 1995 | Coupe | Rally prototype on a coupe base | AWD | 233 cv | 1,130 kg | 725 |
| ![Granito 16, low poly rally car of class C5 Elite](previas/granito.jpg) | **Granito 16** | 1997 | Sedan | Rally prototype on a sedan base | AWD | 224 cv | 1,230 kg | 668 |
| ![Malaquita 16, low poly rally car of class C5 Elite](previas/malaquita.jpg) | **Malaquita 16** | 1999 | Minivan | Rally prototype on a minivan base | AWD | 238 cv | 1,270 kg | 650 |
| ![Turmalina 16, low poly rally car of class C5 Elite](previas/turmalina.jpg) | **Turmalina 16** | 2000 | Hatchback | Rally prototype on a hatchback base | AWD | 233 cv | 1,120 kg | 726 |
| ![Jaspe 16, low poly rally car of class C5 Elite](previas/jaspe.jpg) | **Jaspe 16** | 2001 | Wagon | Rally prototype on a wagon base | AWD | 228 cv | 1,290 kg | 647 |
| ![Obsidiana 16, low poly rally car of class C5 Elite](previas/obsidiana.jpg) | **Obsidiana 16** | 2003 | Pickup | Rally prototype on a pickup base | AWD | 239 cv | 1,200 kg | 679 |
| ![Ágata 16, low poly rally car of class C5 Elite](previas/agata.jpg) | **Ágata 16** | 2004 | Hatchback | Rally prototype on a hatchback base | AWD | 239 cv | 1,150 kg | 727 |
| ![Citrino 16, low poly rally car of class C5 Elite](previas/citrino.jpg) | **Citrino 16** | 2006 | SUV | Rally prototype on an SUV base | AWD | 242 cv | 1,270 kg | 653 |
| ![Scitizia R5, low poly rally car of class C5 Elite](previas/scitizia.jpg) | **Scitizia R5** | 2008 | Hatchback | Rally prototype on a hatchback base | AWD | 228 cv | NaN kg | 708 |
| ![Ametista 16, low poly rally car of class C5 Elite](previas/ametista.jpg) | **Ametista 16** | 2009 | Hatchback | Rally prototype on a hatchback base | AWD | 238 cv | 1,170 kg | 718 |

### C6 Open Group

Unrestricted monsters, all-wheel drive and turbo engines from 2.1 to 2.7. Body types: hatchback, van, coupe, sedan, minivan, convertible, SUV. 11 cars, ID from 841 to 917, power from 301 to 344 cv, mass from 1,030 to 1,250 kg.

| Preview | Car | Year | Body | Archetype | Drive | Power | Mass | ID |
|---|---|---|---|---|---|---|---|---|
| ![Vendaval B, low poly rally car of class C6 Open Group](previas/vendaval.jpg) | **Vendaval B** | 1985 | Hatchback | Unrestricted monster on a hatchback base | AWD | 306 cv | 1,100 kg | 896 |
| ![Ventania 21, low poly rally car of class C6 Open Group](previas/ventania.jpg) | **Ventania 21** | 1991 | Hatchback | Unrestricted monster on a hatchback base | AWD | 301 cv | 1,030 kg | 909 |
| ![Lestada 22, low poly rally car of class C6 Open Group](previas/lestada.jpg) | **Lestada 22** | 1993 | Van | Unrestricted monster on a van base | AWD | 344 cv | 1,250 kg | 841 |
| ![Redemoinho 22, low poly rally car of class C6 Open Group](previas/redemoinho.jpg) | **Redemoinho 22** | 1994 | Coupe | Unrestricted monster on a coupe base | AWD | 330 cv | 1,080 kg | 917 |
| ![Minuano 23, low poly rally car of class C6 Open Group](previas/minuano.jpg) | **Minuano 23** | 1996 | Sedan | Unrestricted monster on a sedan base | AWD | 316 cv | 1,180 kg | 875 |
| ![Lufada 24, low poly rally car of class C6 Open Group](previas/lufada.jpg) | **Lufada 24** | 1999 | Hatchback | Unrestricted monster on a hatchback base | AWD | 318 cv | 1,060 kg | 914 |
| ![Rabanada 24, low poly rally car of class C6 Open Group](previas/rabanada.jpg) | **Rabanada 24** | 2001 | Minivan | Unrestricted monster on a minivan base | AWD | 341 cv | 1,220 kg | 871 |
| ![Procela 25, low poly rally car of class C6 Open Group](previas/procela.jpg) | **Procela 25** | 2003 | Convertible | Unrestricted monster on a convertible base | AWD | 337 cv | 1,200 kg | 907 |
| ![Rebojo 26, low poly rally car of class C6 Open Group](previas/rebojo.jpg) | **Rebojo 26** | 2005 | Hatchback | Unrestricted monster on a hatchback base | AWD | 309 cv | 1,100 kg | 902 |
| ![Aracati 25, low poly rally car of class C6 Open Group](previas/aracati.jpg) | **Aracati 25** | 2008 | SUV | Unrestricted monster on an SUV base | AWD | 337 cv | 1,210 kg | 862 |
| ![Terral 27, low poly rally car of class C6 Open Group](previas/terral.jpg) | **Terral 27** | 2010 | Hatchback | Unrestricted monster on a hatchback base | AWD | 325 cv | 1,190 kg | 893 |

### C7 Off-road

Cross-country rally, all-wheel drive, the heaviest cars in the fleet. Body types: van, convertible, pickup, hatchback, SUV, wagon, minivan, coupe. 11 cars, ID from 522 to 590, power from 238 to 296 cv, mass from 1,630 to 2,050 kg.

| Preview | Car | Year | Body | Archetype | Drive | Power | Mass | ID |
|---|---|---|---|---|---|---|---|---|
| ![Lajedo 32, low poly rally car of class C7 Off-road](previas/lajedo.jpg) | **Lajedo 32** | 1990 | Van | Cross-country rally van | AWD | 275 cv | 2,000 kg | 522 |
| ![Atoleiro 31, low poly rally car of class C7 Off-road](previas/atoleiro.jpg) | **Atoleiro 31** | 1992 | Convertible | Open cross-country rally utility vehicle | AWD | 238 cv | 1,630 kg | 553 |
| ![Jararaca 30, low poly rally car of class C7 Off-road](previas/jararaca.jpg) | **Jararaca 30** | 1995 | Pickup | Cross-country rally pickup | AWD | 283 cv | 1,900 kg | 565 |
| ![Baixio 28, low poly rally car of class C7 Off-road](previas/baixio.jpg) | **Baixio 28** | 1996 | Hatchback | Raised 4x4 cross-country rally hatchback | AWD | 246 cv | 1,680 kg | 556 |
| ![Boqueirão 34, low poly rally car of class C7 Off-road](previas/boqueirao.jpg) | **Boqueirão 34** | 1997 | SUV | Cross-country rally SUV | AWD | 279 cv | 1,860 kg | 564 |
| ![Chapada 33, low poly rally car of class C7 Off-road](previas/chapada.jpg) | **Chapada 33** | 1998 | Wagon | 4x4 cross-country rally wagon | AWD | 296 cv | 2,030 kg | 565 |
| ![Grota 35, low poly rally car of class C7 Off-road](previas/grota.jpg) | **Grota 35** | 2001 | Pickup | Double-cab cross-country rally pickup | AWD | 280 cv | 2,030 kg | 540 |
| ![Vereda 30, low poly rally car of class C7 Off-road](previas/vereda.jpg) | **Vereda 30** | 2004 | Minivan | 4x4 cross-country rally minivan | AWD | 259 cv | 1,810 kg | 552 |
| ![Caatinga 36, low poly rally car of class C7 Off-road](previas/caatinga.jpg) | **Caatinga 36** | 2005 | SUV | Cross-country rally SUV | AWD | 265 cv | 1,900 kg | 539 |
| ![Tabuleiro 37, low poly rally car of class C7 Off-road](previas/tabuleiro.jpg) | **Tabuleiro 37** | 2008 | Pickup | Double-cab cross-country rally pickup | AWD | 286 cv | 2,050 kg | 545 |
| ![Serrote 32, low poly rally car of class C7 Off-road](previas/serrote.jpg) | **Serrote 32** | 2009 | Coupe | Raised 4x4 cross-country rally coupe | AWD | 267 cv | 1,750 kg | 590 |

## Stock street cars

The 12 street cars use the proportions of ordinary cars of each era (length, wheelbase, height, overhang, small 13 to 16 inch wheels) and stock car physics: mass, power, torque, gear spacing and final drive ratio for the car type. The brands are made up and appear in the `marca` field of the sheet and the catalog. They come with stock trim (`"decoracao": "rua"` in the sheet): no competition number, no hood stripes, no fog lights and no mud flaps, with a made-up period license plate (yellow until the 1980s, gray afterwards), trim strips, door handles, taillights with a frame, black or chrome mirrors, hubcaps and street tires.

| Car | Class | Made-up brand | Year | Body | Car type |
|---|---|---|---|---|---|
| **Bombom 1.3** | C1 | Nimbo | 1974 | Hatchback | Small 3-door hatchback |
| **Dengo 1.6** | C1 | Castrel | 1977 | Coupe | Mid-size 2-door coupe |
| **Rapadura 1.6** | C1 | Castrel | 1982 | Wagon | Mid-size wagon |
| **Cocada 1.0** | C1 | Nimbo | 1992 | Hatchback | Budget hatchback with straight lines |
| **Pudim 1.6** | C1 | Ardena | 1996 | Minivan | Compact double-floor minivan |
| **Pirulito 1.0** | C1 | Castrel | 1997 | Hatchback | Budget compact hatchback |
| **Brigadeiro 1.8** | C1 | Castrel | 1999 | Hatchback | Mid-size hatchback with angular lines |
| **Jujuba 1.0** | C1 | Castrel | 2002 | Hatchback | Subcompact with rounded lines |
| **Fósforo 16** | C2 | Castrel | 1983 | Hatchback | Sporty 3-door hatchback |
| **Rastilho 18** | C2 | Vortan | 1984 | Hatchback | Sporty mid-size 3-door hatchback |
| **Lampejo 20** | C2 | Vortan | 1991 | Hatchback | Sporty mid-size hatchback |
| **Pólvora 18** | C2 | Vortan | 1998 | Hatchback | Sporty mid-size turbo hatchback |

## Style of each period

The period of each car's year shows in the proportions and details of the body:

- **1970s**: low bodies with straight lines, round or rectangular headlights and chrome bumpers;
- **1980s**: straight-edged bodies with sharp corners, rectangular or round headlights, dark or chrome bumpers and, on the rally cars, lots of accessories;
- **1990-1995**: straight lines, more upright windshield, thin rectangular headlights and dark bumpers;
- **1996-2000**: rounded shapes, oval headlights, low beltline; the ones with angular lines have an arched roof and tall taillights;
- **2001-2005**: taller bodies, more raked windshield, teardrop headlights and body-colored bumpers;
- **2006-2010**: high beltline, smaller windows, large swept-back headlights; the adventure models get plastic guards.

## Folders

- `modelos/<id>.glb`: the car, ready for real-time use.
- `texturas/<id>_carroceria.png` and `texturas/<id>_roda.png` (and `texturas/<id>_placa.png` on the street cars): the textures as PNG (the same ones embedded in the `.glb`).
- `texturas_hd/<id>_carroceria.webp`, `<id>_roda.webp` (and `<id>_placa.webp`): the same textures eight times larger (2048×2048, 1024×512 and 1024×320 px), repainted by the generator with detail that only shows up close (seams, window rubber, rivets, wear, paint grain, tire tread, lug nuts, smooth lettering on the plate). They use the same UV mapping: just swap the material's image.
- `previas/<id>.jpg`: four views of each car.
- `fichas/<id>.json`: the car's sheet in the game, with name, class, year, body type, archetype, engine and drive (and the made-up brand, on the street cars). The `fisica` section has mass, dimensions, axles, track widths, wheels, power and drive; the `forma` section has the parameters that generate the body (profile, cabin, headlights, colors, paint and accessories).
- `catalogo.json`: list of the 89 cars with class, year, body type, archetype, drive, power, mass, ID and the paths of the model, the preview, the sheet and the textures.
- `docs/`: cover image.

## How to use the models

- Meters, Y axis up. The front of the car points to +Z and the left side to +X. The origin sits on the ground, between the axles.
- Objects in each file:
  - `Carroceria`: body, glass and fixed accessories, with several materials.
  - `Porta_E`, `Porta_D` (and `Porta_TE`, `Porta_TD` on the 4-door cars), `Capo` and `Tampa` (or `Tampa_E`/`Tampa_D` on the vans): empty nodes at the hinge with the child mesh `<name>_malha`. Closed, they sit exactly where the bodywork is. The node's `extras` say how to open it: `movimento` ("giro" or "corre"), `eixo` and `angulo` (degrees, in the file's reference frame) or `desloca` (meters, sliding door).
  - `Farol` and `Lanterna`: films over the lenses, with their own materials (`Farol`, `Lanterna`), to light up with emission. `Interior`: dark boxes on the inside, which show when a part opens.
  - `Roda_DE`, `Roda_DD`, `Roda_TE`, `Roda_TD`: the four wheels (front/rear, left/right), with the origin at the center of the wheel. Rotate around the X axis to spin and around Y to steer.
  - `Pinca_XX` (only on the Scitizia R5): brake calipers, which steer but do not spin.
  - `Sombra`: a dark transparent blob to place on the ground under the car.
- Matte materials match the look: simple diffuse, bilinear filtering and distance fog.

## Frequently asked questions

**What format are the cars in?**
Binary glTF 2.0 (`.glb`), one file per car, with meshes, materials and textures embedded. The textures are also available as loose PNG files in the `texturas/` folder.

**What are the scale and orientation of the models?**
The scale is in meters, with Y up, the front of the car at +Z and the left side at +X. The origin sits on the ground, in the middle of the wheelbase.

**Can I import them into any game engine or 3D program?**
Yes, into any engine, web library or 3D editor that reads glTF 2.0. There are no proprietary extensions: only meshes, simple materials and PNG textures.

**How many triangles does each car have?**
Between 2,844 and 4,506 triangles, counting body, wheels and shadow. The files are 152 to 230 KB.

**What textures do the cars use?**
A 256×256 px texture for the body (paint, headlights, numbers and details) and a 128×64 px one for the wheels; the street cars have one more, 128×40 px, with the plate. The look calls for bilinear filtering and matte materials. For close-up views, the `texturas_hd/` folder has the same textures in high resolution (WebP, 8× larger), with the same UV.

**Do the wheels spin and steer?**
Yes. Each wheel is a separate object with its origin at the center: rotate around the X axis to spin and around the Y axis to steer.

**Do the cars copy real models?**
No. All the cars, names, brands and liveries are fictional, inspired only by generic archetypes (budget hatchback, kit car, rear-wheel drive coupe, turbo 4x4 sedan, prototype, cross-country pickup, ordinary street cars of each era), with no real manufacturer, model or sponsor.

**What is in the JSON sheets?**
Each `fichas/<id>.json` has the identification (name, class, year, body type, archetype, engine, drive and, on the street cars, the made-up brand and the torque), the `fisica` section used by the game (mass, dimensions, axles, track widths, wheel radius, power, gears) and the `forma` section, with the parameters that generate the body.

**What is the ID in the tables?**
It is the game's Performance Index, from 100 to 999, which combines power-to-weight ratio, top speed, traction, handling and braking. It is used to compare cars from different classes.

**How do I list the cars in a program?**
Read the [`catalogo.json`](catalogo.json): it has the 89 cars with all the data from the tables and the file paths of each one.

## License

[CC0 1.0 Universal](LICENSE): public domain.

## How to cite

The citation metadata is in [`CITATION.cff`](CITATION.cff).
