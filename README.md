# sensor-de-luminosidade
O projeto emprega um ESP32 para controlar a luminosidade de um espaço através de um sensor LDR, e se conecta a um broker MQTT público para a troca de informações. O ESP32 confronta a leitura do sensor com um limiar estabelecido e, dependendo do resultado, ativa um LED verde para espaços iluminados ou um LED vermelho e um buzzer para espaços escuros. Ao mesmo tempo, o aparelho divulga mensagens em um tópico MQTT (casa/luz), sinalizando a condição da iluminação.

A mensagem é recebida pelo MQTT Dash, possibilitando o monitoramento do ambiente à distância. Portanto, o projeto ilustra a aplicação do protocolo MQTT na construção de um sistema IoT simples e eficiente para detecção de luminosidade e alerta.

# HARDWARE  
ESP32-WROOM-32 Dev Kit  
Protoboard – 400 furos  
Sensor Foto Resistor LDR  
LED RGB  
Buzzer CC 12mm TMB12A05  
Resistor 220R 1/4W  
