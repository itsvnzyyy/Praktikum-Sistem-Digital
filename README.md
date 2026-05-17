# Praktikum 8 Logic Gate Tinkercad

## 👥 Anggota Kelompok

* **Alvin Syahrinaldi (H1H025040)** 
* **Haiza Aydin Saputra (H1H025045)** 
* **Zakka Ibrahim Izzandra (H1H025046)**

---

# 🚀 Apa itu Tinkercad?

Tinkercad merupakan platform simulasi elektronik berbasis web yang dapat digunakan untuk merancang dan menguji rangkaian digital maupun analog secara virtual. Simulasi ini bertujuan untuk memahami prinsip kerja gerbang logika digital serta cara menghubungkan input dan output pada sebuah rangkaian. Tinkercad dapat digunakan untuk mengimplementasikan berbagai gerbang logika dasar menggunakan IC TTL seri 74HC dengan output berupa LED. Setiap gerbang diuji menggunakan switch (saklar) input dan LED sebagai indikator output. LED akan menyala atau mati sesuai dengan hasil operasi logika dari masing-masing gerbang.

---

## 🔌 Hasil dan Analisis Praktikum

### 1. Gerbang AND
* **Prinsip Kerja**: Output akan bernilai 1 hanya jika kedua input (A dan B) bernilai 1.
* **Komponen Rangkaian**: Power Supply DC, IC 74HC08, LED, Resistor, dan DIP Switch.
* **Tabel Kebenaran**:
  | A | B | Output |
  |---|---|--------|
  | 0 | 0 | 0      |
  | 0 | 1 | 0      |
  | 1 | 0 | 0      |
  | 1 | 1 | 1      |

**Dokumentasi Rangkaian:**

<img width="287" height="257" alt="image" src="https://github.com/user-attachments/assets/5ce27741-ad0c-42b1-9e3b-e459d5db42c1" />

---

### 2. Gerbang OR
* **Prinsip Kerja**: Output akan bernilai 1 jika salah satu atau kedua input (A dan B) bernilai 1.
* **Komponen Rangkaian**: Power Supply DC, IC 74HC32, LED, Resistor, dan DIP Switch.
* **Tabel Kebenaran**:
  | A | B | Output |
  |---|---|--------|
  | 0 | 0 | 0      |
  | 0 | 1 | 1      |
  | 1 | 0 | 1      |
  | 1 | 1 | 1      |

**Dokumentasi Rangkaian:**

<img width="287" height="261" alt="image" src="https://github.com/user-attachments/assets/1fb5e593-b0af-440d-b42c-e9f9554bd883" />

---

### 3. Gerbang NOT
* **Prinsip Kerja**: Berfungsi sebagai pembalik, di mana output akan selalu berkebalikan dengan nilai inputnya.
* **Komponen Rangkaian**: Power Supply DC, IC 74HC04, LED, Resistor, dan DIP Switch.
* **Tabel Kebenaran**:
  | A | Output |
  |---|--------|
  | 0 | 1      |
  | 1 | 0      |

**Dokumentasi Rangkaian:**

<img width="287" height="265" alt="image" src="https://github.com/user-attachments/assets/20256221-df9d-4234-bc6d-1f7fece65247" />

---

### 4. Gerbang NAND
* **Prinsip Kerja**: Output akan bernilai 0 hanya jika kedua input (A dan B) bernilai 1.
* **Komponen Rangkaian**: Power Supply DC, IC 74HC00, LED, Resistor, dan DIP Switch.
* **Tabel Kebenaran**:
  | A | B | Output |
  |---|---|--------|
  | 0 | 0 | 1      |
  | 0 | 1 | 1      |
  | 1 | 0 | 1      |
  | 1 | 1 | 0      |

**Dokumentasi Rangkaian:**

<img width="299" height="250" alt="image" src="https://github.com/user-attachments/assets/76907bdb-216b-47e4-b48b-a5fae8666a3d" />

---

### 5. Gerbang NOR
* **Prinsip Kerja**: Output akan bernilai 1 hanya jika kedua input (A dan B) bernilai 0.
* **Komponen Rangkaian**: Power Supply DC, IC 74HC02, LED, Resistor, dan DIP Switch.
* **Tabel Kebenaran**:
  | A | B | Output |
  |---|---|--------|
  | 0 | 0 | 1      |
  | 0 | 1 | 0      |
  | 1 | 0 | 0      |
  | 1 | 1 | 0      |

**Dokumentasi Rangkaian:**

<img width="299" height="275" alt="image" src="https://github.com/user-attachments/assets/b24f5b0c-c9cb-4383-bdfe-eb231d467381" />

---

### 6. Gerbang XOR
* **Prinsip Kerja**: Output akan bernilai 1 jika kedua input (A dan B) memiliki nilai logika yang berbeda.
* **Komponen Rangkaian**: Power Supply DC, IC 74HC86, LED, Resistor, dan DIP Switch.
* **Tabel Kebenaran**:
  | A | B | Output |
  |---|---|--------|
  | 0 | 0 | 0      |
  | 0 | 1 | 1      |
  | 1 | 0 | 1      |
  | 1 | 1 | 0      |

**Dokumentasi Rangkaian:**

<img width="311" height="279" alt="image" src="https://github.com/user-attachments/assets/89186d5b-6cef-4989-8d13-ac11fa0bfec2" />

---

## 7. Gerbang XNOR
* **Prinsip Kerja**: Output akan bernilai 1 jika kedua input (A dan B) memiliki nilai logika yang sama.
* **Komponen Rangkaian**: Power Supply DC, IC 74HC86, IC 74HC04, LED, Resistor, dan DIP Switch.
* **Tabel Kebenaran**:
  | A | B | Output |
  |---|---|--------|
  | 0 | 0 | 1      |
  | 0 | 1 | 0      |
  | 1 | 0 | 0      |
  | 1 | 1 | 1      |

**Dokumentasi Rangkaian:**

<img width="311" height="245" alt="image" src="https://github.com/user-attachments/assets/0244fe38-fc02-4577-9f01-8bc41ac2c96d" />

---

## 🎯 Kesimpulan

Berdasarkan percobaan gerbang logika yang telah dilakukan menggunakan Tinkercad, karakteristik dan prinsip kerja masing-masing gerbang logika terbukti sesuai dengan teori tabel kebenarannya. Secara keseluruhan, simulasi rangkaian ini berhasil membuktikan prinsip kerja dari ketujuh gerbang logika dasar tersebut.


## 🔗 Link Project Tinkercad
[Project Tinkercad - Logic Gate](https://www.tinkercad.com/things/jmOffzZUeEj-logic-gate-thinkercad)
