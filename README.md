# Automation-Sheets-Make
# ⚙️ Automação de Dados: Make.com & Google Sheets

Este repositório contém o fluxo de ETL (Extração, Transformação e Carga) desenvolvido no **Make.com** para automação e integração de dados operacionais e de marketing com o **Google Sheets**.

---

### 📌 Objetivo do Projeto
Eliminar o processamento manual de relatórios e dados de campanhas, automatizando a recepção de eventos via Webhooks e realizando o tratamento em tempo real para alimentação de planilhas e relatórios de mídia.

---

### 🛠️ Tecnologias Utilizadas
- **Make.com:** Plataforma de orquestração do fluxo.
- **Webhooks:** Recepção de requisições HTTP em tempo real.
- **Google Sheets API:** Inserção e atualização automatizada de linhas.
- **JSON:** Formatação e manipulação das cargas de dados (*payloads*).

---

### 📂 Estrutura do Repositório
- `Automation-Sheets-Make`: Arquivo de exportação do cenário do Make.com.
- `README.md`: Documentação técnica e instruções do projeto.

---

### 🚀 Como Importar e Executar este Cenário

1. Baixe o arquivo `Automation-Sheets-Make` deste repositório.
2. Acesse sua conta no **Make.com** e crie um novo cenário (*New Scenario*).
3. No menu inferior, clique nos três pontos (`...`) e escolha **Import Blueprint**.
4. Selecione o arquivo `.json` baixado.
5. Reconfigure as conexões necessárias (Google Sheets e URL do Webhook).
