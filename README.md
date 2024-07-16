# PowerBI Project: Analysis of Hotel Reservation Data

This project is focused on analyzing hotel reservation data and visualizing these analyses using PowerBI. The analyses included in the project are grouped under Customer Acquisition, Customer Retention, and Revenue Analysis.

## Content

The following files are included in this repository:
- **Emrah_BAS_PowerBI_Project.pbix**: PowerBI file containing all analyses and visualizations within the project.
- **Emrah_BAS_PowerBI_Project.ppsx**: PowerPoint presentation of the analyses and results made in the project.
- **Emrah_BAS_PowerBI_Project_ME.png**: A visual related to Customer Acquisition analysis.

## Dataset

The dataset analyzed contains a table named `hotel_bookings`. The columns and their descriptions are as follows:

1. `hotel`: Hotel type (city hotel or resort hotel)
2. `is_canceled`: Reservation cancellation status (1: canceled, 0: not canceled)
3. `lead_time`: Number of days between booking and check-in
4. `arrival_date_year`: Year of arrival
5. `arrival_date_month`: Month of arrival
6. `arrival_date_week_number`: Week number of arrival
7. `arrival_date_day_of_month`: Day of arrival
8. `stays_in_weekend_nights`: Number of weekend nights stayed
9. `stays_in_week_nights`: Number of week nights stayed
10. `adults`: Number of adults
11. `children`: Number of children
12. `babies`: Number of babies
13. `meal`: Type of meal booked
14. `country`: Country of the guest
15. `market_segment`: Market segment
16. `distribution_channel`: Distribution channel
17. `is_repeated_guest`: Repeated guest status (1: repeated, 0: new)
18. `previous_cancellations`: Number of previous cancellations
19. `previous_bookings_not_canceled`: Number of previous bookings not canceled
20. `reserved_room_type`: Reserved room type
21. `assigned_room_type`: Assigned room type
22. `booking_changes`: Number of booking changes
23. `deposit_type`: Deposit type
24. `agent`: Agent making the reservation
25. `company`: Company making the reservation
26. `days_in_waiting_list`: Number of days in the waiting list
27. `customer_type`: Customer type
28. `adr`: Average Daily Rate
29. `required_car_parking_spaces`: Number of required parking spaces
30. `total_of_special_requests`: Total of special requests
31. `reservation_status`: Reservation status
32. `reservation_status_date`: Reservation status date

## Analyses

### Customer Acquisition Analysis
Customer acquisition analysis is performed to evaluate the hotel's performance in gaining new customers. Key metrics used in this analysis include the number of new customers, customer distribution by market segments, and customer acquisition costs.

### Customer Retention Analysis
This analysis is conducted to evaluate customer loyalty and the rate of repeated customers. Metrics such as repeated customer rate, customer loyalty, and customer satisfaction are used in this analysis.

### Revenue Analysis
Revenue analysis is performed to assess the hotel's revenue performance. Financial metrics used in this analysis include Average Daily Rate (ADR), occupancy rate, and total revenue.

## Usage

You can open the project file with PowerBI Desktop to review the analyses and work with your own data. You can present the summary and key findings of the project using the PowerPoint presentation.

## License

This project is licensed under the MIT License. For more information, please refer to the `LICENSE` file.

## Contact

Feel free to reach out to me with any questions or feedback:

- **Name**: Emrah BAS
- **Email**: [bas_emrah@hotmail.com](mailto:bas_emrah@hotmail.com)

---

# PowerBI Projesi: Otel Rezervasyon Verilerinin Analizi

Bu proje, otel rezervasyon verilerinin analiz edilmesi ve bu analizlerin PowerBI kullanılarak görselleştirilmesi üzerine kurulmuştur. Projede yer alan analizler Müşteri Edinme, Müşteriyi Elde Tutma ve Gelir Analizi başlıkları altında toplanmıştır.

## İçerik

Bu repoda aşağıdaki dosyalar bulunmaktadır:
- **Emrah_BAS_PowerBI_Proje.pbix**: PowerBI dosyası, proje kapsamındaki tüm analizleri ve görselleştirmeleri içerir.
- **Emrah_BAS_PowerBI_Proje.ppsx**: Projede yapılan analizlerin ve sonuçların PowerPoint sunumu.
- **Emrah_BAS_PowerBI_Proje_ME.png**: Müşteri Edinme analizi ile ilgili bir görsel.

## Veri Seti

Analiz edilen veri seti `hotel_bookings` adındaki tabloyu içermektedir. Bu tablonun sütunları ve açıklamaları aşağıdaki gibidir:

1. `hotel`: Otel tipi (şehir oteli veya tatil köyü)
2. `is_canceled`: Rezervasyon iptal durumu (1: iptal edilmiş, 0: iptal edilmemiş)
3. `lead_time`: Rezervasyon ile check-in arasındaki gün sayısı
4. `arrival_date_year`: Geliş yılı
5. `arrival_date_month`: Geliş ayı
6. `arrival_date_week_number`: Geliş haftası numarası
7. `arrival_date_day_of_month`: Geliş günü
8. `stays_in_weekend_nights`: Hafta sonu konaklama geceleri sayısı
9. `stays_in_week_nights`: Hafta içi konaklama geceleri sayısı
10. `adults`: Yetişkin sayısı
11. `children`: Çocuk sayısı
12. `babies`: Bebek sayısı
13. `meal`: Rezervasyon yapılan yemek tipi
14. `country`: Misafirin ülkesi
15. `market_segment`: Pazar segmenti
16. `distribution_channel`: Dağıtım kanalı
17. `is_repeated_guest`: Tekrarlanan misafir durumu (1: tekrarlanan, 0: yeni)
18. `previous_cancellations`: Önceki iptaller sayısı
19. `previous_bookings_not_canceled`: Önceki iptal edilmemiş rezervasyonlar sayısı
20. `reserved_room_type`: Rezerve edilen oda tipi
21. `assigned_room_type`: Atanan oda tipi
22. `booking_changes`: Rezervasyon değişiklikleri sayısı
23. `deposit_type`: Depozito tipi
24. `agent`: Rezervasyonu yapan acente
25. `company`: Rezervasyonu yapan şirket
26. `days_in_waiting_list`: Bekleme listesindeki gün sayısı
27. `customer_type`: Müşteri tipi
28. `adr`: Ortalama günlük fiyat (Average Daily Rate)
29. `required_car_parking_spaces`: Gereken otopark alanı sayısı
30. `total_of_special_requests`: Özel talepler toplamı
31. `reservation_status`: Rezervasyon durumu
32. `reservation_status_date`: Rezervasyon durumu tarihi

## Analizler

### Müşteri Edinme Analizi
Müşteri edinme analizi, otelin yeni müşteri kazanma performansını değerlendirmek için yapılmıştır. Bu analizde kullanılan temel metrikler arasında yeni müşteri sayısı, pazar segmentlerine göre müşteri dağılımı ve müşteri edinme maliyetleri bulunmaktadır.

### Müşteriyi Elde Tutma Analizi
Müşteri sadakati ve tekrarlanan müşteri oranlarını değerlendirmek için yapılan analizdir. Bu analizde tekrarlanan müşteri oranı, müşteri sadakati ve müşteri memnuniyeti gibi metrikler kullanılmıştır.

### Gelir Analizi
Gelir analizi, otelin gelir performansını değerlendirmek için yapılmıştır. Bu analizde ortalama günlük fiyat (ADR), doluluk oranı ve toplam gelir gibi finansal metrikler kullanılmıştır.

## Kullanım

Proje dosyasını PowerBI Desktop uygulaması ile açarak analizleri inceleyebilir ve kendi verilerinizle çalışabilirsiniz. PowerPoint sunumu ile projenin özetini ve önemli bulgularını sunabilirsiniz.

## Lisans

Bu proje MIT Lisansı altında lisanslanmıştır. Daha fazla bilgi için `LICENSE` dosyasını inceleyebilirsiniz.

## İletişim

Herhangi bir sorunuz veya geri bildiriminiz için benimle iletişime geçmekten çekinmeyin:

- **Ad**: Emrah BAS
- **E-posta**: [bas_emrah@hotmail.com](mailto:bas_emrah@hotmail.com)
