# Telefon Sonuç Alanını Sabitleme

## Yapılacaklar
- Oyun sırasında cevap bölümünün altında doğru/yanlış bildirimi için her zaman sabit yükseklikte boş alan ayır.
- Sonuç gelmeden bu alan görünmez kalacak; sonuç geldiğinde aynı yerde dolacak.
- Küçük telefon ekranlarında soru, görsel ve cevapların tek ekrana sığmasını koru.
- Telefon görünümünde cevap verildiğinde içeriğin yukarı kaymadığını doğrula.

## Teknik ayrıntılar
- Oyuncu ekranındaki sonuç bloğunu koşullu ekleyip kaldırmak yerine sabit boyutlu bir kapsayıcı içinde göstereceğim.
- Yardımcı yanlış-cevap metnini de aynı ayrılmış alan içinde tutacağım.
