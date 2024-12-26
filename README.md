# İSG Asistanı 🤖 

> İş sağlığı ve güvenliği konularında size yardımcı olacak akıllı sohbet asistanı.

İSG Asistanı, iş sağlığı ve güvenliği alanında çalışanların ve profesyonellerin sorularını yanıtlamak için tasarlanmış yapay zeka destekli bir chatbot uygulamasıdır. Kişisel koruyucu donanımlardan (KKD) risk değerlendirmelerine kadar geniş bir yelpazede bilgi sağlar.

## ✨ Özellikler

- 💬 Doğal dil işleme ile akıllı sohbet deneyimi
- 🛡️ Kapsamlı İSG bilgi tabanı
- 📱 Responsive tasarım ile her cihazda kusursuz deneyim
- 🔄 Gerçek zamanlı yanıt sistemi

## 🖥️ Ekran Görüntüleri

<div align="center">

### Demo
![Ekran Kaydı](./assets/Screen%20Recording%20Dec%2025%202024.gif)

### Ana Ekran
![Sohbet Başlangıcı](./assets/Screenshot%202024-12-25%20at%2013.10.24.png)
![Ekran Görüntüsü](./assets/Screenshot%202024-12-25%20at%2013.13.17.png)
![Ekran Görüntüsü2](./assets/Screenshot%202024-12-25%20at%2013.14.08.png)

</div>

## 🛠️ Teknoloji Altyapısı

### Frontend
- HTML5 & CSS3
- Modern JavaScript (ES6+)
- Responsive UI framework
- Tailwinds CSS

### Backend
- Rasa

### Veritabanı & AI
- Rasa NLP framework
- Custom trained language model

## 🚀 Kurulum

### Ön Gereksinimler
```bash
# Python 3.8+ gereklidir
python --version
```

### Adım 1: Projeyi İndirin
```bash
git clone <repository-link>
cd chatbot
```

### Adım 2: Bağımlılıkları Yükleyin
```bash
pip install rasa
```

### Adım 3: AI Modelini Eğitin
```bash
rasa train
```

### Adım 4: Uygulamayı Başlatın
```bash
 rasa run -m models --enable-api --cors "*" --port 5005
 index.html dosyasını tarayıcınızda açın
```