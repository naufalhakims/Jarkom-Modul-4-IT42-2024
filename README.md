# Jarkom-Modul-4-IT42-2024

## TOPOLOGI
![Screenshot 2024-11-19 230141](https://github.com/user-attachments/assets/ebf73808-c4a3-4c52-814f-1ee100c6819a)

## RUTE
# Tabel Rute Subnet Hololive

| **Nama Subnet**                                      | **Rute**                                         | **Jumlah IP** | **Netmask** |
|------------------------------------------------------|-------------------------------------------------|--------------|-------------|
| A1   | Hololive > HoloID                             | 2            | /30         |
| A2   | Hololive > HoloID > AREA-15                   | 2            | /30         |
| A3   | Hololive > HoloID > AREA-15 > Switch6 > Moona + Risu + Lofi | 661          | /22         |
| A4   | Hololive > HoloID > holoro                    | 2            | /30         |
| A5   | Hololive > HoloID > holoro > Switch7 > Ollie + Anya + Reine | 34           | /26         |
| A6   | Hololive > HoloID > holoh3ro                  | 2            | /30         |
| A7   | Hololive > HoloID > holoh3ro > Switch8 > Zeta + Kaela + Kobo | 299          | /23         |
| A8   | Hololive > HoloJP                             | 2            | /30         |
| A9   | Hololive > HoloJP > Switch1 > DEV_IS + GEN:0  | 3            | /29         |
| A10  | Hololive > HoloJP > Switch1 > DEV_IS > Re:Gloss > Ririka_Raden + Ao + Hajime_Kanade | 14 | /28 |
| A11  | Hololive > HoloJP > Switch1 > GEN:0 > Switch3 > MiComet + Sora_Robo_AZK + GEN:1 | 2045 | /21 |
| A12  | Hololive > HoloJP > Switch1 > GEN:0 > Switch3 > GEN:1 > Member > FBK_Matsuri + Aki_Hachama | 470 | /23 |
| A13  | Hololive > HoloJP > Switch1 > GEN:0 > Switch3 > GEN:1 > GAMERS | 2 | /30 |
| A14  | Hololive > HoloJP > Switch1 > GEN:0 > Switch3 > GEN:1 > GAMERS > Fubuki > Korone + Okayu + Mio | 120 | /25 |
| A15  | Hololive > HoloEN                             | 2            | /30         |
| A16  | Hololive > HoloEN > HoloAdvent                | 2            | /30         |
| A17  | Hololive > HoloEN > HoloAdvent > Switch0 > FuwaMoco + Shiori_Nerissa + Biboo | 28 | /27 |
| A18  | Hololive > HoloEN > Holo-Myth                 | 2            | /30         |
| A19  | Hololive > HoloEN > Holo-Myth > Switch2 > Gura_Ame_Ina + Kiara_Calli | 503 | /23 |
| A20  | Hololive > HoloEN > Holo-Myth > HoloPromise > Project-Hope + Holo_Council | 3 | /29 |
| A21  | Hololive > HoloEN > Holo-Myth > HoloPromise > Project-Hope > Irys | 3 | /29 |
| A22  | Hololive > HoloEN > Holo-Myth > HoloPromise > Holo-Council > Switch4 > Kronii_Mumei + Bae_Fauna | 62 | /26 |
| **Total**                                            | -                                               | **4263**     | **/19**     |


## VLSM
Ini adalah Penghitungan Subnet menggunakan metode classless VLSM
### VLSM Tree
![image](https://github.com/user-attachments/assets/ebe0019a-7b7c-42bc-b8f2-8839caa1425c)

### PEMBAGIAN IP

# Tabel Alokasi IP Subnet Hololive

| **Nama Subnet** | **Alamat IP**   | **Netmask**       | **Broadcast**   | **Rentang IP**                 |
|------------------|-----------------|-------------------|-----------------|--------------------------------|
| A1               | 10.84.19.72    | 255.255.255.252   | 10.84.19.75     | 10.84.19.73 - 10.84.19.74      |
| A2               | 10.84.19.92    | 255.255.255.252   | 10.84.19.95     | 10.84.19.93 - 10.84.19.94      |
| A3               | 10.84.8.0      | 255.255.252.0     | 10.84.11.255    | 10.84.8.1 - 10.84.11.254       |
| A4               | 10.84.19.96    | 255.255.255.252   | 10.84.19.199    | 10.84.19.97 - 10.84.19.98      |
| A5               | 10.84.18.192   | 255.255.255.192   | 10.84.18.255    | 10.84.18.193 - 10.84.18.254    |
| A6               | 10.84.19.100   | 255.255.255.252   | 10.84.19.103    | 10.84.19.101 - 10.84.19.102    |
| A7               | 10.84.16.0     | 255.255.254.0     | 10.84.17.255    | 10.84.16.1 - 10.84.17.254      |
| A8               | 10.84.19.104   | 255.255.255.252   | 10.84.19.107    | 10.84.19.105 - 10.84.19.106    |
| A9               | 10.84.19.64    | 255.255.255.248   | 10.84.19.71     | 10.84.19.65 - 10.84.19.70      |
| A10              | 10.84.19.32    | 255.255.255.240   | 10.84.19.47     | 10.84.19.33 - 10.84.19.46      |
| A11              | 10.84.0.0      | 255.255.248.0     | 10.84.7.255     | 10.84.0.1 - 10.84.7.254        |
| A12              | 10.84.14.0     | 255.255.254.0     | 10.84.15.255    | 10.84.14.1 - 10.84.15.254      |
| A13              | 10.84.19.76    | 255.255.255.252   | 10.84.19.79     | 10.84.19.77 - 10.84.19.78      |
| A14              | 10.84.18.0     | 255.255.255.128   | 10.84.18.127    | 10.84.18.1 - 10.84.18.126      |
| A15              | 10.84.19.80    | 255.255.255.252   | 10.84.19.83     | 10.84.19.81 - 10.84.19.82      |
| A16              | 10.84.19.84    | 255.255.255.252   | 10.84.19.87     | 10.84.19.85 - 10.84.19.86      |
| A17              | 10.84.19.0     | 255.255.255.224   | 10.84.19.31     | 10.84.19.1 - 10.84.19.30       |
| A18              | 10.84.19.88    | 255.255.255.252   | 10.84.19.91     | 10.84.19.89 - 10.84.19.90      |
| A19              | 10.84.12.0     | 255.255.254.0     | 10.84.13.255    | 10.84.12.1 - 10.84.13.254      |
| A20              | 10.84.19.48    | 255.255.255.248   | 10.84.19.55     | 10.84.19.49 - 10.84.19.54      |
| A21              | 10.84.19.56    | 255.255.255.248   | 10.84.19.63     | 10.84.19.57 - 10.84.19.62      |
| A22              | 10.84.18.128   | 255.255.255.192   | 10.84.18.191    | 10.84.18.129 - 10.84.18.190    |

### Konfigurasi Subnetting

Subnet A1
Hololive (Router)
enable
configure terminal
interface fa0/1
ip address 10.84.19.73 255.255.255.252
no shutdown

Holo-ID (Router)
enable
configure terminal
interface fa0/0
ip address 10.84.19.74 255.255.255.252
no shutdown

Subnet A2
Holo-ID (Router)
enable
configure terminal
interface fa0/1
ip address 10.84.19.93 255.255.255.252
no shutdown

AREA15 (Router)
enable
configure terminal
interface fa0/0
ip address 10.84.19.94 255.255.255.252
no shutdown

Subnet A3
AREA15 (Router)
enable
configure terminal
interface fa0/1
ip address 10.84.8.1 255.255.252.0
no shutdown

Moona (Device)
Interface fa0
IP Address: 10.84.8.2
Subnet Mask: 255.255.252.0
Gateway: 10.84.8.1

Risu (Device)
Interface fa0
IP Address: 10.84.8.3
Subnet Mask: 255.255.252.0
Gateway: 10.84.8.1

lofi (Device)
Interface fa0
IP Address: 10.84.8.4
Subnet Mask: 255.255.252.0
Gateway: 10.84.8.1

Subnet A4
Holo-ID (Router)
enable
configure terminal
interface fa1/0
ip address 10.84.19.97 255.255.255.252
no shutdown

holoro (Router)
enable
configure terminal
interface fa0/0
ip address 10.84.19.98 255.255.255.252
no shutdown

Subnet A5
holoro (Router)
enable
configure terminal
interface fa0/1
ip address 10.84.18.193 255.255.255.192
no shutdown

Ollie (Device)
Interface fa0
IP Address: 10.84.18.194
Subnet Mask: 255.255.255.192
Gateway: 10.84.18.193

Anya (Device)
Interface fa0
IP Address: 10.84.18.195
Subnet Mask: 255.255.255.192
Gateway: 10.84.18.193

Reine (Device)
Interface fa0
IP Address: 10.84.18.196
Subnet Mask: 255.255.255.192
Gateway: 10.84.18.193

Subnet A6
Holo-ID (Router)
enable
configure terminal
interface fa1/1
ip address 10.84.19.101 255.255.255.252
no shutdown

holoh3ro (Router)
enable
configure terminal
interface fa0/0
ip address 10.84.19.102 255.255.255.252
no shutdown

Subnet A7
holoh3ro (Router)
enable
configure terminal
interface fa0/1
ip address 10.84.16.1 255.255.254.0
no shutdown

Zeta (Device)
Interface fa0
IP Address: 10.84.16.2
Subnet Mask: 255.255.254.0
Gateway: 10.84.16.1

Kaela (Device)
Interface fa0
IP Address: 10.84.16.3
Subnet Mask: 255.255.254.0
Gateway: 10.84.16.1

Kobo (Device)
Interface fa0
IP Address: 10.84.16.4
Subnet Mask: 255.255.254.0
Gateway: 10.84.16.1

Subnet A8
Hololive (Router)
enable
configure terminal
interface fa1/0
ip address 10.84.19.105 255.255.255.252
no shutdown

HoloJP (Router)
enable
configure terminal
interface fa0/1
ip address 10.84.19.106 255.255.255.252
no shutdown

Subnet A9
HoloJP (Router)
enable
configure terminal
interface fa0/0
ip address 10.84.19.65 255.255.255.248
no shutdown

DEV_IS (Router)
enable
configure terminal
interface fa0/0
ip address 10.84.19.66 255.255.255.248
no shutdown

GEN:0 (Router)
enable
configure terminal
interface fa0/0
ip address 10.84.19.67 255.255.255.248
no shutdown

Subnet A10
DEV_IS (Router)
enable
configure terminal
interface fa0/1
ip address 10.84.19.33 255.255.255.240
no shutdown

Ririka_Rade (Device)
Interface fa0
IP Address: 10.84.19.34
Subnet Mask: 255.255.255.240
Gateway: 10.84.19.33

Ao (Device)
Interface fa0
IP Address: 10.84.19.35
Subnet Mask: 255.255.255.240
Gateway: 10.84.19.33

Hajime_Kanade (Device)
Interface fa0
IP Address: 10.84.19.36
Subnet Mask: 255.255.255.240
Gateway: 10.84.19.33

Subnet A11
GEN:0 (Router)
enable
configure terminal
interface fa0/1
ip address 10.84.0.1 255.255.248.0
no shutdown

GEN:1 (Router)
enable
configure terminal
interface fa0/0
ip address 10.84.0.2 255.255.248.0
no shutdown

MiComet (Device)
Interface fa0
IP Address: 10.84.0.3
Subnet Mask: 255.255.248.0
Gateway: 10.84.0.1

Sora_Robo_AZK (Device)
Interface fa0
IP Address: 10.84.0.4
Subnet Mask: 255.255.248.0
Gateway: 10.84.0.1

Subnet A12
GEN:1 (Router)
enable
configure terminal
interface fa0/1
ip address 10.84.14.1 255.255.254.0
no shutdown

FBK_Matsuri (Device)
Interface fa0
IP Address: 10.84.14.2
Subnet Mask: 255.255.254.0
Gateway: 10.84.14.1

Aki_Hachama (Device)
Interface fa0
IP Address: 10.84.14.3
Subnet Mask: 255.255.254.0
Gateway: 10.84.14.1

Subnet A13
GEN:1 (Router)
enable
configure terminal
interface fa1/0
ip address 10.84.19.77 255.255.255.252
no shutdown

GAMERS (Router)
enable
configure terminal
interface fa0/0
ip address 10.84.19.78 255.255.255.252
no shutdown

Subnet A14
GAMERS (Router)
enable
configure terminal
interface fa0/1
ip address 10.84.18.1 255.255.255.128
no shutdown

Kerone (Device)
Interface fa0
IP Address: 10.84.18.2
Subnet Mask: 255.255.255.128
Gateway: 10.84.18.1

Okayu (Device)
Interface fa0
IP Address: 10.84.18.3
Subnet Mask: 255.255.255.128
Gateway: 10.84.18.1

Mio (Device)
Interface fa0
IP Address: 10.84.18.4
Subnet Mask: 255.255.255.128
Gateway: 10.84.18.1

Subnet A15
Hololive (Router)
enable
configure terminal
interface fa1/1
ip address 10.84.19.81 255.255.255.252
no shutdown

HoloEN (Router)
enable
configure terminal
interface fa0/0
ip address 10.84.19.82 255.255.255.252
no shutdown

Subnet A16
HoloEN (Router)
enable
configure terminal
interface fa0/1
ip address 10.84.19.85 255.255.255.252
no shutdown

HoloAdvent (Router)
enable
configure terminal
interface fa0/0
ip address 10.84.19.86 255.255.255.252
no shutdown

Subnet A17
HoloAdvent (Router)
enable
configure terminal
interface fa0/1
ip address 10.84.19.1 255.255.255.224
no shutdown

FuwaMoco (Device)
Interface fa0
IP Address: 10.84.19.2
Subnet Mask: 255.255.224.0
Gateway: 10.84.19.1

Shiori_Nerissa (Device)
Interface fa0
IP Address: 10.84.19.3
Subnet Mask: 255.255.224.0
Gateway: 10.84.19.1

Biboo (Device)
Interface fa0
IP Address: 10.84.19.4
Subnet Mask: 255.255.224.0
Gateway: 10.84.19.1

Subnet A18
HoloEN (Router)
enable
configure terminal
interface fa1/0
ip address 10.84.19.89 255.255.255.252
no shutdown

Holo-Myth (Router)
enable
configure terminal
interface fa0/0
ip address 10.84.19.90 255.255.255.252
no shutdown

Subnet A19
Holo-Myth (Router)
enable
configure terminal
interface fa0/1
ip address 10.84.12.1 255.255.254.0
no shutdown

Gura_Ame_Ina (Device)
Interface fa0
IP Address: 10.84.12.2
Subnet Mask: 255.255.254.0
Gateway: 10.84.12.1

Kiara_Calli (Device)
Interface fa0
IP Address: 10.84.12.3
Subnet Mask: 255.255.254.0
Gateway: 10.84.12.1

Subnet A20
Holo-Myth (Router)
enable
configure terminal
interface fa1/0
ip address 10.84.19.49 255.255.255.248
no shutdown

Project-Hope (Router)
enable
configure terminal
interface fa0/0
ip address 10.84.19.50 255.255.255.248
no shutdown

Holo-Council (Router)
enable
configure terminal
interface fa0/0
ip address 10.84.19.51 255.255.255.248
no shutdown

Subnet A21
Project-Hope (Router)
enable
configure terminal
interface fa0/1
ip address 10.84.19.57 255.255.255.248
no shutdown

Irys (Device)
Interface fa0
IP Address: 10.84.19.58
Subnet Mask: 255.255.255.248
Gateway: 10.84.19.57

Subnet A22
Holo-Council (Router)
enable
configure terminal
interface fa0/1
ip address 10.84.18.129 255.255.255.192
no shutdown

Kronii_Mumei (Device)
Interface fa0
IP Address: 10.84.18.130
Subnet Mask: 255.255.255.192
Gateway: 10.84.18.129

Bae_Fauna (Device)
Interface fa0
IP Address: 10.84.18.131
Subnet Mask: 255.255.255.192
Gateway: 10.84.18.129

#### Konfigurasi Routing
Sisi Kanan (Holo-ID)
Hololive
enable
configure terminal
ip route 10.84.19.92 255.255.255.252 10.84.19.74
ip route 10.84.8.0 255.255.252.0 10.84.19.74
ip route 10.84.19.96 255.255.255.252 10.84.19.74
ip route 10.84.18.192 255.255.255.192 10.84.19.74
ip route 10.84.19.100 255.255.255.252 10.84.19.74
ip route 10.84.16.0 255.255.254.0 10.84.19.74
do write

Holo-ID
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 10.84.19.73
ip route 10.84.8.0 255.255.252.0 10.84.19.94
ip route 10.84.18.192 255.255.255.192 10.84.19.98
ip route 10.84.16.0 255.255.254.0 10.84.19.102
do write

AREA15
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 10.84.19.93
do write

holoro
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 10.84.19.97
do write

holoh3ro
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 10.84.19.101
do write

Sisi Bawah (HoloJP)
Hololive
enable
configure terminal
ip route 10.84.19.64 255.255.255.248 10.84.19.106
ip route 10.84.19.32 255.255.255.240 10.84.19.106
ip route 10.84.0.0 255.255.248.0 10.84.19.106
ip route 10.84.14.0 255.255.254.0 10.84.19.106
ip route 10.84.19.76 255.255.255.252 10.84.19.106
ip route 10.84.18.0 255.255.255.128 10.84.19.106
do write

HoloJP
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 10.84.19.105
ip route 10.84.19.32 255.255.255.240 10.84.19.66
ip route 10.84.0.0 255.255.248.0 10.84.19.67
ip route 10.84.14.0 255.255.254.0 10.84.19.67
ip route 10.84.19.76 255.255.255.252 10.84.19.67
ip route 10.84.18.0 255.255.255.128 10.84.19.67
do write

DEV_IS
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 10.84.19.65
ip route 10.84.0.0 255.255.248.0 10.84.19.67
ip route 10.84.14.0 255.255.254.0 10.84.19.67
ip route 10.84.19.76 255.255.255.252 10.84.19.67
ip route 10.84.18.0 255.255.255.128 10.84.19.67
do write

GEN:0
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 10.84.19.65
ip route 10.84.19.32 255.255.255.240 10.84.19.66
ip route 10.84.14.0 255.255.254.0 10.84.0.2
ip route 10.84.19.76 255.255.255.252 10.84.0.2
ip route 10.84.18.0 255.255.255.128 10.84.0.2
do write

GEN:1
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 10.84.0.1
ip route 10.84.18.0 255.255.255.128 10.84.19.78
do write

GAMERS
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 10.84.19.77
do write

Sisi Kiri (HoloEN)
Hololive
enable
configure terminal
ip route 10.84.19.84 255.255.255.252 10.84.19.82
ip route 10.84.19.0 255.255.255.224 10.84.19.82
ip route 10.84.19.88 255.255.255.252 10.84.19.82
ip route 10.84.12.0 255.255.254.0 10.84.19.82
ip route 10.84.19.48 255.255.255.248 10.84.19.82
ip route 10.84.19.56 255.255.255.248 10.84.19.82
ip route 10.84.18.128 255.255.255.192 10.84.19.82
do write

HoloEN
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 10.84.19.81
ip route 10.84.19.0 255.255.255.224 10.84.19.86
ip route 10.84.12.0 255.255.254.0 10.84.19.90
ip route 10.84.19.48 255.255.255.248 10.84.19.90
ip route 10.84.19.56 255.255.255.248 10.84.19.90
ip route 10.84.18.128 255.255.255.192 10.84.19.90
do write

HoloAdvent
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 10.84.19.85
do write

Holo-Myth
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 10.84.19.89
ip route 10.84.19.56 255.255.255.248 10.84.19.50
ip route 10.84.18.128 255.255.255.192 10.84.19.51
do write

Project-Hope
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 10.84.19.49
ip route 10.84.18.128 255.255.255.192 10.84.19.51
do write

Holo-Council
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 10.84.19.49
ip route 10.84.19.56 255.255.255.248 10.84.19.50
do write


# Kesimpulan

### **1. Subnet A1: Koneksi Hololive dan Holo-ID**
- **Hololive (Router)**
  ```bash
  enable
  configure terminal
  interface fa0/1
  ip address 10.84.19.73 255.255.255.252
  no shutdown
  ```

- **Holo-ID (Router)**
  ```bash
  enable
  configure terminal
  interface fa0/0
  ip address 10.84.19.74 255.255.255.252
  no shutdown
  ```

**Penjelasan:**  
Subnet ini menggunakan alamat 10.84.19.72/30 (255.255.255.252) untuk menghubungkan Hololive dan Holo-ID. Alamat broadcast adalah 10.84.19.75.

---

### **2. Subnet A2: Koneksi Holo-ID dan AREA15**
- **Holo-ID (Router)**
  ```bash
  enable
  configure terminal
  interface fa0/1
  ip address 10.84.19.93 255.255.255.252
  no shutdown
  ```

- **AREA15 (Router)**
  ```bash
  enable
  configure terminal
  interface fa0/0
  ip address 10.84.19.94 255.255.255.252
  no shutdown
  ```

**Penjelasan:**  
Subnet ini menggunakan alamat 10.84.19.92/30. Alamat broadcast adalah 10.84.19.95.

---

### **3. Subnet A3: AREA15 dan Perangkat Moona, Risu, Lofi**
- **AREA15 (Router)**
  ```bash
  enable
  configure terminal
  interface fa0/1
  ip address 10.84.8.1 255.255.252.0
  no shutdown
  ```

- **Moona, Risu, Lofi (Devices)**
  ```bash
  Interface fa0
  IP Address: 10.84.8.2, 10.84.8.3, 10.84.8.4
  Subnet Mask: 255.255.252.0
  Gateway: 10.84.8.1
  ```

**Penjelasan:**  
Subnet ini menggunakan alamat 10.84.8.0/22. Dapat mendukung hingga 1022 host.

---

### **4. Routing pada Hololive, Holo-ID, dan AREA15**
- **Routing di Hololive**
  ```bash
  ip route 10.84.19.92 255.255.255.252 10.84.19.74
  ip route 10.84.8.0 255.255.252.0 10.84.19.74
  ```

- **Routing di Holo-ID**
  ```bash
  ip route 0.0.0.0 0.0.0.0 10.84.19.73
  ip route 10.84.8.0 255.255.252.0 10.84.19.94
  ```

- **Routing di AREA15**
  ```bash
  ip route 0.0.0.0 0.0.0.0 10.84.19.93
  ```

**Penjelasan:**  
Routing ini memastikan konektivitas antar subnet menggunakan gateway yang ditentukan.

---

### **5. Subnet A4: Holo-ID dan holoro**
- **Holo-ID (Router)**
  ```bash
  enable
  configure terminal
  interface fa1/0
  ip address 10.84.19.97 255.255.255.252
  no shutdown
  ```

- **holoro (Router)**
  ```bash
  enable
  configure terminal
  interface fa0/0
  ip address 10.84.19.98 255.255.255.252
  no shutdown
  ```

**Penjelasan:**  
Subnet ini menggunakan 10.84.19.96/30. Broadcast: 10.84.19.99.

---

### **6. Subnet A5: holoro dan Perangkat Ollie, Anya, Reine**
- **holoro (Router)**
  ```bash
  enable
  configure terminal
  interface fa0/1
  ip address 10.84.18.193 255.255.255.192
  no shutdown
  ```

- **Ollie, Anya, Reine (Devices)**
  ```bash
  Interface fa0
  IP Address: 10.84.18.194, 10.84.18.195, 10.84.18.196
  Subnet Mask: 255.255.255.192
  Gateway: 10.84.18.193
  ```

**Penjelasan:**  
Subnet ini menggunakan 10.84.18.192/26. Mendukung 62 host.

---

### **7. Routing Tambahan untuk holoro dan holoh3ro**
- **Routing di holoro**
  ```bash
  ip route 0.0.0.0 0.0.0.0 10.84.19.97
  ```

- **Routing di holoh3ro**
  ```bash
  ip route 0.0.0.0 0.0.0.0 10.84.19.101
  ```

**Penjelasan:**  
Routing default digunakan untuk mengarahkan trafik ke router terdekat.

---


