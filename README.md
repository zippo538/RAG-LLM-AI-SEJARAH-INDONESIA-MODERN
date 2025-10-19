## RAG & LLM AI SEJARAH INDONESIA MODERN
<br>

**Deskripsi Proyek**

Proyek ini adalah implementasi sistem Question Answering (Tanya Jawab) berbasis Kecerdasan Buatan (AI) yang secara khusus berfokus pada Sejarah Indonesia Modern.

Kami memanfaatkan arsitektur Retrieval-Augmented Generation (RAG) yang dikombinasikan dengan Large Language Model (LLM) untuk menghasilkan jawaban yang akurat, informatif, dan terverifikasi berdasarkan korpus dokumen sejarah yang telah disediakan.

<br>

**Tujuan**
Tujuan utama dari proyek ini adalah:

1. **Menyediakan Jawaban yang Terverifikasi**: Mengatasi masalah halusinasi pada LLM dengan memastikan semua jawaban didukung oleh kutipan dari dokumen sumber (buku-buku sejarah) yang tersedia di repositori.

2. **Membangun Sumber Daya Pembelajaran Interaktif**: Menciptakan alat yang dapat digunakan untuk eksplorasi dan pembelajaran mendalam mengenai Sejarah Indonesia Modern.

3. **Demonstrasi RAG dalam Konteks Lokal**: Menunjukkan efektivitas penggunaan teknologi RAG untuk informasi spesifik berbahasa Indonesia dan topik lokal.

**Teknologi yang Digunakan**
- **Arsitektur**: Retrieval-Augmented Generation (RAG)
- **Inti Pemrosesan Bahasa**: Large Language Model (LLM)
- **Penyimpanan Vektor**: (Tergantung implementasi di main.ipynb, tambahkan jika sudah ada: misal ChromaDB, FAISS, dll.)
- **Bahasa Pemrograman**: Python
- **Lingkungan Pengembangan**: Jupyter Notebook (main.ipynb)

<br>

**Cara Menjalankan**
1. Kloning Repositori : 
```
git clone https://github.com/zippo538/RAG-LLM-AI-SEJARAH-INDONESIA-MODERN.git
cd RAG-LLM-AI-SEJARAH-INDONESIA-MODERN
```
2. Instalansi Dependensi :
```
pip install -r requirements.txt
```
3. Konfigurasi variabel lingkungan :
- Duplikat dan ganti nama `.env.example` menjadi `.env`
- Isi file `.env` dengan kunci API LLM yang valid   
4. Jalankan notebook : <br>
  Buka `main.ipynb` dan ikuti langkah-langkah di dalamnya untuk memproses data, membuat vector store, dan mulai berinteraksi dengan model AI. 
   
  
