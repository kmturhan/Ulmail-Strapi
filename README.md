# Strapi application

A quick description of your strapi application

# Kullanım 

"npm run start strapi develop" terminal'de bunu kullanarak Strapi'yi development modunda geliştirme yapılabilecek modda çalıştırabiliriz.

Strapi default 1337 portunda çalışıyor.

ilk açılışta "http://localhost:1337/admin" diyerek kullanıcı oluşturulabilir.

Projede iki collection types var. "Brand Lists" ve "Brand Details". Bu iki collection types'tan veri çekilirken GET methoduyla "http://localhost:1337/brand-lists" ve "http://localhost:1337/brand-details" 'e istek atılabilir.

Diğer route'lar için "Settings" menüsünden "USERS & PERMISSIONS PLUGIN" başlığı altındaki "Roles/Public" sayfasından her bir collection types'ın altında bulunan özelliklerine basılarak adresler görülebilir.

**Yeni bir collection types oluşturulup data çekmek istendiğinde izin verilmeli yoksa "Forbidden" uyarısıyla karşılaşırız. İzin vermek için yine "Settings" menüsünden "USERS & PERMISSIONS PLUGIN" başlığı altındaki "Roles/Public" sayfasından ilgili collection type checkbox'ları işaretlenmelidir.
