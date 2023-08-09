# Proje Açıklaması
->Üyeler soru sorup post paylaşabilirler. Kendi Profillerini görüntüleyebilirler. Siteye üye olabilirler. Bu site anasayfa ve profil panelinden oluşur. 

->Anasayfada üyelerin paylaştığı postların listelenir.Her postta içerik, beğeni sayısı, yorum sayısı yer alır.

->Profil sayfası üyenin kendi bilgilerinin yer aldığı sayfadır. Profil sayfasında üyenin seçtiği avatar, kullanıcı adı, leveli , attığı yorum sayısı, beğeni sayısı, bildirimler paneli, son atılan post paneli vb. yer almaktadır. 

# Proje Gereksinimleri
Üyeler üye olabilmeliler.

Üyeler giriş yapabilmeliler.

Üyeler post atabilmeliler.

Üyeler postlara yorum atabilmeliler.

Üyeler postlara beğeni atabilmeliler.

Sistem üyelere mesaj iletebilmeli.

Sistem 7/24 %1'den az bir down ile ayakta olmalıdır. 

# API Design
/users                      (tüm üyeler)

/users/{userId}             (belirli bir üye)

/users/{userId}/profile

#
/posts                       (tüm postlar)

/posts?user={userId}         (belirli bir üyenin tüm postları)

/posts/{postId}              (belirli bir post)


#
/comments                    (Tüm yorumlar)

/comments?postId={postId}    (Belirli bir postun tüm yorumları)

/comments?user={userId}      (Belirli bir üyenin tüm yorumları)

comments/{commentId}         (Belirli bir yorum)

#
/likes                       (Tüm beğeniler)

/likes?postId={postId}       (Belirli bir postun tüm beğenileri)

/likes?user={userId}         (belirli bir üyenin tüm beğenileri)

likes/{likeId}               (Belirli bir beğeni)


# Backend Teknolojileri
Spring Boot

# Frontend Teknolojileri
ReactJS

# Kullanılan IDE
Visual Studio Code

Eclipse

# Arayüz
Mysql Workbench 
