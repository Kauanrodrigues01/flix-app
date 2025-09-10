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

O **Flix App** é uma aplicação web moderna desenvolvida com Streamlit para gerenciamento de filmes, permitindo aos usuários visualizar, cadastrar e gerenciar informações sobre filmes, gêneros, atores e avaliações. A aplicação oferece uma interface intuitiva com dashboards visuais e gráficos interativos.

## ✨ Funcionalidades

### 🏠 Dashboard Principal
- **Estatísticas Gerais**: Visualização do total de filmes cadastrados
- **Gráficos Interativos**: Distribuição de filmes por gênero usando Plotly
- **Métricas de Avaliações**: Total de avaliações e média geral de estrelas

### 🎭 Gerenciamento de Dados
- **🎬 Filmes**: Cadastro e visualização de filmes com informações detalhadas
- **🎭 Atores/Atrizes**: Gerenciamento de elenco
- **🏷️ Gêneros**: Organização por categorias
- **⭐ Avaliações**: Sistema de reviews e classificações

### 🔐 Sistema de Autenticação
- Login seguro com token JWT
- Controle de sessão integrado
- Logout automático em caso de token expirado

## 🛠️ Tecnologias Utilizadas

- **Frontend**: Streamlit
- **Visualização de Dados**: Plotly Express
- **Grid Interativo**: Streamlit-AgGrid
- **Requisições HTTP**: Requests
- **Configuração**: TOML
- **Linting**: Flake8

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
- Python 3.8+
- API Backend rodando em `http://localhost:8000`

### Instalação

1. **Clone o repositório**
```bash
git clone https://github.com/Kauanrodrigues01/flix-app.git
cd flix-app
```

2. **Instale as dependências**
```bash
pip install -r requirements.txt
```

3. **Execute a aplicação**
```bash
streamlit run app.py
```

4. **Acesse no navegador**
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

### Integração com API
- Comunicação segura via JWT
- Tratamento de erros robusto
- Cache de dados para melhor performance

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

## 🤝 Contribuição

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👨‍💻 Autor

**Kauan Rodrigues**
- GitHub: [@Kauanrodrigues01](https://github.com/Kauanrodrigues01)

---

<div align="center">
  Feito com ❤️ e Python
</div>
