---
title: "Evil Twin: En Yakındaki Siber Pusu (Wi-Fi Güvenliği)"
date: 2025-12-30
draft: false
tags: ["Siber Güvenlik", "Evil Twin", "Wi-Fi Güvenliği", "Hacker Teknikleri"]
categories: ["Dijital Savunma"]
description: "Halka açık Wi-Fi ağlarındaki en sinsi tehlike olan Evil Twin (Kötü İkiz) saldırısı nedir? Verilerinizi çalınmaktan nasıl korursunuz? İşte teknik analiz ve korunma rehberi."
---

Sıradan bir kafe veya havaalanı. Telefonunuz "Starbucks_Free_WiFi" veya "Airport_Guest" ağına otomatik bağlandı. Her şey yolunda görünüyor, değil mi? Yanılıyorsunuz. Az önce bir **Evil Twin (Kötü İkiz)** saldırısının hedefi olmuş olabilirsiniz.

## Evil Twin Saldırısı Nedir? (Teknik Analiz)

Kötü İkiz saldırısı, siber saldırganın meşru bir Wi-Fi erişim noktasının adını (SSID) kopyalayarak sahte bir ağ oluşturmasıdır. Cihazlar genelde en yüksek sinyal gücüne sahip olan veya daha önce bağlandıkları isimdeki ağlara otomatik bağlanma eğilimindedir. Saldırgan bu zaafı kullanarak trafiğinizi kendi üzerinden geçirir.

### Veri Sızıntısı Nasıl Gerçekleşir?
Cihazınız bu "sahte ikiz" ağa bağlandığı andan itibaren, üzerinizden geçen tüm dijital trafik saldırganın kontrolündedir (Man-in-the-Middle):
- **Kimlik Avı:** Bankacılık uygulamaları veya sosyal medya girişleri için sahte login ekranları.
- **Şifresiz Veriler:** HTTPS kullanmayan sitelerdeki tüm yazışmalar.
- **DNS Zehirleme:** Sizi gerçek banka siteniz yerine saldırganın kontrolündeki kopyasına yönlendirme.

## Wi-Fi Güvenliği İçin Sistem Yaması (Korunma Rehberi)

1. **Güvenilir Bir VPN Kullanın:** Şifreli bir tünel oluşturarak verilerinizin okunmasını imkansız hale getirin.
2. **"Ağı Unut" Protokolü:** Halka açık ağları kullandıktan sonra telefonunuzdan bu ağları silin ve otomatik bağlanmayı kapatın.
3. **İki Faktörlü Doğrulama (2FA):** Şifreniz çalınsa bile hacker'ın hesabınıza girmesini engelleyin.
4. **WPA3 ve Modern Güvenlik:** Sadece WPA2/WPA3 protokolü ile korunan bilindik ağları tercih edin.

**Unutmayın:** Halka açık, şifresiz Wi-Fi her zaman risk taşır. Veri paketlerinizi korumak sizin sorumluluğunuzdadir.

Sinyalinizi temiz tutun. Daha fazla dijital savunma analizi için [Saha Notları](/saha-notlari) takibinde kalın.
