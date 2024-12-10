Git: É um sistema de controle de versão, que permite que você acompanhe mudanças no código, colabore com outros desenvolvedores e mantenha o histórico completo do projeto.
Github: É uma plataforma que hospeda o repositório GIT na nuvem.
Funções do Github
Hospedagem de repositórios: Armazena seu projeto na nuvem, permitindo acessá-lo de qualquer lugar.
Colaboração: Permite que várias pessoas trabalhem no mesmo projeto simultaneamente, com controle de mudanças.
Gerenciamento de projetos: Inclui ferramentas como issues, pull requests e boards para organizar tarefas e revisões.
Distribuição: Facilita o compartilhamento de código com a comunidade, seja público ou privado.

Passo a passo para criar o projeto:
1- Acesse o site oficial: https://git-scm.com/ para baixar e instalar o Git no computador;
2- Acesse https://github.com/ para criar conta (caso ainda não tenha);
3- Configure o Git Bash no computador
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@exemplo.com"
4- Digite git init para criar repositório Git do projeto no Git Bash;
5- Digite git add para adicionar os arquivos no repositório;
6- Digite git commit -m "Primeiro commit" e faça o primeiro commit;
7- Crie repositório no GitHub
Na tela do GitHub clique no botão New para criar novo repositório
Dê um nome ao repositório e selecione se será (public ou Private), após clique em Create repository
8- Conecte o repositório local ao GitHub
Copie o comando fornecido pelo GitHub após criar o repositório (geralmente começa com git remote add origin)
No bash digite git remote add origin https://github.com/seuusuario/seurepositorio.git e dê Enter
9- Envie o projeto para o GitHub No bash copie código
git branch -M main e dê Enter
git push -u origin main e dê Enter
10- Verifique no GitHub
Acesse o repositório no GitHub para confirmar que os arquivos foram enviados.