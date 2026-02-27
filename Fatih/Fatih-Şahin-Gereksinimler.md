1. **Profilim**
   - **API Metodu:** `GET /maca-gel/users/me`
   - **Açıklama:** Kullanıcı kişisel bilgilerini buradan görüntüler.(Kullanıcı Adı, e-mail, telefon numarası, ...)

2. **Şifremi Unuttum**
   - **API Metodu:** `POST /maca-gel/isForgotPassword`
   - **Açıklama:** Mail sayfasına gider, mailini verir. Biz de ona şifre değişme sayfası veririz.

3. **Şifremi Değiştir**
   - **API Metodu:** `PUT /maca-gel/passwordChange`
   - **Açıklama:** Şifre değiştirme isteği atar.

4. **Yıldız/Yorum atma**
   - **API Metodu:** `POST /maca-gel/rating/{userID}`
   - **Açıklama:** Kullanıcı başka bir kullanıcıya yorum ve yıldız verir.
   
5. **Yıldız/Yorum Güncelleme**
   - **API Metodu:** `PUT /maca-gel/rating/{rateID}`
   - **Açıklama:** Kullanıcı daha önce attığı yorumu ve yıldız puanını günceller.

6. **Yıldız/Yorum Silme**
   - **API Metodu:** `DELETE /maca-gel/rating/{rateID}`
   - **Açıklama:** Kullanıcı daha önce atmış olduğu yorumu ve yıldız puanını siler.

