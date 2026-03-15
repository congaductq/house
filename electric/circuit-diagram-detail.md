
# SO DO MACH DIEN CHI TIET - NHA 4 TANG CO THANG MAY
# (BAN VE THI CONG CHO THO DIEN)

Ngay tao: 2026-03-15

---

# PHAN A: TU DIEN TONG (DAT TAI TANG 1 - GAN CUA CHINH)

## A1. So do nguon chinh

```
                         EVN 3 PHA (A-B-C-N-PE)
                              │
                         Cap tong 4x16mm2 + PE 10mm2
                              │
                    ┌─────────┴──────────┐
                    │  MCB TONG 3P 80A   │
                    │  (Schneider/LS)    │
                    └─────────┬──────────┘
                              │
                    ┌─────────┴──────────┐
                    │  SPD CHONG SET     │
                    │  3P+N, 40kA        │
                    │  (Schneider iC60)  │
                    └─────────┬──────────┘
                              │
                    ┌─────────┴──────────┐
                    │  RCCB 4P 63A 30mA  │
                    │  (Chong ro dien)   │
                    └─────────┬──────────┘
                              │
              ┌───────────────┼───────────────┐
              │               │               │
         BUS PHA A       BUS PHA B       BUS PHA C
              │               │               │
         THANH N (chung)      │          THANH N (chung)
              │               │               │
         THANH PE (chung - tiep dia)          │
```

## A2. Phan bo tu dien tong - Bang ke MCB nhanh

```
╔════════════╦══════════════════╦═════════════╦════════════════════╦══════════════╗
║ STT        ║ MCB              ║ PHA         ║ TAI                ║ CAP (mm2)    ║
╠════════════╬══════════════════╬═════════════╬════════════════════╬══════════════╣
║ 1          ║ MCB 1P 32A       ║ A           ║ Tu tang 1          ║ 2x6 + PE    ║
║ 2          ║ MCB 1P 40A       ║ B           ║ Tu tang 2          ║ 2x6 + PE    ║
║ 3          ║ MCB 1P 32A       ║ C           ║ Tu tang 3          ║ 2x6 + PE    ║
║ 4          ║ MCB 1P 32A       ║ C           ║ Tu tang 4          ║ 2x6 + PE    ║
║ 5          ║ MCB 3P 32A       ║ A-B-C       ║ Thang may          ║ 5x6         ║
║ 6          ║ MCB 1P 10A       ║ A           ║ Den cau thang chung║ 2x1.5       ║
╠════════════╬══════════════════╬═════════════╬════════════════════╬══════════════╣
║            ║ TONG CONG: 6 MCB ║             ║                    ║              ║
╚════════════╩══════════════════╩═════════════╩════════════════════╩══════════════╝
```

---

# PHAN B: SO DO CHI TIET TUNG TANG

---

## B1. TANG 1 - PHA A (Tu dien tang 1, dat trong hop am tuong)

### Nhan dien phong tu mat bang (trai sang phai, truoc ra sau):
- Phong khach (phia truoc, co sofa)
- Phong an / bep (phia sau, co bep tu)
- Phong ngu tang 1 (phia truoc ben phai)
- Phong ve sinh tang 1 (phia sau ben phai)
- Hanh lang + cau thang
- Gara xe (phia truoc cung ben trai)

### So do mach tang 1:

```
MCB 32A (tu tong, PHA A)
  │
  │  Cap 2x6mm2 + PE xuong tu tang 1
  │
  ╔══════════════════════════════════════════════════════════════════════════╗
  ║                        TU DIEN TANG 1                                  ║
  ╠════════╦══════════╦═══════════════════════════════════╦════════════════╣
  ║ Mach   ║ MCB      ║ Mo ta                             ║ Day (mm2)     ║
  ╠════════╬══════════╬═══════════════════════════════════╬════════════════╣
  ║ 1.1    ║ MCB 20A  ║ Dieu hoa phong khach (9000BTU)   ║ 2x2.5 + PE   ║
  ║ 1.2    ║ MCB 20A  ║ Dieu hoa phong ngu T1 (9000BTU)  ║ 2x2.5 + PE   ║
  ║ 1.3    ║ MCB 32A  ║ Bep tu (rieng, day lon)           ║ 2x6 + PE     ║
  ║ 1.4    ║ MCB 20A  ║ Nong lanh phong ve sinh T1        ║ 2x4 + PE     ║
  ║ 1.5    ║ MCB 16A  ║ O cam phong khach (3-4 o cam)     ║ 2x2.5 + PE   ║
  ║ 1.6    ║ MCB 16A  ║ O cam phong ngu T1 (2-3 o cam)   ║ 2x2.5 + PE   ║
  ║ 1.7    ║ MCB 16A  ║ O cam bep (2 o cam, ko tinh bep) ║ 2x2.5 + PE   ║
  ║ 1.8    ║ MCB 10A  ║ Den phong khach + hanh lang       ║ 2x1.5        ║
  ║ 1.9    ║ MCB 10A  ║ Den phong ngu + bep + WC T1       ║ 2x1.5        ║
  ║ 1.10   ║ MCB 10A  ║ Den gara + den ngoai troi         ║ 2x1.5        ║
  ╠════════╬══════════╬═══════════════════════════════════╬════════════════╣
  ║        ║ TONG: 10 ║                                   ║               ║
  ╚════════╩══════════╩═══════════════════════════════════╩════════════════╝
```

### Chi tiet di day tang 1:

```
Mach 1.1 - DIEU HOA PHONG KHACH:
    Tu tang 1 ──MCB 20A── day 2x2.5+PE ── am tuong ── o cam dieu hoa (cao 2.2m)
    Luu y: Dat o cam rieng cho dieu hoa, vi tri phia tren

Mach 1.2 - DIEU HOA PHONG NGU T1:
    Tu tang 1 ──MCB 20A── day 2x2.5+PE ── am tuong ── o cam dieu hoa (cao 2.2m)

Mach 1.3 - BEP TU:
    Tu tang 1 ──MCB 32A── day 2x6+PE ── am tuong ── o cam bep tu (cao 0.3m, sau tu bep)
    *** QUAN TRONG: Day 6mm2, MCB 32A, o cam 32A chuyen dung ***

Mach 1.4 - NONG LANH WC T1:
    Tu tang 1 ──MCB 20A── day 2x4+PE ── am tuong ── o cam nong lanh (cao 1.8m, trong WC)
    *** QUAN TRONG: Qua RCCB 25A 30mA truoc khi vao o cam ***

    MCB 20A ── RCCB 25A 30mA ── day 2x4+PE ── O CAM NONG LANH
                                                    │
                                                   PE noi tiep dia

Mach 1.5 - O CAM PHONG KHACH:
    Tu tang 1 ──MCB 16A── day 2x2.5+PE ──┬── O cam 1 (tuong trai, cao 0.3m)
                                          ├── O cam 2 (tuong phai, cao 0.3m)
                                          ├── O cam 3 (goc TV, cao 0.3m)
                                          └── O cam 4 (gan ban lam viec, cao 0.3m)

Mach 1.8 - DEN PHONG KHACH + HANH LANG:
    Tu tang 1 ──MCB 10A── day 2x1.5 ──┬── CT1 ── Den tran phong khach
                                       ├── CT2 ── Den hanh lang
                                       └── CT3 ── Den trang tri
    CT = cong tac (dat cao 1.2m tu san)
```

---

## B2. TANG 2 - PHA B (Tu dien tang 2)

### Nhan dien phong tu mat bang:
- Phong ngu master (phong lon, co WC rieng)
- Phong ngu 2 (phong nho hon, co WC rieng)
- Phong ngu 3 (phong nho, co WC rieng)
- Hanh lang + cau thang

### So do mach tang 2:

```
MCB 40A (tu tong, PHA B)
  │
  │  Cap 2x6mm2 + PE len tu tang 2
  │
  ╔══════════════════════════════════════════════════════════════════════════╗
  ║                        TU DIEN TANG 2                                  ║
  ╠════════╦══════════╦═══════════════════════════════════╦════════════════╣
  ║ Mach   ║ MCB      ║ Mo ta                             ║ Day (mm2)     ║
  ╠════════╬══════════╬═══════════════════════════════════╬════════════════╣
  ║ 2.1    ║ MCB 20A  ║ Dieu hoa phong ngu master         ║ 2x2.5 + PE   ║
  ║ 2.2    ║ MCB 20A  ║ Dieu hoa phong ngu 2              ║ 2x2.5 + PE   ║
  ║ 2.3    ║ MCB 20A  ║ Dieu hoa phong ngu 3              ║ 2x2.5 + PE   ║
  ║ 2.4    ║ MCB 20A  ║ Nong lanh WC master               ║ 2x4 + PE     ║
  ║ 2.5    ║ MCB 20A  ║ Nong lanh WC phong 2              ║ 2x4 + PE     ║
  ║ 2.6    ║ MCB 20A  ║ Nong lanh WC phong 3              ║ 2x4 + PE     ║
  ║ 2.7    ║ MCB 16A  ║ O cam phong ngu master (3 o cam)  ║ 2x2.5 + PE   ║
  ║ 2.8    ║ MCB 16A  ║ O cam phong ngu 2 (2 o cam)       ║ 2x2.5 + PE   ║
  ║ 2.9    ║ MCB 16A  ║ O cam phong ngu 3 (2 o cam)       ║ 2x2.5 + PE   ║
  ║ 2.10   ║ MCB 10A  ║ Den phong master + WC master      ║ 2x1.5        ║
  ║ 2.11   ║ MCB 10A  ║ Den phong 2 + phong 3 + hanh lang ║ 2x1.5        ║
  ╠════════╬══════════╬═══════════════════════════════════╬════════════════╣
  ║        ║ TONG: 11 ║                                   ║               ║
  ╚════════╩══════════╩═══════════════════════════════════╩════════════════╝
```

### Chi tiet mach nong lanh (3 mach giong nhau):

```
Mach 2.4 / 2.5 / 2.6 - NONG LANH (moi WC 1 mach rieng):

    MCB 20A ── RCCB 25A 30mA ── day 2x4+PE ── O CAM NONG LANH (cao 1.8m)
                                                    │
                                                   PE ── thanh tiep dia

    *** MOI BINH NONG LANH PHAI CO RCCB RIENG ***
```

### Chi tiet di day o cam phong ngu:

```
Mach 2.7 - O CAM PHONG NGU MASTER:
    MCB 16A ── day 2x2.5+PE ──┬── O cam dau giuong trai (cao 0.3m)
                               ├── O cam dau giuong phai (cao 0.3m)
                               └── O cam ban trang diem (cao 0.3m)

Mach 2.8 - O CAM PHONG NGU 2:
    MCB 16A ── day 2x2.5+PE ──┬── O cam dau giuong (cao 0.3m)
                               └── O cam ban hoc (cao 0.8m)

Mach 2.9 - O CAM PHONG NGU 3:
    MCB 16A ── day 2x2.5+PE ──┬── O cam dau giuong (cao 0.3m)
                               └── O cam ban hoc (cao 0.8m)
```

---

## B3. TANG 3 - PHA C (Tu dien tang 3)

### Nhan dien phong tu mat bang:
- Phong ngu 4 (phong lon, co WC rieng)
- Phong ngu 5 (phong nho, co WC rieng)
- Hanh lang + cau thang

### So do mach tang 3:

```
MCB 32A (tu tong, PHA C)
  │
  │  Cap 2x6mm2 + PE len tu tang 3
  │
  ╔══════════════════════════════════════════════════════════════════════════╗
  ║                        TU DIEN TANG 3                                  ║
  ╠════════╦══════════╦═══════════════════════════════════╦════════════════╣
  ║ Mach   ║ MCB      ║ Mo ta                             ║ Day (mm2)     ║
  ╠════════╬══════════╬═══════════════════════════════════╬════════════════╣
  ║ 3.1    ║ MCB 20A  ║ Dieu hoa phong ngu 4              ║ 2x2.5 + PE   ║
  ║ 3.2    ║ MCB 20A  ║ Dieu hoa phong ngu 5              ║ 2x2.5 + PE   ║
  ║ 3.3    ║ MCB 20A  ║ Nong lanh WC phong 4              ║ 2x4 + PE     ║
  ║ 3.4    ║ MCB 20A  ║ Nong lanh WC phong 5              ║ 2x4 + PE     ║
  ║ 3.5    ║ MCB 16A  ║ O cam phong ngu 4 (3 o cam)       ║ 2x2.5 + PE   ║
  ║ 3.6    ║ MCB 16A  ║ O cam phong ngu 5 (2 o cam)       ║ 2x2.5 + PE   ║
  ║ 3.7    ║ MCB 10A  ║ Den phong 4 + WC 4                ║ 2x1.5        ║
  ║ 3.8    ║ MCB 10A  ║ Den phong 5 + WC 5 + hanh lang    ║ 2x1.5        ║
  ╠════════╬══════════╬═══════════════════════════════════╬════════════════╣
  ║        ║ TONG: 8  ║                                   ║               ║
  ╚════════╩══════════╩═══════════════════════════════════╩════════════════╝
```

### Chi tiet nong lanh tang 3 (giong tang 2):

```
Mach 3.3 / 3.4 - NONG LANH:
    MCB 20A ── RCCB 25A 30mA ── day 2x4+PE ── O CAM NONG LANH (cao 1.8m)
                                                    │
                                                   PE ── thanh tiep dia
```

---

## B4. TANG 4 - PHA C (Tu dien tang 4)

### Nhan dien phong tu mat bang:
- Phong da nang / phong tho (phong lon)
- Phong ve sinh
- Khu giat + phoi do
- San thuong / mai

### So do mach tang 4:

```
MCB 32A (tu tong, PHA C)
  │
  │  Cap 2x6mm2 + PE len tu tang 4
  │
  ╔══════════════════════════════════════════════════════════════════════════╗
  ║                        TU DIEN TANG 4                                  ║
  ╠════════╦══════════╦═══════════════════════════════════╦════════════════╣
  ║ Mach   ║ MCB      ║ Mo ta                             ║ Day (mm2)     ║
  ╠════════╬══════════╬═══════════════════════════════════╬════════════════╣
  ║ 4.1    ║ MCB 20A  ║ Dieu hoa phong da nang            ║ 2x2.5 + PE   ║
  ║ 4.2    ║ MCB 20A  ║ Nong lanh WC tang 4               ║ 2x4 + PE     ║
  ║ 4.3    ║ MCB 16A  ║ May giat                          ║ 2x2.5 + PE   ║
  ║ 4.4    ║ MCB 16A  ║ May say                           ║ 2x2.5 + PE   ║
  ║ 4.5    ║ MCB 16A  ║ O cam phong da nang (2-3 o cam)   ║ 2x2.5 + PE   ║
  ║ 4.6    ║ MCB 16A  ║ O cam khu giat (1 o cam du phong) ║ 2x2.5 + PE   ║
  ║ 4.7    ║ MCB 10A  ║ Den phong da nang + WC            ║ 2x1.5        ║
  ║ 4.8    ║ MCB 10A  ║ Den san thuong + mai               ║ 2x1.5        ║
  ╠════════╬══════════╬═══════════════════════════════════╬════════════════╣
  ║        ║ TONG: 8  ║                                   ║               ║
  ╚════════╩══════════╩═══════════════════════════════════╩════════════════╝
```

### Chi tiet mach may giat va may say:

```
Mach 4.3 - MAY GIAT:
    MCB 16A ── day 2x2.5+PE ── o cam may giat (cao 1.2m, gan may giat)
    *** Nen co RCCB 16A 30mA vi gan nguon nuoc ***

    MCB 16A ── RCCB 16A 30mA ── day 2x2.5+PE ── O CAM MAY GIAT

Mach 4.4 - MAY SAY:
    MCB 16A ── day 2x2.5+PE ── o cam may say (cao 1.2m, gan may say)
```

---

# PHAN C: MACH DEN CAU THANG (DAO CHIEU 4 TANG)

## C1. So do nguyen ly dao chieu den cau thang

Dung he thong cong tac dao chieu (2-way switch) + cong tac trung gian (intermediate switch)
de dieu khien den cau thang tu 4 vi tri (tang 1, 2, 3, 4).

```
MCB 10A (tu tong, PHA A)
  │
  │  day 2x1.5mm2
  │
  PHA ────── SW1 (dao chieu, tang 1)
              │  ╲
              │   ╲── day 1 ──┐
              │               │
              │── day 2 ──┐   │
                          │   │
              SW_TG2 (trung gian, tang 2)
              │   ╲       │   │
              │    ╲──────┘   │
              │               │
              │───────────────┘
                          │
              SW_TG3 (trung gian, tang 3)
              │   ╲
              │    ╲──────────┐
              │               │
              │───────────┐   │
                          │   │
              SW4 (dao chieu, tang 4)
              │  ╲        │   │
              │   ╲───────┘   │
              │               │
              │───────────────┘
              │
           DEN CAU THANG (moi tang 1 den)
              │
           NEUTRAL

    SW1, SW4 = cong tac dao chieu (2 way switch)
    SW_TG2, SW_TG3 = cong tac trung gian (intermediate switch)
```

## C2. Vi tri cong tac cau thang

```
Tang 1: Cong tac dao chieu - dat chan cau thang tang 1 (cao 1.2m)
Tang 2: Cong tac trung gian - dat dau cau thang tang 2 (cao 1.2m)
Tang 3: Cong tac trung gian - dat dau cau thang tang 3 (cao 1.2m)
Tang 4: Cong tac dao chieu - dat dau cau thang tang 4 (cao 1.2m)
```

## C3. Vi tri den cau thang

```
Den 1: Tran cau thang giua tang 1 va tang 2
Den 2: Tran cau thang giua tang 2 va tang 3
Den 3: Tran cau thang giua tang 3 va tang 4
```

---

# PHAN D: THANG MAY 3 PHA

```
MCB 3P 32A (tu tong)
  │
  │  Cap 5x6mm2 (3 pha + N + PE)
  │
  ├── PHA A (day do)
  ├── PHA B (day trang)
  ├── PHA C (day xanh)
  ├── NEUTRAL (day den)
  └── PE (day vang xanh) ── noi thanh tiep dia

  *** Day keo tu tang 1 xuong ho thang may (tang ham hoac tang 1) ***
  *** Phai co hop noi rieng cho thang may, do nha cung cap thang may dau noi ***
```

---

# PHAN E: HE THONG TIEP DIA

```
                    COC TIEP DIA (dong xuong dat)
                    │
                    │  Day dong tran 10mm2
                    │
              THANH TIEP DIA CHINH (tang 1, trong tu tong)
                    │
                    ├── PE tu dien tang 1
                    ├── PE tu dien tang 2
                    ├── PE tu dien tang 3
                    ├── PE tu dien tang 4
                    ├── PE thang may
                    └── Noi vo tu dien

    *** Dien tro tiep dia phai < 4 ohm ***
    *** Dung it nhat 2 coc tiep dia, dai 2.4m, cach nhau 3m ***
```

---

# PHAN F: BANG TONG HOP VAT TU

## F1. Tu dien va thiet bi dong cat

```
╔════╦════════════════════════════════════╦══════╦════════╗
║ STT║ Thiet bi                           ║ SL   ║ Ghi chu║
╠════╬════════════════════════════════════╬══════╬════════╣
║ 1  ║ MCB 3P 80A (tu tong)              ║ 1    ║        ║
║ 2  ║ SPD 3P+N 40kA                     ║ 1    ║        ║
║ 3  ║ RCCB 4P 63A 30mA                  ║ 1    ║ Tong   ║
║ 4  ║ MCB 3P 32A (thang may)            ║ 1    ║        ║
║ 5  ║ MCB 1P 32A (tang 1, tang 3, T4)   ║ 3    ║        ║
║ 6  ║ MCB 1P 40A (tang 2)               ║ 1    ║        ║
║ 7  ║ MCB 1P 10A (den cau thang)        ║ 1    ║        ║
║ 8  ║ MCB 1P 20A (dieu hoa, nong lanh)  ║ 16   ║ Nhanh  ║
║ 9  ║ MCB 1P 32A (bep tu)               ║ 1    ║        ║
║ 10 ║ MCB 1P 16A (o cam, may giat/say)  ║ 11   ║        ║
║ 11 ║ MCB 1P 10A (den)                  ║ 8    ║        ║
║ 12 ║ RCCB 1P 25A 30mA (nong lanh)      ║ 7    ║ WC     ║
║ 13 ║ RCCB 1P 16A 30mA (may giat)       ║ 1    ║        ║
╠════╬════════════════════════════════════╬══════╬════════╣
║    ║ TONG MCB/RCCB NHANH               ║ 44   ║        ║
╚════╩════════════════════════════════════╩══════╩════════╝
```

## F2. Day cap dien

```
╔════╦═════════════════════════╦═══════════════╦═════════════════════════════╗
║ STT║ Loai day                 ║ Uoc luong (m) ║ Su dung                     ║
╠════╬═════════════════════════╬═══════════════╬═════════════════════════════╣
║ 1  ║ Cap 4x16mm2 + PE 10mm2 ║ 15            ║ Tu dong ho EVN vao tu tong  ║
║ 2  ║ Cap 5x6mm2             ║ 20            ║ Thang may                   ║
║ 3  ║ Cap 2x6mm2 + PE        ║ 80            ║ Cap tang (4 tang) + bep tu  ║
║ 4  ║ Day 2x4mm2 + PE        ║ 70            ║ Nong lanh (7 cai)           ║
║ 5  ║ Day 2x2.5mm2 + PE      ║ 300           ║ O cam + dieu hoa            ║
║ 6  ║ Day 2x1.5mm2           ║ 200           ║ Den + cong tac              ║
║ 7  ║ Day dong 10mm2         ║ 15            ║ Tiep dia                    ║
╚════╩═════════════════════════╩═══════════════╩═════════════════════════════╝
```

## F3. O cam va cong tac

```
╔════╦════════════════════════════╦══════╦══════════════════════════╗
║ STT║ Thiet bi                    ║ SL   ║ Ghi chu                  ║
╠════╬════════════════════════════╬══════╬══════════════════════════╣
║ 1  ║ O cam doi co PE            ║ ~30  ║ Dat cao 0.3m             ║
║ 2  ║ O cam don dieu hoa         ║ 8    ║ Dat cao 2.2m             ║
║ 3  ║ O cam don nong lanh        ║ 7    ║ Dat cao 1.8m             ║
║ 4  ║ O cam 32A bep tu           ║ 1    ║ Dat cao 0.3m             ║
║ 5  ║ O cam may giat/say         ║ 2    ║ Dat cao 1.2m             ║
║ 6  ║ Cong tac don               ║ ~25  ║ Dat cao 1.2m             ║
║ 7  ║ Cong tac dao chieu         ║ 2    ║ Cau thang T1, T4         ║
║ 8  ║ Cong tac trung gian        ║ 2    ║ Cau thang T2, T3         ║
╚════╩════════════════════════════╩══════╩══════════════════════════╝
```

---

# PHAN G: DO CAO LAP DAT TIEU CHUAN

```
╔═══════════════════════════════╦══════════════════╗
║ Thiet bi                       ║ Do cao (tu san)  ║
╠═══════════════════════════════╬══════════════════╣
║ O cam thuong                   ║ 0.3m             ║
║ O cam ban bep                  ║ 1.1m (tren mat)  ║
║ O cam may giat/say             ║ 1.2m             ║
║ O cam nong lanh                ║ 1.8m             ║
║ O cam dieu hoa                 ║ 2.2m             ║
║ Cong tac den                   ║ 1.2m             ║
║ Tu dien tang                   ║ 1.4m (tam tu)    ║
║ Tu dien tong                   ║ 1.4m (tam tu)    ║
╚═══════════════════════════════╩══════════════════╝
```

---

# PHAN H: LUU Y THI CONG QUAN TRONG

1. **Moi dieu hoa phai co MCB rieng 20A** - khong duoc gop chung
2. **Bep tu phai dung day 6mm2 va MCB 32A** - khong duoc dung day nho hon
3. **Moi binh nong lanh phai co RCCB 30mA rieng** - chong giat dien
4. **May giat nen co RCCB** vi gan nguon nuoc
5. **Tiep dia phai < 4 ohm** - do khi co thang may
6. **Day PE (tiep dia) mau vang-xanh** - bat buoc moi mach
7. **Ong luon day: dung ong PVC D20 cho day den, D25 cho day o cam/dieu hoa**
8. **Khong duoc noi day trong ong** - chi noi tai hop noi hoac o cam
9. **Moi phong WC phai co quat hut** - mach chung voi den WC
10. **Den cau thang dung LED 7-10W** - tiet kiem dien
11. **Cap tang di trong hop gen ky thuat** - tu tang 1 len cac tang tren
12. **Danh so tung mach trong tu dien** - de bao tri sau nay

---
