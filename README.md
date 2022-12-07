[code]
//Semaforo cruzamento de carros
void setup() {
  pinMode(2, OUTPUT);//verm1
  pinMode(3, OUTPUT);//verm2
  pinMode(4, OUTPUT);//verm3
  pinMode(5, OUTPUT);//vermelho
  pinMode(6, OUTPUT);//amarelo
  pinMode(7, OUTPUT);//verde
  pinMode(8, OUTPUT);//vermelho2
  pinMode(9, OUTPUT);//amarelo2
  pinMode(10, OUTPUT);//verde2
  pinMode(11, OUTPUT);//verde1
  pinMode(12, OUTPUT);//verde2
  pinMode(13, OUTPUT);//verde3
}

void loop() {
  digitalWrite(5, HIGH);
  digitalWrite(10, HIGH);
  digitalWrite(2, HIGH);
  digitalWrite(6, LOW);
  digitalWrite(7, LOW);
  delay(2000);

  digitalWrite(6, HIGH);
  digitalWrite(5, LOW);
  digitalWrite(10, LOW);
  digitalWrite(2, LOW);
  digitalWrite(3, HIGH);
  digitalWrite(7, LOW);
  delay(2000);

  digitalWrite(6, LOW);
  digitalWrite(7, HIGH);
  digitalWrite(8, HIGH);
  digitalWrite(5, LOW);
  digitalWrite(10, LOW);
  digitalWrite(2, LOW);
  digitalWrite(3, LOW);
  digitalWrite(4, HIGH);
  delay(2000);

  digitalWrite(6, LOW);
  digitalWrite(7, LOW);
  digitalWrite(8, LOW);
  digitalWrite(9, HIGH);
  digitalWrite(5, LOW);
  digitalWrite(10, LOW);
  digitalWrite(2, LOW);
  digitalWrite(3, LOW);
  digitalWrite(4, LOW);
  digitalWrite(11, HIGH);
  delay(2000);

  digitalWrite(6, LOW);
  digitalWrite(7, LOW);
  digitalWrite(8, LOW);
  digitalWrite(9, LOW);
  digitalWrite(5, HIGH);
  digitalWrite(10, HIGH);
  digitalWrite(2, LOW);
  digitalWrite(3, LOW);
  digitalWrite(4, LOW);
  digitalWrite(11, LOW);
  digitalWrite(12, HIGH);
  delay(2000);

  digitalWrite(6, HIGH);
  digitalWrite(7, LOW);
  digitalWrite(8, LOW);
  digitalWrite(9, LOW);
  digitalWrite(5, LOW);
  digitalWrite(10, LOW);
  digitalWrite(2, LOW);
  digitalWrite(3, LOW);
  digitalWrite(4, LOW);
  digitalWrite(11, LOW);
  digitalWrite(12, LOW);
  digitalWrite(13, HIGH);
  delay(2000);

  digitalWrite(6, LOW);
  digitalWrite(7, HIGH);
  digitalWrite(8, HIGH);
  digitalWrite(9, LOW);
  digitalWrite(5, LOW);
  digitalWrite(10, LOW);
  digitalWrite(2, LOW);
  digitalWrite(3, LOW);
  digitalWrite(4, LOW);
  digitalWrite(11, LOW);
  digitalWrite(12, LOW);
  digitalWrite(13, LOW);
  delay(2000);

  digitalWrite(6, LOW);
  digitalWrite(7, LOW);
  digitalWrite(8, LOW);
  digitalWrite(9, LOW);
  digitalWrite(5, LOW);
  digitalWrite(10, LOW);
  digitalWrite(2, LOW);
  digitalWrite(3, LOW);
  digitalWrite(4, LOW);
  digitalWrite(11, LOW);
  digitalWrite(12, LOW);
  digitalWrite(13, LOW);
  delay(2000);

}
[/code]
