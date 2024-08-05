# Galaxia Curso GitHub

Bem-vindo ao repositório **Galaxia Curso GitHub**! Este repositório é parte de um curso ministrado por [Brenno Sullivan](https://x.com/brennosullivan) que ensina os conceitos iniciais de Git e GitHub, incluindo versionamento, branches, commits, autenticação com o GitHub e integração com o VSCode.

## Pré-requisitos

Antes de começar o curso, certifique-se de ter os seguintes softwares instalados em seu computador:

1. **Git Bash**
   - [Download Git Bash](https://git-scm.com/downloads)

2. **Visual Studio Code (VSCode) July 2024 (version 1.92)**
   - [Download VSCode](https://code.visualstudio.com/Download)

## Iniciando com Git e GitHub

### Configuração Inicial do Git

1. **Instale o Git Bash** e abra o terminal Git Bash.
2. Configure seu nome de usuário e email no Git:
   ```bash
   git config --global user.name "Seu Nome"
   git config --global user.email "seu_email@dominio.com"


## Gerando Chaves SSH

Para autenticar seu computador com o GitHub, você precisará gerar chaves SSH.

1. Gerar a chve SSH pública e privada:
   ``` bash
   ssh-keygen -t rsa -b 4096 -C "seu_email@dominio.com"

2. Acessar o diretório onde está sua chave SSH pública:
   ```bash
   cd ~/.ssh/

3. Exibir a chave SSH pública
   ```bash
   cat id_rsa.pub

4. Copiar essa chave e adicionar ao GitHub:
   * Vá para [GitHub Settings](https://github.com/settings/keys) > [SSH and GPG keys](https://github.com/settings/keys).
  

## Autenticação no VSCode
Para sincronizar suas configurações do VSCode com o GitHub:

1. Abra o VSCode.
2. Clique no seu perfil no canto inferior esquerdo.
3. Clique em Sign in to sync Settings(1).
4. Escolha a opção Sign in with GitHub.
5. Forneça suas credenciais do GitHub e autorize a integração.
6. No VSCode, confirme a autorização no canto inferior direito.

   
## Conteúdo do Curso
Durante este curso, você aprenderá:

* Conceitos básicos de Git
  **Versionamento
  **Branches
  **Commits
* Como utilizar o terminal Git Bash
* Como configurar e gerenciar repositórios Git
* Como autenticar seu computador com o GitHub
* Como integrar o GitHub com o VSCode.

## Recursos Adicionais

* [Documentação Oficial do Git](https://git-scm.com/doc)
* [Documentação do GitHub](https://docs.github.com/pt)
* [Documentação do VSCode](https://code.visualstudio.com/docs)

  **Autor**: Brenno Sullivan (Todos os direitos reservados)

