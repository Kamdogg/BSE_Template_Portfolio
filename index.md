# Gesture Control Robot
This project uses the gestures of your hand movements to control the direction and speed of the car. Using an accelerometer to read the gestures to Arduino modules by bluetooth. 
| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Kameron N | Courtland Highschool | Electrical Engineering | Incoming Senior

![Headstone Image]![IMG_1665](https://user-images.githubusercontent.com/107581114/176966509-777a667a-ae49-49cf-9b38-960bb9acfc37.jpg)



# Demo Night 

[![Demo Night]
<iframe width="560" height="315" src="https://www.youtube.com/embed/3wdcaILSAGs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

  
# Final Milestone
My final milestone is allowing the bluetooth to read gestures from the accelorometer and have the car be able to move foward and backwards. After getting my car built and wired up to the arduino, H bridge and motors the last thing i needed was for the ADXL345 to communicate the chracters of the gestures to the robot. Once I got the accelormeter, which reads gestures, to connect to my blutooth and allow the arduino micro to read the code. This allowed the car to move based off the gestures of the accelerometer

[![Final Milestone]
<iframe width="560" height="315" src="https://www.youtube.com/embed/4Pcw4EDEFpg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# First Milestone
My first milestone was configuring the accelerometer to to my arduino uno allowing it to read the acceleration and tilt needed to make my car. After many tries I was able to read my XYZ values on the serial monitor for Arduino IDE. Using ADXL345 and installing its software I used a sensortest to test the values. 

[![First Milestone]
<iframe width="560" height="315" src="https://www.youtube.com/embed/q0oDf7IUYQs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# Schematics
![gesture_schem](https://user-images.githubusercontent.com/107581114/176968678-0d59da09-787c-4331-87c6-551276ff1f74.jpg)

# Materials

| **Part** | **Qty** | **Description** | **Cost** | **Site**
|:--:|:-:|:--:|:-:|:-:|
| Robot Kit | 1 | chassis, battery pack, DC motors, wheels, ect. |
| Arduino Micro| 1 | microcontroller board | 19.44 | [amazon](https://www.amazon.com/Arduino-Micro-Headers-A000053-Controller/dp/B00AFY2S56/ref=sxin_24_ac_d_mf_brs?ac_md=1-0-QXJkdWlubw%3D%3D-ac_d_mf_brs_brs&content-id=amzn1.sym.6b0ccabb-f0a5-41c0-b8ab-e3d0522dfb7d%3Aamzn1.sym.6b0ccabb-f0a5-41c0-b8ab-e3d0522dfb7d&crid=3UO1VODGVNPO7&cv_ct_cx=Arduino+Micro&keywords=Arduino+Micro&pd_rd_i=B00AFY2S56&pd_rd_r=91911c6f-d855-4425-aaf2-f7735bfd5b36&pd_rd_w=OLXf2&pd_rd_wg=aHsRk&pf_rd_p=6b0ccabb-f0a5-41c0-b8ab-e3d0522dfb7d&pf_rd_r=G4JY1NFDRFHR60JCZGD4&psc=1&qid=1656709108&sprefix=arduino+mic%2Caps%2C192&sr=1-1-8b2f235a-dddf-4202-bbb9-592393927392)
| Arduino UNO | 1 | main programming board | 25.94 | [amazon](https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/ref=sr_1_3?crid=2OE11U49IY91O&keywords=Arduino+Uno&qid=1656709365&s=electronics&sprefix=arduino+uno%2Celectronics%2C88&sr=1-3) 
| H-Bridge | 1 | controls DC motors | 5.99 | [amazon](https://www.amazon.com/Solu-Stepper-Controller-H-Bridge-Mega2560/dp/B00YZV80C0/ref=sr_1_20?crid=35MV4PC2M2ESG&keywords=h+bridge&qid=1656709561&s=hi&sprefix=h+bridge%2Ctools%2C88&sr=1-20) 
| HC-05 bluetooth module | 2 | Allows communication between each other | 9.99 | [amazon](https://www.amazon.com/HiLetgo-Wireless-Bluetooth-Transceiver-Arduino/dp/B071YJG8DR/ref=sr_1_7?keywords=Hc-05+module&qid=1656709683&sr=8-7)
| Multi colored jumper wires | 1 | Wires to connect | 6.98 | [amazon](https://www.amazon.com/Elegoo-EL-CP-004-Multicolored-Breadboard-arduino/dp/B01EV70C78/ref=sr_1_1_sspa?crid=1LXO1MIKWCKXJ&keywords=multicolor+jumper+wires&qid=1656710276&sprefix=multi+colr+jumper+wires%2Caps%2C104&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFIMzlTN0JYT0lJVjYmZW5jcnlwdGVkSWQ9QTAwMjc2MjEyNVdXSjBSTE9UQVBJJmVuY3J5cHRlZEFkSWQ9QTA5NDUzMjExRUtQVk9KOTU5MVg5JndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ==) 
| ADXL345 | 1 | Digital accelerometer | 2.15 | [amazon](https://www.amazon.com/ADXL345-Digital-Sensor-Accelerometer-arduino/dp/B07VSLXGF1/ref=sr_1_12?crid=170VK10HX55B0&keywords=adxl345+digital+accelerometer&qid=1656710498&sprefix=adxl345+di%2Caps%2C102&sr=8-12) 

# Tools Required 
| **Tool** | **Cost** | **Site** |
|:--:|:-:|:-:|
| Soldering Kit | 20.99 | [amazon](https://www.amazon.com/Soldering-Iron-Kit-Temperature-Desoldering/dp/B07S61WT16/)
| Screwdriver Kit | 6.99 | [amazon](https://www.amazon.com/Small-Screwdriver-Set-Mini-Magnetic/dp/B08RYXKJW9/) 
 
# Final Code 
#include <Wire.h>

void setup()
{
  Wire.begin();
  Serial.begin(9600);
  Serial.println("I2C Scanner");
}

void loop()
{
  byte error, address;
  int nDevices;

  Serial.println("Scanning...");

  nDevices = 0;
  for(address = 1; address < 127; address++ )
  {
    Wire.beginTransmission(address);
    error = Wire.endTransmission();

    if (error == 0)
    {
      Serial.print("I2C device found at address 0x");
      if (address < 16)
        Serial.print("0");

      Serial.print(address,HEX);
      Serial.println("  !");

      nDevices++;
    }
    else if (error==4)
    {
      Serial.print("Unknown error at address 0x");
      if (address < 16)
        Serial.print("0");

      Serial.println(address,HEX);
    }
  }

  if (nDevices == 0)
    Serial.println("No I2C devices found");
  else
    Serial.println("done");

  delay(5000); // wait 5 seconds for next scan
}
void setup()
{
  Serial.begin(38400);
  Serial1.begin(38400);
}

void loop()
{
  if (Serial1.available())
  {
    Serial.print((char)Serial1.read());
  }
  if (Serial.available())
  {
    Serial1.write(Serial.read());
  }
}
#include <SoftwareSerial.h>

#define tx 2
#define rx 3

SoftwareSerial configBt(rx, tx);
long tm,t,d; //variables to record time in seconds

void setup()
{
  Serial.begin(38400);
  configBt.begin(38400);
  pinMode(tx, OUTPUT);
  pinMode(rx, INPUT);
}

void loop()
{
  if (configBt.available())
  {
    Serial.print((char)configBt.read());
  }
  if (Serial.available())
  {
    configBt.write(Serial.read());
  }
}
int motor1f = 7;
int motor1b = 8;
int motor2f = 12;
int motor2b = 11;
void setup()
{
  //opens serial monitor and bluetooth serial monitor
  Serial.begin(38400);
  Serial1.begin(38400);

  //initializes all motor pins as outputs
  pinMode(motor1f, OUTPUT);
  pinMode(motor1b, OUTPUT);
  pinMode(motor2f, OUTPUT);
  pinMode(motor2b, OUTPUT);
}

void loop()
{
  Serial.println("forward");
  forward();
  delay(3000);
  Serial.println("backward");
  back();
  delay(3000);
  Serial.println("left");
  left();
  delay(3000);
  Serial.println("right");
  delay(3000);
  Serial.println("freeze");
  freeze();
  delay(3000);
}

//moves robot forward 
void forward(){
  
    //chages directions of motors
    digitalWrite(motor1f, HIGH);
    digitalWrite(motor1b, LOW);
    digitalWrite(motor2f, HIGH);
    digitalWrite(motor2b, LOW);
  }

//moves robot left
void left(){

    //changes directions of motors
    digitalWrite(motor1f, HIGH);
    digitalWrite(motor1b, LOW);
    digitalWrite(motor2f, LOW);
    digitalWrite(motor2b, HIGH);
  }

//moves robot right
void right(){

    //changes directions of motors
    digitalWrite(motor1f, LOW);
    digitalWrite(motor1b, HIGH);
    digitalWrite(motor2f, HIGH);
    digitalWrite(motor2b, LOW);
  }

//moves robot backwards
void back(){

    //changes directions of motors
    digitalWrite(motor1f, LOW);
    digitalWrite(motor1b, HIGH);
    digitalWrite(motor2f, LOW);
    digitalWrite(motor2b, HIGH);
  }

//stops robot
void freeze(){

    //changes directions of motors
    digitalWrite(motor1f, LOW);
    digitalWrite(motor1b, LOW);
    digitalWrite(motor2f, LOW);
    digitalWrite(motor2b, LOW);
  }
  #include <Wire.h>
#include <Adafruit_Sensor.h>
#include <Adafruit_ADXL345_U.h>

Adafruit_ADXL345_Unified accel = Adafruit_ADXL345_Unified(12345);
 
void setup(void) 
{
#ifndef ESP8266
  while (!Serial);
#endif
  Serial.begin(9600);
  Serial.println("Accelerometer Test"); Serial.println("");


  if(!accel.begin())
  {
    Serial.println("Ooops, no ADXL345 detected ... Check your wiring!");
    while(1);
  }

  accel.setRange(ADXL345_RANGE_16_G);

  Serial.println("");
}

void loop(void) 
{
  sensors_event_t event; 
  accel.getEvent(&event);
  double accelerationX = event.acceleration.x;
  double accelerationY = event.acceleration.y;
  double accelerationZ = event.acceleration.z;
  if (accelerationY >= 7.50) {
    Serial.println('F');
  }
  else if (accelerationY <= -5) {
    Serial.println('B');
  }
  else if (accelerationX <= -5.25) {
    Serial.println('L');
  }
  else if (accelerationX >= 5.25) {
    Serial.println('R');
  }
  else {
    Serial.println('S');
  }
  delay(500);
}
#include <Wire.h>
#include <Adafruit_Sensor.h>
#include <Adafruit_ADXL345_U.h>
#include <SoftwareSerial.h>
#define tx 2
#define rx 3

SoftwareSerial configBt(rx, tx);

Adafruit_ADXL345_Unified accel = Adafruit_ADXL345_Unified(12345);
 
void setup(void) 
{
  
  configBt.begin(38400);
  pinMode(tx, OUTPUT);
  pinMode(rx, INPUT);
  Serial.begin(9600);
  Serial.println("Accelerometer Test"); 
  Serial.println("");


  if(!accel.begin())
  {
    Serial.println("Ooops, no ADXL345 detected ... Check your wiring!");
    while(1);
  }

  accel.setRange(ADXL345_RANGE_16_G);

  Serial.println("");
}

void loop(void) 
{
  sensors_event_t event; 
  accel.getEvent(&event);
  double accelerationX = event.acceleration.x;
  double accelerationY = event.acceleration.y;
  double accelerationZ = event.acceleration.z;
  if (accelerationY >= 7.50) {
    configBt.write('w');
  }
  else if (accelerationY <= -5) {
    configBt.write('a');
  }
  else if (accelerationX <= -5.25) {
    configBt.write('s');
  }
  else if (accelerationX >= 5.25) {
    configBt.write('d');
  }
  delay(500);
}
#define motor1f 7;
#define motor1b 8;
#define motor1e 9;
#define motor2f 12;
#define motor2b 11;
#define motor2e 10;

//character variable for command
char c = "";

//start at 50% duty cycle
int s = 120;

void setup()
{
  //opens serial monitor and bluetooth serial monitor
  Serial.begin(38400);
  Serial1.begin(38400);

  //initializes all motor pins as outputs
  pinMode(motor1f, OUTPUT);
  pinMode(motor1b, OUTPUT);
  pinMode(motor1e, OUTPUT);
  pinMode(motor2f, OUTPUT);
  pinMode(motor2b, OUTPUT);
  pinMode(motor2e, OUTPUT);
}

void loop()
{
  //checks for bluetooth data
  if (Serial1.available()){
    //if available stores to command character
    c = (char)Serial1.read();
    //prints to serial
    Serial.println(c);
  }

  //acts based on character
  switch(c){
    
    //forward case
    case 'w':
      forward();
      break;
      
    //left case
    case 'a':
      left();
      break;
      
    //right case
    case 's':
      right();
      break;
      
    //back case
    case 'd':
      back();
      break;
      
    //speed up case
    case 'q':
      speedup();
      break;
      
    //slow down case
    case 'e':
      slowdown();
      break;
      
    //default is to stop robot
    default:
      freeze();
    }
}

//moves robot forward 
void forward(){
  
    //chages directions of motors
    digitalWrite(motor1f, HIGH);
    digitalWrite(motor1b, LOW);
    digitalWrite(motor2f, HIGH);
    digitalWrite(motor2b, LOW);

    //writes the speed
    analogWrite(motor1e, s);
    analogWrite(motor2e, s);
  }

//moves robot left
void left(){

    //changes directions of motors
    digitalWrite(motor1f, HIGH);
    digitalWrite(motor1b, LOW);
    digitalWrite(motor2f, LOW);
    digitalWrite(motor2b, HIGH);

    //writes the speed
    analogWrite(motor1e, s);
    analogWrite(motor2e, s);
  }

//moves robot right
void right(){

    //changes directions of motors
    digitalWrite(motor1f, LOW);
    digitalWrite(motor1b, HIGH);
    digitalWrite(motor2f, HIGH);
    digitalWrite(motor2b, LOW);

    //writes the speed
    analogWrite(motor1e, s);
    analogWrite(motor2e, s);
  }

//moves robot backwards
void back(){

    //changes directions of motors
    digitalWrite(motor1f, LOW);
    digitalWrite(motor1b, HIGH);
    digitalWrite(motor2f, LOW);
    digitalWrite(motor2b, HIGH);

    //writes the speed
    analogWrite(motor1e, s);
    analogWrite(motor2e, s);
  }

//stops robot
void freeze(){

    //changes directions of motors
    digitalWrite(motor1f, LOW);
    digitalWrite(motor1b, LOW);
    digitalWrite(motor2f, LOW);
    digitalWrite(motor2b, LOW);

    //writes the speed
    analogWrite(motor1e, 0);
    analogWrite(motor2e, 0);
  }

//speeds up robot
void speedup(){

  //adds 10 to speed
  s+=10;

  //saturates speed so it doesn't write improper value
  if(s>255)
    s = 255;
  }

void slowdown(){

  //subtracts 10 from speed
  s -= 10;

  //saturates speed so it doesn't write improper value
  if(s<0)
    s = 0;
  }
BTMotor.ino
4 KB

