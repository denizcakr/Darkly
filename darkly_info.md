# Darkly
---

Bu proje, basit bir web sitesini denetleyerek riskler ve güvenlik açıkları hakkında bilgi vermeyi amaçlamaktadır. (This project, aims to inform about risks and security vulnerabilities by auditing a simple website.)

---

`OWASP Top 10 listesinin açıklamalarını ve çalışmalarımı içerir, bu repoya eklemeler devam etmektedir. (It includes the OWASP Top 10 list and my project work, additions to this repository are ongoing.)`

## OWASP Nedir?
---

OWASP (Open Web Application Security Project), web uygulama güvenliği alanında dünya çapında tanınan, kar amacı gütmeyen bir organizasyondur. Bu topluluk, web uygulamalarının güvenliğini artırmak için araçlar, dokümantasyon, standartlar ve eğitim materyalleri geliştirmektedir.

---

## OWASP Top 10 Nedir?

---

OWASP Top 10, web uygulamalarında karşılaşılan en kritik 10 güvenlik riskini listeleyen, düzenli olarak güncellenen bir standarttır. İlk kez 2003 yılında yayımlanan bu liste, her 3-4 yılda bir güncellenmekte ve sektördeki güvenlik uzmanları tarafından referans olarak kullanılmaktadır.

---

# OWASP Top 10 Listesi (Güncel)

`A01: Broken Access Control (Erişim Kontrolü Zafiyetleri)`

---
Kullanıcıların yetki alanları dışındaki işlemleri gerçekleştirmesine olanak tanıyan zafiyetlerdir;

-URL manipülasyonu ile başka kullanıcıların verilerine erişim
-Yetki yükseltme saldırıları
-IDOR (Insecure Direct Object References) zafiyetleri


`A02: Cryptographic Failures (Kriptografik Hatalar)`

---
Hassas verilerin şifrelenmemesi veya zayıf şifreleme kullanılmasıyla ilgili sorunlardır;

-Düz metin halinde saklanan parolalar
-Zayıf şifreleme algoritmaları kullanımı
-Yetersiz anahtar yönetimi


`A03: Injection (Enjeksiyon)`

---
Güvenilmeyen veri kaynaklarından gelen girişlerin doğrulanmadan işlenmesi sonucu oluşan zafiyetlerdir;

-SQL Injection
-Command Injection
-LDAP Injection
-XML Injection


`A04: Insecure Design (Güvensiz Tasarım)`

---
Tasarım aşamasında güvenlik gereksinimlerinin göz ardı edilmesiyle oluşan zafiyetlerdir;

-Threat modeling eksikliği
-Güvenlik kontrolleri tasarımının yetersizliği
-Risk analizi yapılmaması


`A05: Security Misconfiguration (Güvenlik Yanlış Yapılandırması)`

---
Sistem ve uygulamaların güvenli şekilde yapılandırılmamasından kaynaklanan sorunlardır;

-Varsayılan parolaların kullanılması
-Gereksiz servislerin açık bırakılması
-Hata mesajlarında hassas bilgilerin görünmesi


`A06: Vulnerable and Outdated Components (Zafiyet İçeren ve Güncel Olmayan Bileşenler)`

---
Güvenlik zafiyeti bulunan veya desteklenmeyen üçüncü taraf bileşenlerin kullanılmasıdır;

-Güncel olmayan kütüphaneler
-Zafiyet bulunan framework'ler
-Güvenlik yamalarının uygulanmaması


`A07: Identification and Authentication Failures (Kimlik Doğrulama ve Tanıma Hataları)`

---
Kullanıcı kimlik doğrulama süreçlerindeki zafiyetlerdir;

-Zayıf parola politikaları
-Session yönetimi zafiyetleri
-Brute force saldırılarına karşı korunma eksikliği


`A08: Software and Data Integrity Failures (Yazılım ve Veri Bütünlüğü Hataları)`

---
Yazılım güncellemeleri ve kritik verilerin bütünlüğünün doğrulanmamasıyla ilgili sorunlardır;

-Güvenilmeyen kaynaklardan gelen güncellemeler
-CI/CD pipeline güvenlik zafiyetleri
-Dijital imza doğrulama eksikliği


`A09: Security Logging and Monitoring Failures (Güvenlik Kayıtları ve İzleme Hataları)`

---
Güvenlik olaylarının yeterince loglanmaması ve izlenmemesidir;

-Yetersiz log kayıtları
-Güvenlik olaylarının tespit edilememesi
-Incident response süreçlerinin eksikliği


`A10: Server-Side Request Forgery (SSRF) (Sunucu Tarafı İstek Sahteciliği)`

---
Web uygulamasının iç ağdaki kaynaklara istek göndermesi için manipüle edilmesidir;

-İç ağ keşfi
-Cloud metadata servislerine erişim
-Port tarama saldırıları

