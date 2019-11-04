# Pemeriksaan ejaan bahasa Nias

In English: spell check dictionary for Nias language.

Ada dua file utama di folder ini: nia_NIA.dic dan nia_NIA.aff.

**nia_NIA.dic** berisi kata-kata yang dikumpulkan oleh hunspell kala memeriksa teks, sedangkan **nia_NIA.aff** berisi aturan pemenggalan kata dalam bahasa Nias.

Untuk memeriksa teks dan menyuruh hunspell menyimpan kata-kata dalam kamus nia_NIA.dic jalankan perintah berikut di *command line* di dalam folder ini:

```
hunspell -p ./nia_NIA.dic -d ./nia_NIA.dic NAMA_FILE_TEKS
```

Misalnya untuk memeriksa ejaan teks bernama *harumani.txt*:

```
hunspell -p ./nia_NIA.dic -d ./nia_NIA.dic harumani.txt
```

## Syarat untuk menggunakan

Silakan instalasi **hunspell** di komputer Anda. Paling gampang di *command line* di Ubuntu Linux:

```
sudo apt install hunspell
```


