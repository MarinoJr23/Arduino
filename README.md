Repositório para os códigos do projeto Arduino de ADS Objetos Inteligentes Mackenzie 2024.
Código do sensor e IDE.

Explicação do Código Arduino sem LED
Inclusão da Biblioteca: Importei a biblioteca PulseSensorPlayground.
Definição dos Pinos: Defini o pino analógico A0 para a entrada do sensor.
Configuração: No setup(), configurei o pino e inicializei a comunicação serial para depuração. Configurei o PulseSensor para usar o pino especificado e defini um limiar de batimentos.
Loop Principal: No loop(), o código lê os batimentos por minuto (BPM) e verifica se um novo batimento foi detectado. Se sim, imprime os valores no console serial.
