# 🟩 Kick Discord Yayın Bildirim Botu

<p align="center">
  <b>Kick yayıncılarını anlık takip eden, gelişmiş etiketleme ve özel duyuru mesajı destekli Discord botu.</b>
</p>

---

## 📌 Özellikler

- 🔴 **Canlı Yayın Takibi:** Kick API entegrasyonu ile dakikalık periyotlarla yayın kontrolü.
- 🔔 **Esnek Etiketleme:** `@everyone`, `@here` veya isteğe bağlı `@Rol` etiketleme seçenekleri.
- 💬 **Özel Duyuru Mesajları:** Her yayıncı için dinamik değişkenli (`{yayinci}`, `{url}`) metinler.
- 🖼️ **Zengin Embed Görseli:** Yayın kapağı veya Kick profil resmi, anlık izleyici sayısı ve kategori bilgisi.
- 🔘 **Hızlı Erişim Butonları:** Yayına ve Destek Sunucusuna tek tıkla ulaşım butonları.
- ⚙️ **Özel Durum (Presence):** Bot profilinde otomatik *"Yayıncılar takip ediliyor..."* görünümü.
- 🛡️ **Yetki Koruması:** Yalnızca `Sunucuyu Yönet` yetkisi olan yöneticiler yayıncı ekleyip çıkarabilir.

---

## 📂 Proje Yapısı

```text
kick-notifier-bot/
├── assets/
│   └── kick-banner.jpg
├── commands/
│   ├── yardim.js
│   ├── yayin-cikar.js
│   ├── yayin-ekle.js
│   ├── yayin-liste.js
│   └── yayin-test.js
├── events/
│   ├── interactionCreate.js
│   └── ready.js
├── utils/
│   ├── database.js
│   └── kickChecker.js
├── config.json
├── database.json
├── index.js
├── package.json
└── README.md
```



<img width="473" height="441" alt="image" src="https://github.com/user-attachments/assets/4fe133bd-29ce-49d2-ae8d-1d7787e741b6" />
<img width="326" height="108" alt="image" src="https://github.com/user-attachments/assets/5bbfccc7-c3da-4ee1-85d9-c0725926e9ba" />
<img width="378" height="335" alt="image" src="https://github.com/user-attachments/assets/21ff0c6a-c76f-49aa-a074-abada8feaa17" />
<img width="568" height="75" alt="image" src="https://github.com/user-attachments/assets/bdd514f2-9c7e-410c-beec-b2d1d2fece65" />
<img width="497" height="337" alt="image" src="https://github.com/user-attachments/assets/d0aa00da-9886-4eb8-87ae-70e2f5507478" />
<img width="840" height="77" alt="image" src="https://github.com/user-attachments/assets/5734b150-8b68-49c6-97de-538d5d6db598" />
