# CyberAttack_CVE_Microsoft_Exchange_Serve

# Tổng quan đề tài 
Thời gian phát hiện 
Vào cuối tháng 9/2022, GTSC đã báo cáo về một cuộc tấn công vào cơ sở hạ tầng quan 
trọng diễn ra vào tháng 8/2022. Trong quá trình điều tra, các chuyên gia phát hiện ra 
rằng hai lỗ hổng zero-day trong Microsoft Exchange Server đã được sử dụng trong cuộc 
tấn công.  
Lỗ hổng đầu tiên, sau này được xác định là CVE-2022-41040, là lỗ hổng giả mạo yêu cầu 
phía máy chủ (SSRF), cho phép kẻ tấn công được xác thực kích hoạt từ xa lỗ hổng tiếp 
theo – CVE-2022-41082.  
Lỗ hổng thứ hai cho phép thực thi mã từ xa (RCE) khi kẻ tấn công có thể truy cập MS 
Exchange PowerShell.  
Như đã lưu ý trong báo cáo GTSC, cả hai lỗ hổng đều bị khai thác cùng nhau để tạo 
backdoor trên máy chủ bị tấn công. 
Link bài báo cáo của GTSC: 
https://gteltsc.vn/blog/warning-new-attack-campaign-utilized-a-new-0day-rce-vulnerability-on-microsoft-exchange-server-12715.html