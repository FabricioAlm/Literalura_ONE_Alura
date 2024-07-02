# Literalura

![Leralura-img1](https://github.com/fabriciooliv/Literalura--ONE-Alura/assets/146496164/39b59d3a-ae10-462a-9588-a51516f62d13)

A "Literalura" é uma aplicação Java/Spring Boot dedicada aos entusiastas de livros. Ela facilita a busca de livros, a listagem de livros registrados, a apresentação de autores, e oferece diversas funcionalidades voltadas para a leitura e organização de obras literárias.

## 📘 Menu da Aplicação

1. **Buscar livros pelo título**: Consulta a API Gutendex para buscar livros pelo título.
2. **Listar livros registrados**: Exibe todos os livros registrados no banco de dados.
3. **Listar autores registrados**: Exibe todos os autores dos livros registrados.
4. **Listar autores vivos em um determinado ano**: Lista autores que estavam vivos em um ano especificado.
5. **Listar autores nascidos em determinado ano**: Lista autores que nasceram em um ano especificado.
6. **Listar autores por ano de sua morte**: Lista autores que morreram em um ano especificado.
7. **Listar livros em um determinado idioma**: Lista livros registrados no banco de dados em um idioma especificado.
8. **Encerrar a aplicação**: Encerra o programa.

## 💻 Tecnologias Utilizadas

- **IntelliJ IDEA 2024.1.1 (Community Edition)**
- **Java 17**
- **Spring Boot 3.3**
- **Maven**
- **PostgreSQL**
- **Gutendex API**

## 🔨 Configuração do Projeto

### Pré-requisitos

- Java 17 ou superior
- Maven
- PostgreSQL

## 🌁 Estrutura do Projeto

- `br.com.alura.literalura`: Pacote principal do projeto.
  - `principal`: Contém a classe `Principal`, que gerencia a execução da aplicação.
  - `model`: Contém as classes de modelo (`Livro`, `Autor`, `LivroDTO`, `AutorDTO`).
  - `repository`: Contém as interfaces de repositório Spring Data JPA.
  - `service`: Contém as classes de serviço (`ConsumoAPI`, `ConverteDados`).


### 📕 Tutorial para o uso

1. **Buscar livros pelo título**:
   - Digite `1` e pressione Enter.
   - Insira o título do livro que deseja buscar.
   - A aplicação fará uma consulta à API Gutendex e exibirá os resultados encontrados.

2. **Listar livros registrados**:
   - Digite `2` e pressione Enter.
   - A aplicação listará todos os livros registrados no banco de dados.

3. **Listar autores registrados**:
   - Digite `3` e pressione Enter.
   - A aplicação listará todos os autores dos livros registrados.

4. **Listar autores vivos em um determinado ano**:
   - Digite `4` e pressione Enter.
   - Insira o ano desejado.
   - A aplicação listará os autores que estavam vivos naquele ano.

5. **Listar autores nascidos em determinado ano**:
   - Digite `5` e pressione Enter.
   - Insira o ano desejado.
   - A aplicação listará os autores que nasceram naquele ano.

6. **Listar autores por ano de sua morte**:
   - Digite `6` e pressione Enter.
   - Insira o ano desejado.
   - A aplicação listará os autores que morreram naquele ano.

7. **Listar livros em um determinado idioma**:
   - Digite `7` e pressione Enter.
   - Insira o código do idioma desejado (por exemplo, `pt` para Português, `en` para Inglês).
   - A aplicação listará todos os livros registrados no banco de dados naquele idioma.
8. **Encerrar a aplicação**:
   - Digite `0` e pressione Enter.
   - A aplicação será encerrada.



