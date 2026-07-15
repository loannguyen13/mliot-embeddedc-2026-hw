Kim Loan, sau khi đọc JD của Team IoT và biết định hướng của em, mình nhận ra một điều:

**Career Path của một Embedded Engineer và lộ trình để vào MLIoT Lab giống nhau khoảng 80%.**

20% còn lại là MLIoT Lab đòi hỏi **tư duy xây dựng một hệ thống IoT hoàn chỉnh (End-to-End)** chứ không chỉ viết firmware.

---

# Đây là hai lộ trình

## Career Path thông thường

```text
C
↓
Embedded C
↓
MCU
↓
Driver
↓
RTOS
↓
Peripheral
↓
Embedded Engineer
```

Đây là lộ trình để đi làm firmware.

---

## MLIoT Lab

JD của Lab đang yêu cầu:

```text
Sensor
↓
MCU
↓
Firmware
↓
RTOS
↓
Connectivity
↓
IoT Protocol
↓
Cloud
↓
OTA
↓
Security
↓
Edge AI
```

Tức là họ muốn người làm được **cả hệ thống IoT**.

---

# Mình sẽ bổ sung roadmap của Kim Loan

## Giai đoạn 1 — Foundation (2026)

```text
C
↓
Embedded C
↓
Bitwise
Pointer
Volatile
Static
Struct
Union
Function Pointer
```

↓

```text
CE103
Vi xử lý - Vi điều khiển
```

↓

```text
STM32
ESP32
Register
GPIO
Interrupt
Timer
UART
SPI
I2C
ADC
PWM
```

Đây là giai đoạn Kim Loan đang học.

---

# Giai đoạn 2 — Firmware

```text
Driver

↓

HAL

↓

Bare Metal

↓

RTOS
```

↓

```text
CE107
Hệ thống nhúng
```

↓

```text
CE338
Hệ thống thời gian thực
```

Lúc này Kim Loan sẽ học thêm:

* Scheduler
* Task
* Queue
* Semaphore
* Mutex
* ISR

---

# Giai đoạn 3 — IoT

↓

```text
CE339
IoT
```

Ở đây mình sẽ bổ sung rất nhiều từ khóa mà JD nhắc tới.

## Communication

```text
UART
SPI
I2C
CAN
USB
```

---

## IoT Protocol

```text
MQTT

MQTTS

CoAP

HTTP

HTTPS

WebSocket
```

---

## Network

Đây là lợi thế của Kim Loan.

```text
TCP

UDP

IPv4

IPv6

DNS

DHCP

TLS

SSL
```

---

## Wireless

```text
WiFi

BLE

Zigbee

Thread

LoRa

NB-IoT

LTE-M
```

Không cần giỏi tất cả.

Biết nguyên lý.

---

# Giai đoạn 4 — Device

Đây là phần JD nhắc rất nhiều.

```text
Flash

EEPROM

Bootloader

OTA

FOTA

Provisioning
```

↓

Quản lý firmware từ xa.

---

# Giai đoạn 5 — Sensor

↓

```text
CE348
```

Lúc này học

```text
Temperature

Humidity

IMU

GPS

Camera

Pressure

Current Sensor
```

↓

Hiểu Datasheet.

---

# Giai đoạn 6 — Cloud

Đây là thứ JD muốn.

```text
ESP32

↓

MQTT

↓

Broker

↓

Cloud

↓

Dashboard
```

Có thể dùng

```text
ThingsBoard

EMQX

HiveMQ

AWS IoT

Azure IoT
```

Không cần học hết.

---

# Giai đoạn 7 — Security

JD nhắc

```text
TLS

SSL

Authentication

Encryption
```

Nền của Kim Loan học mạng sẽ rất lợi.

---

# Giai đoạn 8 — AI

↓

```text
CE340
```

Từ khóa:

```text
TensorFlow Lite Micro

Edge Impulse

TinyML
```

↓

Deploy AI lên MCU.

---

# Giai đoạn 9 — Robotics

↓

```text
CE347
```

↓

Điều khiển

Robot

Drone

PID

Motor

Encoder

Navigation

---

# Đây là roadmap mình muốn đồng hành cùng Kim Loan

```text
Embedded C
│
├── Bitwise
├── Pointer
├── Volatile
├── Static
├── Struct
├── Union
├── Function Pointer
│
▼
CE103
Vi xử lý - Vi điều khiển
│
├── GPIO
├── UART
├── SPI
├── I2C
├── ADC
├── PWM
├── Timer
├── Interrupt
│
▼
CE107
Hệ thống nhúng
│
├── Driver
├── HAL
├── Bare Metal
├── Memory Map
├── Datasheet
│
▼
CE338
RTOS
│
├── Task
├── Queue
├── Semaphore
├── Mutex
├── Scheduler
│
▼
CE339
IoT
│
├── MQTT
├── HTTP
├── CoAP
├── WebSocket
├── TCP/IP
├── WiFi
├── BLE
│
▼
CE348
Sensor
│
├── IMU
├── GPS
├── Camera
├── ADC
├── Calibration
│
▼
CE345
IoT Architecture
│
├── Edge
├── Gateway
├── Cloud
├── OTA
├── Device Provisioning
├── Security
│
▼
CE340
AI Embedded
│
├── TinyML
├── TensorFlow Lite Micro
├── Edge Impulse
│
▼
CE347
Robot
│
├── PID
├── Motor Control
├── Encoder
├── Navigation
└── Drone
```

## Điều mình muốn Kim Loan nhớ

Điều khiến mình thích nhất ở roadmap này là **nó rất khớp với dự án drone bướm của em**.

* Nền **Mạng máy tính** giúp em mạnh về giao thức và kết nối.
* Nền **Embedded** giúp em điều khiển phần cứng.
* **IoT Architecture** giúp em kết nối thiết bị với cloud.
* **AI Embedded** mở ra khả năng xử lý thông minh ngay trên thiết bị.
* **Robot** là bước cuối để tích hợp điều khiển, cảm biến và chuyển động.

Nếu chúng ta kiên trì học 1–2 giờ mỗi ngày như đã thống nhất, thì mục tiêu không chỉ là **được nhận vào MLIoT Lab**, mà còn là khi bước vào lab, Kim Loan có đủ nền tảng để **theo kịp các anh chị và tận dụng tối đa môi trường đó**. Đây mới là giá trị lớn nhất của việc chuẩn bị từ bây giờ.
