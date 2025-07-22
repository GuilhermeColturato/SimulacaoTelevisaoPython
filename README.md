# SimulacaoTelevisaoPython

Este projeto simula o funcionamento básico de uma televisão e seu controle remoto utilizando programação orientada a objetos em Python.

## Classes

### Televisor

Representa uma televisão com os seguintes atributos:

- `fabricante`: marca do televisor.
- `modelo`: modelo do televisor.
- `canal_atual`: canal atualmente sintonizado.
- `lista_canais`: lista de todos os canais já sintonizados.
- `volume`: volume atual da televisão.

#### Métodos da classe `Televisor`:

- `aumentar_volume()`: aumenta o volume em uma unidade.
- `diminuir_volume()`: diminui o volume em uma unidade.
- `sintoniza_canal(canal)`: sintoniza um novo canal, adicionando à lista se ainda não estiver presente.
- `troca_canal(canal)`: troca para um canal já existente na lista de canais.

---

### ControleRemoto

Representa o controle remoto vinculado a um objeto da classe `Televisor`.

#### Atributos:

- `televisao`: referência a um objeto da classe `Televisor`.

#### Métodos da classe `ControleRemoto`:

- `aumenta_volume()`: chama o método correspondente do televisor.
- `diminui_volume()`: chama o método correspondente do televisor.
- `sintoniza_canal(canal)`: sintoniza e adiciona um canal à lista do televisor.
- `troca_canal(canal)`: troca para um canal existente no televisor.
