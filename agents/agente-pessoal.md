# Agente Pessoal (Orquestrador)

## Responsabilidade
Atuar como o agente central do sistema, responsável por interpretar a intenção do usuário e orquestrar a execução das tarefas.

## Funções
- Receber mensagens do usuário via chat
- Interpretar intenção utilizando LLM
- Decidir qual agente especializado deve ser acionado
- Encaminhar a solicitação para o workflow correto
- Consolidar e retornar respostas ao usuário

## Estratégia de Funcionamento
O Agente Pessoal não executa ações finais diretamente.  
Ele atua como **orquestrador**, delegando responsabilidades para agentes especialistas.

## Diferencial
- Centralização da lógica de decisão
- Fácil extensibilidade para novos agentes
- Separação clara entre decisão e execução
