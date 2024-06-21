# Projeto-Dio-UML
Projeto DIO UML

Código UML

    classDiagram 
    class ReprodutorMusical {
        +tocar()
        +pausar()
        +selecionarMusica(String musica)
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

    class RerprodutorVideo {
        +reproduzirVideo()
        +pausarVideo()
        +selecionarVideo(String video)
        +modoWidescreen()

    }

    

    class iPhone {
    }

    iPhone --> ReprodutorMusical
    iPhone --> AparelhoTelefonico
    iPhone --> NavegadorInternet
    iPhone --> RerprodutorVideo
    


