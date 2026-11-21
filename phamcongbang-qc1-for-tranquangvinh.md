# Phiếu QC 1 — Road v1.0

Lô được kiểm: Trần Quang Vinh  
Người kiểm: Phạm Công Bằng  
Ngày: 21/11/2026  
Phiên bản guideline: Road v1.0  
File được kiểm: tranquangvinh-front.zip, tranquangvinh-fisheye.zip  
Số ảnh kiểm: 6 ảnh chính và 8 ảnh thêm  
Số nhãn đã kiểm: 116 nhãn  

## Tổng hợp theo mã
| Mã | Loại lỗi | Số mục kiểm | Số lỗi | Mức |
| --- | --- | ---: | ---: | --- |
| QC1-01 tag camera | sai thuộc tính / bỏ sót | 24 | 0 | nặng |
| QC1-02 đủ L1, R1 | bỏ sót | 9 | 0 | nặng |
| QC1-03 position | sai thuộc tính / thừa | 13 | 0 | nặng |
| QC1-04 tâm vạch, chiều, điểm dừng | sai phạm vi / bỏ sót | 13 | 0 | chính |
| QC1-05 vạch đứt, che | sai phạm vi / sai thuộc tính | 13 | 0 | chính |
| QC1-06 style, color, kind | sai thuộc tính | 13 | 0 | chính |
| QC1-07 vùng lái | sai phạm vi / bỏ sót / thừa | 19 | 0 | chính |
| QC1-08 đèn, màu | bỏ sót / sai phạm vi / sai thuộc tính | 25 | 0 | nặng / chính |
| QC1-09 facing, type, group, biển phụ | sai thuộc tính | 58 | 2 | chính |
| QC1-10 hình in, đủ biển | bỏ sót / sai phạm vi | 33 | 1 | chính |
| QC1-11 fisheye | sai phạm vi / sai thuộc tính | 9 | 0 | chính |
| QC1-12 file | lỗi file | 116 | 0 | nhẹ / nặng |

## Danh sách lỗi
| # | Mã | Ảnh | Nhãn | Mức | Mô tả ngắn |
| --- | --- | --- | --- | --- | --- |
| 1 | QC1-09 | A08 | traffic_sign 11 | chính | Biển tên đường màu xanh lá ở góc ngã tư gán front, nên chọn side |
| 2 | QC1-09 | A08 | traffic_sign 30 | chính | Biển phụ hạn chế xe gắn kèm biển chỉ dẫn nên chọn prohibitory |
| 3 | QC1-10 | A10 | traffic_sign 13 | chính | Khung viền biển báo ở xa vẽ hơi rộng ở mép dưới |

## Ca mơ hồ
| Ảnh | Câu hỏi cho lead | Lời đáp |
| --- | --- | --- |
| A08 | Đường không có vạch kẻ tim đường thì có bị tính thiếu L1 không | Không tính lỗi vì mặt đường thực tế không có vạch sơn |

## Quyết định
Lỗi nặng: 0  
Lỗi chính: 3 / 116 nhãn = 2.59%  
Lỗi nhẹ: 0  
Ca chờ lead: 0  

Quyết định: Release  
Lý do: Không có lỗi nặng và tỉ lệ lỗi chính 2.59% nằm dưới mức cho phép 5%.
