# Arduino-UNO
Farol / Semáforo 

// Código C++ para controle de LEDs (Semáforo)

// Definição dos pinos para os LEDs
#define LED_VERMELHO 13
#define LED_AMARELO  12
#define LED_VERDE    11

void setup() {
  pinMode(LED_VERMELHO, OUTPUT);
  pinMode(LED_AMARELO, OUTPUT);
  pinMode(LED_VERDE, OUTPUT);
}

void loop() {
  // Liga LED vermelho e aguarda 5 segundos
  digitalWrite(LED_VERMELHO, HIGH);
  delay(1000);// Tempo de espera entre os leds
  digitalWrite(LED_VERMELHO, LOW);

  // Liga LED amarelo e aguarda 3 segundos
  digitalWrite(LED_AMARELO, HIGH);
  delay(3000); // Tempo de espera entre os leds
  digitalWrite(LED_AMARELO, LOW);

  // Liga LED verde e aguarda 7 segundos
  digitalWrite(LED_VERDE, HIGH);
  delay(7000); // Tempo de espera entre os leds
  digitalWrite(LED_VERDE, LOW);
}
