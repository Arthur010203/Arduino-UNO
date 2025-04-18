#include <Servo.h>
Servo myservo;
// Código C++ para controle de LEDs (Semáforo)

// Definição dos pinos para os LEDs
#define LED_VERMELHO 13
#define LED_AMARELO 12
#define LED_VERDE 11
#define LED_AZUL 8

void setup() {
  pinMode(LED_VERMELHO, OUTPUT);
  pinMode(LED_AMARELO, OUTPUT);
  pinMode(LED_VERDE, OUTPUT);
  pinMode(LED_AZUL, OUTPUT);
  myservo.attach(9);  // Diz que o objeto "myservo" está ligado ao pino 9
}

void loop() {
  // Liga LED vermelho e aguarda 5 segundos
  digitalWrite(LED_VERMELHO, HIGH);
  delay(100);  // Tempo de espera entre os leds
  digitalWrite(LED_VERMELHO, LOW);

  // Liga LED amarelo e aguarda 3 segundos
  digitalWrite(LED_AMARELO, HIGH);
  delay(100);  // Tempo de espera entre os leds
  digitalWrite(LED_AMARELO, LOW);

  // Liga LED verde e aguarda 7 segundos
  digitalWrite(LED_VERDE, HIGH);
  delay(100);  // Tempo de espera entre os leds
  digitalWrite(LED_VERDE, LOW);

  // Liga LED azul e aguarda 7 segundos
  digitalWrite(LED_AZUL, HIGH);
  delay(100); // Tempo de espera entre os leds
  digitalWrite(LED_AZUL, LOW);

  //Servo motor
  myservo.write(180);  // Comando para mandar o servo para posição 180
  delay(500);          // Espera de 500 ms
  myservo.write(0);    // Comando para mandar o servo para posição 0
  delay(500);          // Espera de 500 ms
  myservo.write(360);   // Comando para mandar o servo para posição 90
  delay(500);          // Espera de 500 ms
}
