<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"></a>
    <span> Contribuindo em um Projeto Open Source no GitHub</span>
</h1>

Repositório desenvolvido para fins didáticos, com a disponibilização de materiais de apoio para o lab **Contribuindo em um Projeto Open Source no GitHub** da [Digital Innovation One](https://www.dio.me/).

[![Link do Lab](https://img.shields.io/badge/▶-000?style=for-the-badge&logo=movie&logoColor=E94D5F)](https://web.dio.me/lab/desafio-de-projeto-contribuindo-em-um-projeto-open-source-no-github/learning/913f26fd-1018-4643-b59a-6356ea77dc2e) 
[![Link do Lab](https://img.shields.io/badge/Acesse%20o%20Lab%20na%20Plataforma-E94D5F?style=for-the-badge)](https://web.dio.me/lab/desafio-de-projeto-contribuindo-em-um-projeto-open-source-no-github/learning/913f26fd-1018-4643-b59a-6356ea77dc2e)

## Objetivo.
Aprender o básico sobre contribuição no GitHub.

Instruções de Instalação :

# Guia de Instalação do Visual Studio Code

Este guia fornece instruções básicas para instalar o Visual Studio Code em diferentes sistemas operacionais: Windows, MacOS e Linux.

## Windows:

1. Acesse o site oficial do Visual Studio Code: [https://code.visualstudio.com/](https://code.visualstudio.com/)
2. Clique no botão "Download for Windows".
3. Execute o arquivo do instalador que foi baixado.
4. Siga as instruções do assistente de instalação, aceitando as configurações padrão ou personalizando conforme necessário.
5. Após a instalação, o Visual Studio Code estará disponível no menu Iniciar ou na área de trabalho.

## MacOS:

1. Acesse o site oficial do Visual Studio Code: [https://code.visualstudio.com/](https://code.visualstudio.com/)
2. Clique no botão "Download for Mac".
3. Abra o arquivo .dmg do Visual Studio Code que foi baixado.
4. Arraste o ícone do Visual Studio Code para a pasta "Applications" para instalá-lo.
5. Após a instalação, você pode encontrar o Visual Studio Code em sua pasta "Applications".

## Linux (Debian/Ubuntu):

1. Abra um terminal.
2. Execute os seguintes comandos:

   ```bash
   sudo apt update
   sudo apt install software-properties-common apt-transport-https wget
   wget -q https://packages.microsoft.com/keys/microsoft.asc -O- | sudo gpg --dearmor -o /usr/share/keyrings/microsoft-archive-keyring.gpg
   echo "deb [arch=amd64 signed-by=/usr/share/keyrings/microsoft-archive-keyring.gpg] https://packages.microsoft.com/repos/code stable main" | sudo tee /etc/apt/sources.list.d/vscode.list
   sudo apt update
   sudo apt install code
O Visual Studio Code será instalado em seu sistema.
Linux (Fedora):
Abra um terminal.

Execute os seguintes comandos:

bash
Copy code
sudo rpm --import https://packages.microsoft.com/keys/microsoft.asc
sudo dnf install https://packages.microsoft.com/repos/code/stable/x86_64/code-1.59.1-1628129344.el8.x86_64.rpm
O Visual Studio Code será instalado em seu sistema.

Após a instalação, você pode iniciar o Visual Studio Code a partir do menu de aplicativos ou executando o comando "code" no terminal. Certifique-se de que as versões mencionadas nos comandos são as mais recentes no momento da sua instalação.

css
Copy code

Lembre-se de que, ao adicionar este guia a um arquivo README, você pode personalizar o título, a formatação e os detalhes adicionais conforme necessário para se adequar ao seu projeto.





## Ferramentas
[![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=30A3DC)](https://docs.github.com/)
[![Git](https://img.shields.io/badge/Git-000?style=for-the-badge&logo=git&logoColor=E94D5F)](https://git-scm.com/doc) 

## Percurso
<table>
  <thead>
    <tr align="left">
      <th>Nº</th>
      <th>Etapas</th>
      <th>Materiais de Apoio</th>
    </tr>
  </thead>
  <tbody align="left">
    <tr>
      <td>01</td>
      <td>Introdução ao Lab</td>
      <td align="center">
        <a href="">
           <img align="center" alt="Material de Apoio" src="https://img.shields.io/badge/Ver%20Material-30A3DC?style=for-the-badge">
        </a>
      </td>
    </tr>
    <tr>
      <td>02</td>
      <td>Formas de Contribuir num Projeto Open Source</td>
      <td align="center">
        <a href="">
           <img align="center" alt="Material de Apoio" src="https://img.shields.io/badge/Ver%20Material-E94D5F?style=for-the-badge">
        </a>
      </td>
    </tr>
    <tr>
      <td>03</td>
      <td>Desenvolvendo e Enviando uma Contribuição</td>
      <td align="center">
        <a href="">
           <img align="center" alt="Material de Apoio" src="https://img.shields.io/badge/Ver%20Material-30A3DC?style=for-the-badge">
        </a>
      </td>    
    </tr>
    <tr>
      <td>04</td>
      <td>Dicas e Materiais de Apoio</td>
      <td align="center">
        <a href="">
           <img align="center" alt="Material de Apoio" src="https://img.shields.io/badge/Ver%20Material-E94D5F?style=for-the-badge">
        </a>
      </td>    
    </tr>
  </tbody>
  <tfoot></tfoot>
</table>

---
##  Desafio: Profile README
 Contribua no diretório "Community", criando um Profile README contendo informações sobre você que deseje compartilhar com a comunidade. Para isso, você pode inserir: badges indicando suas habilidades; cards com suas estatísticas no GitHub e projetos que criou, colaborou ou que deseje que outras pessoas colaborem. Além disso, você pode inserir também links para seus desafios de projeto e artigos na plataforma da [Digital Innovation One](https://www.dio.me/). <br>
 Inspire-se consultando os exemplos na pasta [`community`](https://github.com/elidianaandrade/dio-lab-open-source/tree/main/community), confira alguns utilitários na pasta [`utils`](https://github.com/elidianaandrade/dio-lab-open-source/tree/main/utils) e use sua criatividade para criar o seu 😊💙.

### Instruções (PT/BR)
1. Faça um **Fork** deste repositório;
2. Clone localmente: `git clone https://github.com/SEUUSERNAME/dio-lab-open-source.git`;
3. Adicione o remote upstream para manter seu repositório local atualizado: `git remote add upstream https://github.com/elidianaandrade/dio-lab-open-source.git`;
    > Utilize o comando `git pull upstream main` para baixar e mesclar as alterações no seu repositório local com base na branch `main` deste repositório original de onde você fez o fork, ou `git fetch upstream main` para baixar sem mesclar. Veja mais em: [Primeiros Passos com Git e GitHub](https://github.com/elidianaandrade/dio-curso-git-github/blob/main/materiais-de-apoio/03-primeiros-passos-com-git-e-github.md).
4. Crie uma nova **branch** e nomeie como `feat/community/seunomedeusuario`: `git checkout -b feat/community/seunomedeusuario`;
    > Exemplo: `git checkout -b feat/community/elidianaandrade`
5. Dentro da pasta [`community`](https://github.com/elidianaandrade/dio-lab-open-source/tree/main/community), crie um arquivo em Markdown (extensão `.md`) e nomeie com o mesmo nome do seu usuário no GitHub;
    > Exemplo: `elidianaandrade.md` <br>
6. Desenvolva o seu perfil. Para isso, você pode ver exemplos na pasta [`community`](https://github.com/elidianaandrade/dio-lab-open-source/tree/main/community) e adicionar alguns dos utilitários presentes na pasta [`utils`](https://github.com/elidianaandrade/dio-lab-open-source/tree/main/utils);
    > **Observação:** Use os outros exemplos como inspiração e não cópia.
7. Adicione suas alterações à "staging area" com o comando `git add community/seunomedeusuario.md`;
8. Crie um commit e adicione a mensagem indicando a adição do seu perfil `git commit -m"feat: add seunomedeusuario profile"`;
9. Envie as alterações para o seu repositório remoto `git push origin feat/community/seunomedeusuario`; 
10. Crie um **Pull Request**.

### Instructions (EN/US)
1. **Fork** the repository;
2. Clone locally: `git clone https://github.com/SEUUSERNAME/dio-lab-open-source.git`;
3. Add upstream remote to keep your local repository up to date: `git remote add upstream https://github.com/elidianaandrade/dio-lab-open-source.git`;
    > Use the command `git pull upstream main` to download and merge changes to your local repository based on the branch `main` from this original repository you forked it from, or `git fetch upstream main` to download without merging. See more at: [Getting Started with Git and GitHub](https://github.com/elidianaandrade/dio-curso-git-github/blob/main/materiais-de-apoio/03-primeiros-passos-com-git-e-github.md).
4. Create a new **branch** and name it as `feat/community/seunomedeusuario`: `git checkout -b feat/community/yourusername`;
    > Example: `git checkout -b feat/community/elidianaandrade`
5. Inside the folder [`community`](https://github.com/elidianaandrade/dio-lab-open-source/tree/main/community), create a file in Markdown (extension `.md`) and name it the same as your GitHub username;
    > Example: `elidianaandrade.md` <br>
6. Develop your profile. For this you can see examples in the folder [`community`](https://github.com/elidianaandrade/dio-lab-open-source/tree/main/community) and add some of the utilities present in the folder [`utils`](https://github.com/elidianaandrade/dio-lab-open-source/tree/main/utils);
    > **Note:** Use the other examples as inspiration, not copy.
7. Add your changes to the "staging area" with the command `git add community/yourusername.md`;
8. Create a commit and add the message indicating the addition of your profile `git commit -m"feat: add yourusername profile"`;
9. Push changes to your remote repository `git push origin feat/community/yourusername`; 
10. Create a **Pull Request**.

### Utilitários

[![Badges](https://img.shields.io/badge/Badges-30A3DC?style=for-the-badge)](https://github.com/elidianaandrade/dio-lab-open-source/blob/main/utils/badges/badges.md)
[![Card Stats](https://img.shields.io/badge/Card%20Stats-E94D5F?style=for-the-badge)](https://github.com/elidianaandrade/dio-lab-open-source/blob/main/utils/cards/github-stats.md)
[![Badges](https://img.shields.io/badge/Card%20Streak%20States-30A3DC?style=for-the-badge)](https://github.com/elidianaandrade/dio-lab-open-source/blob/main/utils/cards/github-streak-stats.md)

---

## Contribua
[![Star](https://img.shields.io/github/stars/elidianaandrade/dio-lab-open-source?style=social)](https://github.com/elidianaandrade/dio-lab-open-source/stargazers)
[![Forks](https://img.shields.io/github/forks/elidianaandrade/dio-lab-open-source?style=social)](https://github.com/elidianaandrade/dio-lab-open-source/forks)
[![GitHub Issues](https://img.shields.io/github/issues/elidianaandrade/dio-lab-open-source?style=social)](https://github.com/elidianaandrade/dio-lab-open-source/issues/)

 Este é um projeto feito para a comunidade, então sinta-se livre para contribuir. Algumas formas de contribuição além do seu exemplo de Profile README, é inserir outros utilitários na pasta [`utils`](https://github.com/elidianaandrade/dio-lab-open-source/tree/main/utils), ou melhorar a página de pesquisa dos READMEs fazendo modificações nos arquivos da pasta [`docs`](https://github.com/elidianaandrade/dio-lab-open-source/tree/main/docs). <br>
 Além disso, você também pode contribuir:
 
⚠️ Resolvendo, respondendo ou indicando **issues**

⭐ Adicionando aos favoritos (**star**) 

### Membros da comunidade que já contribuiram:
<a href="https://github.com/elidianaandrade/dio-lab-open-source/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=elidianaandrade/dio-lab-open-source"/>
</a>

##
<div align="center">Feito com 💙 por <a href="https://github.com/elidianaandrade">Eli</a>.</div>
