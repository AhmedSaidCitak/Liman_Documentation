# İkinci Sunucunun Liman'a Eklenmesi ve Migrate İşleminin Yapılması

İkinci bir sunucuyu limana ekleyip samba eklentisinin hazır hale getirilmesi için;

1. **Sanal Makine Kurulumu (Virtual Box).md**

2. **Liman'a Sunucu Ekleme.md**

3. **Sambahvl Eklentisinin Sunucuya Yüklenmesi.md / Sambahvl Eklentisinin Sunucuya Eklenmesi**

4. **SambaHVL Paketini Kurma.md**

   aşamalarının tamamlanması gerekiyor.


**SambaHVL** paketinin kurulumu da tamamlandıktan sonra karşımıza çıkan ekrandan **Migration İşlemleri** altındaki **Migrate Et** butonuna basarak **migration** işlemini başlatmış oluyoruz.

<img src="/assets/Migration_1.png">



Açılan penceredeki **IP adresi** kısmına migrate edilecek olan sunucunun IP adresini yazıyoruz.

**Kullanıcı adı** kısmına **Administrator**,

**Parola** kısmına da migrate edilecek olan **etki alanının parolasını** yazıyoruz ve **Bağlantıyı Kontrol Et** butonuna tıklıyoruz.

<img src="/assets/Migration_2.png">



Sıradaki aşama olarak **Etki alanımız** içerisindeki **Site Seçimini** tamamlıyoruz ve **migration** işlemini başlatıyoruz.

<img src="/assets/Migration_3.png">



**Migration işlemi** başladıktan sonra süreci takip etmek için ekrana yazılan **log kayıtlarını** inceleyebiliriz.

<img src="/assets/Migration_4.png">



Migration işlemi bittikten sonra **Başarılı** uyarısını alıyorsak **migration** işlemini başarılı bir şekilde tamamlamışız demektir.

<img src="/assets/Migration_5.png">



Sunucumuzu **Etki alanına** başarılı bir şekilde **migrate** etmiş olduk. 

Daha farklı konularda işlem yapmak veya bilgi almak için eklentide bulunan **tabları** inceleyebiliriz

<img src="/assets/Migration_6.png">



**Kullanıcılar** tabına geldiğimiz zaman **Bağlantı Sertifikası** hatası verecektir. Sertifika eklemek için belirtilen alana tıklıyoruz.

<img src="/assets/Migration_7.png">



 Sistem bizi **Sertifika Ekleme** bölümüne yönlendiriyor. 

<img src="/assets/Migration_8.png">



Burada Önce **Al** butonuna basıyoruz.

<img src="/assets/Migration_9.png">



 Daha sonra da **Sertifikayı Onayla** butonuna basarak **Sertifika Ekleme** işlemini tamamlıyoruz.

<img src="/assets/Migration_10.png">



Sertifikamız başarıyla eklendikten sonra **İkinci Samba sunucumuza** dönebiliriz ve **Kullanıcılar** tabında bilgileri görüntüleyebiliriz.

<img src="/assets/Migration_11.png">

