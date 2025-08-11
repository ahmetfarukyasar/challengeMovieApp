
# challengeMovieApp

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  
[![React Version](https://img.shields.io/badge/React-18.2.0-blue)](https://reactjs.org/)

**challengeMovieApp**, TMDB API kullanarak film verilerini listeleyen, detaylarını gösteren ve kullanıcıların favori filmlerini yönetebildiği modern bir React uygulamasıdır.  
Kullanıcı dostu arayüzü, filtreleme ve favorilere ekleme gibi özellikleriyle film keşfetmeyi kolaylaştırır.

---

## İçindekiler

- [Özellikler](#özellikler)  
- [Kurulum](#kurulum)  
- [Kullanım](#kullanım)  
- [Teknolojiler](#teknolojiler)  
- [API Anahtarı](#api-anahtarı)  
- [Katkıda Bulunma](#katkıda-bulunma)  
- [Lisans](#lisans)  

---

## Özellikler

- Popüler filmleri listeleme  
- Film detaylarını görüntüleme (özeti, çıkış tarihi, vb.)  
- Film türlerine göre filtreleme  
- Yıllara göre filtreleme  
- Favori filmleri ekleyip çıkartma  
- Responsive ve hızlı arayüz  
- Çevresel değişkenler ile API anahtarı yönetimi  

---

## Kurulum

Projeyi yerel ortamınıza klonlayın:

```bash
git clone https://github.com/ahmetfarukyasar/challengeMovieApp.git
cd challengeMovieApp
```

Gerekli bağımlılıkları yükleyin:

```bash
npm install
```

`.env` dosyasını oluşturun ve TMDB API anahtarınızı ekleyin:

```env
VITE_API_KEY=your_tmdb_api_key_here
```

Projeyi başlatın:

```bash
npm run dev
```

Tarayıcınızda `http://localhost:5173` adresine giderek uygulamayı görüntüleyebilirsiniz.

---

## Kullanım

- Ana sayfada popüler filmler listelenir.  
- Film kartlarına tıklayarak detay sayfasına geçebilirsiniz.  
- Sağ üstteki filtre alanlarından tür ve yıl seçerek listeyi daraltabilirsiniz.  
- Her film kartındaki kalp simgesine tıklayarak favorilerinize ekleyebilirsiniz. Favoriler context ile yönetilmektedir.  

---

## Teknolojiler

- React 18  
- Vite (React build tool)  
- Tailwind CSS  
- Axios (HTTP istemcisi)  
- React Router  
- React Context API  
- TMDB (The Movie Database) API  

---

## API Anahtarı

Bu proje TMDB API’sini kullanmaktadır.  
TMDB API anahtarınızı [https://www.themoviedb.org/](https://www.themoviedb.org/) adresinden ücretsiz olarak alabilirsiniz.  
Anahtarı `.env` dosyasına `VITE_API_KEY` olarak eklemeyi unutmayınız.

---

## Katkıda Bulunma

Projeye katkı yapmak isterseniz, lütfen şu adımları takip edin:

1. Forklayın ve yerel kopyanızı oluşturun.  
2. Yeni bir branch açın (`git checkout -b feature/özellik-adi`).  
3. Değişikliklerinizi commit edin (`git commit -m 'Yeni özellik eklendi'`).  
4. Branch’e pushlayın (`git push origin feature/özellik-adi`).  
5. Pull request gönderin.  

Her türlü öneri ve hatalar için issue açabilirsiniz.

---

## Lisans

Bu proje MIT Lisansı altında lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasına bakabilirsiniz.

---

**ahmetfarukyasar** © 2025
