<h1 align="center">
  <img alt="Fastfeet" title="Fastfeet" src="github/logo.png" width="300px" />
</h1>

<h3 align="center">Desafio 2: FastFeet, o início</h3>

<p align="center">Nesse projeto foi desenvolvido uma aplicação Back-end para uma transportadora fictícia, o FastFeet </a>.</p>


# 🚀 Tecnologias

- ⚡ [JavaScript](https://skylab.rocketseat.com.br/journey/starter)

- ⚡ [Node](https://nodejs.org/en/)
- ⚡ [Sequelize](https://sequelize.org/)

# 🔥 Instalação
1. Faça o clone do projeto `git clone git@github.com:morattojr/bootcamp-gostack-challenge-02.git`

# 💻 Execução
1. Entre na pasta `bootcamp-gostack-challenge-02`;

2. Execute `yarn install` para instalar todas as dependências;
3. Crie os seguintes contâiners no docker:
 ```
 docker run --name fastfeat -e POSTGRES_PASSWORD=123 -p 5432:5432 -d postgres
 ```
* `Lembrando que é necessário renomear o arquivo .env.example para .env e assim colocar as suas devidas variáveis de acordo com seu ambiente;`
4. Execute as migrations com `yarn sequelize db:migrate`;

5. Execute as seeds com `yarn sequelize db:seed:all`;
6. Clique neste botão <a href="https://insomnia.rest/run/?label=Fastfeet%2001&uri=https%3A%2F%2Fraw.githubusercontent.com%2Fmorattojr%2Fbootcamp-gostack-challenge-02%2Fmaster%2FInsomnia_2020-04-15.json" target="_blank"><img src="https://insomnia.rest/images/run.svg" alt="Run in Insomnia"></a> para que seja importado todo o workspace no seu Insomnia ou navegue até **[aqui](https://raw.githubusercontent.com/morattojr/bootcamp-gostack-challenge-02/master/Insomnia_2020-04-15.json)** para acessar o arquivo JSON para consumo da API.
7. E por último execute os comandos `yarn dev` e logo após `yarn queue`;

## 🧾 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.

---

<p>Made with ♥ by Geraldo Moratto Junior- <a href="https://www.linkedin.com/in/geraldo-moratto-junior/" target="_blank" rel="nofollow">Get in touch!</a></p>
