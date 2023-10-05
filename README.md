# MarketPlace API

Projeto de uma **API** de um market place, utilizando a técnologia ***Ruby on Rails*** como *framework* e aplicar boas práticas de padrões de projeto.

## Technologies
### IDE's
<a id="vscode" href="https://code.visualstudio.com/" target="_blank"><img alt="VS Code Icon" height="60" width="50" src="https://raw.githubusercontent.com/Volaxy/Volaxy/7a188050404d5162ab30fe1440c6915c2c3aa0b7/icons/visual-studio-code.svg" /></a>

### Languages
<a id="ruby" href="https://www.ruby-lang.org/en/" target="_blank"><img alt="Ruby Icon" height="60" width="50" src="https://raw.githubusercontent.com/Volaxy/Volaxy/7a188050404d5162ab30fe1440c6915c2c3aa0b7/icons/ruby.svg" /></a>

### Frameworks
<a id="ruby-on-rails" href="https://rubyonrails.org/" target="_blank"><img alt="Ruby on Rails Icon" height="60" width="50" src="https://raw.githubusercontent.com/Volaxy/Volaxy/7a188050404d5162ab30fe1440c6915c2c3aa0b7/icons/rails.svg" /></a>

### DB
<a id="postgres" href="https://www.postgresql.org/" target="_blank"><img alt="Postgres Icon" height="60" width="50" src="https://raw.githubusercontent.com/Volaxy/Volaxy/7a188050404d5162ab30fe1440c6915c2c3aa0b7/icons/postgresql.svg" /></a>

### Websites
<a href="https://rubygems.org/" target="_blank"><img alt="Rubygems Icon" height="60" width="50" src="https://raw.githubusercontent.com/Volaxy/Volaxy/7a188050404d5162ab30fe1440c6915c2c3aa0b7/icons/rubygems.svg" /></a>

<hr>

## &#x2699; Configurações Iniciais
1. Baixe as tecnologias nescessárias na parte de [Technologies](#technologies):
- [VS Code](#vscode).
- [Ruby](#ruby).
- [Ruby on Rails](#ruby-on-rails).
- [Postgres](#postgres)
2. Clone o projeto no seu ambiente.
3. Instale todas as dependências do projeto:
```shell
bundle install
```

4. Crie os bancos de dados:
```shell
rails db:create
```

> IMPORTANTE! Mude as informações de conexão com o banco no arquivo *config/database.yml*

## 🖥️ Como Executar o Projeto
1. Digite o comando:
```shell
rails s
```
> Por padrão o servidor executa na porta **3000**

2. Abra o navegador de sua preferência na *URL*: <a href="localhost:3000" target="_blank">localhost:3000</a>