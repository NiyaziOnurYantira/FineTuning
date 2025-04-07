
# 🩺 AIMO MED - Tıbbi Yardım Chatbot'u

Bu proje, Mistral tabanlı bir modelin tıbbi sorulara yanıt vermesi için ince ayarlandığı bir Streamlit uygulamasıdır.

## 🚀 Kurulum ve Başlatma

Aşağıdaki adımları izleyerek uygulamayı başlatabilirsiniz.

### 1. Gerekli Kütüphaneleri Yükleyin

```bash
!pip install -q datasets peft requests torch bitsandbytes transformers trl accelerate sentencepiece matplotlib
!pip install streamlit pyngrok transformers peft torch python-dotenv --upgrade
```

### 2. `app.py` Dosyasını Kaydedin

Aşağıdaki komutla `app.py` dosyasını oluşturun veya kendi kopyanızı yükleyin:

```python
%%writefile app.py
# (Buraya tam app.py içeriğini yapıştırın.)
```

### 3. Uygulamayı Çalıştırın ve Tünel Açın

```bash
!curl https://loca.lt/mytunnelpassword
!streamlit run app.py & npx localtunnel --port 8501
```

## 🌐 Web Arayüzüne Erişim

1. Terminalde aşağıdaki komutu çalıştırdıktan sonra:

   ```bash
   curl https://loca.lt/mytunnelpassword
   ```

2. Şu şekilde bir soru göreceksiniz:
   ```
   Ok to proceed? (y)
   ```

3. **`y`** yazıp enter'a basın.

4. Ardından terminalde şu tarz bir link göreceksiniz:
   ```
   https://tender-worms-sort.loca.lt
   ```

5. Bu linke gidin ve **şifreyi** girerek uygulamayı kullanmaya başlayın.

---

## 🧑‍⚕️ Hazırlayan

- Hugging Face Modeli: [OnurYantira/medical-bot-2025-03-30_16.27.25](https://huggingface.co/OnurYantira/medical-bot-2025-03-30_16.27.25)
