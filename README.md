# ChatFusion  

**ChatFusion**, sohbet platformlarından (örneğin, WhatsApp veya Slack) elde edilen yazışmaları analiz ederek veri sınıflandırma, görselleştirme ve bir dil modeli (LLM) tabanlı soru-cevap sistemi oluşturmayı hedefleyen bir projedir.  

## Proje Amacı  
Bu proje, kullanıcıların sohbet verilerinden anlamlı içgörüler çıkarabilmelerini sağlamayı ve bu bilgileri yapay zeka destekli bir sistemle kullanarak hızlı, doğru cevaplar sunmayı amaçlar.  

## Özellikler  
- Sohbet verilerinin analizi ve sınıflandırılması  
- Metin madenciliği ve görselleştirme  
- Dil modeli tabanlı soru-cevap botu geliştirme  
- Dinamik veri işleme ve raporlama  

---

## Proje Aşamaları  

### 1. **Veri Toplama ve Hazırlık**  
- Örnek sohbet veri setleri bulunacak (örn: açık kaynak WhatsApp veya Slack veri setleri).  
- Veri anonimleştirilerek gizlilik sağlanacak.  
- Eksik veya hatalı veriler temizlenecek ve yapılandırılacak.  

### 2. **Veri Analizi ve Görselleştirme**  
- Mesajların analiz edilmesi:  
  - Kelime sıklığı analizi  
  - Duygu analizi  
  - Önemli anahtar kelimelerin çıkarılması  
- Analiz sonuçlarının grafikler ve görselleştirmeler ile sunulması.  

### 3. **Veri Sınıflandırma**  
- Sohbetlerin türlerine göre sınıflandırılması (örn: iş, sosyal, bilgilendirme).  
- Makine öğrenmesi algoritmalarının kullanılması (örn: Naive Bayes, Logistic Regression).  

### 4. **Dil Modeli (LLM) Tabanlı Soru-Cevap Sistemi**  
- Sohbet verisi üzerinden dil modeli eğitilecek veya var olan bir model (örn: OpenAI GPT) adapte edilecek.  
- Kullanıcının sohbet verileri üzerinde sorular sorabileceği bir arayüz tasarlanacak.  

### 5. **Sonuçların Sunumu ve Geri Bildirim Mekanizması**  
- Kullanıcı dostu bir dashboard oluşturulacak.  
- Kullanıcı geri bildirimleriyle model iyileştirilecek.  

---

## Gereksinimler  
- **Programlama Dilleri:** Python  
- **Kütüphaneler:**  
  - Veri İşleme: `pandas`, `numpy`  
  - Görselleştirme: `matplotlib`, `seaborn`, `plotly`  
  - Makine Öğrenmesi: `scikit-learn`, `tensorflow` veya `pytorch`  
  - Dil İşleme: `nltk`, `spaCy`, `transformers`  
- **Araçlar:**  
  - Jupyter Notebook  
  - Git ve GitHub  
  - Docker (isteğe bağlı)  

---

## Kullanım  
1. Depoyu klonlayın:  
   ```bash
   git clone https://github.com/falcondynamic/ChatFusion.git
   cd ChatFusion

2. Gerekli kütüphaneleri yükleyin:
    ```bash
    pip install -r requirements.txt

3. Örnek veri setini data klasörüne yerleştirin.

  Adım adım not defterlerini çalıştırarak süreci takip edin:
  - 01_data_preparation.ipynb
  - 02_data_analysis.ipynb
  - 03_model_training.ipynb
  - 04_question_answering.ipynb


## Örnek projeler  
1. https://www.kaggle.com/code/omgits0mar/chatbot-from-scratch-llms-finetune
