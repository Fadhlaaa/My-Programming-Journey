#define BUZZER_PIN 17

void setup() {

pinMode(BUZZER_PIN, OUTPUT); }

void loop() {

digitalWrite(BUZZER_PIN, HIGH);

delay(1000);

digitalWrite(BUZZER_PIN, LOW);

delay(1000);}
