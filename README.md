# GoodCharge AI — EV ChargeOps Assistant

Chatbot conversacional desenvolvido para o EV Challenge 2026 (FIAP × GoodWe), com foco no gerenciamento compartilhado de recarga de veículos elétricos em condomínios.

---

# Integrantes

Lucas Silva de Abreu - RM 572321

Guilherme Reiche - RM 

Enzo Guislandi - RM 

João Camperlingo - RM 568957

Nicolas Nishi - RM 572242

---

# Problema abordado

O crescimento da mobilidade elétrica trouxe novos desafios para condomínios residenciais que utilizam carregadores compartilhados para veículos elétricos.

Muitos condomínios enfrentam problemas relacionados à organização das filas de recarga, controle de horários, dúvidas operacionais dos moradores e dificuldades no rateio do consumo energético.

O projeto GoodCharge AI foi desenvolvido para atuar como um assistente virtual inteligente especializado no contexto GoodWe EV ChargeOps, auxiliando moradores e síndicos com suporte rápido e contextualizado.

---

# Contexto escolhido

## Contexto B — EV ChargeOps (uso condominial)

O grupo escolheu o contexto condominial por permitir interações mais próximas da realidade dos usuários finais.

Os principais problemas abordados são:

- organização da fila de recarga;
- regras de utilização;
- suporte operacional;
- consumo energético;
- comunicação entre moradores e administração.

---

# Persona atendida

## Persona principal: Síndico

O síndico é responsável pelo gerenciamento operacional do condomínio e frequentemente precisa responder dúvidas relacionadas ao uso dos carregadores elétricos.

O chatbot foi projetado para reduzir a sobrecarga operacional do síndico.

## Persona secundária: Morador

O morador poderá utilizar o chatbot para tirar dúvidas relacionadas ao uso dos carregadores compartilhados.

---

# Objetivo do chatbot

O objetivo do GoodCharge AI é atuar como um assistente virtual inteligente especializado no gerenciamento de recarga compartilhada em condomínios.

O chatbot deverá:

- responder dúvidas operacionais;
- auxiliar moradores;
- explicar regras de uso;
- fornecer suporte contextualizado;
- manter respostas dentro do escopo GoodWe EV ChargeOps.

---

# Tecnologias utilizadas

| Camada | Tecnologia |
|---|---|
| Linguagem | Python 3.10+ |
| Modelo IA | Gemini |
| Framework | LangChain |
| Interface | Terminal |
| Memória | Histórico de conversa |
| Versionamento | Git + GitHub |

---

# Justificativa técnica

## Python

Python foi escolhido pela facilidade de integração com bibliotecas de Inteligência Artificial.

## Gemini

Gemini foi escolhido por possuir versão gratuita e boa performance em português brasileiro.

## LangChain

LangChain será utilizado para gerenciamento do fluxo conversacional e memória.

---

# Fluxograma

O fluxograma representa o funcionamento lógico do chatbot.

## Fluxo principal

1. Usuário envia mensagem;
2. Sistema recebe entrada;
3. Injeção do system prompt;
4. Recuperação do histórico;
5. Processamento da solicitação;
6. Geração da resposta pelo LLM;
7. Resposta enviada ao usuário;
8. Atualização do histórico.

O fluxograma visual está disponível em:

```text
/docs/fluxograma.png
```

---

# Estrutura do projeto

```text
GoodCharge-AI/
│
├── README.md
├── .gitignore
│
├── docs/
│   └── fluxograma.png
│
├── prompts/
│   └── system_prompt.md
│
├── tests/
│   └── modelo_de_teste.md
```

---

# Modelo de teste

Veja:

```text
/tests/modelo_de_teste.md
```

---

# System Prompt

Veja:

```text
/prompts/system_prompt.md
```

---

# Limitações conhecidas

- O chatbot não possui acesso ao sistema real do condomínio;
- Não realiza agendamentos reais;
- Não controla fisicamente os carregadores.

---

# Próximos passos

Na Sprint 2 o grupo pretende:

- desenvolver o chatbot em Python;
- integrar o modelo Gemini;
- implementar memória de contexto;
- criar interface interativa.

---

# Licença

Projeto acadêmico desenvolvido para o EV Challenge 2026 — FIAP × GoodWe.
