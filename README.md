# 🔁 1D Extended Kalman Filter (EKF) – Simulink Uygulaması

Bu proje, Simulink ortamında sabit hızla ilerleyen bir cismin konumunu ve hızını **yalnızca gürültülü konum ölçümünden** tahmin etmek amacıyla Extended Kalman Filter (EKF) algoritmasının uygulanmasını içerir.

## 📌 İçerik

- Sabit hızla ilerleyen bir nesne (sanal model)
- Gürültülü ölçüm (Random Number)
- MATLAB Function bloğunda EKF algoritması
- Scope ekranında:
  - Gerçek Konum
  - Ölçüm (Z)
  - EKF Tahmini (x_hat)

## 🧠 EKF Neyi Başarıyor?

Yalnızca gürültülü ölçümle:
- Gerçek konumu filtreliyor
- Aynı zamanda sistemin hızını da tahmin ediyor

## 🛠️ Nasıl Kullanılır?

1. `ekf_1d.slx` dosyasını aç  
2. Simülasyonu çalıştır (`Run`)  
3. `Scope` ekranından tahmin vs ölçüm farkını gözlemle  
4. `Style` ayarlarından sinyal adlarını görebilirsin

## 📈 Örnek Çıktı

![EKF Scope Çıktısı](ekf_scope.png)

## 🔄 Geliştirme Fikirleri

- 2D pozisyon + hız modeline genişlet
- IMU verileri ile gerçek uygulama entegrasyonu
- Gürültü seviyelerini değiştirerek EKF dayanıklılığı test et

---

📌 Bu proje eğitim ve araştırma amaçlı hazırlanmıştır.
