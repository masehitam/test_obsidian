# test_obsidian

Cara mudah untuk mensinkronkan catatan di Obsidian menggunakan git di iOS, caranya : 
1. Install aplikasi ish, dan masukan perintah :
   ```bash
   # install git
   apk add git
   # buat folder
   mkdir myVault
   # buat folder obsidian, pilih folder obsidian di file manager
   mount -t ios . myVault/
   # masuk ke vault tadi
   cd myVault
   # Clone repository terlebih dahulu, dengan menyisipkan API key
   git clone --depth=1 https://username:API_KEY@github.com/username/test_obsidian.git
   ```
2. Jika berhasil, vault seharusnya muncul di obsidian
3. jangan lupa install git plugin di obsidian
