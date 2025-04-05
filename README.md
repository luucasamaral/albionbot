# 🤖 Albion Bot

Albion Bot é um bot de Discord desenvolvido com amor por fãs de Albion Online.  
Ele permite consultar rapidamente informações de jogadores diretamente pelo jogo, com dados atualizados, organizados e de forma divertida!

---

## ⚙️ Tecnologias

- Python 3.11+
- discord.py
- requests
- Albion Data API

---

## 🚀 Como rodar localmente

1. Clone o projeto
```bash
git clone https://github.com/seu-user/albinbot.git
cd albonbot
```

2. Crie e ative um ambiente virtual
```bash
python -m venv venv
.env\Scriptsctivate
```

3. Instale as dependências
```bash
pip install -r requirements.txt
```

4. Crie o arquivo `.env` e adicione sua token do Discord:
```env
DISCORD_TOKEN=coloque_aqui_sua_token
```

5. Rode o bot
```bash
python debug.py
```

---

## 📜 Comandos disponíveis

- `/player <nome>`  
  Retorna informações básicas do jogador: guilda, kill fame, última morte etc.

---

## 📍 Roadmap – AlbonBot v2

### Funcionalidades novas
- [ ] `/comparar jogador1 jogador2`
- [ ] `/ultimakill` e `/ultimamorte`
- [ ] `/guilda <nome>` para listar membros e ranking da guilda

### UX e Estética
- [ ] Respostas com embed bonitão
- [ ] Emojis personalizados e separações visuais 🧩
- [ ] Botões interativos com "Ver mais"

### Integrações e Monitoramento
- [ ] Log em JSON com histórico de pesquisas
- [ ] Dash de visualizações e uso do bot

### Qualidade de Vida
- [ ] Autocomplete de nomes
- [ ] Cache de resultados para evitar flood
- [ ] Comando `/help` com todas as opções

---

## 🙌 Créditos

Feito por [Seu Nome Aqui] com suporte técnico do ChatGPT (aka. Sobis 💻)  
Ideias, testes e melhorias em progresso!
