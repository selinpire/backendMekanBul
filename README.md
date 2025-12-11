# Mekanbul Backend

**Demo:** https://backend-mekan-bul-fjhr.vercel.app/

Bu repo mekanbul—backend uygulamasının basit Node.js + Express + Mongoose backend'idir.

## Kısa Açıklama

- API, mekan (venue) verilerini yönetir: listeleme, ekleme, görüntüleme, güncelleme ve silme.
- MongoDB Cloud kullanır. Bağlantı bilgisi için `app_api/models/db.js` dosyasına bakın.

## Kurulum
```bash
cd /path/to/backend
npm install

```
## Uygulamayı Çalıştırma
```bash
npm start
```


## API Endpoints

- **Tüm mekanları listele:** GET /api/venues
- **Yeni mekan ekle:** POST /api/venues
- **Mekan detayını getir:** GET /api/venues/:venueid
- **Mekanı güncelle:** PUT /api/venues/:venueid
- **Mekanı sil:** DELETE /api/venues/:venueid
- **Yorum ekle (mekana):** POST /api/venues/:venueid/comments
- **Yorum getir:** GET /api/venues/:venueid/comments/:commentid
- **Yorum güncelle:** PUT /api/venues/:venueid/comments/:commentid
- **Yorum sil:** DELETE /api/venues/:venueid/comments/:commentid

---

## Postman Test Sonuçları

Aşağıda Postman ile alınmış test sonuçlarının ekran görüntüleri bulunmaktadır:

![](./tests/AddComment.png)
![](./tests/AddVenue.png)
![](./tests/DeleteComment.png)
![](./tests/DeleteVenue.png)
![](./tests/GetComment.png)
![](./tests/GetVenue.png)
![](./tests/ListNearbyVenues.png)
![](./tests/UpdateComment.png)
![](./tests/UpdateVenue.png)







