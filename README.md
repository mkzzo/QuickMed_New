# 🏥 QuickMed

> Plataforma web para agendamento, consulta e gestão de atendimentos médicos e serviços de saúde.

[![Deploy static content to Pages](https://github.com/mkzzo/QuickMed_New/actions/workflows/main.yml/badge.svg)](https://github.com/mkzzo/QuickMed_New/actions/workflows/main.yml)
[![GitHub Pages](https://img.shields.io/badge/Demo-GitHub%20Pages-blue?style=flat&logo=github)](https://mkzzo.github.io/QuickMed_New/)

---

## 📌 Sobre o Projeto

O **QuickMed** é uma interface web desenvolvida para conectar pacientes a serviços de saúde de forma ágil, intuitiva e centralizada. A plataforma oferece navegação completa entre página inicial informativa, visualização de especialidades médicas e áreas de autenticação para usuários e profissionais.

### 🌐 Demonstração Online
Acesse a versão publicada diretamente pelo GitHub Pages:  
👉 **[https://mkzzo.github.io/QuickMed_New/](https://mkzzo.github.io/QuickMed_New/)**

---

## 🚀 Funcionalidades

- **Página Inicial Institucional:** Apresentação da plataforma, serviços oferecidos e chamadas para ação.
- **Fluxo de Autenticação:** Telas dedicadas para login e cadastro de usuários/pacientes.
- **Navegação Responsiva:** Estrutura visual adaptada para visualização em diferentes resoluções.
- **Deploy Automatizado (CI/CD):** Pipeline configurada via **GitHub Actions** para entrega contínua diretamente no **GitHub Pages**.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Semântica e estrutura de conteúdo.
- **CSS3:** Estilização, layout responsivo e identidade visual.
- **JavaScript (Vanilla):** Comportamentos interativos da interface.
- **GitHub Actions:** Automação de compilação e deploy contínuo (CI/CD).
- **GitHub Pages:** Hospedagem estática do projeto.

---

## 📂 Estrutura de Diretórios

```text
QuickMed_New/
├── .github/
│   └── workflows/
│       └── main.yml        # Pipeline de deploy contínuo no GitHub Pages
├── Pagina_Inicial/         # Estrutura principal da interface
│   ├── index.html
│   ├── styles.css
│   └── script.js
├── assets/                 # Imagens, ícones e mídias estáticas
├── index.html              # Ponto de entrada raiz
└── README.md               # Documentação do projeto
```

---

## 💻 Como Executar Localmente

### Pré-requisitos
- Um navegador web atualizado (Chrome, Edge, Firefox ou Safari).
- [Git](https://git-scm.com/) instalado no computador.

### Passo a passo

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/mkzzo/QuickMed_New.git
   ```

2. **Acesse o diretório do projeto:**
   ```bash
   cd QuickMed_New
   ```

3. **Abra no navegador:**
   - Dê um duplo clique no arquivo `index.html` na raiz; ou
   - Utilize a extensão **Live Server** no VS Code para rodar um servidor local com recarregamento em tempo real.

---

## ⚙️ Pipeline CI/CD

O projeto conta com um workflow automatizado em `.github/workflows/main.yml`. A cada novo `push` ou `pull request` integrado na branch `main`:
1. O runner `ubuntu-latest` realiza o checkout do repositório.
2. Os artefatos estáticos são empacotados.
3. O deploy é publicado instantaneamente no ambiente do GitHub Pages.

---

## 👤 Autor

Desenvolvido por **Hiago Melo**.

- **GitHub:** [@mkzzo](https://github.com/mkzzo)
