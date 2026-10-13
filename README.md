# Tugas Algoritma Bebas
## Algoritma Menentukan Lulus atau Tidak Lulus Siswa
Seorang guru ingin menentukan lulus atau tidaknya mahasiswa dengan syarat jika nilai siswa yang ia didik diatas atau sama dengan 75 makan siswa yang dinilai akan dinyatakan lulus jika nilai siswa dibawah 75 akan dinyatakan tidak lulus.

### Analisis
- Variable: nilai
  
### Algoritma Deskriptif
1. Mulai
2. Tentukan nilai siswa
3. Apabila siswa memiliki nilai diatas atau sama dengan 75 maka siswa tersebut dinyatakan LULUS
4. Apabila siswa memiliki nilai dibawah 75 maka siswa tersebut dinyatakan TIDAK LULUS
5. Selesai

### Algoritma Flowchart
```mermaid
  flowchart TD
    start@{ shape: circle, label: "Start" }
    inputNilai@{ shape: lean-r, label: "nilai" }
    if@{ shape: diamond, label: "nilai >= 75" }
    outputLulus@{ shape: lean-r, label: "#quot;Lulus#quot;" }
    outputTidakLulus@{ shape: lean-r, label: "#quot;Tidak Lulus#quot;" }
    stop@{ shape: dbl-circ, label: "Stop" }

    start --> inputNilai
    inputNilai --> if
    if --tidak--> outputTidakLulus
    if --yes--> outputLulus
    outputLulus & outputTidakLulus --> stop
```

### Pseudo-code
```
DECLARE nilai : INTEGER
INPUT nilai
IF nilai >= 75 THEN
    OUTPUT "Lulus"
ELSE
    OUTPUT "Tidak Lulus"
ENDIF
```
