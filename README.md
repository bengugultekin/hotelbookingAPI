# HotelBookingAPI

Bu projede bir hotel kayıt sistemi için basit düzeyde bir API hazırlanmıştır. API kullanımı için detaylı bilgiler ve uygulamaya ait swagger arayüzü görünümü için ekran görüntüleri aşağıda verilmiştir.


## API Kullanımı

#### Tüm öğeleri getir

```http
  GET /api/HotelBooking/GetAll
```

| Parametre | Tip     | Açıklama                |
| :-------- | :------- | :------------------------- |
| `api_key` | `int` | **Gerekli**. API anahtarınız. |

#### Tek Bir Öğeyi getir

```http
  GET /api/HotelBooking/Get
```

| Parametre | Tip     | Açıklama                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `int` | **Gerekli**. Çağrılacak öğenin anahtar değeri |

#### Tek Bir Öğeyi Siler

```http
  GET /api/HotelBooking/Delete
```

| Parametre | Tip     | Açıklama                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `int` | **Gerekli**. Silinecek öğenin anahtar değeri |

#### Tek Bir Öğeyi kayıt eder veya Günceller

```http
  GET /api/HotelBooking/CreateEdit
```

| Parametre | Tip     | Açıklama                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `int` | Düzenlenecek öğenin anahtar değeri |
| `roomNumber`      | `int` | **Gerekli**. Eklenecek öğenin oda bilgisi |
| `clientName`      | `string` | **Gerekli**. Eklenecek öğenin isim bilgisi |


##### /api/HotelBooking/GetAll
![getall](https://github.com/bengugultekin/csharp-101/assets/44199167/c52d2a9b-7beb-46dc-b01b-1d5fbafcb32b)

##### /api/HotelBooking/Get
![get](https://github.com/bengugultekin/csharp-101/assets/44199167/dc0a14c2-8256-44d7-b945-af9e83057195)

##### /api/HotelBooking/Delete
![delete](https://github.com/bengugultekin/csharp-101/assets/44199167/000633ff-3bbf-4fc1-a4cd-7deb6564c3d2)

##### /api/HotelBooking/CreateEdit
![createEdit](https://github.com/bengugultekin/csharp-101/assets/44199167/a0589939-2213-4cb2-905f-1bab325baebe)



  
