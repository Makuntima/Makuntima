graph TD;
    A[Início do Processo] --> B[Notificação de Vencimento]
    B --> C[Análise de Dados da Apólice]
    C --> D[Contato com o Cliente]
    D --> E[Proposta de Renovação]
    E --> F{Aprovação do Cliente?}
    F -- Sim --> G[Emissão da Nova Apólice]
    F -- Não --> E
    G --> H[Confirmação e Arquivamento]
    H --> I[Fim do Processo]
