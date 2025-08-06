#include <LiquidCrystal.h>

LiquidCrystal lcd(12, 11, 5, 4, 3, 2);

void setup() {
  lcd.begin(16, 2);
  lcd.print("Hello, world!");
}

void loop() {
}# LCD-Hello-World-
Liquid display crystal is designed to show a grid of letters numbers and characters.
