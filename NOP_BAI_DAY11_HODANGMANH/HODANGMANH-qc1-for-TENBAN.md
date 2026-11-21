# Phiếu QC 1 — Road v1.0

> MẪU CHỜ KIỂM THỰC TẾ — CHƯA PHẢI PHIẾU QC HOÀN THÀNH.
> Người kiểm: HODANGMANH. Phải điền kết quả từ lô được phân công của bạn khác; không dùng 4 cảnh báo tự kiểm trên bộ nhãn HODANGMANH để làm kết quả QC của bạn được kiểm.

Lô được kiểm (học viên): `[HỌ TÊN NGƯỜI BẠN ĐƯỢC PHÂN CÔNG KIỂM]`  
Người kiểm (học viên): HODANGMANH  
Ngày: `[NGÀY KIỂM THỰC TẾ]`  
Phiên bản guideline: Road v1.0  
File được kiểm (tên + revision trong manifest): `[FILE CỦA BẠN ĐƯỢC KIỂM, REVISION]`  
Số ảnh kiểm: 6 (+ `[SỐ ẢNH THÊM, NẾU CÓ]` ảnh thêm, ghi riêng)  
Số nhãn đã kiểm (shape + tag): `[ĐẾM TỪ SÁU ẢNH THỰC SỰ KIỂM]`

## Tổng hợp theo mã

> Điền Số mục kiểm và Số lỗi từ việc nhìn từng ảnh/nhãn; không tự điền số 0 nếu chưa kiểm.

| Mã | Loại lỗi | Số mục kiểm | Số lỗi | Mức |
| --- | --- | ---: | ---: | --- |
| QC1-01 tag camera | sai thuộc tính / bỏ sót | — | — | nặng |
| QC1-02 đủ L1, R1 | bỏ sót | — | — | nặng |
| QC1-03 position | sai thuộc tính / thừa | — | — | nặng |
| QC1-04 tâm vạch, chiều, điểm dừng | sai phạm vi / bỏ sót | — | — | chính |
| QC1-05 vạch đứt, che | sai phạm vi / sai thuộc tính | — | — | chính |
| QC1-06 style, color, kind | sai thuộc tính | — | — | chính |
| QC1-07 vùng lái | sai phạm vi / bỏ sót / thừa | — | — | chính |
| QC1-08 đèn, màu | bỏ sót / sai phạm vi / sai thuộc tính | — | — | nặng / chính |
| QC1-09 facing, type, group, biển phụ | sai thuộc tính | — | — | chính |
| QC1-10 hình in, đủ biển | bỏ sót / sai phạm vi | — | — | chính |
| QC1-11 fisheye | sai phạm vi / sai thuộc tính | — | — | chính |
| QC1-12 file | lỗi file | — | — | nhẹ / nặng |

## Danh sách lỗi (mỗi lỗi một dòng)

| # | Mã | Ảnh | Nhãn (label, id) | Mức | Mô tả ngắn |
| --- | --- | --- | --- | --- | --- |
| `[ĐIỀN KHI PHÁT HIỆN]` | — | — | — | — | — |

## Ca mơ hồ

| Ảnh | Câu hỏi cho lead | Lời đáp (nếu có) |
| --- | --- | --- |
| `[NẾU CÓ]` | — | — |

## Quyết định

Lỗi nặng: `[CẦN ĐẾM]`  
Lỗi chính: `[CẦN ĐẾM]` / `[SỐ NHÃN ĐÃ KIỂM]` nhãn = `[CẦN TÍNH]` %  
Lỗi nhẹ: `[CẦN ĐẾM]`  
Ca chờ lead: `[CẦN ĐẾM]`  
Quyết định (Release / Hold / Rework): `[CHƯA QUYẾT ĐỊNH]`  
Lý do (theo luật của phiếu): `[ĐIỀN SAU KHI KIỂM VÀ THAM KHẢO docs/qc_severity_road_v1.0.md]`

Ghi nhớ: Bỏ sót = thiếu nhãn phải có; thừa = gán cái không phải đối tượng; sai phạm vi = hình lệch, sai chiều, dừng sai chỗ, tràn vùng. Quyết định QC phải dựa trên ảnh gốc/GT và rubric, không chỉ kết quả `road_check lint`.
