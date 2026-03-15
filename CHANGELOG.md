# Changelog - SintaxeP

Todas as mudanças notáveis neste projeto serão documentadas neste arquivo.

## [1.0.0] - 2024-05-21
### Adicionado
- **Banco de Dados:** Comandos `BD.Abrir`, `BD.Executar`, `BD.Consulta` e `BD.Fechar` para interagir com bancos de dados SQLite.
- **Entrada Avançada:** Comando `LerTeclas()` para capturar uma única tecla pressionada sem precisar de Enter.
- **API Web:** Função `Fetch(url, opcoes)` para fazer requisições HTTP (GET/POST) e `Json(texto)` / `TextoJson(objeto)` para manipular JSON.
- **Utilitários:** Comando `Copiar(texto)` para enviar texto para a área de transferência.

## [0.9.0]
### Adicionado
- **Programação Orientada a Objetos:** Suporte inicial a `Classe` e `Novo("NomeClasse")` para criar objetos.
- **Interface Gráfica (GUI):** Comandos `Janela.Criar`, `Janela.Texto`, `Janela.Botao` e `Janela.Loop` para criar interfaces visuais básicas com Tkinter.
- **Rede (Sockets):** Comandos `Socket.Conectar`, `Socket.Enviar` e `Socket.Receber` para comunicação TCP.

## [0.8.0]
### Adicionado
- **Automação de Interface:** Comandos `Mouse.Mover(x, y)` e `Mouse.Clicar()`.
- **Medição de Tempo:** Objeto `Cronometro` com `Cronometro.Iniciar()` e `Cronometro.Tempo()`.
- **Entrada Segura:** Comando `InputSenha("mensagem")` que esconde a digitação.

## [0.7.0]
### Adicionado
- **Gerenciador de Pacotes:** Comando `InstalarPacote("nome")` para baixar bibliotecas de um repositório central.
- **Módulos com Namespace:** O comando `Importar` agora suporta um segundo argumento para criar um alias (ex: `Importar("lib.sxp", "Mat")`).
- **Controle de Loop:** Comando `Quebrar` para sair de loops `Enquanto`.

## [0.6.0]
### Adicionado
- **Manipulação de Tipos:** Funções `Tipo()`, `Inteiro()` e `Texto()`.
- **Manipulação de Listas/Texto:** Funções `Juntar()`, `Dividir()` e `Contem()`.
- **Gerenciamento de Arquivos:** Funções `DeletarArquivo()` e `ListarArquivos()`.
- **Utilitários:** Funções `Raiz()` (raiz quadrada) e `AleatorioItem()` (item aleatório de uma lista).

## [0.5.0]
### Adicionado
- **Tratamento de Erros:** Blocos `Tentar { ... } Capturar { ... }` para lidar com erros em tempo de execução.
- **Lógica Composta:** Suporte para operadores `&&` (E) e `||` (OU) em condições `Se`.
- **Melhoria de Erros:** Mensagens de erro mais detalhadas, indicando linha, coluna e sugestões.

## [0.4.0]
### Adicionado
- **Estruturas de Dados:** Suporte básico a Listas (Arrays), com criação (`[1, 2, 3]`), acesso (`lista[0]`) e atribuição (`lista[0] = valor`).

## [0.3.0]
### Adicionado
- **Interação com o Sistema:**
    - `Arg(indice)` para ler argumentos da linha de comando.
    - `Env("VAR")` para ler variáveis de ambiente.
- **Manipulação de Texto:** Funções `Tamanho()`, `Maiuscula()` e `Minuscula()`.

## [0.2.0]
### Adicionado
- **Funções Personalizadas:** Suporte para `Funcao Nome() { ... }` para criar blocos de código reutilizáveis.
- **Importação de Módulos:** Comando `Importar('outro.sxp')` para incluir outros scripts.

## [0.1.0] - Versão Inicial
### Adicionado
- **Comandos Básicos:** `Falar`, `Definir`, `Esperar`, `ExecutarCMD`.
- **Estruturas de Controle:** `Se (condicao) { ... } Senão { ... }` e `Enquanto (condicao) { ... }`.
- **Funções Nativas:** `Aleatorio(min, max)`, `ExisteArquivo(path)`, `LerArquivo(path)`.
