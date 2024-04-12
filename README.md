# WEB SCRAPING FINANCE
![imagem_de_precos_acoes](assets/webscraping_project.jpg)
---

**1. Título do Projeto:**  Web Scraping Finance

**2. Descrição:**
   O projeto Web Scraping Finance é uma aplicação em Python desenvolvida para coletar dados históricos de páginas da web de forma automatizada. Utiliza técnicas de raspagem de dados para extrair informações específicas de sites e armazená-las localmente para análise posterior.

**3. Objetivo:**
   O objetivo principal do projeto é demonstrar como criar um web scraper simples em Python para coletar dados históricos de preço, como ações e cotações de páginas da web, como ações, cotação de moedas entre outros.

**4. Funcionalidades:**
   - Extrair informações específicas de páginas da web.
   - Armazenar os dados coletados em formato estruturado
   - Permitir a configuração de parâmetros de scraping, como URLs alvo, elementos HTML a serem extraídos, entre outros.

**5. Tecnologias Utilizadas:**
   - Python 3.11.0
   - Bibliotecas / Pacotes:
     - Pandas: para manipulação e análise de dados.
     - Selenium WebDriver: para automatizar ações no navegador.
     - Yfinance: para acessar os dados históricos de preços do Yahoo Finance.
     - Cryptocmd: para acessar os dados históricos de preços de Criptomoedas.
     - BCB: para acessar os dados históricos do site do Banco do Brasil.

**6. Uso:**
- Acesse aos notebooks:
    - [Criptomoedas](notebooks/criptomoedas.ipynb)
    - [Banco Central](notebooks/dados_banco_central.ipynb)
    - [Fundamentus](notebooks/dados_fundamentus.ipynb)
    - [Yahoo Finance](notebooks/yahoo_finance.ipynb)
- Configure as URLs alvo e os elementos HTML a serem extraídos dentro do código ou como argumentos de linha de comando.
- Execute o script para iniciar a coleta de dados.
- Os dados coletados serão salvos em DataFrame.

**7. Exemplo de Uso:**
- Extraindo histórico de preços do Dólar no site do Banco Central
- Fonte: [Banco Central](https://www.bcb.gov.br/)

```python
#Instalando o pacote bcb
pip install python-bcb

# Importando o sgs
from bcb import sgs

# Requisição para acessar os dados
dados_do_bc = sgs.get({"DOLAR": 1})

# Exibindo os dados
dados_do_bc

   ```

**8. Contribuições:**
   Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas (issues) ou enviar pull requests com melhorias ou correções.

**9. Autor:**
   - Ronaldo da Gama C. Junior
   - E-mail: ronaldo.profissional@hotmail.com

**10. Licença:**
   Este projeto está licenciado sob a [Licença MIT](https://opensource.org/licenses/MIT).

---