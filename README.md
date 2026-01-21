# chatbot-telegram
Desenvolvido no curso de Pós Graduação IA e Automação da Faculdade RocketSeat.

# Será que vai chover? bot Telegram (n8n)

Chatbot de Telegram que retorna a temperatura atual de uma cidade usando a API OpenWeather.

## Importação
1. Abra o n8n
2. Import Workflow
3. Selecione `workflow-telegram-chatbot.json`

## Variáveis de Ambiente
Defina no ambiente do n8n:

OPENWEATHER_API_KEY=xxxx
TELEGRAM_BOT_TOKEN=xxxx

## Uso
Envie mensagens no formato:
Cidade,UF

Exemplo:
Arroio Trinta, SC
