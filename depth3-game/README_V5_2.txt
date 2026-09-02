MINEOW DEPTH 3 — V5.2 UI + CAT SCALE FIX

ĐÃ SỬA:
1) Nút điều khiển bên trái nhỏ lại
- Joystick giảm từ 128px xuống 108px
- Knob giảm tương ứng
- Dịch xuống/gọn hơn để bớt che gameplay

2) Khi bắt đầu game không che mất chú mèo
- Vị trí spawn ban đầu dời sang phải
- Checkpoint đầu cũng dời theo để hồi sinh không bị chồng lên joystick

3) Chú mèo cao và to hơn một ít cho hợp nền game
- Main map: tăng từ 98x146 lên 110x164
- Room scenes: tăng từ 86x118 lên 96x132
- Deadend/Depth 4 scene: tăng từ 90x132 lên 98x142

GIỮ NGUYÊN:
- Asset mèo, logo, key, merch, artifact, cửa và toàn bộ nội dung đã duyệt
- Logic hố ở bản V5.1

CHẠY:
cd ~/storage/downloads
unzip -o MINEOW_DEPTH3_WEB_V5_2_UI_CAT_SCALE_FIX.zip -d MINEOW_DEPTH3_WEB_V5_2_UI_CAT_SCALE_FIX
cd MINEOW_DEPTH3_WEB_V5_2_UI_CAT_SCALE_FIX
python -m http.server 8094

MỞ:
http://127.0.0.1:8094/?v=5.2
