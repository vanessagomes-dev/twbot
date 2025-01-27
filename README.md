# TwBot - Chatbot Inteligente 🤖

TwBot é um chatbot inteligente desenvolvido em Python, projetado para responder perguntas, realizar tarefas básicas e interagir com usuários. Ele utiliza técnicas de **Processamento de Linguagem Natural (NLP)** e pode ser integrado a diversas plataformas. O projeto também inclui uma interface gráfica simples criada com **Tkinter**.

---

## 🚀 **Funcionalidades**
- **Respostas Automáticas**: Baseadas em padrões configurados com a biblioteca `nltk.chat.util`.
- **Treinamento Personalizado**: Usando `ChatterBot`, o chatbot pode ser treinado com frases específicas.
- **Extração de Informações da Web**: Coleta textos de sites usando `Goose3`.
- **Cotação de Moedas em Tempo Real**: Consulta valores de moedas como dólar via API.

---

## 🛠️ **Tecnologias Utilizadas**
As principais tecnologias utilizadas no desenvolvimento do TwBot são:

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-3766AB?style=for-the-badge&logo=python&logoColor=white)
![ChatterBot](https://img.shields.io/badge/ChatterBot-Informal?style=for-the-badge&logo=ai&logoColor=white)
![Tkinter](https://img.shields.io/badge/Tkinter-GUI-blue?style=for-the-badge)
![Goose3](https://img.shields.io/badge/Goose3-Web_Scraping-FF4500?style=for-the-badge)
![Requests](https://img.shields.io/badge/Requests-HTTP_Requests-green?style=for-the-badge)

---

## 📷 **Interface Gráfica**

O TwBot possui uma interface gráfica simples e funcional, criada com **Tkinter**. A interface inclui:
- Campo de entrada para o usuário enviar mensagens.
- Botão de "Enviar" para iniciar a interação com o chatbot.
- Área de histórico para exibir as conversas.


---

## 📂 **Estrutura do Projeto**
```plaintext
TwBot/
├── README.md                # Documentação do projeto
├── requirements.txt         # Bibliotecas necessárias
├── interface.py             # Código com a interface gráfica
├── chatbot_nltk.py          # Chatbot utilizando NLTK
├── chatbot_chatterbot.py    # Chatbot utilizando ChatterBot
├── web_scraper.py           # Código para extração de textos com Goose3
└── cotacao.py               # Consulta de cotação de moedas

🖥️ Como Usar
Siga estas etapas para rodar o projeto em sua máquina:

Pré-requisitos
Certifique-se de que você tem o Python 3.8+ instalado e o pip atualizado:

python --version
python -m pip install --upgrade pip

##
Passos
**Clone este repositório:**

```git clone https://github.com/seuusuario/TwBot.git
cd TwBot

**Instale as dependências:**

```pip install -r requirements.txt

**Execute o chatbot com a interface gráfica:**
```python interface.py

##
Interaja com o chatbot:

Digite mensagens como "Oi" ou "Qual tecnologia está em alta?".
Para sair, digite "sair".
🌐 API para Cotação
A funcionalidade de cotação utiliza a API AwesomeAPI. Você pode consultar a cotação do dólar, euro, entre outras moedas.

##
👩‍💻 Contribuindo
Contribuições são bem-vindas! Siga estas etapas para contribuir:

**Faça um fork do repositório.**

**Crie uma branch para sua funcionalidade:**
```git checkout -b minha-nova-feature

**Faça um commit das suas mudanças:**
```git commit -m "Adicionei uma nova feature"

**Suba as alterações para o GitHub:**
```git push origin minha-nova-feature

**Abra um Pull Request.**

##
📜 Licença
Este projeto está licenciado sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.

##
✨ Contato
Desenvolvido por Vanessa Gomes. Entre em contato comigo no LinkedIn ou envie um e-mail para vanessagomesdev@gmail.com.

