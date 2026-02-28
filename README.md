🚀 Tecnologias e Fluxo de Trabalho
A aplicação funciona através de um ciclo de três etapas principais:

1. Speech-to-Text (STT) com Whisper
O Whisper é o modelo de Reconhecimento Automático de Fala (ASR) da OpenAI. Diferente de modelos comuns, ele foi treinado com 680.000 horas de dados multilíngues.

Diferencial: Alta robustez contra ruídos de fundo, sotaques variados e terminologias técnicas.

Função: Transcrever o áudio do usuário para texto com precisão.

2. Processamento com ChatGPT
O texto transcrito é enviado para a API do ChatGPT, que atua como o "cérebro" do sistema.

Função: Analisar a pergunta, processar o contexto e gerar uma resposta inteligente em formato de texto.

3. Text-to-Speech (TTS) com gTTS
Para fechar o ciclo de interação, utilizamos o Google Text-To-Speech.

Função: Converter a resposta textual do ChatGPT em áudio, permitindo que o usuário "ouça" a IA.
