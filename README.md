# Xưởng học CAD · BIM · M&E

Web app học và thực hành **AutoCAD, Revit, M&E Design và PLC**, giao diện tiếng Việt, cài được lên iPhone như một ứng dụng và chạy cả khi không có mạng.

**Link app:** https://dykhanhnehi.github.io/xuong-hoc/

## Nội dung

- **AutoCAD**: giao diện, hệ tọa độ, bắt điểm, lệnh vẽ và hiệu chỉnh, layer, block, xref, ghi chú, layout và in.
- **Revit**: tư duy BIM, Category/Family/Type, view, Level/Grid, dựng kiến trúc cơ bản, Revit MEP (điện, HVAC, nước), phối hợp va chạm, hồ sơ.
- **M&E Design**: phụ tải, chọn CB và cáp, sụt áp, bù công suất phản kháng, chiếu sáng, nối đất và chống sét, HVAC, cấp thoát nước, PCCC.
- **PLC**: cấu trúc và chu kỳ quét, đấu nối vào ra, địa chỉ, Ladder (tự giữ, liên động), timer, counter, analog, IEC 61131-3, truyền thông, chẩn đoán lỗi.

## Thực hành

- Phòng vẽ mô phỏng AutoCAD có dòng lệnh (L, C, REC, E, U, Z), 6 bài vẽ tự chấm.
- Sắp xếp trình tự dựng mô hình Revit (kiến trúc, điện, HVAC).
- 8 dạng bài tính M&E có số liệu ngẫu nhiên và lời giải từng bước.
- Bàn mô phỏng PLC Ladder: 6 bài (tự giữ, đảo chiều, TON, sao tam giác, đếm sản phẩm), nhấn nút chạy thử và chấm tự động.
- Luyện phím tắt AutoCAD và Revit, thẻ ghi nhớ, trắc nghiệm có giải thích.

## Dự án thực hành

5 dự án nối tiếp trên cùng một xưởng mẫu, làm trên phần mềm thật, có bảng tự kiểm tra:

1. Bộ bản vẽ điện xưởng sản xuất (AutoCAD)
2. Hồ sơ tính toán điện (Excel/Sheets, DIALux)
3. Mô hình Revit MEP điện
4. Trạm bơm hai bơm luân phiên (PLC + HMI)
5. Đóng gói hồ sơ năng lực

## Cài lên iPhone

1. Mở link app bằng **Safari**.
2. Bấm nút **Chia sẻ**, chọn **Thêm vào MH chính**.

## Ghi chú

- Tiến độ học được lưu ngay trên thiết bị đang dùng.
- Công thức và giá trị tiêu chuẩn chỉ để tham khảo khi học; khi thiết kế thật cần đối chiếu tiêu chuẩn hiện hành, catalog nhà sản xuất và yêu cầu dự án.

## Cấu trúc file

| File | Vai trò |
|---|---|
| `index.html` | Toàn bộ app |
| `manifest.webmanifest` | Tên, icon, chế độ toàn màn hình khi cài |
| `sw.js` | Lưu bộ nhớ đệm để chạy offline |
| `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` | Icon app |
