# 🏝️ Survivor Web API

Bu proje, ASP.NET Core ile geliştirilmiş bir RESTful Web API uygulamasıdır. Yarışmacılar ve kategoriler üzerinde CRUD işlemleri yapılabilir.

## 📌 Öne Çıkan Özellikler

- ✅ **Soft Delete:** `IsDeleted` özelliği ile kayıt silmeden işaretlenir.  
- 🔄 **Eager Loading:** `Include` ile ilişkili veriler getirilir.  
- 🔧 **PATCH İşlemleri:** JSON Patch ile kısmi güncellemeler yapılabilir.  
- 📦 **DTO Kullanımı:** Veri iletimi sadeleştirilir, gereksiz alanlar gizlenir.  
- 🔍 **Kategoriye Göre Filtreleme:** Belirli bir kategoriye ait yarışmacılar listelenebilir.

## 🚀 Teknolojiler

- .NET 7 (veya 6)
- ASP.NET Core Web API
- Entity Framework Core
- PostgreSQL
- Swagger (Swashbuckle)
- JSON Patch (Microsoft.AspNetCore.JsonPatch)

## 🧪 Örnek API Uç Noktaları

| Metot | URL | Açıklama |
|-------|-----|----------|
| `GET` | `/api/competitors` | Tüm yarışmacıları getirir |
| `GET` | `/api/categories` | Tüm kategorileri getirir |
| `POST` | `/api/competitors` | Yeni yarışmacı oluşturur |
| `PATCH` | `/api/categories/{id}` | Kategori bilgilerini kısmi günceller |
| `GET` | `/api/categories/{categoryId}/competitors` | Belirli kategoriye ait yarışmacıları getirir |

## 🔧 Kurulum

1. Bağımlılıkları yükle:
dotnet restore
2. Veritabanını oluştur:
3. dotnet ef database update

markdown
Kopyala
Düzenle

3. Projeyi başlat:
dotnet run

markdown
Kopyala
Düzenle

4. Swagger arayüzüne git:
https://localhost:{port}/swagger

python
Kopyala
Düzenle

