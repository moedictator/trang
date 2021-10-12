# Quy trình check SMS

### Các rủi ro có thể xuất hiện khi TVTS gửi SMS

| STT | Các rủi ro có thể xuất hiện khi TVTS gửi SMS                                                                                                                                                |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | SMS ảo (note MOL sms nhưng không có lịch sử sms)                                                                                                                                            |
| 2   | SMS không gửi được do gửi tới mạng VietnamMobile                                                                                                                                            |
| 3   | SMS không gửi được do sai định dạng SDT (thừa số 0/thiếu số)                                                                                                                                |
| 4   | SMS không gửi được do thuê bao klld/thuê bao chặn sms từ SM/...                                                                                                                             |
| 5   | SMS không gửi được do chứa từ cấm                                                                                                                                                           |
| 6   | SL ký tự >160                                                                                                                                                                               |
| 7   | SMS cho level không được phép sms                                                                                                                                                           |
| 8   | **Nội dung** nhắc lịch Test cho HV cụ thể được nhắn qua MOL                                                                                                                                 |
| 9   | **Nội dung** quảng cáo, ưu đãi thể hiện trong file đặt hàng SS                                   Check vào **thứ 5 hàng tuần** [https://tinyurl.com/y8kdttfa](https://tinyurl.com/y8kdttfa) |
| 10  | **Nội dung** đúng/sai? (Tên TVTS?/Tên + Địa chỉ Cơ sở SM)                                                                                                                                   |

### **QUY TRÌNH CHECK SMS h**àng ngày

**Bước 1.** Vào Lịch sử SMS

![Đảo chiều mũi tên --> Click "Lịch sử SMS"](<../../../.gitbook/assets/1 (9).png>)

**Bước 2.** Lọc SMS

![](<../../../.gitbook/assets/2 (8).png>)

**Bước 3.** Điền nội dung nhận xét SMS [https://bit.ly/3j1RxK9](https://bit.ly/3j1RxK9)

![](<../../../.gitbook/assets/3 (8).png>)

### QUY TRÌNH CHECK SMS hàng tuần

Bổ sung các rủi ro có thể có với SMS hàng tuần

| STT | Rủi ro với SMS hàng tuần                                                                                                                           |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | MOL note sms đặt hàng SS nhưng không có trong DS đặt hàng                                                                                          |
| 2   |  **SMS** với các Level C, các CTS sai số, không có SĐT                                                                                             |
| 3   | Nội dung nên linh hoạt, không nên luôn luôn là ưu đãi sẽ khiến nhờn thông tin, nên nhắn thêm về nhận diện thương hiệu và tăng độ thân thiết với KH |

1. Check level của sms đặt hàng gửi
