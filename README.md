# dio-agente-microsoft-copilot-studio
Resumo dos passos para se criar um agente do Copiloto no Microsoft Copilot Studio para criar um Agente de Seguros Personalizado com Microsoft Copilot Studio
Com o Microsoft Copilot Studio, você pode criar um agente de seguros personalizado que interage com seus clientes, responde a perguntas e realiza ações específicas, tudo integrado ao Microsoft 365 Copilot. Veja como:

1. Criar um Agente:
	- Acesse o Copilot Studio: Navegue até o Microsoft Copilot Studio e faça login com sua conta Microsoft 365.
	- Crie um novo copiloto: Clique em "Novo copiloto" e siga as instruções para configurar seu agente. Dê um nome relevante, como "Agente de Seguros [Nome da sua empresa]".
	- Defina o idioma: Escolha o idioma principal do seu agente, neste caso, português.
	
2. Criar Tópicos Relacionados ao Domínio de Seguros:
	- Identifique os principais tópicos: Pense nas perguntas e tarefas mais comuns que seus clientes realizam, como:
	- Cotação de seguros (auto, residencial, vida)
	- Abertura de sinistros
 	- Informações sobre coberturas e apólices
 	- Pagamento de seguros
	- Dúvidas sobre planos específicos
	- Crie tópicos no Copilot Studio: Para cada tópico, crie um novo tópico no Copilot Studio.
	- Defina frases de gatilho: Adicione frases que os clientes podem usar para iniciar o tópico (ex: "quero cotar um seguro auto", "como faço para abrir um sinistro?").
	- Crie o fluxo de conversa: Use o editor visual para criar o fluxo de conversa, incluindo perguntas, respostas e ações.
	
3. Criar Ações de Conversa Relacionadas ao Tópico:
 	- Exemplo: Cotação de Seguro Auto:
	- No tópico "Cotação de Seguro Auto", adicione uma ação para coletar informações do cliente:
	- Marca e modelo do veículo
	- Ano de fabricação
	- CEP de residência
	- Dados do condutor
	- Utilize conectores para integrar com sistemas externos:
	- Conecte-se a APIs de seguradoras para obter cotações em tempo real.
	- Armazene os dados coletados em um banco de dados.
	- Apresente as cotações ao cliente: Mostre as opções de seguro com detalhes de cobertura e preço.

4. Refinar a Ação de Conversa com GenAI:
	- Melhorar a qualidade das respostas:
	- Utilize a geração de linguagem natural (NLG) para criar respostas mais personalizadas e amigáveis.
	- Integre modelos de linguagem grandes (LLMs) para responder a perguntas complexas e fornecer informações detalhadas.
	- Use a análise de sentimento para adaptar o tom da conversa às emoções do cliente.
	- Exemplo:
	- Em vez de simplesmente mostrar uma tabela de cotações, o agente pode gerar um resumo personalizado, destacando os benefícios de cada opção e respondendo a perguntas adicionais do cliente.
	- O copilot pode ser programado para entender quando o cliente esta nervoso, ou chateado, e mudar o tom da conversa para um tom mais calmo e atencioso.
	- Diminuir a qualidade das respostas:
	- Em casos onde o cliente precisa de informações mais objetivas, ou de respostas mais diretas, pode-se configurar o copilot para usar uma linguagem mais direta.
	- Pode ser configurado para o copilot fornecer respostas padrão, para perguntas muito especificas, onde a GenAI pode gerar respostas incorretas, ou com informações desatualizadas.

5. Testar o Agente:
	- Use o painel de teste: O Copilot Studio possui um painel de teste integrado onde você pode simular conversas com seu agente.
	- Teste todos os tópicos e ações: Verifique se o agente responde corretamente às perguntas e executa as ações desejadas.
	- Peça feedback: Convide colegas ou clientes para testar o agente e fornecer feedback sobre a experiência.

6. Publicar o Agente em um Site de Demonstração:
	- No Copilot Studio, clique em "Publicar" e siga as instruções para publicar seu agente em um site de demonstração.
	- Compartilhe o link: Compartilhe o link do site de demonstração com seus clientes ou colegas para que eles possam interagir com o agente.
	- Integre com o Microsoft 365 Copilot: Após a aprovação do administrador do locatário, a ação poderá ser adicionada às experiências do Microsoft 365 Business Chat.

7. Considerações de Compliance e LGPD:
	- Garanta que seu agente esteja em conformidade com as leis de proteção de dados e políticas de segurança da sua empresa.
	- Atualização contínua: Mantenha seu agente atualizado com as últimas informações e funcionalidades.
	- Feedback do cliente: Utilize o feedback dos clientes para melhorar continuamente a experiência do seu agente.
