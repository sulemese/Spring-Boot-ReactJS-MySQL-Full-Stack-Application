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
/users

/users/{userId}

/users/{userId}/profile

#
/posts

/posts?user={userId}

/posts/{postId}


#
/comments

/comments?postId={postId}

/comments?user={userId}

comments/{commentId}

#
/likes

/likes?postId={postId}

/likes?user={userId}

likes/{likeId}


# Backend Teknolojileri
Spring Boot

# Frontend Teknolojileri
ReactJS

# Kullanılan IDE
Visual Studio Code

Eclipse

# Arayüz
Mysql Workbench 
