# 🏠 Maquete Eletrônica Automatizada com Arduino

Este projeto consiste em uma maquete eletrônica interativa desenvolvida com Arduino para demonstrar conceitos de automação residencial e controle de iluminação por zonas utilizando LEDs, sensores e atuadores.

---

## 📌 Funcionalidades

- **Iluminação por Ambientes:** Controle individual de LEDs simulando os cômodos de uma residência (Sala, Quarto, Cozinha, Garagem).
- **Modo Noturno Automático:** Acionamento automático da iluminação externa utilizando sensor LDR ao detectar baixa luminosidade.
- **Detecção de Presença:** Acionamento de luzes de garagem/corredor com sensor de movimento PIR.
- **Controle Manual:** Botões (push-buttons) para alternar o status das lâmpadas manualmente.

---

## 🛠️ Componentes Utilizados

| Componente | Quantidade | Descrição |
| :--- | :---: | :--- |
| **Arduino Uno / Nano** | 1 | Microcontrolador principal do projeto |
| **LEDs (Cores Variadas)** | 6 | Simulação da iluminação interna e externa |
| **Resistores 220Ω** | 6 | Proteção para os LEDs |
| **Resistor 10kΩ** | 1 | Divisor de tensão para o sensor LDR |
| **Sensor LDR** | 1 | Medição de luminosidade ambiente |
| **Sensor de Presença PIR** | 1 | Detecção de movimento |
| **Push-buttons** | 2 | Controle manual de iluminação |
| **Protoboard & Jumpers** | — | Conexão dos componentes na maquete |

---

## 🔌 Esquema do Circuito

Abaixo está a representação básica das conexões do circuito na protoboard:

<Image src="image_agent_tag_17080549942309246915" alt="Esquema de ligação de um LED com resistor no Arduino" caption="Conexão do circuito Arduino no Tinkercad" />
