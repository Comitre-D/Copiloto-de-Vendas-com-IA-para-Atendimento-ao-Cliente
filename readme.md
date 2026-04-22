Copiloto-de-Vendas-com-IA-para-Atendimento-ao-Cliente
Atividade final do bootcamp DIO - LUPO.

Copiloto de Vendas Inteligente - Hardware & TIO - Copiloto de Vendas Inteligente é uma solução de Inteligência Artificial desenvolvida para atuar como um Consultor Especialista em hardware.

O sistema utiliza uma Lógica de Estados para guiar o vendedor desde a identificação da oportunidade até o protocolo de pós-venda, garantindo que as recomendações sejam tecnicamente precisas e baseadas em dados reais.

🧠 Lógica de Funcionamento: O agente opera sob uma estrutura de Filtro de Contexto que identifica o momento da venda: ESTADO 1: OPORTUNIDADE, Diagnóstico: Classificação de Ticket (High/Low) e identificação de lacunas de informação. Qualificação: Perguntas estratégicas baseadas no uso (FPS, Office, Edição). Oferta: Consulta dinâmica à base de preços oficial (Base_Precos_Copiloto_Vendas_v1) alocada no Google Drive. Ancoragem: Estratégia de preços comparativa (Bom/Ótimo/Premium). ESTADO 2: SUCESSO - Acionado após a confirmação da venda.

Gera mensagens personalizadas para WhatsApp.Define estratégias de fidelização e LTV (Lifetime Value).

🛠️ Tecnologias e MetodologiasI: A Generativa: Configurada com diretrizes de personalidade, tom de voz e ética consultiva. Prompt Engineering: Uso de técnicas de Chain-of-Thought para garantir que o diagnóstico venha antes da oferta. Integração de Dados: Preparado para ler bases de dados externas (Google Drive/Sheets) via ferramentas de busca e recuperação.

Gatilhos de Performance: Lógica condicional para identificar palavras-chave (ex: "travamento" aciona foco em SSD/RAM).

📋 Exemplo de Fluxo/Entrada do Cliente/Ação da IA - Resultado Esperado "Quero um PC para Warzone" Gatilho de Competição - Foco em alta taxa de atualização e baixa latência. "O PC está lento" Gatilho de Performance. Recomendação de Upgrade de SSD e Memória RAM. "Venda fechada" Protocolo de Sucesso - Mensagem de agradecimento técnica e sugestão de pós-venda.

📖 Como Utilizar Input de Interesse: Forneça o que o cliente busca e o perfil de uso. Qualificação: A IA gerará as perguntas certas para fechar o diagnóstico. Aprovação: Utilize o Checkpoint de Validação para confirmar os itens e valores. Fechamento: Ao confirmar o "Sim", o protocolo de pós-venda é ativado automaticamente. Nota: Este projeto foi desenvolvido durante o Bootcamp - Assistente de TI - Vendas, focado em transformar IAs em ferramentas práticas de aumento de produtividade comercial.
