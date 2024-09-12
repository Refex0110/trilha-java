diagram-iphone
    
    classDiagram

    class ReprodutorMusical {
        +tocar() void 
        +pausar() void
        +selecionarMusica(String exemplo) String
    }

    class AparelhoTelefonico {
        +ligar() void
        +atender() void
        +iniciarCorreioVoz() void
    }

    class NavegadorInternet {
        +exibirPagina(String url) void
        +adicionarNovaAba() void
        +atualizarPagina() void
    }

    class iPhone {
    }

    iPhone --> ReprodutorMusical
    iPhone --> AparelhoTelefonico
    iPhone --> NavegadorInternet
