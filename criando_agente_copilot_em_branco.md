# Guia Rápido: Criando e Customizando um Agente no Microsoft Copilot Studio

## 🚀 1. Criar um agente Copilot do zero (em branco)

1. Acesse o [Microsoft Copilot Studio](https://copilotstudio.microsoft.com).
2. Clique em **"Criar agente"**.
3. Escolha a opção **"Em branco"**.
4. Dê um **nome**, selecione o **idioma** e clique em **Criar**.
5. O agente será criado com uma estrutura básica e sem tópicos.

---

## 🧠 2. Customizar um tópico

1. No menu lateral, vá até **"Tópicos"**.
2. Clique em **“+ Novo tópico”**.
3. Defina um nome para o tópico (ex: “Agendar reunião”).
4. Adicione **gatilhos** (frases que o usuário pode dizer para iniciar o tópico).
   - Ex: “Quero marcar uma reunião”, “Agendar call”.
5. Em seguida, configure a **resposta do agente** usando a árvore de conversa com caixas de diálogo.
6. Salve e publique.

---

## ❌ 3. Personalizar mensagem de erro do tópico

1. No editor de tópicos, clique em **“+”** para adicionar uma ação após uma tentativa de resposta.
2. Para personalizar a **mensagem de erro padrão**:
   - Vá para **Configurações do agente > Mensagens do sistema**.
   - Edite a mensagem em **"O agente não conseguiu encontrar uma resposta"**.
   - Insira um texto amigável ou direcione para outro tópico.
   - Exemplo: “Desculpe, não entendi. Você pode tentar reformular ou falar com um atendente?”

---

## 🔧 4. Ajustar a qualidade da resposta com GenAI

1. No tópico, adicione um **bloco de resposta com IA**.
2. Escreva um **prompt personalizado** para guiar a resposta da IA.
3. Use o controle de **criatividade da resposta**:
   - Acesse o bloco de IA e ajuste o **nível de criatividade**:
     - **Mais baixo**: respostas mais diretas e objetivas.
     - **Mais alto**: respostas mais criativas e detalhadas.
4. Você também pode usar **parâmetros de contexto** para refinar a geração da resposta (ex: tom, estilo e detalhes).

---
