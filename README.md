# ❌ Jogo da Velha Avançado - React + Vite ⭕

Um jogo da velha moderno desenvolvido com **React** e **Vite**, que conta com um sistema completo de autenticação e controle de rotas baseado em três tipos de perfis: **Comum**, **Aviso** (Restrito) e **Administrador**.

### Integrantes:
* Matheus da Silva Marcondes - BP3061493
* João Vitor Oliveira Durães - BP3061353
* Eduardo Lourenço Soares - BP
* Raul Ramos Cirilo - BP
* João Vitor Moraes Sant'Anna - BP

---

## 🚀 Funcionalidades

### 🔐 Sistema de Autenticação e Perfis
O acesso ao jogo e ao painel é controlado por níveis de permissão:
* **Usuário Administrador:** Acesso total ao sistema. Pode gerenciar usuários, visualizar relatórios gerais de partidas, limpar históricos e configurar avisos do sistema.
* **Usuário Comum:** Pode jogar contra outros jogadores localmente (ou bot), visualizar seu próprio histórico de partidas, ranking e estatísticas pessoais.
* **Usuário em "Aviso":** Conta temporariamente restrita ou marcada. O usuário recebe um alerta global ao fazer login e possui limitações de uso (ex: chat bloqueado ou impossibilidade de entrar no ranking oficial) até que a pendência seja resolvida.

### 🎮 Mecânicas do Jogo
* Tabuleiro interativo com transições suaves.
* Histórico de jogadas e placar em tempo real.
* Sistema de ranking (Leaderboard) para os usuários comuns.

---

## 🛠️ Tecnologias Utilizadas

* **React** — Biblioteca JavaScript para construção da interface.
* **Vite** — Build tool ultra-rápida para o ambiente de desenvolvimento.
* **React Router Dom** — Gerenciamento de rotas e proteção de caminhos privados.
* **Tailwind CSS** — Estilização moderna e responsiva (opcional - altere se usar outra).
* **Context API / Redux** — Gerenciamento de estado global da autenticação e do jogo.

---

## 📦 Como Instalar e Rodar o Projeto

Siga os passos abaixo para executar o projeto localmente em sua máquina.

### Pré-requisitos
Certifique-se de ter o [Node.js](https://nodejs.org) instalado (versão 18+ recomendada).

### Passo a Passo

1. **Clone o repositório:**
   ```bash
   git clone https://github.com
   ```

2. **Entre na pasta do projeto:**
   ```bash
   cd nome-do-repositorio
   ```

3. **Instale as dependências:**
   ```bash
   npm install
   # ou usando yarn / pnpm
   yarn install
   ```

4. **Inicie o servidor de desenvolvimento:**
   ```bash
   npm run dev
   # ou
   yarn dev
   ```

5. **Acesse no navegador:**
   Abra a URL exibida no terminal (geralmente `http://localhost:5173`).

---

## 🔑 Credenciais de Teste (Mock)

Caso o projeto utilize dados locais/mockados para homologação, você pode testar os diferentes fluxos com os usuários abaixo:

| E-mail | Senha | Nível de Acesso / Perfil |
| :--- | :--- | :--- |
| `admin@jogo.com` | `admin123` | **Administrador** (Painel de controle) |
| `player@jogo.com` | `player123` | **Usuário Comum** (Acesso ao jogo e ranking) |
| `aviso@jogo.com` | `aviso123` | **Usuário de Aviso** (Tela de alerta / restrições) |

---









































/
