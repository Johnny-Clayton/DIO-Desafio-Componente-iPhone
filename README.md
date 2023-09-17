# Diagrama UML para o iPhone

## Classes e Interfaces

### iPhone

- **Atributos**
    - nome: String

- **Métodos**
    - ligar(): void
    - atender(): void
    - iniciarCorreioVoz(): void

### ReprodutorMusical (Interface)

- **Métodos**
    - tocar(): void
    - pausar(): void
    - selecionarMusica(): void

### AparelhoTelefonico (Interface)

- **Métodos**
    - ligar(): void
    - atender(): void
    - iniciarCorreioVoz(): void

### NavegadorInternet (Interface)

- **Métodos**
    - exibirPagina(): void
    - adicionarNovaAba(): void
    - atualizarPagina(): void

