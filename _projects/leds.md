---
layout: page
title: LED's
date: 2022-08-22T18:08:42-04:00
description: "Touching wires and breadboards is good for the CS major."
img: assets/img/leds/leds.jpg
importance: 1
toc:
    sidebar: true
giscus_comments: true
category: fun
---

Quote from page description is from [Eric](https://eric-unc.tech).

{% include video.html path="https://www.youtube.com/embed/hia_4dOh098" class="img-fluid rounded z-depth-1" center=1 %}

## Code

```c
// Pin 3: Input for reading button
// Pin 2: Output for controlling LED

int button_value = 0;
int BUTTON = 3;
int LED1 = 2;
int LED2 = 4;
void setup() {
  // put your setup code here, to run once:
  pinMode(BUTTON, INPUT);
  pinMode(LED1, OUTPUT);
  pinMode(LED2, OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
  button_value = digitalRead(BUTTON);
  // button not pressed, based on my hardware implementation
  if (button_value == 0){
    digitalWrite(LED1, HIGH);
    digitalWrite(LED2, HIGH);
  } else {
    digitalWrite(LED1, HIGH);
    digitalWrite(LED2, LOW);
    delay(100);
    digitalWrite(LED1, LOW);
    digitalWrite(LED2, HIGH);
    delay(100);
  }
}
```

<div class="caption"><code>toggle.ino</code></div>
