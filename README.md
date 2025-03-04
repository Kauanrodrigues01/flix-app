# Flix App

Flix App é uma aplicação web desenvolvida com **Streamlit** que consome a **Flix API**, permitindo aos usuários explorar um catálogo de filmes, fazer buscas, filtrar conteúdos, visualizar detalhes e avaliar filmes. O sistema também conta com um sistema de autenticação para gerenciar acessos.

## Funcionalidades

- **Autenticação de Usuários**: Login e registro utilizando a API.
- **Catálogo de Filmes**: Lista completa dos filmes cadastrados na **Flix API**.
- **Busca Avançada**: Filtragem por gênero, popularidade e data de lançamento.
- **Detalhes do Filme**: Exibição de informações detalhadas sobre cada filme.
- **Avaliações**: Usuários podem avaliar e comentar sobre os filmes.
- **Interface Simples e Intuitiva**: Desenvolvida com **Streamlit**, focada na experiência do usuário.

## Tecnologias Utilizadas

- **Streamlit**: Framework para criação de aplicações web interativas em Python.
- **Python**: Linguagem principal do projeto.
- **Flix API**: API RESTful desenvolvida em **Django REST Framework**.
- **JWT**: Autenticação baseada em tokens.

## Instalação e Execução

1. **Clonar o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/flix-app.git
   cd flix-app
   ```

2. **Criar e ativar um ambiente virtual:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate  # Windows
   ```

3. **Instalar as dependências:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Executar a aplicação:**
   ```bash
   streamlit run app.py
   ```

A aplicação estará disponível em: [http://localhost:8501](http://localhost:8501)
