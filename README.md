# 🔥 Smoke & Fire Detection 

Bem-vindo(a) ao projeto! 🚀
Aqui, brinquei de detetive do fogo usando dados ambientais coletados por sensores IoT.
A missão é simples:
👉 Treinar um modelo de Machine Learning que consiga prever se existe ou não um incêndio, usando variáveis do ambiente como temperatura, umidade, gases e partículas suspensas no ar.

📊 Sobre a Base de Dados - smoke_detection_.csv

O dataset é quase como uma central de monitoramento ambiental em miniatura. Ele traz 62 mil registros com diversas variáveis medidas em tempo real:

UTC → tempo em segundos (cronômetro da coleta ⏱️)

Temperature [C] → temperatura do ar 🌡️

Humidity [%] → umidade do ar 💧

TVOC [ppb] → compostos orgânicos voláteis (basicamente, cheiros suspeitos 👃)

eCO2 [ppm] → concentração equivalente de dióxido de carbono 🌫️

Raw H2 → nível bruto de hidrogênio

Raw Ethanol → nível bruto de etanol (sim, até isso o sensor pega 🍷😅)

Pressure [hPa] → pressão atmosférica 🌍

PM1.0 / PM2.5 → partículas sólidas no ar, tipo fumaça invisível 😶‍🌫️

NC0.5 / NC1.0 / NC2.5 → contagem numérica de partículas por tamanho

CNT → contador de amostras (basicamente, quantos registros o sensor já pegou 📈)

E, claro, a cereja do bolo:

🎯 Fire_Alarm → nossa variável alvo!

1 = incêndio detectado 🔥

0 = tudo sob controle ✅

🧑‍💻 A MISSÃO:

Aplicar validação cruzada (Cross-Validation) para:

Treinar um modelo de classificação (aqui usamos Random Forest 🌲✨).

Avaliar o desempenho do modelo em prever a ocorrência de incêndios.

Garantir que ele não esteja “decorando” os dados, mas sim aprendendo padrões úteis.
