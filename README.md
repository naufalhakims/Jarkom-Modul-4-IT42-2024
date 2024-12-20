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



# Network Configuration

Berikut adalah konfigurasi jaringan untuk beberapa subnet yang terhubung melalui router dan perangkat yang relevan.

## Subnet A1
### Hololive (Router)
```bash
enable
configure terminal
interface fa0/1
ip address 10.84.19.73 255.255.255.252
no shutdown
```

### Holo-ID (Router)
```bash
enable
configure terminal
interface fa0/0
ip address 10.84.19.74 255.255.255.252
no shutdown
```

## Subnet A2
### Holo-ID (Router)
```bash
enable
configure terminal
interface fa0/1
ip address 10.84.19.93 255.255.255.252
no shutdown
```

### AREA15 (Router)
```bash
enable
configure terminal
interface fa0/0
ip address 10.84.19.94 255.255.255.252
no shutdown
```

## Subnet A3
### AREA15 (Router)
```bash
enable
configure terminal
interface fa0/1
ip address 10.84.8.1 255.255.252.0
no shutdown
```

### Devices
- **Moona**
  - Interface: `fa0`
  - IP Address: `10.84.8.2`
  - Subnet Mask: `255.255.252.0`
  - Gateway: `10.84.8.1`
- **Risu**
  - Interface: `fa0`
  - IP Address: `10.84.8.3`
  - Subnet Mask: `255.255.252.0`
  - Gateway: `10.84.8.1`
- **Lofi**
  - Interface: `fa0`
  - IP Address: `10.84.8.4`
  - Subnet Mask: `255.255.252.0`
  - Gateway: `10.84.8.1`

## Subnet A4
### Holo-ID (Router)
```bash
enable
configure terminal
interface fa1/0
ip address 10.84.19.97 255.255.255.252
no shutdown
```

### Holoro (Router)
```bash
enable
configure terminal
interface fa0/0
ip address 10.84.19.98 255.255.255.252
no shutdown
```

## Subnet A5
### Holoro (Router)
```bash
enable
configure terminal
interface fa0/1
ip address 10.84.18.193 255.255.255.192
no shutdown
```

### Devices
- **Ollie**
  - Interface: `fa0`
  - IP Address: `10.84.18.194`
  - Subnet Mask: `255.255.255.192`
  - Gateway: `10.84.18.193`
- **Anya**
  - Interface: `fa0`
  - IP Address: `10.84.18.195`
  - Subnet Mask: `255.255.255.192`
  - Gateway: `10.84.18.193`
- **Reine**
  - Interface: `fa0`
  - IP Address: `10.84.18.196`
  - Subnet Mask: `255.255.255.192`
  - Gateway: `10.84.18.193`

## Subnet A6

### Router: HoloJP-Gen0
```bash
enable
configure terminal
interface fa0/0
ip address 10.84.1.1 255.255.255.224
no shutdown
```

### Devices:
- **Sora_Roboco**
  - Interface: `fa0`
  - IP Address: `10.84.1.2`
  - Subnet Mask: `255.255.255.224`
  - Gateway: `10.84.1.1`

- **Suisei_Azki**
  - Interface: `fa0`
  - IP Address: `10.84.1.3`
  - Subnet Mask: `255.255.255.224`
  - Gateway: `10.84.1.1`

---

## Subnet A7

### Router: HoloJP-Gen1
```bash
enable
configure terminal
interface fa0/0
ip address 10.84.2.1 255.255.255.224
no shutdown
```

### Devices:
- **Fubuki_Matsuri**
  - Interface: `fa0`
  - IP Address: `10.84.2.2`
  - Subnet Mask: `255.255.255.224`
  - Gateway: `10.84.2.1`

- **Mel_Aki**
  - Interface: `fa0`
  - IP Address: `10.84.2.3`
  - Subnet Mask: `255.255.255.224`
  - Gateway: `10.84.2.1`

---

## Subnet A8

### Router: HoloJP-Gen2
```bash
enable
configure terminal
interface fa0/0
ip address 10.84.3.1 255.255.255.224
no shutdown
```

### Devices:
- **Aqua_Shion**
  - Interface: `fa0`
  - IP Address: `10.84.3.2`
  - Subnet Mask: `255.255.255.224`
  - Gateway: `10.84.3.1`

- **Ayame_Choco**
  - Interface: `fa0`
  - IP Address: `10.84.3.3`
  - Subnet Mask: `255.255.255.224`
  - Gateway: `10.84.3.1`

---

## Subnet A9

### Router: HoloJP-Gen3
```bash
enable
configure terminal
interface fa0/0
ip address 10.84.4.1 255.255.255.224
no shutdown
```

### Devices:
- **Pekora_Marine**
  - Interface: `fa0`
  - IP Address: `10.84.4.2`
  - Subnet Mask: `255.255.255.224`
  - Gateway: `10.84.4.1`

- **Noel_Flare**
  - Interface: `fa0`
  - IP Address: `10.84.4.3`
  - Subnet Mask: `255.255.255.224`
  - Gateway: `10.84.4.1`

---

## Subnet A10

### Router: HoloJP-Gen4
```bash
enable
configure terminal
interface fa0/0
ip address 10.84.5.1 255.255.255.224
no shutdown
```

### Devices:
- **Kanata_Coco**
  - Interface: `fa0`
  - IP Address: `10.84.5.2`
  - Subnet Mask: `255.255.255.224`
  - Gateway: `10.84.5.1`

- **Watame_Towa**
  - Interface: `fa0`
  - IP Address: `10.84.5.3`
  - Subnet Mask: `255.255.255.224`
  - Gateway: `10.84.5.1`

---

## Subnet A11

### Router: HoloJP-Gen5
```bash
enable
configure terminal
interface fa0/0
ip address 10.84.6.1 255.255.255.224
no shutdown
```

### Devices:
- **Nene_Lamy**
  - Interface: `fa0`
  - IP Address: `10.84.6.2`
  - Subnet Mask: `255.255.255.224`
  - Gateway: `10.84.6.1`

- **Polka_Botan**
  - Interface: `fa0`
  - IP Address: `10.84.6.3`
  - Subnet Mask: `255.255.255.224`
  - Gateway: `10.84.6.1`

## Subnet A12

### Router: HoloJP-Gen6
```bash
enable
configure terminal
interface fa0/0
ip address 10.84.7.1 255.255.255.224
no shutdown
```

### Devices:
- **Aloe_Suisei**
  - Interface: `fa0`
  - IP Address: `10.84.7.2`
  - Subnet Mask: `255.255.255.224`
  - Gateway: `10.84.7.1`

- **Luna_Shiba**
  - Interface: `fa0`
  - IP Address: `10.84.7.3`
  - Subnet Mask: `255.255.255.224`
  - Gateway: `10.84.7.1`

---

## Subnet A13

### Router: HoloID-Gen1
```bash
enable
configure terminal
interface fa0/0
ip address 10.84.8.1 255.255.255.224
no shutdown
```

### Devices:
- **Moona_Iofi**
  - Interface: `fa0`
  - IP Address: `10.84.8.2`
  - Subnet Mask: `255.255.255.224`
  - Gateway: `10.84.8.1`

- **Risu_Kobo**
  - Interface: `fa0`
  - IP Address: `10.84.8.3`
  - Subnet Mask: `255.255.255.224`
  - Gateway: `10.84.8.1`

---

## Subnet A14

### Router: HoloID-Gen2
```bash
enable
configure terminal
interface fa0/0
ip address 10.84.9.1 255.255.255.224
no shutdown
```

### Devices:
- **Ollie_Anya**
  - Interface: `fa0`
  - IP Address: `10.84.9.2`
  - Subnet Mask: `255.255.255.224`
  - Gateway: `10.84.9.1`

- **Reine_Kaela**
  - Interface: `fa0`
  - IP Address: `10.84.9.3`
  - Subnet Mask: `255.255.255.224`
  - Gateway: `10.84.9.1`

---

## Subnet A15

### Router: HoloEN-Gen1
```bash
enable
configure terminal
interface fa0/0
ip address 10.84.10.1 255.255.255.224
no shutdown
```

### Devices:
- **Amelia_Gura**
  - Interface: `fa0`
  - IP Address: `10.84.10.2`
  - Subnet Mask: `255.255.255.224`
  - Gateway: `10.84.10.1`

- **Ina_Kiara**
  - Interface: `fa0`
  - IP Address: `10.84.10.3`
  - Subnet Mask: `255.255.255.224`
  - Gateway: `10.84.10.1`

---

## Subnet A16

### Router: HoloEN-Gen2
```bash
enable
configure terminal
interface fa0/0
ip address 10.84.11.1 255.255.255.224
no shutdown
```

### Devices:
- **Kronii_Baelz**
  - Interface: `fa0`
  - IP Address: `10.84.11.2`
  - Subnet Mask: `255.255.255.224`
  - Gateway: `10.84.11.1`

- **Fauna_Sana**
  - Interface: `fa0`
  - IP Address: `10.84.11.3`
  - Subnet Mask: `255.255.255.224`
  - Gateway: `10.84.11.1`

---

## Subnet A17

### Router: HoloAdvent
```bash
enable
configure terminal
interface fa0/1
ip address 10.84.19.1 255.255.255.224
no shutdown
```

### Devices:
- **FuwaMoco**
  - Interface: `fa0`
  - IP Address: `10.84.19.2`
  - Subnet Mask: `255.255.255.224`
  - Gateway: `10.84.19.1`

- **Shiori_Nerissa**
  - Interface: `fa0`
  - IP Address: `10.84.19.3`
  - Subnet Mask: `255.255.255.224`
  - Gateway: `10.84.19.1`

- **Biboo**
  - Interface: `fa0`
  - IP Address: `10.84.19.4`
  - Subnet Mask: `255.255.255.224`
  - Gateway: `10.84.19.1`

---

## Subnet A18

### Router: HoloEN
```bash
enable
configure terminal
interface fa1/0
ip address 10.84.19.89 255.255.255.252
no shutdown
```

### Router: Holo-Myth
```bash
enable
configure terminal
interface fa0/0
ip address 10.84.19.90 255.255.255.252
no shutdown
```

---

## Subnet A19

### Router: Holo-Myth
```bash
enable
configure terminal
interface fa0/1
ip address 10.84.12.1 255.255.254.0
no shutdown
```

### Devices:
- **Gura_Ame_Ina**
  - Interface: `fa0`
  - IP Address: `10.84.12.2`
  - Subnet Mask: `255.255.254.0`
  - Gateway: `10.84.12.1`

- **Kiara_Calli**
  - Interface: `fa0`
  - IP Address: `10.84.12.3`
  - Subnet Mask: `255.255.254.0`
  - Gateway: `10.84.12.1`

---

## Subnet A20

### Router: Holo-Myth
```bash
enable
configure terminal
interface fa1/0
ip address 10.84.19.49 255.255.255.248
no shutdown
```

### Routers:
- **Project-Hope**
  ```bash
  enable
  configure terminal
  interface fa0/0
  ip address 10.84.19.50 255.255.255.248
  no shutdown
  ```

- **Holo-Council**
  ```bash
  enable
  configure terminal
  interface fa0/0
  ip address 10.84.19.51 255.255.255.248
  no shutdown
  ```

---

## Subnet A21

### Router: Project-Hope
```bash
enable
configure terminal
interface fa0/1
ip address 10.84.19.57 255.255.255.248
no shutdown
```

### Devices:
- **Irys**
  - Interface: `fa0`
  - IP Address: `10.84.19.58`
  - Subnet Mask: `255.255.255.248`
  - Gateway: `10.84.19.57`

---

## Subnet A22

### Router: Holo-Council
```bash
enable
configure terminal
interface fa0/1
ip address 10.84.18.129 255.255.255.192
no shutdown
```

### Devices:
- **Kronii_Mumei**
  - Interface: `fa0`
  - IP Address: `10.84.18.130`
  - Subnet Mask: `255.255.255.192`
  - Gateway: `10.84.18.129`

- **Bae_Fauna**
  - Interface: `fa0`
  - IP Address: `10.84.18.131`
  - Subnet Mask: `255.255.255.192`
  - Gateway: `10.84.18.129`

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

### CIDR
Dibawah ini pembagian IP menggunakan CIDR
### Pembagian Subnet
![subnetting_gns](https://github.com/user-attachments/assets/5cd7b016-987c-4434-ae13-376b40ccc928)
### CIDR TREE
![image](https://github.com/user-attachments/assets/baaf99a4-461e-4a66-a4e7-a6f9a39c3c6f)
### CIDR pembagian IP
![image](https://github.com/user-attachments/assets/84b1d3a4-7026-4620-9da4-88399c1439a1)
### Config
## Konfigurasi
### Hololive (Gateway)
```
#A1
auto eth1
iface eth1 inet static
address 10.85.16.1
netmask 255.255.255.252
#A9
auto eth2
iface eth2 inet static
address 10.84.160.1
netmask 255.255.255.252
#A16
auto eth3
iface eth3 inet static
address 10.84.64.1
netmask 255.255.255.252
```
### Holo-EN (Gateway)
```
#A1
auto eth0
iface eth0 inet static
address 10.85.16.2
netmask 255.255.255.252
gateway 10.85.16.1
#A2
auto eth1
iface eth1 inet static
address 10.85.4.1
netmask 255.255.255.252
#A7
auto eth2
iface eth2 inet static
address 10.85.8.33
netmask 255.255.255.252
```
### Holo-Myth (Gateway)
```
#A2
auto eth0
iface eth0 inet static
address 10.85.4.2
netmask 255.255.255.252
gateway 10.85.4.1
#A3
auto eth1
iface eth1 inet static
address 10.85.0.1
netmask 255.255.254.0
#A4
auto eth2
iface eth2 inet static
address 10.85.2.129
netmask 255.255.255.248
```
### Gura_Ame_Ina (Client)
```
#A3
auto eth0
iface eth0 inet static
address 10.85.0.3
netmask 255.255.254.0
gateway 10.85.0.1
```
### Kiara_Calli (Client)
```
#A3
auto eth0
iface eth0 inet static
address 10.85.0.2
netmask 255.255.254.0
gateway 10.85.0.1
```
### HoloAdvent (Gateway)
```
#A7
auto eth0
iface eth0 inet static
address 10.85.8.34
netmask 255.255.255.252
gateway 10.85.8.33
#A8
auto eth1
iface eth1 inet static
address 10.85.8.1
netmask 255.255.255.224
```
### FuwaMoco (Client)
```
#A8
auto eth0
iface eth0 inet static
address 10.85.8.2
netmask 255.255.255.224
gateway 10.85.8.1
```
### Shiori_Nerissa (Client)
```
#A8
auto eth1
iface eth1 inet static
address 10.85.8.3
netmask 255.255.255.224
gateway 10.85.8.1
```
### Biboo (Client)
```
#A8
auto eth2
iface eth2 inet static
address 10.85.8.4
netmask 255.255.255.224
gateway 10.85.8.1
```
### Project-Hope (Gateway)
```
#A4
auto eth0
iface eth0 inet static
address 10.85.2.130
netmask 255.255.255.248
gateway 10.85.2.129
#A5
auto eth1
iface eth1 inet static
address 10.85.2.65
netmask 255.255.255.248
```
### Irys (Client)
```
#A5
auto eth0
iface eth0 inet static
address 10.85.2.66
netmask 255.255.255.248
gateway 10.85.2.65.
```
### Holo-Council (Gateway)
```
#A4
auto eth0
iface eth0 inet static
address 10.85.2.131
netmask 255.255.255.248
gateway 10.85.2.129
#A6
auto eth1
iface eth1 inet static
address 10.85.2.1
netmask 255.255.255.192
```
### Kronii_Mumei (Client)
```
#A6
auto eth0
iface eth0 inet static
address 10.85.2.2
netmask 255.255.255.192
gateway 10.85.2.1
```
### Bae_Fauna (Client)
```
#A6
auto eth0
iface eth0 inet static
address 10.85.2.3
netmask 255.255.255.192
gateway 10.85.2.1
```
### Holo-ID (Gateway)
```
#A9
auto eth0
iface eth0 inet static
address 10.84.160.2
netmask 255.255.255.252
#A10
auto eth1
iface eth1 inet static
address 10.84.132.1
netmask 255.255.255.252
#A12
auto eth2
iface eth2 inet static
address 10.84.136.65
netmask 255.255.255.252
#A14
auto eth3
iface eth3 inet static
address 10.84.146.1
netmask 255.255.255.252
```
### AREA15 (Gateway)
```
#A10
auto eth0
iface eth0 inet static
address 10.84.132.2
netmask 255.255.255.252
gateway 10.84.132.1
#A11
auto eth1
iface eth1 inet static
address 10.84.128.1
netmask 255.255.252.0
```
### lofi (Client)
```
#A11
auto eth0
iface eth0 inet static
address 10.84.128.4
netmask 255.255.252.0
gateway 10.84.128.1
```
### Moona (Client)
```
#A11
auto eth0
iface eth0 inet static
address 10.84.128.3
netmask 255.255.252.0
gateway 10.84.128.1
```
### Risu (Client)
```
#A11
auto eth0
iface eth0 inet static
address 10.84.128.2
netmask 255.255.252.0
gateway 10.84.128.1
```
### holoro (Gateway)
```
#A12
auto eth0
iface eth0 inet static
address 10.84.136.66
netmask 255.255.255.252
gateway 10.84.136.65
#A13
auto eth1
iface eth1 inet static
address 10.84.136.1
netmask 255.255.252.192
```
### Ollie (Client)
```
#A13
auto eth0
iface eth0 inet static
address 10.84.136.2
netmask 255.255.255.192
gateway 10.84.136.1
```
### Anya (Client)
```
#A13
auto eth0
iface eth0 inet static
address 10.84.136.3
netmask 255.255.252.192
gateway 10.84.136.1
```
### Reine (Client)
```
#A13
auto eth0
iface eth0 inet static
address 10.84.136.4
netmask 255.255.255.192
gateway 10.84.136.1
```
### holoh3ro (Gateway)
```
#A14
auto eth0
iface eth0 inet static
address 10.84.146.2
netmask 255.255.255.252
gateway 10.84.146.1
#A15
auto eth1
iface eth1 inet static
address 10.84.144.1
netmask 255.255.254.0
```
### Zeta (Client)
```
#A15
auto eth0
iface eth0 inet static
address 10.84.144.2
netmask 255.255.254.0
gateway 10.84.144.1
```
### Kaela (Client)
```
#A15
auto eth0
iface eth0 inet static
address 10.84.144.3
netmask 255.255.254.0
gateway 10.84.144.1
```
### Kobo (Client)
```
#A15
auto eth0
iface eth0 inet static
address 10.84.144.4
netmask 255.255.254.0
gateway 10.84.144.1
```
### Holo-JP (Gateway)
```
#A16
auto eth0
iface eth0 inet static
address 10.84.64.2
netmask 255.255.255.252
#A17
auto eth1
iface eth1 inet static
address 10.84.16.1
netmask 255.255.255.252
```
### DEV_IS (Gateway)
```
#A17
auto eth0
iface eth0 inet static
address 10.84.16.3
netmask 255.255.255.252
gateway 10.84.16.1
#A18
auto eth1
iface eth1 inet static
address 10.84.32.1
netmask 255.255.255.240
```
### Ririka_Raden (Client)
```
#A18
auto eth0
iface eth0 inet static
address 10.84.32.2
netmask 255.255.255.240
gateway 10.84.32.1
```
### Ao (Client)
```
#A18
auto eth0
iface eth0 inet static
address 10.84.32.3
netmask 255.255.255.240
gateway 10.84.32.1
```
### Hajime_Kanade (Client)
```
#A18
auto eth0
iface eth0 inet static
address 10.84.32.4
netmask 255.255.255.240
gateway 10.84.32.1
```
### GEN:0 (Gateway)
```
#A17
auto eth0
iface eth0 inet static
address 10.84.16.2
netmask 255.255.255.248
gateway 10.84.16.1
#A19
auto eth1
iface eth1 inet static
address 10.84.0.1
netmask 255.255.248.0
```
### MiComet (Client)
```
#A19
auto eth0
iface eth0 inet static
address 10.84.0.2
netmask 255.255.248.0
gateway 10.84.0.1
```
### Sora_Robo_AZKi (Client)
```
#A19
auto eth0
iface eth0 inet static
address 10.84.0.3
netmask 255.255.248.0
gateway 10.84.0.1
```
### GEN:1 (Gateway)
```
#A19
auto eth0
iface eth0 inet static
address 10.84.0.4
netmask 255.255.248.0
gateway
#A20
auto eth1
iface eth1 inet static
address 10.84.8.1
netmask 255.255.254.0
#A21
auto eth2
iface eth2 inet static
address 10.84.10.129
netmask 255.255.255.252
```
### FBK_Matsuri (Client)
```
#A20
auto eth0
iface eth0 inet static
address 10.84.8.2
netmask 255.255.254.0
gateway 10.84.8.1
```
### Aki_Hachama (Client)
```
#A20
auto eth0
iface eth0 inet static
address 10.84.8.3
netmask 255.255.248.0
gateway 10.84.8.1
```
### Gamers (Gateway)
```
#A21
auto eth0
iface eth0 inet static
address 10.84.10.130
netmask 255.255.255.252
gateway 10.84.10.129
#A22
auto eth1
iface eth1 inet static
address 10.84.10.1
netmask 255.255.255.128
```
### Korone (Client)
```
#A22
auto eth0
iface eth0 inet static
address 10.84.10.2
netmask 255.255.255.128
gateway 10.84.10.1
```
### Okayu (Client)
```
#A22
auto eth0
iface eth0 inet static
address 10.84.10.3
netmask 255.255.255.128
gateway 10.84.10.1
```
### Mio (Client)
```
#A22
auto eth0
iface eth0 inet static
address 10.84.10.4
netmask 255.255.255.128
gateway 10.84.10.1
```




