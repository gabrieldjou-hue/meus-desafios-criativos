Atue como um especialista em N8N e automações para restaurantes.

Crie uma automação para registrar e encaminhar automaticamente contatos, pedidos de reserva e solicitações recebidas pelo site da A Boa Di Nápoles.

Público:
Equipe responsável pelo atendimento do restaurante.

Ferramentas envolvidas:
Site hospedado no GitHub, formulário de contato, N8N, webhook, Google Sheets e Gmail ou WhatsApp.

Fluxo:
1. Receber os dados enviados pelo formulário do site através de um webhook.
2. Validar nome, telefone, e-mail e mensagem do cliente.
3. Classificar a solicitação como reserva, pedido, dúvida ou reclamação.
4. Registrar os dados em uma planilha do Google Sheets.
5. Enviar uma notificação para a equipe do restaurante.
6. Enviar uma confirmação automática ao cliente informando que a solicitação foi recebida.
7. Sinalizar reclamações e solicitações urgentes para atendimento prioritário.
8. Registrar erros e enviar um alerta ao responsável quando o fluxo falhar.

Regras:
Não registrar solicitações sem nome ou telefone.
Validar o formato do e-mail quando ele for informado.
Evitar registros duplicados.
Não confirmar uma reserva automaticamente sem a validação da equipe sobre a disponibilidade.
Proteger os dados pessoais dos clientes e registrar somente as informações necessárias.
Caso ocorra um erro, preservar os dados recebidos e avisar o responsável.

Explique quais nós do N8N devem ser utilizados, a configuração de cada nó, os campos necessários no webhook, a estrutura da planilha e a lógica de tratamento de erros.

Apresente também um exemplo de workflow em formato JSON compatível com importação no N8N.