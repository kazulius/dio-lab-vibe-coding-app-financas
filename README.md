# 💸 App de Finanças Pessoais com Vibe Coding - FinChat

Aprenda a **criar soluções com IA** de forma criativa, guiando ferramentas como o **Copilot** e o **Lovable** com uma comunicação simples e natural. O foco é desenvolver o conceito de um **App de Organização de Finanças Pessoais**, mas, acima de tudo, aprender o **jeito Vibe de programar com IA**.

## ✨ O que é Vibe Coding

**Vibe Coding** é uma forma leve e criativa de desenvolver com IA, baseada em **conversas naturais e bem estruturadas**. Você não precisa escrever código linha por linha. Em vez disso, aprende a **guiar a IA** descrevendo suas ideias de forma clara, com **intenção e contexto**. Em outras palavras:

> Você mostra a vibe da sua ideia e a IA transforma em solução (ou em um caminho para ela).

## 🎯 Desafio

Problema: Muitas pessoas não conseguem manter um controle financeiro porque os aplicativos exigem muita entrada de dados manual, e a criação de orçamentos é vista como algo tedioso. 

Precisamos de uma solução que permita **controlar as finanças por meio de uma conversa simples**, com **agentes de IA** capazes de criar **planos de economia personalizados e automatizados**. Você deve utilizar as ideias de **Vibe Coding** e **MVP (Produto Mínimo Viável)** para desenvolver o **conceito de um aplicativo** que resolva o problema citado.

> [!IMPORTANT]
> Você **não precisa construir o código**! O foco está em **usar a IA como sua parceira criativa**, transformando boas ideias e prompts em conceitos funcionais que simulam um produto real.

## 🪄 Etapas do Desafio

### 1. Saber o que Pedir é a Chave! Otimize seus Prompts!

Antes de pedir para a IA "criar um app", é importante definir com clareza o que você quer construir e por quê. Para isso, você vai criar um **PRD (Product Requirements Document)** simplificado, uma especificação que serve como _briefing_ para a IA entender sua ideia.

Um bom PRD deve descrever o problema, quem será beneficiado, as principais funcionalidades e o que você espera que a IA entregue. Use o modelo abaixo como ponto de partida e adapte conforme o seu estilo:

Esse é o prompt que usei após edição no Copilot:

```markdown
Crie uma app de finanças pessoais com base no seguinte PRD (Product Requirements Document):

PRD – App de Organização de Finanças Pessoais Conversacional

1. Contexto
O aplicativo busca simplificar o controle financeiro pessoal por meio de interações em linguagem natural.
Em vez de formulários complexos ou planilhas, o usuário conversa com um “Agente Financeiro” que registra gastos, sugere economias e ajuda a acompanhar metas.

2. Problema
- Usuários desistem de apps financeiros porque exigem muita entrada manual.
- Falta personalização e experiência fluida.
- Necessidade de uma solução prática e acessível para iniciantes.

3. Público-Alvo
- Pessoas que desejam começar a organizar suas finanças sem complicação.
- Principalmente iniciantes sem familiaridade com planilhas ou apps tradicionais.
- Usuários que preferem interações naturais em vez de interfaces rígidas.

4. Funcionalidades-Chave
1. Registro de gastos via chat em linguagem natural.
2. Classificação automática das transações.
3. Definição e acompanhamento de metas financeiras.
4. Dicas personalizadas de economia via “Agente Financeiro”.
5. Relatórios simples e personalizados.

5. MVP (Produto Mínimo Viável)
Telas/Fluxos Principais:
- Tela de Conversa: interface central para registrar gastos e interagir com o agente.
- Tela de Metas: criação e acompanhamento de objetivos financeiros.
- Tela de Relatórios: gráficos simples mostrando categorias de gastos e evolução das metas.

Recursos Necessários:
- Processamento de linguagem natural (NLP).
- Motor de categorização automática.
- Sistema de notificações e dicas personalizadas.
- Banco de dados para histórico de gastos e metas.

Validação Inicial:
- Testes com grupo piloto de usuários iniciantes.
- Coleta de feedback sobre clareza da conversa e utilidade das recomendações.
- Métricas: frequência de uso, número de gastos registrados, satisfação com relatórios.
```

Depois de preencher o modelo, use o Copilot Web para revisar e melhorar o seu prompt antes de ir ao Lovable. A ideia é lapidar o texto até que ele fique claro, direto e reflita exatamente a sua intenção.

Interações com o Lovable:

> Após a criação das telas iniciais do app no Lovable, utilize o seguinte comando:

```markdown
Crie também uma tela com o extrato além das 3 telas atuais. Utilize ordem cronológica do mais recente para o mais antigo. inclua a categoria (com a cor) e exiba também o saldo atualizado a cada transação realizada.
```

> [!TIP]
> Pense no PRD/Prompt como “o briefing que a IA precisa para entender sua vibe”. Portanto, quanto mais claro e intencional for o texto, mais próximas do ideal serão as respostas da IA.

### 2. Explorando o Lovable na Prática

Com seu PRD pronto e revisado, é hora de colocar a IA em ação. Abra o Lovable, cole seu prompt completo e peça o plano inicial do MVP do seu aplicativo. Como o plano gratuito limita você a 5 interações por dia, seja estratégico:
- Faça perguntas diretas e construtivas, como “crie o fluxo de telas com base nas funcionalidades listadas” ou “gere uma versão resumida do plano de MVP”;
- Priorize clareza nas instruções para aproveitar ao máximo cada resposta;

Durante essa etapa, você pode orientar a IA para três entregas principais:
1. Agente Financeiro: defina o comportamento e o tom de voz de um consultor financeiro pessoal, alinhado ao público e objetivo do app.
2. Fluxo de Telas: peça à IA para gerar o fluxo conceitual de telas com base nas funcionalidades descritas no PRD, simulando a interação por conversa.
3. Plano de MVP: solicite um resumo das 5 funcionalidades principais, dos recursos necessários e um plano de validação inicial (como medir se o app cumpre seu propósito).

Resultado final do Lovable: app publicado em https://kazulius.lovable.app/
<img width="1010" height="924" alt="image" src="https://github.com/user-attachments/assets/f0400630-c278-4e15-a835-119434054772" />

## Reflexão;
 - O app foi criado normalmente, mas observei que os recursos não atenderam totalmente o que foi proposto no prompt. 
 - O app já vem com dados fictícios.
 - Apesar da aula ter mostrado o app gerado já com autenticação, o meu não foi criado com essa opção.
 - O app não está funcional.
 - Ainda precisamos ser muito detalhistas nos prompts de IA para obter os resultados esperados.

> [!TIP]
> Se preferir, você pode fazer tudo com o **Copilot**. O importante é exercitar a habilidade de transformar intenções em instruções claras e testar os limites da IA como parceira criativa.

### 3. Entregando o Desafio na DIO

Finalize seu projeto criando um **repositório no GitHub** (pode ser um **fork** deste).  
No README do seu repositório, inclua:

- Seu **prompt final** (PRD);  
- Prints ou pequenos vídeos das interações com a IA;  
- Um resumo do que o seu **App de Finanças Pessoais** faz;  
- Uma breve **reflexão sobre o processo**:
  - O que funcionou bem?  
  - O que não funcionou como o esperado?  
  - O que aprendeu sobre conversar com IAs?

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
