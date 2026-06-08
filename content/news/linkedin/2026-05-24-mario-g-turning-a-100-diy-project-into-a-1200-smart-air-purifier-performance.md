---
publish: true
title: "Turning a €100 DIY Project into a €1200 Smart Air Purifier Performance! 🌬️"
date: 2026-05-24
source_url: "https://www.linkedin.com/posts/mario-g-89728b3b2_embeddedsystems-iot-esp32-activity-7464431419398754304-xaiD?utm_source=combined_share_message&utm_medium=member_desktop&rcm=ACoAACa6SM4BOEYYJg0wEbtEW0fBaNusd_6tSlw"
source_type: linkedin
author: "Mario G."
author_url: "https://www.linkedin.com/in/mario-g-89728b3b2?miniProfileUrn=urn%3Ali%3Afs_miniProfile%3AACoAAGTGzzMBLIuazjeR-H7uuYUCRpXTDGwIA2E"
author_headline: "​IoT & Embedded Systems Enthusiast | Linux & Network Security | High School Student & Hardware Maker"
likes: 1
comments: 0
shares: 0
tags: [author-person, funding, int, iot, linkedin]
---
> 🔗 [LinkedIn пост](https://www.linkedin.com/posts/mario-g-89728b3b2_embeddedsystems-iot-esp32-activity-7464431419398754304-xaiD?utm_source=combined_share_message&utm_medium=member_desktop&rcm=ACoAACa6SM4BOEYYJg0wEbtEW0fBaNusd_6tSlw) · **Mario G.** · ​IoT & Embedded Systems Enthusiast | Linux & Network Security | High School Student & Hardware Maker · 2026-05-24 · 👍 1 · 💬 0 · 🔁 0

🚀 Turning a €100 DIY Project into a €1200 Smart Air Purifier Performance! 🌬️

I’m excited to share a sneak peek of my latest hardware project: a fully custom, DIY Smart Air Purifier built from scratch on an ESP32-S3 micro-controller. While it's still a work in progress (showing just the raw hardware setup in the video!), the results are already incredible.

What’s under the hood?

Sensors: It features state-of-the-art Sensirion SGP41, AHT20 + BMP280 sensors to live-monitor PM2.5 (dust particles)

The Brains: Driven by an ESP32, running custom C++ firmware. I implemented Sensirion’s advanced Gas Index Algorithm to calculate dynamic real-time VOC (Volatile Organic Compounds) and NOx (Nitrogen Oxides) indices based on adaptive environmental baseline calibration.

Smart Ecosystem: Fully integrated with the Blynk IoT platform via Wi-Fi for remote telemetry, real-time fan speed control, and push notifications for air quality alerts.

Industrial Control: Features an LCD ST7789 display with a custom-built UI and controls a heavy-duty air turbine using precise high-frequency 25kHz PWM signaling to eliminate motor humming and optimize power efficiency.

💡 Engineering Flex: To handle the intense electromagnetic interference (EMI) and power ripples caused by the high-velocity turbine motor, I engineered a custom software watchdog inside the UART communication loop. If the serial data from the PMS dust sensor gets corrupted or freezes due to motor noise, the ESP32 automatically detects…

