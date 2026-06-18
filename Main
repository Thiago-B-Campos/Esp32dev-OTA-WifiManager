//Include file the OTA_WIFI
#include "OTA.h"

#define LED_PIN 2

void setup(){
  //setup OTA and WIFI
  setupOTA_e_wifi();
  pinMode(LED_PIN, OUTPUT);
}

void loop(){
  //Normal inicialize
  ArduinoOTA.handle();
  digitalWrite(LED_PIN, HIGH);
}
