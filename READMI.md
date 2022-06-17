Como Criar um Repositório Local e Remoto

PASSO 1 - GITHUB
- Baixe o GitHub Desktop no seu computador
- Baixe o Git
- Crie uma conta no GitHub

PASSO 2 - CRIAR DIRETÓRIOS
- Crie um Diretório no disco local e nomeie ele de GitHub;
- Dentro desse diretório crie outro diretório e dê um nome para ele;
- Selecione essa pasta e com o botão direito do mouse clique em "Git Bash Hee";
- Ele irá abrir um terminal.

PASSO 3 - COMANDOS
No terminal digite:
- git init (para iniciar um repositório local)
Agora dentro do diretório que foi criado na pasta GuitHub, crie um documento de texto.
Abra o terminal novamente e dê o comando:
- git add " " ou git add . OBS:Entre as aspas adicione o nome do arquivo de texto que foi criado. (para atrelar o arquivo.txt ao repositório);
- git commit -m "dê um nome ao commit" (para commitar o arquivo);
- git log (ele empurra o arquivo para o repositório local);

PASSO 4 - REPOSITÓRIO REMOTO
Agora entre na sua conta do Github para criar um repositório remoto.
- Clique em " Repositório ";
- Clique em " Novo ";
- Dê um nome ao seu repositório;
- Coloque uma descriçaõ;
- Selecione " Público " (para que as pessoas possam ver o seu trabalho)
- Criar Repositório;

Após ter feito isso, volte la no terminal e digite os seguintes comandos:
- git remote add origin " " (entre as aspas adicione o link do seu repositório remoto)
Isso permite que o repositório remoto se conecte ao repositório local.
- git push origin main (ele faz subir todos os arquivos para do reositório local para o reamoto)

PASSO 5 - READMI
No diretório criado dentro da pasta Github crie um arquivo Readmi.md
- Botão direito do mouse - novo - Arquivo de  texto;
- Nomeie o de " READMI " e mude a extensão do arquivo para " .md ";

Volte para o terminal e adicione o arquivo readmi.md no se repositório local.
- git status (ele mostrará que tem um arquivo que não foi adicionado ainda;
- git add . ou git " READMI.md " (para addicinar o arquivo);
- git commit -m " READMI "
- git log
- git push origin main (para subir o Redmi la pro repositório remoto)

Agora está criado um arquivo para ser alterado e rastreado.