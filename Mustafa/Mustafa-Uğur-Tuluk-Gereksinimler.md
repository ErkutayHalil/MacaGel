1. **Maç Geçmişi**
   - **API Metodu:** `GET /maca-gel/matchHistory`
   - **Açıklama:** Kullanıcının geçmişte oynadığı maçları gösterir.

2. **Oyuncu Önizlemesi**
   - **API Metodu:** `GET /maca-gel/playerPreview/me`
   - **Açıklama:** Kendi oyun detaylarını gösterir (yıldız, maç sayısı...)

3. **Maç Kartı Oluştur**
   - **API Metodu:** `POST /maca-gel/createMatch`
   - **Açıklama:** Kullanıcı maç kartını oluşturur.

4. **Maç Kartını Güncelle**
   - **API Metodu:** `PUT /maca-gel/updateMatch`
   - **Açıklama:** Kullanıcı maç kartında değişim yapar (maç adı, kişi sayısı...)

5. **Maç Kartını Sil**
   - **API Metodu:** `DELETE /maca-gel/deleteMatch`
   - **Açıklama:** Önceden oluşturulmuş ama henüz oynanmamış maçı siler.

6. **Arkadaş Silme**
   - **API Metodu:** `DELETE /maca-gel/myFriends`
   - **Açıklama:** Arkadaşı, arkadaş listesinden çıkartır (silenin ve silinenin ID'si gönderilecek)