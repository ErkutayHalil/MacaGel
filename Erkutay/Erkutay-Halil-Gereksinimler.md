1. **Maç Kartlarını Alma**
   - **API Metodu:** `GET /maca-gel/getMatches`
   - **Açıklama:** Kullanıcıya mevcuttaki maçların verilerini çekip, kartlara yerleştirir.
2. **Yaklaşan Maçlar**
   - **API Metodu:** `GET /maca-gel/upcomingMatch`
   - **Açıklama:** Kullanıcının yaklaşmakta olan maçlarını gösterir.

3. **Üye Olma**
   - **API Metodu:** `POST /maca-gel/register`
   - **Açıklama:** Kullanıcıların yeni hesaplar oluşturarak sisteme kayıt olmasını sağlar. Kişisel bilgilerin toplanmasını ve hesap oluşturma işlemlerini içerir. Kullanıcılar email adresi ve şifre belirleyerek hesap oluşturur.

4. **Maçtaki Pozisyona Katılma**
   - **API Metodu:** `POST /maca-gel/joinPosition`
   - **Açıklama:** Kullanıcı maçta boş gözüken pozisyonlardan birine katılır.

5. **Profili Güncelleme**
   - **API Metodu:** `PUT /maca-gel/updateProfile`
   - **Açıklama:** Kullanıcının, kullanıcı adı, telefon numarası, profil fotosu ve e-mail adresi güncellenir.

6. **Hesabı Silme**
   - **API Metodu:** `DELETE /maca-gel/deleteAccount`
   - **Açıklama:** Kullanıcının hesabını sistemden kalıcı olarak silmesini sağlar. Kullanıcı hesabını kapatmak istediğinde veya yönetici tarafından hesap kapatılması gerektiğinde kullanılır. Bu işlem geri alınamaz ve kullanıcının tüm verileri silinir. Güvenlik için giriş yapmış olmak gerekir.