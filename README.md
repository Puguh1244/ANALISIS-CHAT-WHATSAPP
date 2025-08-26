# 📊 Analisis Chat WhatsApp (2 Partisipan)

Project ini menganalisis percakapan WhatsApp antara **dua orang** (Via & Puguh) 
untuk menemukan pola komunikasi, konsistensi balasan, serta tema percakapan.

---

## 🎯 Tujuan
1. Mengetahui **pola intensitas chat** berdasarkan waktu (jam & hari).  
2. Menganalisis **partisipasi tiap orang** → siapa lebih aktif, siapa lebih cepat membalas.  
3. Mengelompokkan **tema percakapan** (kategori: percintaan, formal, dll).  
4. Menggali insight dari **hubungan interaksi** antar kedua partisipan.  

---

## 📂 Data
- Sumber: **Ekspor Chat WhatsApp** (tanpa media)  
- Jumlah pesan: ± **54.581**  
- Periode: **Januari – Agustus 2025**  

---

## 🔎 Analisis Utama

### ⏰ Pola Waktu
- **Jam tersibuk**: pukul **21.00 WIB**  
- **Hari tersibuk**: **Senin & Jumat**  
- **Jam paling sepi**: pukul **03.00 WIB** (dini hari)  
- **Hari paling sepi**: **Sabtu**  

### 👥 Analisis Partisipan
- **Via** lebih cepat & konsisten dalam membalas (median ±1 menit)  
- **Puguh** sering slow respon ekstrem (hingga 2,5 hari)  
- Volume balasan hampir **seimbang** (±218 balasan per orang)  

### 💬 Tema Percakapan
Hasil eksplorasi kata kunci menunjukkan tema dapat dibagi menjadi:
- ❤️ **Percintaan** → sapaan mesra, emotikon, candaan personal  
- 📚 **Formal/Organisasi** → nilai, tugas, rekapan, lomba  
- 🎉 **Kasual/Entertainment** → IG reels, wkwk, obrolan santai  

---

## 📈 Insight
- Percakapan **terbanyak malam hari** → menandakan obrolan dilakukan di waktu pribadi.  
- Hubungan komunikasi **dua arah**, meski kecenderungan slow respon lebih banyak di sisi **Puguh**.  
- Tema obrolan **bercampur** antara hal formal (tugas, organisasi) dan personal (percintaan).  
- Menunjukkan adanya **kedekatan hubungan** yang tidak sekadar formal, tetapi juga emosional.  

---

## 🛠️ Tools
- Python (pandas, matplotlib, seaborn, plotly)  
- Analisis teks dasar (regex, word frequency)  
- Visualisasi data interaktif  

---

## 📌 Next Step
- Membuat **word cloud** untuk tema percakapan  
- Analisis **sentimen** (positif/negatif)  
- Deteksi otomatis **kategori topik** dengan NLP sederhana  

