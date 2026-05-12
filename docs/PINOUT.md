# Pinout - SYNEDA URTK6 ZED-F9P

## Header auxiliar lateral

Ordem física informada, do lado do USB para baixo:

| Posição | Sinal |
|---:|---|
| 1 | SDA |
| 2 | SCL |
| 3 | VCC |
| 4 | 3V3 |
| 5 | GND |
| 6 | TX2 |
| 7 | RX2 |

## Conector J1

Sinais indicados no footprint:

| Sinal |
|---|
| RTK |
| PPS |
| TX1 |
| RX1 |
| VCC |

## Ligações internas consideradas

| Sinal | Observação |
|---|---|
| VCC / 5V | Considerados fisicamente ligados |
| 3V3 | Barramento comum |
| GND | Barramento comum |
| SDA | Header AUX ligado ao SDA do header 2x20 |
| SCL | Header AUX ligado ao SCL do header 2x20 |

## Mapeamento especial

O módulo possui deslocamento físico em relação à numeração Raspberry Pi.

| Pino do módulo | Sinal equivalente |
|---:|---|
| 2 | 3V3 |
| 1 | VCC / 5V |
| 4 | SCL |
| 6 | SDA |
