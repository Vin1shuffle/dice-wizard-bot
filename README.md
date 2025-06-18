# 🎲 Dice Wizard Bot

Um bot de Discord simples e funcional para rolagem de dados de RPG de mesa, feito em **Python** com a biblioteca `discord.py`.

## ✨ Sobre o Projeto

O **Dice Wizard Bot** foi desenvolvido com o objetivo de facilitar rolagens de dados em partidas de RPG dentro do Discord. Ele interpreta comandos no formato clássico como `1d20+5`, `2d6`, `1d100-2` e responde com o resultado total, exibindo cada dado individual e o modificador aplicado.

Esse é um dos primeiros projetos do meu portfólio, focado no aprendizado prático de:

- Programação com Python
- Manipulação de expressões regulares
- Lógica de rolagem de dados
- Criação de bots para Discord
- Versionamento com Git e GitHub

## 🚀 Funcionalidades

- Comando `!roll` para rolagem de dados.
- Suporte a modificadores positivos e negativos (ex: `1d20+3`, `2d6-1`).
- Feedback detalhado do resultado no chat.
- Organização do código para futuras melhorias.

### Exemplo de uso:

```text
Usuário: !roll 2d6+1
Bot: @Usuário rolou 2d6+1 e obteve: [4, 5]+ 1 = 10
```

## 🛠️ Tecnologias Utilizadas

- Python 3.x
- [discord.py](https://discordpy.readthedocs.io/)
- Expressões Regulares (`re`)
- Git e GitHub

## 📦 Como Rodar Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/Vin1shuffle/dice-wizard-bot.git
   ```

2. Acesse a pasta do projeto:
   ```bash
   cd dice-wizard-bot
   ```

3. Crie e ative o ambiente virtual:
   ```bash
   python -m venv .venv
   .venv\Scripts\activate  # Windows
   source .venv/bin/activate  # Linux/macOS
   ```

4. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

5. Crie um arquivo `.env` com o seu token de bot:
   ```
   DISCORD_TOKEN=seu_token_aqui
   ```

6. Execute o bot:
   ```bash
   python bot.py
   ```

## 🧠 Próximos Passos

- Adicionar comando `!help`
- Suporte a rolagens com vantagem/desvantagem
- Interface web para configurar o bot (futuramente)
- Hospedar em nuvem (Replit / PythonAnywhere)

## 🤝 Contribuição

Sinta-se livre para abrir issues ou contribuir com sugestões e melhorias!

---

Feito com 💻 por [Vin1shuffle](https://github.com/Vin1shuffle)
