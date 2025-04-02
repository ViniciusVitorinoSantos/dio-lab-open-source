<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"></a>
    <span> Profiles README DIO</span>
</h1>

## Sobre o Projeto
Página desenvolvida para fins didáticos para o curso **Contribuindo em um Projeto Open Source no GitHub** da [Digital Innovation One](https://www.dio.me/). Lembre-se de que Markdown é mais voltado para a documentação e apresentação de texto formatado, enquanto a remoção de bugs normalmente envolve a compreensão detalhada do código e o uso de ferramentas de desenvolvimento adequadas à linguagem de programação específica.

[![Preview](https://img.shields.io/badge/Preview-000?style=for-the-badge&logo=github&logoColor=30A3DC)](https://digitalinnovationone.github.io/dio-lab-open-source/)

```
docs/
├── assets/
│   ├── css/
│   │   └── styles.css
│   └── js/
│       └── scripts.js
├── favicon.ico
├── index.html
└── README.md
```

## Tecnologias
![HTML](https://img.shields.io/badge/HTML-000?style=for-the-badge&logo=html5&logoColor=30A3DC)
![CSS](https://img.shields.io/badge/CSS-000?style=for-the-badge&logo=css3&logoColor=E94D5F)
![JavaScript](https://img.shields.io/badge/JavaScript-000?style=for-the-badge&logo=javascript&logoColor=30A3DC)

 ---
# GitHub PR Manager

[![Python Version](https://img.shields.io/badge/python-3.7%2B-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/license-MIT-green)](https://opensource.org/licenses/MIT)

Este projeto é uma ferramenta para gerenciar Pull Requests (PRs) de um repositório no GitHub. Ele utiliza a API do GitHub para buscar todos os PRs abertos e adicionar uma label a eles, se necessário.

## Funcionalidades

- Recupera todos os PRs abertos de um repositório no GitHub.
- Adiciona uma label específica a PRs que não a possuem.
- Usa uma sessão persistente de requisições HTTP para melhorar a performance.

## Pré-requisitos

- Python 3.7 ou superior.
- Um token de autenticação do GitHub (veja a seção "Autenticação").
- A variável de ambiente `GITHUB_TOKEN` deve ser configurada com seu token de autenticação.

## Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio
```
2. Crie um ambiente virtual (opcional, mas recomendado):
```bash
python3 -m venv venv
source venv/bin/activate  # No Windows use: venv\Scripts\activate
```
3. Instale as dependências:
```bash
pip install -r requirements.txt
```
4. Defina a variável de ambiente GITHUB_TOKEN:
No terminal, no Linux/Mac:
```bash
export GITHUB_TOKEN="seu_token_aqui"
```
5. No Windows (PowerShell):
```bash
$env:GITHUB_TOKEN="seu_token_aqui"
```
Como Usar
Certifique-se de ter configurado o token corretamente.
Execute o script:
```bash
python script.py
```
O script irá buscar todos os PRs abertos no repositório e adicionar a label "run dio workflow" caso ela não exista.










