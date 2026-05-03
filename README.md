# 🚀 Copilot Prompt Hub

Coleção estratégica de prompts para Copilotos de IA, otimizada para engenharia de software. Dividido em 5 modos operacionais (Ask, Edit, Plan, Agent e Study), este repositório padroniza a interação com a IA para diferentes fluxos de trabalho: desde a análise técnica e refatoração direta até o aprendizado profundo e autonomia de agentes.

---

## 🛠️ Modos de Operação

O repositório está organizado em perfis específicos para otimizar o consumo de tokens e a precisão das respostas:

| Modo | Objetivo | Comportamento Principal |
| :--- | :--- | :--- |
| **Ask** | Entender | Atua como mentor técnico, explica conceitos e debuga sem alterar arquivos. |
| **Edit** | Mudar | Focado em refatoração, ajustes de lógica e transformações diretas no código. |
| **Plan** | Projetar | Decompõe problemas complexos em etapas antes da implementação. |
| **Agent** | Executar | Atua com autonomia para navegar no projeto e criar múltiplas funcionalidades. |
| **Study** | Aprender | Tutor didático (Persona: Cortana) focado em conceitos, analogias e progresso. |

---

## 📁 Estrutura do Repositório

*   `ask.md`: Instruções para análise de código e suporte a dúvidas técnicas.
*   `edit.md`: Prompts para refatoração, limpeza de código e conversão de linguagens.
*   `plan.md`: Protocolo para arquitetura de soluções e validação de abordagens.
*   `agent.md`: Configuração para automação de tarefas complexas e múltiplos arquivos.
*   `study.md`: Guia de aprendizado ativo com foco em Java/Spring Boot e fundamentos de TI.

---

## 🚀 Como Usar

Para utilizar estes modos, você pode:

1.  **Copiar e colar** o conteúdo do arquivo `.md` correspondente nas "Custom Instructions" do seu Copiloto (Cursor, GitHub Copilot, ChatGPT, etc.).
2.  **Referenciar o arquivo** diretamente se a sua ferramenta permitir o uso de arquivos de regras (como o `.cursorrules`).
3.  **Ajustar a Stack:** Embora o modo Study esteja pré-configurado para Java e Spring Boot, as instruções são facilmente adaptáveis para outras linguagens no topo de cada arquivo.

---

## 🧠 Filosofia

Este projeto nasceu da necessidade de separar o **ruído da execução**. Ao definir modos claros, evitamos que a IA tente "adivinhar" se você quer apenas uma explicação ou uma mudança drástica no seu repositório, economizando tempo e revisões desnecessárias.
