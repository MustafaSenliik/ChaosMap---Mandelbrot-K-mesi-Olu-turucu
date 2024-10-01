# ChaosMap - Mandelbrot Kümesi Oluşturucu

Bu proje, **Mandelbrot kümesi** adı verilen karmaşık sayıların bir kümesini görselleştirmek için geliştirilmiş bir **Flask** tabanlı web uygulamasıdır. Kullanıcı, X ve Y koordinatlarını ve yakınlaştırma düzeyini girerek belirli bir bölgenin Mandelbrot kümesini oluşturabilir ve sonuçları grafiksel olarak görüntüleyebilir.

## Özellikler

- Kullanıcı tarafından girilen X ve Y koordinatlarına göre Mandelbrot kümesi oluşturma.
- Yakınlaştırma düzeyini ayarlayarak farklı detay seviyelerinde küme görselleştirme.
- Üretilen Mandelbrot kümesini renkli bir grafik olarak görüntüleme.

## Kurulum

Projeyi yerel makinenizde çalıştırmak için aşağıdaki adımları izleyin:

### Gereksinimler

- Python 3.12+
- Flask
- Matplotlib
- NumPy

### Adımlar

1. Bu projeyi klonlayın:
    ```bash
    git clone https://github.com/kullanıcı_adınız/ChaosMap.git
    cd ChaosMap
    ```

2. Gerekli Python paketlerini yükleyin:
    ```bash
    pip install -r requirements.txt
    ```

3. Uygulamayı başlatın:
    ```bash
    python app.py
    ```

4. Tarayıcınızı açın ve `http://localhost:5000` adresine gidin.

## Kullanım

- X ve Y koordinatlarını virgüllü değerlerle girin (örn. 0.5 veya -1.25).
- Yakınlaştırma düzeyini girin.
- **Hesapla** butonuna tıklayın, Mandelbrot kümesi otomatik olarak oluşturulacak ve görüntülenecektir.

## Katkıda Bulunma

Katkılarınızı memnuniyetle karşılıyoruz! Lütfen bir `issue` açarak veya `pull request` göndererek projeye katkıda bulunun.

