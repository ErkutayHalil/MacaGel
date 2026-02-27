1. **Maçtaki Kişilerin Bilgisini Çekme**
   - **API Metodu:** `GET /maca-gel/getMatchPlayers`
   - **Açıklama:** Kişinin Seçtiği maç kartında bulunan kişileri sayfa açılırken çeker.

2. **Arkadaşlarımı Göster**
   - **API Metodu:** `GET /maca-gel/myFriends`
   - **Açıklama:** Kullanıcının arkadaş olduğu kişileri gösterir.

3. **Giriş Yapma**
   - **API Metodu:** `PUT /maca-gel/login`
   - **Açıklama:** Kullanıcı Girişini yapar(BenimId'm ile Benim Name'im dönecek)

4. **Arkadaş Ekle**
   - **API Metodu:** `POST /maca-gel/addFriend`
   - **Açıklama:** Arkadaş olma istegi atar.

5. **Maça Kod İle Katıl**
   - **API Metodu:** `PUT /maca-gel/inviteCode`
   - **Açıklama:** Kullanıcı girdigi Kod ile ilgili koddaki maça katılır.

6. **Maçtan Çıkart**
   - **API Metodu:** `DELETE /maca-gel/quite`
   - **Açıklama:** Yöneticinin Kick işlemi ile Kullanıcının Çıkış işleminin isteğini yapar (DB'den tek satır siler, matchId ile userId(çıkıcak olan/atılacak olan kişinin) gönderilir)
