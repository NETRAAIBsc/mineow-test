MINEOW DEPTH 3 — V5.4 COIN DAMAGE SYSTEM

CƠ CHẾ MỚI:
- Mỗi lần va chạm thật với vật cản/enemy: trừ 1 coin.
- Mỗi lần rơi xuống hố: trừ 1 coin.
- Có cooldown va chạm nên một lần chạm không bị trừ nhiều coin liên tiếp.
- Khi coin giảm về 0: tự động bắt đầu lại từ đầu Depth 3.

KHI BẮT ĐẦU LẠI:
- Coin = 0
- Coin trên map xuất hiện lại
- Key reset về 0
- 3 cửa reset
- Checkpoint reset
- Xe bị phá được phục hồi
- Miner Cat trở về vị trí đầu game

KHÔNG THÊM POPUP/TEXT TRONG GAME.
GIỮ NGUYÊN TOÀN BỘ ASSET VÀ GIAO DIỆN V5.3.

CHẠY:
cd ~/storage/downloads
unzip -o MINEOW_DEPTH3_WEB_V5_4_COIN_DAMAGE_SYSTEM.zip -d MINEOW_DEPTH3_WEB_V5_4_COIN_DAMAGE_SYSTEM
cd MINEOW_DEPTH3_WEB_V5_4_COIN_DAMAGE_SYSTEM
python -m http.server 8096

MỞ:
http://127.0.0.1:8096/?v=5.4
