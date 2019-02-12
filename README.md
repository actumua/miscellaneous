# Miscellaneous
Dưới đây là tổng hợp các file mẹo vặt, giúp ích cho bạn trong công việc.

# Batch tắt GTA

- Khi bạn bị đứng máy, Ctrl Alt Delete không xử lý được thì batch này sẽ giải quyết giúp bạn.
- Gồm 3 file: 
	+ AutoHotKey.exe (file đã được compiled, bạn chỉ cần bỏ `killgta.bat` vào thư mục D:\Files và dùng phím tắt Ctrl + K để tắt game thôi)
	+ AutoHotkey.ahk (file mã nguồn, bạn có thể edit lại phím tắt tuỳ thích)
	+ killgta.bat (chỉ khi GTA SAN chạy với quyền admin)

Không có quyền admin, bạn sửa toàn bộ file `killgta.bat` thành:

taskkill /F /IM "gta_sa.exe" /T

Liên hệ facebook của mình nếu bạn có thắc mắc: fb.me/kophaitin
