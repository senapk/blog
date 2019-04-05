# Instalando, Configurando e Trabalhando com Repositórios Git no VSCode.


## Instalando o VSCode
- Instalar [VSCode](https://code.visualstudio.com/)
- ![](vscode.png)

## Instalando o Git
- Instalar [Git](https://git-scm.com/download)
- Baixe o git ![](git1.png)
- Instaleos pacotes **Git Bash** e **Git Gui** ![](git2.png)
- Selectione o VSCode como Editor Default do Git ![](git3.png)
- **Use as opções default para todas as próximas perguntas na instalação do Git**.
- Ao final, você deve ter um aplicativo de nome **Git Bash** acessível pelo menu iniciar.
- Abra o Git Bash e digite os seguintes comandos para definir seu nome de usuário e email:

        git config --global user.email "seu_email@example.com"
        git config --global user.name "Seu Nome Aqui"

## Criando sua conta no GitHub
    - Se possível, crie seu email institucional para ter acesso a várias vantagens como repositórios privados e o pacote Git Student.
    - Não custa dizer, mas decore seu username e seu password.

## Abrindo o git bash no vscode
- Abra o VSCode
- Abra o Terminal
    - View -> Terminal ou apenas `Ctrl + '`
- Você pode modificar o Prompt para o Bash
    - ![](vscode2.png)


## Criando seu próprio repositório
- Criando seu repositório local
    - Vá em Arquivo -> Abrir pasta, escolha a pasta onde será seu respositório local.
    - 1. Clique em Controle de Versão
    - 2. Clique em Inicializar Repositório
    - 3. Escolha sua pasta
    - ![](git5.png)

- Salvando os arquivos localmente
    - Todos os arquivos da pasta devem aparecer agora no controle de versão. ![](git6.png)
    - Você pode individualmente ir clicando no + que aparecerá quando pusero + sobre cada arquivo ou clicar no + do lado de CHANGES para adicionar todos os arquivos para serem salvos.
    - O status dos arquivos adicionados muda de `U`(Unstaged) para `A`(Added).
    - Arquivos modificados aparecem com letra `M`. Clique no + para adicioná-los. ![](git7.png)
    - Após adicionar todas os arquivos nas versões que deseja salvar. Escreva a mensagem e clique no botão de commit.
    - Pronto, seus arquivos estão salvos localmente. Se for até o terminal e digitar `git log` em qualquer lugar dentro do diretório raiz, poderá ver o número do seu commit e sua mensagem. ![](git8.png)
- Vinculando seu repositório local com seu repositório Remoto.
    - Opção 1: via vscode
        - Entre na usa conta do github e crie seu repositório remoto. Não adicione o README. ![](git9.png)
        - Copie o link do repositório. ![](git10.png)
        - No VSCode abra a Paleta de Comandos, normalmente através do atalho `Ctrl + Shift + P`
        - Procure e execute o comando `Git: Add Remote`
        - No nome do repositório remoto coloque `origin`
        - Na url, coloque a url, no meu caso `https://github.com/senapk/blog.git`
    - Via linha de comando
        - Copie e cole essa linha no terminal do vscode ![](git12.png)
- Enviando ao servidor Remoto.
    - Após adicionar e comitar suas alterações execute o comando "Git: Push" a partir da paleta ou do `...` na aba do controle de versão.
    - No primeiro envio, basta confirmar que você deseja criar o ramo principal `master` no servidor remoto, e a partir de então, basta dar o push para enviar as atualizações.

- Instalar [MinGW]
    - Selecionar Pacotes
    - Marcar Apply
    - 