# 🛒 MarketX

> Um sistema completo de marketplace para Minecraft (Paper/Spigot), permitindo compra, venda e troca de itens entre jogadores de forma simples, segura e intuitiva.

---

## ✨ Visão Geral

O **MarketX** transforma a economia do seu servidor em um verdadeiro marketplace.

Com suporte a:
- 💰 Venda por dinheiro (Vault)
- 🔄 Troca de itens (item ↔ item)
- 📦 Sistema de resgate
- 🔔 Notificações inteligentes
- 🧠 UX moderna via GUI

Tudo isso com foco em performance, organização e experiência do jogador.

---

## 🚀 Funcionalidades Principais

### 🛍️ Sistema de Loja
- Cada jogador possui sua própria loja
- Criação de ofertas de forma simples via GUI
- Suporte a:
  - Venda por dinheiro
  - Troca por item
- Visualização da loja de outros jogadores

---

### 🌍 Loja Global
- Lista todas as ofertas disponíveis no servidor
- Interface organizada e intuitiva
- Navegação rápida entre ofertas

---

### 💰 Integração com Economia (Vault)
- Suporte completo a plugins de economia
- Compra e venda com dinheiro
- Transferência automática de saldo
- Validação de saldo antes da compra

---

### 🔄 Sistema de Troca (Item ↔ Item)
- Permite trocar itens diretamente entre jogadores
- Exemplo:
  - 1 diamante por 64 madeiras
- Confirmação visual antes de concluir

---

### 📦 Sistema de Resgate
- Itens recebidos não vão direto para o inventário
- Ficam armazenados em uma aba de resgate
- Evita perda de itens
- Funciona mesmo com jogador offline

---

### 🔔 Sistema de Notificações
- Notificações em tempo real:
  - venda realizada
  - compra concluída
- Notificações offline:
  - ao entrar no servidor, o jogador é informado sobre vendas feitas
- Feedback com:
  - mensagens
  - sons
  - títulos/action bar

---

### 📜 Histórico
- Registro de ações do jogador:
  - vendas realizadas
  - ofertas canceladas
  - itens adicionados/removidos do estoque
- Cada ação contém:
  - descrição
  - data e hora

---

### 🔎 Sistema de Busca e Navegação
- Interface baseada em inventário (GUI)
- Navegação fluida e intuitiva
- Preparado para:
  - filtros
  - paginação
  - busca por item

---

### 🛠️ Permissões
Sistema básico configurável via `config.yml`:

```yml
permissions:
  use: "autotrader.use"
  admin: "autotrader.admin"
