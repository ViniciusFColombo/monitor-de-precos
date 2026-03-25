# 📊 Monitor de Preços de Produto

Projeto desenvolvido para monitorar automaticamente o preço de um produto e gerar histórico de variações ao longo do tempo.

---

## 🚀 Funcionalidades

- 🔎 Coleta automática de preço via Web Scraping
- 💾 Armazenamento de histórico em CSV
- 📈 Registro contínuo de preços
- 🔄 Identificação de mudança de preço
- 🚨 Alerta quando o preço diminui
- 📊 Geração de relatório profissional em Excel

---

## 🛠️ Tecnologias utilizadas

- Python
- requests
- BeautifulSoup
- pandas
- openpyxl

---

## 📂 Estrutura do projeto
monitor-preco/

  -app.py

  -historico_precos.csv

  -Relatorio_Precos.xlsx

  -README.md

---

## ⚙️ Como funciona

1. O script acessa a página do produto
2. Captura o preço atual
3. Compara com o último valor salvo
4. Registra no histórico:
   - Data
   - Preço
   - Se houve mudança
   - Se houve queda (alerta)
5. Gera um relatório em Excel com formatação profissional

---

## 📊 Exemplo de saída

| Data       | Preço | Mudou | Alerta |
|-----------|------|------|--------|
| 25/03     | 19.79 | Sim  | Não    |
| 25/03     | 18.90 | Sim  | Sim    |

---

## 💼 Aplicação

Esse projeto pode ser utilizado para:

- Monitoramento de preços de produtos
- Acompanhamento de oportunidades de compra
- Automação de coleta de dados
- Base para dashboards e análises

---

## 🔥 Diferenciais

- Histórico contínuo de dados
- Lógica de detecção de mudança
- Sistema de alerta
- Geração de relatório automatizado

---

## 👨‍💻 Autor

Desenvolvido por Vinicius Colombo
