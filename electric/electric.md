
# SO DO DIEN NHA 4 TANG CO THANG MAY (3 PHA)

Ngay tao: 2026-03-14

---

# 1. Tong quan he thong

Nha 4 tang + mai (dat cuc nong dieu hoa)
Co thang may 3 pha 450kg

Nguon dien: 3 pha A B C + N + PE

Phan bo pha de can bang tai:

PHA A -> Tang 1 + bep tu  
PHA B -> Tang 2  
PHA C -> Tang 3 + Tang 4  
3 PHA ABC -> Thang may

---

# 2. Cau truc tu dien tong

EVN
 ↓
MCB TONG 3P 80A
 ↓
SPD CHONG SET
 ↓
RCCB 4P 63A 30mA
 ↓
Thanh bus pha A B C
Thanh bus N
Thanh tiep dia PE
 ↓
MCB cac nhanh

- MCB 3P 32A -> Thang may
- MCB 1P 32A -> Tang 1 (pha A)
- MCB 1P 40A -> Tang 2 (pha B)
- MCB 1P 32A -> Tang 3 (pha C)
- MCB 1P 32A -> Tang 4 (pha C)

---

# 3. ASCII so do tong

```

EVN 3P
  │
  ├── MCB TONG 3P 80A
  │
  ├── SPD CHONG SET
  │
  ├── RCCB 4P 63A 30mA
  │
  ├── BUS PHA A ── MCB 32A ── TANG 1 + BEP TU
  │
  ├── BUS PHA B ── MCB 40A ── TANG 2
  │
  ├── BUS PHA C ── MCB 32A ── TANG 3
  │                │
  │                └── MCB 32A ── TANG 4
  │
  └── MCB 3P 32A ── THANG MAY 3 PHA

```

---

# 4. Tiet dien day khuyen nghi

Den: 1.5 mm2  
O cam: 2.5 mm2  
Dieu hoa: 2.5 - 4 mm2  
Nong lanh: 4 mm2  
Bep tu: 6 mm2  
Thang may: 5x6 mm2  
Cap tang: 2x6 mm2 + PE  
Cap tong: 4x16 mm2

---

# 5. So do dien tang 1 (PHA A)

Tai tang 1:
- 2 dieu hoa
- bep tu
- 1 nong lanh

ASCII:

```
MCB 32A
 │
 ├── MCB 20A ── DIEU HOA 1
 │
 ├── MCB 20A ── DIEU HOA 2
 │
 ├── MCB 32A ── BEP TU
 │
 ├── MCB 20A ── NONG LANH
 │
 ├── MCB 16A ── O CAM PHONG KHACH
 │
 └── MCB 10A ── DEN
```

---

# 6. So do tang 2 (PHA B)

Tai tang 2:
- 3 dieu hoa
- 3 nong lanh

```
MCB 40A
 │
 ├── MCB 20A ── DIEU HOA 1
 ├── MCB 20A ── DIEU HOA 2
 ├── MCB 20A ── DIEU HOA 3
 │
 ├── MCB 20A ── NONG LANH 1
 ├── MCB 20A ── NONG LANH 2
 ├── MCB 20A ── NONG LANH 3
 │
 └── MCB 10A ── DEN + O CAM
```

---

# 7. So do tang 3 (PHA C)

```
MCB 32A
 │
 ├── MCB 20A ── DIEU HOA 1
 ├── MCB 20A ── DIEU HOA 2
 │
 ├── MCB 20A ── NONG LANH 1
 ├── MCB 20A ── NONG LANH 2
 │
 └── MCB 10A ── DEN + O CAM
```

---

# 8. So do tang 4 (PHA C)

```
MCB 32A
 │
 ├── MCB 20A ── DIEU HOA
 │
 ├── MCB 20A ── NONG LANH
 │
 ├── MCB 16A ── MAY GIAT
 │
 ├── MCB 16A ── MAY SAY
 │
 └── MCB 10A ── DEN + O CAM
```

---

# 9. So do thang may

```
MCB 3P 32A
 │
 └── THANG MAY
      │
      ├── PHA A
      ├── PHA B
      ├── PHA C
      ├── NEUTRAL
      └── PE (TIEP DIA)
```

---

# 10. Cong tac dao chieu den cau thang

Dung 2 cong tac dao chieu

```
PHA
 │
SW1
 │  ╲
 │   ╲
 │    ╲
 │    ╱
 │   ╱
 │  ╱
SW2
 │
DEN
 │
NEUTRAL
```

Cho phep bat tat den tu 2 dau cau thang.

---

# 11. Luu y quan trong

1. Tat ca dieu hoa nen co CB rieng.
2. Bep tu phai day 6mm2.
3. Nha co thang may nen lam tiep dia tot (<4 ohm).
4. Nen co SPD chong set.
5. Nen tach CB tung tang de sua chua de dang.
6. Tat ca o cam phong tam nen qua RCCB.

---
