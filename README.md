# Xyber_Auto_SPin

Link AIdrop : https://t.me/HVchannelss/271

Tham Gia Discor ( Vip ) : https://discord.gg/gKxvTNu5

Tham gia NHóm VIp Với Chi Phí 8u/1thang Lợi ích tham gia nhóm ViP Sẽ được cấp keey sử dụng các tool vip trong discor hỗ trợ Và tham khao Code các tool dự án mà các bạn đề xuất

Gửi Phí tháng vào đây và chụp hình gửi trực tiếp cho tôi tại discor để xác nhận Role VIp ☕ https://huynhviet933.github.io/donate_viet_mmo/ Có thể tặng tôi ít cafe tại đây

=========================================================================
          HƯỚNG DẪN SỬ DỤNG XYBER AUTO BOT V7 (RAINBOW & SILENT)
=========================================================================

1. YÊU CẦU HỆ THỐNG:
   - Đã cài đặt Node.js (Phiên bản 18 trở lên).
   - Kết nối Internet ổn định (hoặc Proxy sạch).

2. CÀI ĐẶT THƯ VIỆN (Chạy lệnh này tại thư mục chứa tool):
   npm install axios ethers chalk gradient-string ora uuid https-proxy-agent

3. CHUẨN BỊ DỮ LIỆU (Tạo các file .txt sau trong cùng thư mục):
   - privatekeys.txt : Mỗi dòng chứa 1 Private Key ví ETH (Dùng để Login).
   - proxy.txt       : Mỗi dòng chứa 1 Proxy (Định dạng: http://user:pass@ip:port hoặc ip:port).
   - user_agents.txt : Mỗi dòng chứa 1 User-Agent trình duyệt (Để giả lập người dùng thật).
   - SOL.txt         : Mỗi dòng chứa 1 địa chỉ ví Solana (Dùng để làm nhiệm vụ Link ví).

4. CÁCH VẬN HÀNH TOOL:
   - Mở Terminal/Command Prompt tại thư mục tool.
   - Chạy lệnh: node up.js (Hoặc tên file bạn đã lưu).
   - Nhập License Key khi được yêu cầu (Key sẽ được lưu vào file license.key cho lần sau).

5. CƠ CHẾ HOẠT ĐỘNG:
   - License Check : Xác thực phần cứng và Key với server trước khi khởi động.
   - Đa luồng (10)  : Tool chạy cuốn chiếu 10 ví cùng lúc. Ví nào xong sẽ tự lấy ví tiếp theo.
   - Delay Logic   : 
     + Khởi động mỗi luồng cách nhau 3-10 giây.
     + Sau khi Login, đợi 1-5 giây mới Spin.
     + Sau khi Spin, đợi 1-7 giây mới Link Solana.
     + Xong 1 tài khoản, nghỉ 10-60 giây mới sang tài khoản mới.
   - Vòng lặp      : Sau khi chạy hết danh sách ví, tool nghỉ 12 tiếng rồi tự động chạy lại.

6. LƯU Ý BẢO MẬT:
   - Không chia sẻ file Profiles.json và license.key cho người khác.
   - Hãy đảm bảo số lượng ví Solana trong SOL.txt đủ cho số lượng ví ETH của bạn.
=========================================================================
