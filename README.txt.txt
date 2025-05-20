Paola Pereira git init: Este é o primeiro passo! Executar git init em um diretório transforma essa pasta em um repositório Git. Ele cria uma subpasta .git onde o Git rastreia todas as alterações e informações de histórico.

Bash

git init
git clone <url>: Se você já tem um repositório Git hospedado remotamente (como no GitHub, GitLab ou Bitbucket), use git clone para criar uma cópia local completa desse repositório.

Bash

git clone https://github.com/usuario/repositorio.git
Gerenciando suas Mudanças:

git status: Este comando é seu melhor amigo! Ele mostra o estado atual do seu diretório de trabalho e da área de staging. Você verá arquivos modificados, arquivos staged (preparados para commit) e arquivos não rastreados.

Bash

git status
git add <arquivo(s)>: Use git add para adicionar arquivos à área de staging. Isso diz ao Git que você deseja incluir as alterações desses arquivos no seu próximo commit. Você pode adicionar arquivos específicos ou usar git add . para adicionar todas as alterações no diretório atual.

Bash

git add meu_arquivo.txt
git add pasta/outro_arquivo.py
git add .
git commit -m "<mensagem>": Este comando salva suas alterações na história do repositório local. É crucial escrever mensagens de commit claras e concisas, explicando o que foi alterado e por quê. A opção -m permite que você escreva a mensagem diretamente na linha de comando.

Bash

git commit -m "Adiciona funcionalidade de login"
git commit -m "Corrige bug na renderização da página inicial"
git rm <arquivo>: Se você deseja remover um arquivo do seu projeto e do controle de versão do Git, use git rm. Para apenas remover o arquivo do controle de versão (mantendo-o no seu disco), use git rm --cached <arquivo>.

Bash

git rm arquivo_desnecessario.txt
 Esta atividade tem como objetivo principal introduzir e praticar os comandos básicos do Git, um sistema de controle de versão distribuído amplamente utilizado no desenvolvimento de software. Ao longo desta tarefa, você irá criar um repositório no GitHub, cloná-lo para sua máquina local, adicionar arquivos, realizar commits, criar e gerenciar branches, e enviar suas alterações para o repositório remoto. A atividade culminará na edição de um arquivo em uma branch separada e na sua integração com a branch principal (main). A documentação de cada etapa através de printscreens é fundamental para demonstrar a execução dos comandos e o entendimento do fluxo de trabalho do Git. 