# SintaxeP - Linguagem de Script em Português

**SintaxeP** é uma linguagem de programação interpretada, criada para ser simples, intuitiva e totalmente em português. Ela é focada em automação, manipulação de arquivos e criação rápida de scripts.

## 🚀 Funcionalidades

*   **100% em Português:** Comandos como `Se`, `Enquanto`, `Falar`, `Funcao`.
*   **Automação:** Controle o Mouse, Teclado e Arquivos facilmente.
*   **Interface Gráfica:** Crie janelas e botões com poucas linhas.
*   **Conectividade:** Faça requisições Web, baixe arquivos e use Sockets.
*   **Extensível:** Sistema de pacotes e importação de bibliotecas.
*   **Moderna:** Suporte a Classes (OOP), JSON e Banco de Dados SQLite.

## 📦 Instalação

1.  Baixe o arquivo `.zip` da versão mais recente.
2.  Descompacte em uma pasta de sua preferência (Ex: `C:\SintaxeP`).
3.  Clique com o botão direito no arquivo `associar_icone.py` e selecione **"Executar como administrador"** (ou abra com Python).
    *   *Isso irá configurar os ícones e permitir que você execute scripts clicando duas vezes.*
4.  Pronto! Crie um arquivo `.sxp` e divirta-se.

## 📝 Primeiros Passos

Crie um arquivo chamado `ola.sxp` e escreva:

```javascript
Titulo("Meu Primeiro Script");
Falar("&aOlá, Mundo!&r");

Definir nome = Perguntar("Qual seu nome?");
Falar("Bem-vindo, ${nome}!");

Esperar(2);
```

# 📚 Exemplos Avançados

## 1. Automação de Mouse
```javascript
Falar("Vou clicar em 3 segundos...");
Esperar(3);
Mouse.Mover(500, 500);
Mouse.Clicar();
```
## 2. Interface Gráfica (GUI)
```javascript
Funcao Clicou() {
    Falar("Você clicou no botão!");
}

Janela.Criar("Minha App", "300x200");
Janela.Texto("Clique abaixo:");
Janela.Botao("Clique Aqui", "Clicou");
Janela.Loop();
```
## 3. Consultando API (Web)
```javascript
Falar("Consultando CEP...");
Definir json = Fetch("https://viacep.com.br/ws/01001000/json/");
Definir dados = Json(json);
Falar("Rua: ${dados['logradouro']}");
```
## 4. Orientação a Objetos
```javascript
Classe Pessoa {
    nome = "Desconhecido"
    idade = 0
}

Definir p = Novo("Pessoa");
Definir p['nome'] = "Lucas";
Falar("Objeto criado: ${p['nome']}");
```

# 🛠️ Comandos Disponíveis
- Saída/Entrada: Falar, Perguntar, InputSenha, Limpar, LerTeclas.
- Lógica: Se, Senão, Enquanto, Quebrar, Tentar/Capturar.
- Sistema: Esperar, ExecutarCMD, Copiar, Aleatorio.
- Arquivos: Salvar, LerArquivo, ExisteArquivo, ListarArquivos, DeletarArquivo.
- Web/Rede: Fetch, Baixar, Web, Socket.
- Dados: Json, TextoJson, BD (SQLite).
- Outros: Cronometro, Mouse, Janela.

  
### Dica:
Salve esse conteúdo em um arquivo chamado `README.md` na raiz do seu projeto. Se você colocar no GitHub, esse texto aparecerá formatado bonitinho na página inicial do repositório.

<!--
[PROMPT_SUGGESTION]Como criar um arquivo de licença (LICENSE) MIT para o meu projeto?[/PROMPT_SUGGESTION]
[PROMPT_SUGGESTION]Crie um changelog (CHANGELOG.md) listando todas as versões e mudanças que fizemos até agora.[/PROMPT_SUGGESTION]
-->
