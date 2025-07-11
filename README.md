# desafio-azure-dio
Desafio DIO – Speech e Language Studio

🗣️ Speech Studio 
Objetivo: Converter áudio em texto (Speech to Text)

Passos:
Acessar o site: https://speech.microsoft.com/portal
Navegar até a aba "Speech to Text".
Selecionar a opção de upload de arquivo de áudio (.wav ou .mp3).
Escolher o idioma do áudio (ex: português - pt-BR).
Clicar em "Transcrever".
O sistema retorna a transcrição do áudio.
Analisar o resultado, avaliando se houve erros ou acertos na transcrição.

Objetivo: Converter texto em fala (Text to Speech)

Passos:
Ainda na interface do Speech Studio, ir até a seção "Text to Speech".
Escrever um texto curto (ex: "Olá, tudo bem? Bem-vindo ao Azure!").
Escolher um idioma e uma voz (ex: "pt-BR - Francisca, voz neural").
Clicar em "Play" para ouvir a geração da fala.
Explorar as opções de entonação, pausas e expressividade.
(Opcional) Baixar o áudio gerado para uso em outro sistema.

📚 Language Studio – Testes reais com interface pública
Objetivo: Analisar o sentimento de um texto

Passos:
Acessar https://language.azure.com
Selecionar a opção "Sentiment Analysis" no menu lateral.
Inserir um texto de exemplo (ex: "Hoje foi um dia maravilhoso!").
Clicar em "Run".
Ver o resultado: classificação como positivo, neutro ou negativo, com score.

Objetivo: Detecção de entidades nomeadas (NER)

Passos:
Na mesma interface, selecionar "Named Entity Recognition".
Inserir um texto que contenha nomes, datas, locais, etc.
Ex: "Maria viajou para São Paulo no dia 5 de julho de 2025".
Clicar em "Run".
Observar como o modelo reconhece:
"Maria" como pessoa
"São Paulo" como local
"5 de julho de 2025" como data

Objetivo: Gerar resumo automático de um texto longo

Passos:
Acessar a opção "Extractive Summarization".
Inserir um parágrafo longo (mínimo de 5 frases).
Clicar em "Run".
Observar como a IA retorna um ou dois parágrafos que resumem a ideia principal.

💡 Observação
Alguns recursos exigem uma chave de API ou conta com crédito Azure — esses não foram acessíveis diretamente.

Em vídeos e tutoriais, vi exemplos de uso em integrações com chatbots, sistemas de atendimento e legendagem automática.
