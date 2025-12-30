---
title: "Evil Twin Saldırısı: En Yakınınızdaki Wi-Fi Tehlikesi (Teknik Analiz)"
date: 2025-12-30
draft: false
tags: ["Siber Güvenlik", "Evil Twin", "Wi-Fi Güvenliği", "Hacker Teknikleri", "Veri Gizliliği"]
categories: ["Dijital Savunma"]
description: "Halka açık Wi-Fi ağlarındaki en sinsi tehdit olan Evil Twin (Kötü İkiz) saldırısını derinlemesine inceleyin. Hackerlar verilerinizi nasıl çalıyor ve nasıl korunursunuz?"
---

Modern dünyada internete bağlı kalmak bir ihtiyaç haline geldi. Bir kafeye girdiğimizde, bir otele yerleştiğimizde veya bir havaalanında beklerken gözümüzün ilk aradığı şey "Ücretsiz Wi-Fi" tabelası oluyor. Ancak bu masum arayış, sizi siber suçluların en eski ve en etkili tuzaklarından biri olan **Evil Twin (Kötü İkiz)** saldırısının kurbanı yapabilir.

Bu yazıda, bir Ar-Ge mühendisi gözüyle bu saldırının anatomisini, nasıl çalıştığını ve dijital savunmanızı nasıl güçlendireceğinizi en ince ayrıntısına kadar inceleyeceğiz.

## Evil Twin Saldırısı Nedir?

Teknik olarak bakıldığında, bir Evil Twin saldırısı bir **"Man-in-the-Middle" (Aradaki Adam)** saldırı türüdür. Saldırgan, meşru bir kablosuz erişim noktasının (Access Point) adını (SSID) kopyalayan sahte bir ağ oluşturur. 

Örneğin, "Starbucks_Wi-Fi" adında gerçek bir ağ olduğunu düşünün. Saldırgan, elindeki bir Wi-Fi adaptörü ve özel bir yazılımla aynı isimde (ve hatta bazen aynı MAC adresini taklit ederek) çok daha güçlü bir sinyal yayan sahte bir ağ başlatır. Cihazlarımız doğası gereği en güçlü ve tanıdık gelen sinyale bağlanmaya programlandığı için, telefonunuz veya bilgisayarınız sessizce bu sahte ağa bağlanır.

## Saldırının Anatomisi: Hackerlar Nasıl Çalışır?

Saldırganın bu operasyonu gerçekleştirmesi için karmaşık donanımlara ihtiyacı yoktur. Sadece bir dizüstü bilgisayar ve sinyal gücü yüksek bir harici Wi-Fi adaptörü yeterlidir.

### 1. Keşif Aşaması
Saldırgan hedef bölgedeki ağları tarar. En çok kullanılan ve şifresiz olan (veya şifresi kolayca tahmin edilebilen) ağları belirler.

### 2. İkizleme (Cloning)
Meşru ağın aynısını oluşturur. Eğer gerçek ağ şifreliyse, saldırgan genellikle bir **"Deauthentication"** saldırısı başlatarak mevcut kullanıcıları gerçek ağdan düşürür. Bağlantısı kopan cihazlar, otomatik olarak daha güçlü sinyal veren "Kötü İkiz"e bağlanmaya çalışır.

### 3. Veri Hasadı
Siz internette gezindiğinizi sanırken, gönderdiğiniz her bir veri paketi saldırganın terminal ekranından geçer. Eğer girdiğiniz site şifrelenmemişse (HTTP), kullanıcı adlarınız, şifreleriniz ve mesajlarınız düz metin olarak okunabilir. Eğer site HTTPS kullanıyorsa, saldırgan **SSL Stripping** gibi tekniklerle bağlantıyı güvensiz hale getirmeye çalışabilir.

## Evil Twin Saldırısından Nasıl Korunulur?

Sistemin kodlarını çözmek yetmez; savunma hattını da kurmak gerekir. İşte her "Admin" seviyesindeki kullanıcının uygulaması gereken protokoller:

### Güçlü Bir VPN (Virtual Private Network) Kullanın
VPN, cihazınız ile internet arasında şifreli bir tünel oluşturur. Evil Twin ağına bağlansanız bile, gönderdiğiniz veriler şifreli olduğu için saldırgan bunları okuyamaz. Halka açık her ağda VPN kullanmak bir seçenek değil, bir zorunluluktur.

### Otomatik Bağlanma Özelliğini Kapatın
Telefonunuzun ayarlarından "Bilinen Ağlara Otomatik Bağlan" özelliğini kapatın. Cihazınızın eski ağları hatırlaması konforlu olabilir ancak bu, saldırganlara sizi sahte ağlara kolayca çekme fırsatı verir.

### HTTPS Everywhere ve HSTS Bilinci
Ziyaret ettiğiniz sitelerin başında asma kilit simgesi olduğundan emin olun. Tarayıcınıza "HTTPS Everywhere" gibi eklentiler kurarak tüm bağlantılarınızı şifreli olmaya zorlayabilirsiniz.

### İki Faktörlü Doğrulama (2FA)
Diyelim ki savunma hattınız delindi ve şifreniz çalındı. İşte burada 2FA (SMS olmayan, Authenticator veya donanım anahtarı tabanlı) devreye girer. Saldırgan şifrenizi bilse bile hesabınıza giremez.

## Sonuç: Tetikte Kalın

Dijital dünyada hiçbir ağ %100 güvenli değildir. Kendi mobil veriniz her zaman en güvenli seçenektir. Ancak mecbur kaldığınızda, yukarıdaki protokolleri uygulayarak sistemin kurbanı olmaktan kurtulabilirsiniz.

Unutmayın; siber güvenlik bir ürün değil, bir süreçtir. Sinyalinizi temiz tutun.

Daha fazla dijital savunma analizi ve sistem analizi için [Saha Notları](/saha-notlari) sayfamızı takip etmeye devam edin.
