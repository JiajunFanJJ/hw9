int led = 8;

void setup() {
 Serial.begin(19200);
 pinMode(A0, INPUT);
}
void loop() {
 int value;
 value = analogRead(A0);
 Serial.println(value);

 if (value < 200) {
   digitalWrite(led, HIGH);
   delay(2000);
 }
 else {
  digitalWrite(led, LOW);
   delay(500);
 }
}
