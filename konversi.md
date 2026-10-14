# Pekerjaan Rumah
membuat algoritma untuk konversi suku, tapi inputnya hanya 1 yaitu dari Celsius tapi untuk hasilnya ketiga satuan besar lainya (kelvin, Fahrenheit, reamour)

### Algoritma Deskriptif
 1. Mulai
 2. Tentukan nilai Celsius yang mau dikonversi
 3. untuk konversi Celsius ke kelvin bisa dengan cara celsius ditambah 273,15
 4. untuk konversi Celsius ke fahrenheit bisa dengan cara 9 per 5 dikali celcius kemudian ditambah 32
 5. untuk konversi Celsius ke reamur bisa dengan cara 4 per 5 kemudian dikali celcius
 6. cetak hasil konversi
 7. selesai
    
### Algoritma Flowchart
``` mermaid
flowchart TD
    A@{ shape: circle, label: "Start" }
    B@{ shape: lean-r, label: "C" }
    C@{ shape: rect, label: "K = C + 273.15" }
    D@{ shape: rect, label: "F = (9/5 * C) + 32" }
    E@{ shape: rect, label: "R = (4/5) * C" }
    F@{ shape: lean-r, label: "K" }
    G@{ shape: lean-r, label: "F" }
    H@{ shape: lean-r, label: "R" }
    I@{ shape: dbl-circ, label: "Stop" }

    A --> B
    B --> C
    C --> D
    D --> E
    E --> F
    F --> G
    G --> H
    H --> I
  
```
### Pseudo-code

```
DECLARE C : REAL
DECLARE K : REAL
DECLARE F : REAL
DECLARE R : REAL

INPUT C

K <- C + 273.15
F <- (9/5 * C) + 32
R <- (4/5) * C

OUTPUT K
OUTPUT F
OUTPUT R

```
