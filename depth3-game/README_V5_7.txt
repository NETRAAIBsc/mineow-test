MINEOW DEPTH 3 — V5.7 ROOM JUMP + SMASH

ĐÃ SỬA:
- Trong Door 1 / MerchRoom, Miner Cat có thể NHẢY.
- Trong Door 2 / ArtifactRoom, Miner Cat có thể NHẢY.
- Nút cuốc hoạt động trong cả 2 room: 1 nhấn = 1 nhát cuốc animation.
- Coin bonus được đặt cao hơn để người chơi phải nhảy lên chạm mới nhận.
- Coin chỉ cộng khi sprite mèo thật sự chạm coin.
- Secret Key vẫn chỉ nhận khi mèo thật sự chạm vào key.
- Depth 4 deadend cũng hỗ trợ jump/smash, nhưng logic seal giữ nguyên.

GIỮ NGUYÊN:
- Miner Cat / logo / coin / key / merch / artifact assets
- Không thêm popup text
- Cơ chế trừ coin và restart
- Tone nền và kích thước mèo V5.5

CHẠY:
cd ~/storage/downloads
unzip -o MINEOW_DEPTH3_WEB_V5_7_ROOM_JUMP_SMASH.zip -d MINEOW_DEPTH3_WEB_V5_7_ROOM_JUMP_SMASH
cd MINEOW_DEPTH3_WEB_V5_7_ROOM_JUMP_SMASH
python -m http.server 8099

MỞ:
http://127.0.0.1:8099/?v=5.7
