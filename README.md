
# 📊 Linguagens por Repositórios de Empresas

Este projeto coleta dados públicos do GitHub para verificar quais linguagens de programação são utilizadas em repositórios de empresas específicas. O objetivo é realizar uma análise simples de popularidade de linguagens com base em alguns perfis corporativos.

## 🧩 O que o projeto faz

* Recebe uma lista de empresas (nomes de usuários/organizações do GitHub)
* Consulta os repositórios públicos de cada empresa
* Extrai a linguagem principal de cada repositório
* Agrupa e salva os dados em um arquivo `.csv` para análise posterior

## 🛠️ Tecnologias utilizadas

* Python 3
* `requests`
* `pandas`

## ▶️ Como executar

1. Clone o repositório:

   ```bash
   git clone https://github.com/Ligia-lab/linguagens-repositorios-empresas.git
   cd linguagens-repositorios-empresas
   ```

2. Crie um ambiente virtual:

   ```bash
   python -m venv .venv
   source .venv/bin/activate  # Linux/macOS
   ```

3. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

4. Execute o script principal:

   ```bash
   python linguagens_github.py
   ```


## 📝 Notas

* A API do GitHub tem limite de requisições por hora. Se necessário, adicione autenticação com token pessoal.
* Os dados podem variar conforme os repositórios públicos de cada empresa.

