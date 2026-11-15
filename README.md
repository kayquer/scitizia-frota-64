# Scitizia: frota 64 bits

Carros de rali em poucos polígonos, no visual dos consoles de 64 bits, feitos para o jogo **Scitizia Rally Championship**. Todos os carros, nomes e pinturas são inventados: nenhum fabricante, modelo ou patrocinador real aparece aqui.

Cada carro tem entre 2 e 2,5 mil triângulos, uma textura de 256 px para a carroceria e uma de 128×64 px para as rodas.

| | Carro | Classe | Arquétipo | Tração | Potência | Massa | ID |
|---|---|---|---|---|---|---|---|
| ![](previas/miudo.jpg) | **Miúdo 1.4** | C1 Novato | Hatch compacto popular | FWD | 95 cv | 1.000 kg | 373 |
| ![](previas/faisca.jpg) | **Faísca KC** | C2 Kit Car | Hatch esportivo preparado | FWD | 156 cv | 1.000 kg | 540 |
| ![](previas/brasa.jpg) | **Brasa 24** | C3 Clássico | Cupê de tração traseira dos anos 70/80 | RWD | 170 cv | 1.050 kg | 529 |
| ![](previas/trovao.jpg) | **Trovão 4T** | C4 Produção | Sedã de série 4x4 turbo | AWD | 204 cv | 1.300 kg | 605 |
| ![](previas/scitizia.jpg) | **Scitizia R5** | C5 Elite | Protótipo de rali sobre base de hatch | AWD | 228 cv | 1.150 kg | 708 |
| ![](previas/vendaval.jpg) | **Vendaval B** | C6 Grupo Livre | Monstro sem restrição, estilo anos 80 | AWD | 306 cv | 1.100 kg | 896 |
| ![](previas/jararaca.jpg) | **Jararaca 30** | C7 Off-road | Picape de rali cross-country | AWD | 252 cv | 1.900 kg | 521 |

ID é o Índice de Desempenho do jogo (100 a 999).

## Pastas

- `modelos/<id>.glb`: o carro pronto para uso em tempo real.
- `texturas/`: as texturas da carroceria e das rodas em PNG (as mesmas que vão dentro do `.glb`).
- `previas/`: quatro vistas de cada carro.
- `fichas/<id>.json`: ficha do carro no jogo. A seção `fisica` traz massa, medidas, eixos, bitolas, rodas, potência e tração; a seção `forma` traz os parâmetros que geram a carroceria (perfil, cabine, faróis, cores, pintura e acessórios).

## Como usar os modelos

- Metros, eixo Y para cima. A frente do carro aponta para +Z e a esquerda para +X. A origem fica no chão, entre os eixos.
- Objetos de cada arquivo:
  - `Carroceria`: carroceria, vidros e acessórios numa malha só, com vários materiais.
  - `Roda_DE`, `Roda_DD`, `Roda_TE`, `Roda_TD`: as quatro rodas (dianteira/traseira, esquerda/direita), com a origem no centro da roda. Gire em torno do eixo X para rodar e em torno de Y para esterçar.
  - `Pinca_XX` (só no Scitizia R5): pinças de freio, que esterçam mas não giram.
  - `Sombra`: uma mancha escura com transparência para pôr no chão sob o carro.
- Materiais sem brilho combinam com o visual: difuso simples, filtro bilinear e neblina por distância.
