# 🏗️ Faz 03: Teknik Mimari ve İnşa

## "Metal Yaka" Hızlı Geliştirme Protokolü
Amacımız mükemmel kod yazmak değil; çalışan, güvenli ve ölçeklenebilir bir sistemi en kısa sürede yayına almaktır.

### 🛡️ Temel Mimari Prensipler
1. **Modülerlik**: Her özelliği bağımsız bir bileşen olarak tasarlayın.
2. **Hata Yönetimi (Error Handling)**: Sentry veya benzeri bir araçla hataları gerçek zamanlı izleyin.
3. **Veri Güvenliği**: RBAC (Rol Tabanlı Erişim Kontrolü) kullanarak kullanıcı verilerini koruyun.

### 🚀 Stack Detayları
- **Next.js (App Router)**: Server Components ile maksimum hız.
- **Supabase**: Veritabanı, Auth ve Storage için "All-in-one" çözüm.
- **Prisma**: Tip güvenli veritabanı sorguları.
- **Stripe SDK**: Abonelik ve tek seferlik ödeme entegrasyonu.

### 📜 Checkpoint Listesi
- [ ] Veritabanı şeması normalize edildi mi?
- [ ] Kimlik doğrulama akışları (Login/Signup/Reset) tamam mı?
- [ ] Webhook'lar (Stripe için) test edildi mi?
- [ ] responsive tasarım mobil uyumlu mu?
