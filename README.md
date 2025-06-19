# Quadro de Disponibilidade - UTE Pernambuco III

Painel multiplataforma para monitoramento, atualização e registro de status dos equipamentos da UTE Pernambuco III, integrado ao Google Sheets para colaboração em tempo real.

---

## 📋 **Funcionalidades**

- Visualização do status de todos os equipamentos (dados em tempo real do Google Sheets)
- Atualização individual do status dos equipamentos (admin)
- Atualização em lote via CSV (admin)
- Controle de acesso: modo admin (edita) e operador (só visualiza)
- Interface moderna e responsiva, inspirada em Flutter

---

## 🚀 **Como usar**

1. **Login**
   - `admin` / `admin`: acesso total, pode editar
   - `operador` / `operador`: visualização apenas

2. **Navegação**
   - `status.html`: painel principal, visualização ao vivo
   - `entrada.html`: formulário para atualizar status individual
   - `csv_update.html`: atualização em lote via CSV
   - `index.html`: tela de login inicial

3. **Integração**
   - Todos os dados são lidos e atualizados direto em uma planilha Google (Google Sheets) usando Google Apps Script como backend.

---

## 🛠️ **Configuração do Backend**

1. Crie uma planilha no Google Sheets com as colunas:
