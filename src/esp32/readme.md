# ESP32 + IoT (EP-06)

Implementação inicial da **Opção 1** do "Ir Além": coleta de sensores com ESP32 + envio via Wi-Fi.

## Sensores definidos
- DHT22: temperatura e umidade do ar
- Sensor de umidade do solo (analógico)

## Destino dos dados
- API HTTP (JSON) na AWS (`sa-east-1`)

## Arquivos
- `main.cpp`: leitura dos sensores + envio HTTP periódico

## Próximos passos
1. Criar projeto no Wokwi com ESP32 + DHT22 + sensor de umidade do solo
2. Mapear pinos conforme simulação
3. Inserir credenciais Wi-Fi e endpoint AWS em `main.cpp`
4. Validar fluxo completo: sensor -> ESP32 -> API
