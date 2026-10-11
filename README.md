# 🎯 Proje Adı: ÖzetleGPT

**Takım İsmi:** ZeroToHero  
**Roller:** Product Owner, Scrum Master, Developer (solo çalışıldı)

---

## 🧠 Proje Amacı

ÖzetleGPT, kullanıcıların YouTube videolarını izlemeye vakit ayırmadan kısa ve anlaşılır özetler almasını sağlayan yapay zeka tabanlı bir araç olarak geliştirilmektedir.  
Proje, eğitim ve araştırma amaçlı videoları hızlıca anlamayı kolaylaştırmak için tasarlanmıştır.

---

## 👥 Hedef Kitle

- Öğrenciler  
- Akademisyenler  
- Yoğun çalışanlar  
- Bilgiye hızlı ulaşmak isteyen herkes

---

## ✨ Ürün Özellikleri

- YouTube linki girişi  
- “Özetle” butonu  
- Özetin sayfa içinde gösterilmesi  
- (Gelecek sprintte) Gerçek LLM entegrasyonu (OpenAI API gibi)  
- (Gelecek sprintte) Transkript desteği

---

## 🧰 Kullanılan Teknolojiler

| Katman          | Kullanılan Teknoloji / Yöntem                                         |
|-----------------|----------------------------------------------------------------------|
| 🖥️ Front-End     | HTML5, CSS (inline style), Vanilla JavaScript                       |
| 🧠 NLP / Prompt  | Hazır örnek çıktı (şu an için sahte özet) – Prompt tabanlı yapı planlandı |
| 🔧 Back-End      | Henüz yok – Sprint 3'te OpenAI API ile Node.js / Python Flask planı |
| 📄 Dokümantasyon | Markdown (`README.md`), Canva (PDF sunum), GitHub Project Board     |
| ☁️ Versiyon Kontrol | Git, GitHub (public repo, sprint bazlı commit yapısı)               |

---

## 📌 Kullanım Senaryosu

1. Kullanıcı YouTube linkini girer  
2. “Özetle” butonuna basar  
3. Video içeriğinin özeti kullanıcıya gösterilir  
4. Gerçek zamanlı ChatGPT veya başka LLM ile detaylandırma yapılır (Sprint 3 hedefi)

---

## 📦 Sprint 1: Ürün Fikri ve Planlama

### ✅ Yapılanlar:
- Ürün fikri geliştirildi  
- Takım yapısı belirlendi (solo çalışma)  
- Kullanıcı ihtiyaçları analiz edildi  
- Hedef kitle netleştirildi  
- İlk sunum hazırlandı

### 🔁 Product Backlog:
- [x] Ürün ismi kararlaştırıldı  
- [x] Problem ve çözüm tanımı  
- [x] Canva sunumu hazırlandı  
- [x] GitHub projesi başlatıldı

---

## 💻 Sprint 2: İlk Çalışan Demo ve Geliştirme

### ✅ Yapılanlar:
- `index.html` dosyası oluşturuldu  
- YouTube linki alma alanı geliştirildi  
- “Özetle” butonu işlevsel hale getirildi (şimdilik örnek/sahte çıktı)  
- `README.md` güncellendi  
- Proje GitHub’a tam olarak yüklendi

### 🔍 Ekran Görüntüsü:

> 📌 `index.html` dosyasını tarayıcıda açarak çıkan ekran:  
> *(Resmi buraya yükleyebilirsin: PNG veya JPG olarak)*

---

## 🧪 Sprint 2: Review & Retrospective

### ✔️ İyi Gidenler:
- GitHub ve proje yükleme mantığı öğrenildi  
- Tasarım ve demo kısa sürede tamamlandı  
- Canva + GitHub birlikte kullanıldı

### ❗ Eksikler:
- Gerçek zamanlı özetleme API’si henüz bağlanmadı  
- Video transkript çıkarma özelliği eksik  
- Zaman yönetimi tek kişi olduğum için zorlayıcıydı

### 💡 Öğrendiklerim:
- Süreç planlaması ve belgelenmesi projenin yarısı  
- Basit çalışan demo, teoriden daha değerli  
- GitHub'da markdown ile düzgün belge oluşturmak sunum kadar etkili

---

## 📁 Proje Dosyaları

| Dosya | Açıklama |
|-------|----------|
| `index.html` | Demo uygulama arayüzü |
| `README.md` | Proje dokümantasyonu (bu dosya) |
| `ÖzetleGPT sunum.pdf` | İlk sprint sunumu (ayrıca eklendi) |
| `2_sprint_sunumu.pdf` | İkinci sprint sunumu (ayrıca eklendi) |

---

## 🔗 Canlı Bağlantılar ve Depolar

- GitHub Reposu: [https://github.com/aliyilmazgh/ozetle-gpt)  

---

## 🚀 Sonraki Adımlar (Sprint 3 Planı)

- [ ] Gerçek ChatGPT API entegrasyonu ile özet oluşturma  
- [ ] Arayüz tasarımını daha modern hale getirme  
- [ ] Kullanıcıdan gelen linkten video transkript çıkarma (YouTube Captions)  
- [ ] Demo Day için sunum slaytlarını güncelleme  
- [ ] Canlı demo’yu GitHub Pages üzerinden yayına alma

---

