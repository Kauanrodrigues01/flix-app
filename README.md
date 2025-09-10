# 🎬 Flix App

<div align="center" style="display: flex; justify-content: center; align-items: center; gap: 20px; flex-wrap: wrap;">
  <img src="https://raw.githubusercontent.com/Kauanrodrigues01/Kauanrodrigues01/refs/heads/main/images/projetos/flix-app/desktop.jpeg" alt="Flix App Desktop" width="500"/>
  <img src="https://raw.githubusercontent.com/Kauanrodrigues01/Kauanrodrigues01/refs/heads/main/images/projetos/flix-app/mobile.jpeg" alt="Flix App Mobile" width="120"/>
</div>

<br>

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Requests](https://img.shields.io/badge/Requests-FF6F00?style=for-the-badge&logo=python&logoColor=white)

</div>

## 📝 Sobre o Projeto

O **Flix App** é uma aplicação web desenvolvida com **Streamlit** que consome a **Flix API**, permitindo aos usuários explorar um catálogo de filmes, fazer buscas, filtrar conteúdos, visualizar detalhes e avaliar filmes. O sistema também conta com um sistema de autenticação para gerenciar acessos e oferece uma interface intuitiva com dashboards visuais e gráficos interativos.

A aplicação funciona como um frontend moderno que se comunica com a **Flix API** (desenvolvida em **Django REST Framework**), proporcionando uma experiência completa de gerenciamento de filmes com funcionalidades avançadas de visualização de dados.

## ✨ Funcionalidades

### 🔐 Autenticação de Usuários
- **Login e Registro**: Sistema de autenticação utilizando a **Flix API**
- **JWT Token**: Autenticação baseada em tokens para segurança
- **Controle de Sessão**: Gerenciamento automático de sessões ativas
- **Logout Automático**: Desconexão em caso de token expirado

### 🎬 Catálogo de Filmes
- **Lista Completa**: Acesso a todos os filmes cadastrados na **Flix API**
- **Busca Avançada**: Filtragem por gênero, popularidade e data de lançamento
- **Detalhes Completos**: Visualização de informações detalhadas sobre cada filme
- **Interface Intuitiva**: Navegação simples e responsiva

### 🏠 Dashboard Interativo
- **Estatísticas em Tempo Real**: Visualização do total de filmes cadastrados
- **Gráficos Interativos**: Distribuição de filmes por gênero usando Plotly
- **Métricas de Avaliações**: Total de avaliações e média geral de estrelas
- **Visualização de Dados**: Charts e gráficos dinâmicos

### 🎭 Gerenciamento Completo
- **🎬 Filmes**: Cadastro e visualização de filmes com informações detalhadas
- **🎭 Atores/Atrizes**: Gerenciamento completo do elenco
- **🏷️ Gêneros**: Organização e categorização por gêneros
- **⭐ Avaliações**: Sistema completo de reviews, comentários e classificações

## 🛠️ Tecnologias Utilizadas

### Frontend
- **Streamlit**: Framework para criação de aplicações web interativas em Python
- **Plotly Express**: Biblioteca para visualização de dados e gráficos interativos
- **Streamlit-AgGrid**: Componente para grids interativos e tabelas avançadas

### Backend Integration
- **Flix API**: API RESTful desenvolvida em **Django REST Framework**
- **Requests**: Biblioteca para requisições HTTP e comunicação com a API
- **JWT**: Sistema de autenticação baseado em tokens

### Desenvolvimento
- **Python**: Linguagem principal do projeto
- **TOML**: Formato de configuração
- **Flake8**: Ferramenta de linting para qualidade de código

## 🏗️ Arquitetura

O projeto segue uma arquitetura bem estruturada com separação de responsabilidades:

```
flix-app/
├── 📁 actors/          # Módulo de atores
├── 📁 api/             # Serviços de API
├── 📁 genres/          # Módulo de gêneros
├── 📁 home/            # Página inicial
├── 📁 login/           # Sistema de autenticação
├── 📁 movies/          # Módulo de filmes
├── 📁 reviews/         # Sistema de avaliações
├── 📄 app.py           # Aplicação principal
├── 📄 config.toml      # Configurações
└── 📄 requirements.txt # Dependências
```

Cada módulo contém:
- `page.py` - Interface do usuário
- `service.py` - Lógica de negócio
- `repository.py` - Acesso a dados via API

## 🚀 Como Executar

### Pré-requisitos
- **Python 3.8+**
- **Flix API**: Backend rodando em `http://localhost:8000`
- **Ambiente Virtual**: Recomendado para isolamento de dependências

### Instalação

1. **Clone o repositório**
```bash
git clone https://github.com/Kauanrodrigues01/flix-app.git
cd flix-app
```

2. **Crie e ative um ambiente virtual**
```bash
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows
```

3. **Instale as dependências**
```bash
pip install -r requirements.txt
```

4. **Execute a aplicação**
```bash
streamlit run app.py
```

5. **Acesse no navegador**
```
http://localhost:8501
```

### Para Desenvolvimento

```bash
pip install -r requirements_dev.txt
flake8 .
```

## 📊 Funcionalidades Principais

### Dashboard Interativo
- Gráfico de pizza mostrando distribuição de filmes por gênero
- Métricas em tempo real
- Interface responsiva e intuitiva

### Gerenciamento Completo
- CRUD completo para todas as entidades
- Validação de dados
- Feedback visual para ações do usuário

### Integração com Flix API
- **Comunicação Segura**: Todas as requisições utilizam autenticação JWT
- **Endpoints RESTful**: Consumo completo da API Django REST Framework
- **Tratamento de Erros**: Sistema robusto de tratamento de exceções
- **Cache Inteligente**: Otimização de performance com cache de dados em sessão
- **Sincronização**: Dados sempre atualizados com o backend

## 🔧 Configuração

O arquivo `config.toml` permite personalizar:
```toml
[general]
app_title = "Flix App"
```

## 📱 Interface Responsiva

A aplicação foi desenvolvida com design responsivo, funcionando perfeitamente em:
- 💻 Desktop
- 📱 Mobile
- 📟 Tablet

## 👨‍💻 Autor

**Kauan Rodrigues Lima**

- GitHub: [@Kauanrodrigues01](https://github.com/Kauanrodrigues01)
- LinkedIn: [Kauan Rodrigues](https://www.linkedin.com/in/kauan-rodrigues-lima/)

---
