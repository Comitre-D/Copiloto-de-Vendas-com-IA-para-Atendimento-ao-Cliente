# 🤖 Copiloto de Vendas com IA para Atendimento ao Cliente
> **Atividade Final:** Bootcamp DIO - LUPO.

O **Copiloto de Vendas Inteligente - Hardware & TI** é uma solução de Inteligência Artificial desenvolvida para atuar como um Consultor Especialista. O sistema utiliza uma **Lógica de Estados** para guiar o vendedor desde a identificação da oportunidade até o protocolo de pós-venda, garantindo recomendações tecnicamente precisas.

---

## 🧠 Lógica de Funcionamento
O agente opera sob uma estrutura de **Filtro de Contexto** que identifica o momento exato da venda:

### 🔹 ESTADO 1: OPORTUNIDADE
* **Diagnóstico:** Classificação de Ticket (High/Low) e identificação de lacunas de informação.
* **Qualificação:** Perguntas estratégicas baseadas no perfil de uso (FPS/Games, Office, Edição de Vídeo).
* **Oferta:** Consulta dinâmica à base de preços oficial (via Google Drive/Sheets).
* **Ancoragem:** Estratégia de preços comparativa (**Bom / Ótimo / Premium**).

### 🔸 ESTADO 2: SUCESSO
* **Finalização:** Acionado imediatamente após a confirmação da venda.
* **Engajamento:** Gera mensagens personalizadas para WhatsApp.
* **Retenção:** Define estratégias de fidelização e análise de **LTV (Lifetime Value)**.

---

## 🛠️ Tecnologias e Metodologias
* **IA Generativa:** Configurada com diretrizes de personalidade, tom de voz profissional e ética consultiva.
* **Prompt Engineering:** Uso de técnicas de *Chain-of-Thought* (Cadeia de Pensamento) para garantir que o diagnóstico venha sempre antes da oferta.
* **Integração de Dados:** Preparado para leitura de bases externas via ferramentas de busca e recuperação (RAG).
* **Gatilhos de Performance:** Lógica condicional para identificar palavras-chave (ex: "travamento" aciona foco imediato em SSD/RAM).

---

## 📋 Exemplo de Fluxo e Resultados
| Entrada do Cliente (Input) | Gatilho Identificado | Resultado Esperado da IA |
| :--- | :--- | :--- |
| "Quero um PC para Warzone" | **Competição** | Foco em alta taxa de atualização e baixa latência. |
| "O PC está lento" | **Performance** | Recomendação de Upgrade de SSD e Memória RAM. |
| "Venda fechada" | **Protocolo de Sucesso** | Mensagem de agradecimento técnica e sugestão de pós-venda. |

---

## 📖 Como Utilizar
1.  **Input de Interesse:** Forneça o que o cliente busca e o perfil de uso.
2.  **Qualificação:** A IA gerará as perguntas certas para fechar o diagnóstico técnico.
3.  **Aprovação:** Utilize o *Checkpoint de Validação* para confirmar os itens e valores.
4.  **Fechamento:** Ao confirmar o "Sim", o protocolo de pós-venda é ativado automaticamente.

---
> **Nota:** Este projeto foi desenvolvido durante o **Bootcamp Lupo/DIO**, focado em transformar IAs em ferramentas práticas de aumento de produtividade comercial e suporte técnico.
