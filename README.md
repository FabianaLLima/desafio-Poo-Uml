# desafio-Poo-UML

### Modelagem e Diagramação UML de um Componente iPhone:

Neste desafio, o objeivo é modelar e diagramar a representação UML do componente iPhone, abrangendo suas funcionalidades como Reprodutor Musical, Aparelho Telefônico e Navegador na Internet.


```mermaid
classDiagram
    class ReprodutorMusical {
        +tocar()
        +pausar
        +selecionarMusica(String selecionarMusica)
    }

    class AparelhoTelefonico {
        +ligar(String numero)
        +atender()
        +iniciarCorreioVoz()
    }

    class NavegadorInternet {
        +exibirPagina(String url)
        +adicionarNovaAba()
        +atualizarPagina()
    }

    class iPhone {
    }

    iPhone --> ReprodutorMusical
    iPhone --> AparelhoTelefonico
    iPhone --> NavegadorInternet
