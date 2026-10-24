# 🎵 Analisis Top 10 Lagu Spotify Indonesia 2025

Mini project pertama saya setelah menyelesaikan **Python Fundamental for Data Science** dari DQLab.

Project ini menganalisis lagu-lagu terpopuler di Spotify Indonesia berdasarkan chart akhir 2025.

### 📊 Tools yang dipakai
- Python
- Pandas (untuk olah data)
- Matplotlib (untuk visualisasi)
- Sumber data: Spotify Charts 2025 via Popnable

### 🔍 Insight yang didapat (Update 2025)
1.  Lagu #1 akhir 2025 adalah **Sedia Aku Sebelum Hujan - Idgitaf** dengan 2.3jt+ daily stream.
2.  Lagu paling konsisten di chart 2025: **Bergema Sampai Selamanya - Nadhif Basalamah** (281 hari di chart) dan **Everything U Are - Hindia**.
3.  Artis **Feast** masih bertahan di Top 10 dengan lagu **Tarot**.
4.  Rata-rata lagu populer 2025 memiliki energy > 0.7, pendengar Indonesia masih suka lagu energetik & galau.

### 💻 Kode Utama
```python
df.sort_values('popularity', ascending=False).head(10)
df['artist'].value_counts()
plt.barh(df['track_name'], df['popularity'])
### 🔗 Sertifikat
[📄 Lihat Sertifikat DQLab Saya - Python Fundamental](intandqlab.pdf)
