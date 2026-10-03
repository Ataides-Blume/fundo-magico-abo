# 🪄 Sejam bem vindos ao Projeto: Fundo Mágico

Gerador de backgrounds com IA. O usuário descreve o fundo que deseja e a aplicação mostra o **preview ao vivo** junto com o **código HTML e CSS** pronto para copiar.


## 🧰 Tecnologias

HTML5 · CSS3 · JavaScript · n8n Cloud · Google Gemini

## 🧠 Etapas até o resultado

1. **Descrição:** o usuário escreve o fundo desejado no campo de texto.
2. **Envio:** o JavaScript envia a descrição por `POST` para um Webhook do n8n.
3. **Geração:** o AI Agent, com o modelo Google Gemini, cria o HTML e o CSS do background.
4. **Tratamento:** um nó de código em JavaScript limpa a resposta da IA e converte o texto em JSON.
5. **Resposta:** o nó Respond to Webhook devolve o resultado para o front-end.
6. **Exibição:** a página aplica o preview do fundo e mostra os códigos HTML e CSS em cards.

```
Front-end ─▶ Webhook ─▶ AI Agent (Gemini) ─▶ Code in JavaScript ─▶ Respond to Webhook ─▶ Front-end
```

## 📁 Estrutura do projeto

```
Fundo Mágico/
├── src/
│ ├── css/
│ │ ├── styles.css
│ │ ├── reset.css
│ │ └── responsive.css
│ ├── images/
│ ├── js/
│ │ └── index.js
│ └── index.html
└── README.md
```

## 🙏 Agradecimentos

Obrigado por conhecer o Fundo Mágico! Este projeto me ajudou a praticar HTML, CSS e JavaScript e a integrar o front-end com automação e inteligência artificial. Fico aberto a sugestões e feedbacks.

**Ataides Blume Oliveira**
Santo André - SP

