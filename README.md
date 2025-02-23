# 📚 Estudos sobre Colaborações

Repositório de teste criado a fim de estudos sobre o GitHub através da Formação GitHub Certification da Dio.me

## 🏫 Fundamentos

**📁 Ao meu entendimento o que é um repositório no Git e no GitHub?**
Se trata do diretório local ou remoto onde estará armazenado o projeto (todo o código fonte do projeto) público ou privado que será trabalhado em contribuição ou distribuído usuários selecionados ou não.
*Em outras palavras: a pastinha onde ficará salvo os códigos.*

**📂 Ao meu entendimento o que são Branches?**
Ao meu entender é uma forma de trabalhar no código fonte, sem afetar o código fonte original, ou seja... uma cópia do código fonte para ser trabalhada para não afetar o código fonte original enquanto aquela cópia não esteja estável para se mesclar ao original.

**📥 Ao meu entendimento que são Pull Request?**
Ao meu entender é uma solicitação de revisão das alterações ao mesmo tempo que é um pedido para que elas sejam mescladas ao código fonte.

**🗂️ Ao meu entendimento que é Merge?**
Uma operação de mesclar os códigos de duas branches diferentes (por exemplo: mesclar a branche modificada a branche original).

**📑 Ao meu entendimento o que é um Fork?**
Uma cópia do repositório que pode ser modificada, e então ser incorporada ao código original ou não.

**📄 O que é um arquivo Markdown?**
Um arquivo ".md", por exemplo: README.md, arquivo de texto que utiliza a formatação Markdown 
https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

# 📝 Testes feitos: 
- Envio de repositório local para o GitHub.
*Ao abrir a pasta do repositório com o Git instalado, e apertar o botão direito e acionar a opção "Open GitBash here", foi possível começar a trabalhar nesse teste.*

## 📟 Comandos utilizados no Git:  

### ✍🏻 Preparando o Repositório

Criei uma pasta com o nome idêntico ao repositório que criei no GitHub
e então comecei a escrever esse arquivo README.md através do Visual Studio Code e o salvei dentro da pasta desse repositório.
Ao abrir a pasta do repositório com o Git instalado, e apertar o botão direito e acionar a opção "Open GitBash here" comecei utilizando o comando:

`git init` 
Para inicializar a operação do repositório.
*Observei que uma pasta oculta chamada .git começa a ser criada dentro do repositório toda vez que o preparo.*

*Se caso eu não tivesse o arquivo README.md já pré-pronto, eu poderia utilizar o comando:*
*`git add README.md`*

`git add .` 
Para adicionar as alterações que fiz no repositório.

`git commit -m "Primeiro Commit"`
Para adicionar o meu primeiro commit.

*Relembrando que `commit` ao meu entender se trata de um comentário adicionado aquela atualização, que ficará registrado (dizendo o que aconteceu naquela alteração, como se fosse um changelog)*

`git branch -M main`
Comando utilizado para sair da branch master para ir para a branch main.

*Curiosidade: o termo "master" para branchs no GitHub é desencorajado ou senão descontinuado por questões históricas-culturais, pois relembra conceitos de escravidão, atualmente seu sucessor é o termo "main"*

`git remote add origin https://github.com/Redyiel/colaboracoes`
Comando utilizado para definir a origem do repositório remoto, tal repositório que será atualizado conforme as mudanças.

`git push -u origin main`
Comando utilizado para enviar as atualizações do repositório ao GitHub.


