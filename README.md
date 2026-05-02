# 🔬 DermAI: Kaggle HAM10000 Tabanlı Akıllı Cilt Analiz 
🎯 Proje Hakkında
Bu çalışma, Bartın Üniversitesi Yapay Zeka Operatörlüğü bölümü kapsamında geliştirilmiş bir erken teşhis asistanıdır. DermAI, cilt kanseri teşhisinde kullanılan klinik protokolleri (ABCDE kriterleri ve Fitzpatrick ölçeği) makine öğrenmesi mantığıyla harmanlayarak kullanıcıya kişiselleştirilmiş bir risk raporu sunar.

Yapay zekayı bir amaç değil, insan sağlığını korumada bir araç olarak konumlandıran bu proje; kullanıcı deneyimini (UX) ön plana çıkararak tıbbi farkındalığı artırmayı hedefler.

🚀 Öne Çıkan Özellikler
Klinik Anamnez Soruları: Dermatologların sorduğu profesyonel sorularla (geçmiş güneş yanıkları, genetik faktörler vb.) detaylı analiz.

Görsel Analiz Desteği: Kullanıcıdan alınan lezyon fotoğrafları üzerinden görsel takip imkanı.

Akıllı Skorlama: ABCDE kriterlerine göre ağırlıklandırılmış dinamik risk hesaplama.

MHRS Entegrasyonu: Yüksek risk durumunda kullanıcıyı doğrudan randevu sistemine yönlendiren akıllı buton.

📊 Veri Seti ve Metodoloji
Proje, dünya çapında kabul gören Skin Cancer MNIST: HAM10000 veri setindeki parametreler temel alınarak modellenmiştir.

Kaynak: Kaggle / HAM10000 Analysis.

Vaka Sayısı: 10,015 adet dermoskopik görüntü referans alınmıştır.

### 🛠️ Kurulum ve Çalıştırma

Projeyi yerel bilgisayarınızda çalıştırmak için şu adımları izleyin:

1. **Depoyu Klonlayın:**
\`\`\`bash
git clone https://github.com/aysegul-drn/Kanser_Projesi.git
\`\`\`

2. **Gerekli Kütüphaneleri Yükleyin:**
\`\`\`bash
pip install -r requirements.txt
\`\`\`

3. **Uygulamayı Başlatın:**
\`\`\`bash
streamlit run app.py
\`\`\`



