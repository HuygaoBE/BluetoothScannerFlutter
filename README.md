# Bluetooth Scanner Flutter

**_[Language VietNamese]_**

Ứng dụng Bluetooth Scanner Flutter đơn giản có thể nhận diện các gói quảng cáo Advertisement, có thể nhận diện các dạng quảng cáo như, quét quảng cáo không phản hồi, quảng cáo phản hồi...nhận diện dữ liệu quảng cáo dành riêng cho nhà sản xuất, nhận diện url...
![](https://github.com/HuygaoBE/BluetoothScannerFlutter/blob/main/images/find_device.PNG | width=150) ![](https://github.com/HuygaoBE/BluetoothScannerFlutter/blob/main/images/show_adv.PNG | width=150)

## 🔑Features
Ứng dụng này có thể quét các gói quảng cáo, do các thiết bị bluetooth phát ra và phản hồi các gói tin quảng cáo yêu cầu quét phản hồi.

Quét các gói tin quảng cáo:
  * Tên thiết bị quảng cáo đầy đủ(Complete Local Name: 0x09).
  * Tên thiết bị quảng cáo rút gọn(Shortened Local Name: 0x08).
  * Cờ(Flags: 0x01).
  * Danh sách đầy đủ các UUID lớp dịch vụ(UUID: 0x03).
  * Dữ liệu dành riêng cho nhà sản xuất(Manufacturer specific data: 0xFF).
  * Cường độ tính hiệu(RSSI)
  * ...

## 🔧Installation setup
Các class interface của thư viện [Flutter_blue](https://pub.dev/packages/flutter_blue)
 * BluetoothDevice: Có thể quét và kết nối các thiết bị bluetooth lân cận.
 * BluetoothService: Có thể khám phá các dịch vụ Bluetooth, sau khi được kết nối với thiết bị.
 * BluetoothCharacteristic;  BluetoothDescriptor: Các đặc điểm của thiết bị phát các gói quảng cáo Bluetooth
   * UUID(16bit, 128bit)
   * PDU quảng cáo
   * AD Type thường gặp
   
 * Để hiểu thêm về giao thức Bluetooth đầy đủ, mời bạn có thể tham khảo tài liệu do tôi viết: [Document](https://github.com/HuygaoBE/ProductAdvertisingBLE/blob/main/B1709280-%20Nguy%E1%BB%85n%20Thanh%20Huy-%20H%E1%BB%87%20th%E1%BB%91ng%20qu%E1%BA%A3ng%20c%C3%A1o%20s%E1%BA%A3n%20ph%E1%BA%A9m%20d%E1%BB%B1a%20tr%C3%AAn%20c%C3%B4ng%20ngh%E1%BB%87%20Bluetooth-Mobile%20App.pdf)

## 📘Main libraries used
* [Flutter_blue](https://pub.dev/packages/flutter_blue)

  * FlutterBlue là một plugin bluetooth cho Flutter , một SDK ứng dụng mới để giúp các nhà phát triển xây dựng các ứng dụng đa nền tảng hiện đại.

## 🌏Other Social Media

📌[GitHub](https://github.com/HuygaoBE)

📌[FaceBook](https://www.facebook.com/profile.php?id=100007416721622)

Vui lòng đánh giá sao cho các dự án của tôi trên GitHub, để tôi có thêm động lực để tạo ra nhiều dự án hữu ích cho cộng đồng.
