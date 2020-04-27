# Desafio 04: Conceitos do React Native 

Desenvolver uma aplicação que irá armazenar repositórios do seu portfólio, que você já desenvolveu o backend no [desafio](https://github.com/AndreGros/Desafio02-Conceitos-NodeJS) utilizando o NodeJS,  e no último [desafio](https://github.com/AndreGros/Desafio03-Conceitos-ReactJS) em ReactJS.

### **Funcionalidades da aplicação**

- **Listar os repositórios da sua API:** Deve ser capaz de criar uma lista de todos os repositórios que estão cadastrados na sua API com os campos title, techs e número de curtidas seguindo o padrão ${repository.likes} curtidas, apenas alterando o número para ser dinâmico.

- **Curtir um repositório listado da API:**  Deve ser capaz de curtir um item na sua API através de um botão com o texto Curtir e deve atualizar o número de likes na listagem no mobile.
 
### **Para esse desafio temos os seguintes testes:**

- **should add a like to the like counter of the repository:** Para que esse teste passe, sua aplicação deve permitir ao clicar no botão Curtir, um like seja adicionado ao repositório listado, e que essa atualização possa ser visualizada na tela.

### Pré requisitos

 - Ter o [Yarn](https://classic.yarnpkg.com/en/docs/install#windows-stable) versão 1.XX.X instalado
 - Ter o [Git](https://git-scm.com/downloads) instalado

### Subindo a aplicação e testando

O primeiro passo é clonar o repositório na sua maquina, para isto rode:

`git clone https://github.com/AndreGros/Desafio04-Conceitos-React-Native`

Acesse a pasta do projeto e rode o comando abaixo, para atualizar as dependencias, no terminal:

`yarn`

Agora rode o seguinte comando para rodar os testes da aplicação:

`yarn test`
