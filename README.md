# 🚀 VibeForge — Hướng dẫn Cài đặt, Sử dụng & Gia hạn Toàn diện

Chào mừng bạn đến với **VibeForge** — công cụ tạo nội dung bằng AI giúp tối ưu hoá quy trình làm video TikTok Affiliate, Reels, Shorts. VibeForge tạo video, tạo & chỉnh sửa ảnh, làm nét ảnh/video, và clone video đối thủ — tất cả chạy trên đám mây **Roboneo/Meitu** nên máy bạn không bị nóng, không chiếm CPU/GPU.

> 💡 **Mẹo vàng:** Toàn bộ chi phí render được tính bằng **cà rốt (credits)** trong tài khoản Roboneo.

---

## 📥 1. Tải & Cài đặt

1. **Tải phần mềm:** Tải bản mới nhất từ mục **Releases** trên GitHub (file installer `.exe`, ví dụ `vibeforge-setup-26.6.5.exe`).
2. **Cài đặt:** Double-click file `.exe` để cài tự động. Phần mềm sẽ tạo shortcut ngoài Desktop.
3. **Nếu Windows cảnh báo:** Khi Windows Defender / SmartScreen hiện cảnh báo (do app chưa mua chứng chỉ số doanh nghiệp), nhấn **More info → Run anyway** để tiếp tục.
4. **Tự động cập nhật:** VibeForge tự kiểm tra và tải bản mới nhất khi khởi động. Khi có bản mới, bạn chỉ cần nhấn cập nhật — không phải tải lại thủ công.

> ⚠️ **Quan trọng:** Hãy luôn dùng **bản mới nhất**. Các bản cũ sẽ không còn được hỗ trợ và có thể không kích hoạt được.

---

## 🔑 2. Kích hoạt & Gia hạn Bản quyền (License Key)

### 🛡️ Kích hoạt lần đầu
1. Mở app lần đầu, màn hình kích hoạt sẽ hiện ra.
2. Nhập mã có dạng `XXXXX-XXXXX-XXXXX-XXXXX-XXXXX`.
3. Nhấn **Kích hoạt**. Mỗi mã gắn với **một máy tính** — muốn đổi máy hãy liên hệ Admin để reset.

### 💸 Gia hạn
* Khi key sắp hết hạn (trong 7 ngày) hoặc đã hết, app hiện nút **"Liên hệ Admin"**.
* Liên hệ Admin của bạn để được cấp hoặc gia hạn key.

---

## 🥕 3. Cấu hình Tài khoản Roboneo

VibeForge render qua tài khoản Roboneo có sẵn **cà rốt**. Đây là phần quan trọng nhất để app chạy được.

### 🛒 Cấu hình tài khoản
Vui lòng sử dụng các tài khoản Roboneo hợp lệ đã nạp sẵn cà rốt để phục vụ tạo nội dung.

> ✅ Để app hoạt động ổn định và tránh lỗi đăng nhập, hãy đảm bảo tài khoản của bạn hoạt động bình thường trên hệ thống.

### ⚙️ Thêm tài khoản vào app
1. Mở tab **Tài khoản (Accounts)** ở menu trái.
2. Nhấn **Thêm tài khoản** → nhập **Email** + **Mật khẩu** tài khoản Roboneo (có thể dán hàng loạt nhiều dòng).
3. Nhấn **Lưu**. App tự kiểm tra trạng thái và hiển thị số cà rốt còn lại của từng tài khoản.
4. **Mẹo:** Lọc nhanh các tài khoản sắp hết cà rốt để chủ động nạp thêm hoặc thay tài khoản.

> 💡 **App tự chia việc thông minh:** khi tạo nhiều video cùng lúc, app tự động phân bổ job sang các tài khoản đủ cà rốt và chạy song song — càng nhiều tài khoản, càng nhiều luồng chạy đồng thời, càng nhanh.

---

## 🎬 4. Tab Motion — Tạo Video Hàng Loạt

Tạo video chất lượng cao từ **ảnh nhân vật tĩnh** + **video mẫu chuyển động**.

1. Mở tab **Motion**.
2. Chọn **Ảnh nhân vật** (JPG/PNG), **Video mẫu** (MP4) và **Thư mục lưu**.
3. Chọn **Model AI**:
   * **Kling 3.0** — chất lượng đỉnh, mượt nhất. **206 cà rốt/video**.
   * **Kling 2.6** — tiết kiệm, chất lượng vẫn rất tốt. **72 cà rốt/video**.
4. (Tuỳ chọn) Viết **Prompt** riêng hoặc dùng mẫu có sẵn.
5. Nhấn **Tạo video**. App tải lên đám mây, render khoảng **6–10 phút/video**, rồi **tự tải file `.mp4` về** thư mục đã chọn.

---

## 🖼️ 5. Tab Tạo Ảnh (Image Gen) — 2 chế độ

Tab Tạo Ảnh chia làm 2 chế độ ở phía trên:

### ✏️ Edit Image (mặc định) — Sửa nhiều ảnh cùng lúc
* **Mỗi ảnh tải lên = 1 dòng (row) riêng**, có ô nhập prompt riêng cho từng ảnh.
* Có thể thêm nhiều ảnh vào một dòng (giống GPT cho nhiều ảnh tham chiếu).
* **Ô nhập prompt hàng loạt ở trên cùng:** dán nhiều prompt (mỗi dòng 1 prompt) rồi nhấn **Phối prompt** để rải tự động xuống từng dòng ảnh bên dưới.
* Tỉ lệ mặc định **9:16** (chuẩn dọc TikTok/Reels).
* Mỗi dòng = 1 ảnh kết quả. Ảnh lưu trong thư mục con `image/edit/`.

### 📝 Text to Image — Tạo ảnh từ chữ
* Nhập nhiều prompt, **mỗi dòng 1 prompt**.
* Chọn **số ảnh mỗi prompt**. Ví dụ: 2 prompt × 3 ảnh = 6 ảnh.
* Ảnh lưu trong thư mục con `image/text/`.

> 🥕 Tạo/chỉnh ảnh thường tốn khoảng **10 cà rốt/ảnh** (tuỳ model).

---

## ✨ 6. Tab Làm Nét (Enhance) — Làm nét & khử nhiễu hàng loạt

Nâng cấp chất lượng **ảnh và video** đã có sẵn.

1. Mở tab **Làm nét (Enhance)**.
2. Kéo thả (hoặc chọn) **nhiều ảnh** và/hoặc **nhiều video** vào 2 khu vực tương ứng.
3. Với ảnh, chọn thao tác:
   * **Khử nhiễu (Denoise)** — xoá hạt/nhiễu.
   * **Làm nét (Enhance)** — tăng độ sắc nét, chi tiết.
   * Có thể **bật cả hai** (app chạy khử nhiễu trước, rồi làm nét).
4. Với video: **Làm nét HD**.
5. Nhấn chạy. Kết quả lưu gọn vào thư mục con: ảnh → `enhance/image/`, video → `enhance/video/`.

> 🥕 Làm nét/khử nhiễu ảnh ~**3 cà rốt/thao tác**; làm nét video HD ~**15 cà rốt/video**.

---

## 👯 7. Tab Clone Video — Nhân bản video đối thủ

Lấy video đối thủ làm mẫu và thay bằng nhân vật của bạn.

1. Mở tab **Clone Video**, dán **link video đối thủ** (hoặc link kênh để lấy nhiều video).
2. **Bước nhân vật & nền:**
   * **Ảnh mẫu (bắt buộc):** ảnh nhân vật của bạn.
   * **Ảnh nền (tuỳ chọn):**
     * Không chọn nền → giữ nguyên nền của ảnh mẫu.
     * Có chọn nền → đặt nhân vật vào nền mới (app tự hoà sáng, đổ bóng, cân màu cho tự nhiên).
3. **Chế độ tạo:**
   * **Tự động** — chạy thẳng từ ghép ảnh đến ra video, không cần duyệt.
   * **Thủ công** — tạo ảnh ghép trước để bạn **duyệt**, ưng rồi mới tạo video.
4. **Cài đặt nâng cao (nút bên cạnh "Cấu hình"):**
   * **Tự khắc phục khi ảnh lỗi (20001)** — *mặc định BẬT*. Khi tạo ảnh dính lỗi nội dung/hệ thống "20001", app tự chạy quy trình khắc phục nhiều bước để vẫn ra ảnh dùng được, thay vì để job thất bại. Tốn thêm vài cà rốt nhưng ít video bị lỗi hơn nhiều. Tắt đi nếu muốn tiết kiệm tối đa (lỗi 20001 sẽ làm job dừng ngay).

---

## ❓ 8. Lỗi Thường Gặp & Cách Khắc Phục

| Lỗi | Nguyên nhân | Cách xử lý |
|---|---|---|
| 🔴 **System Busy / Lỗi 20001** | Máy chủ Roboneo quá tải giờ cao điểm, hoặc nội dung bị bộ lọc của Roboneo chặn. | App tự thử lại + đổi tài khoản/IP. Chờ **1–3 phút** rồi **Chạy lại** nếu cần. Với Clone, bật "Tự khắc phục khi ảnh lỗi" để app tự xử lý. |
| 🥕 **Không đủ cà rốt** | Tài khoản Roboneo còn ít cà rốt hơn mức cần (206 / 72 / 10 / 3 tuỳ chức năng). | Đổi sang tài khoản nhiều cà rốt hơn hoặc nạp thêm cà rốt. App tự chia nhỏ chi phí qua nhiều tài khoản khi có thể. |
| 🔑 **Đăng nhập thất bại** | Tài khoản không hợp lệ, hết hạn, hoặc không được hỗ trợ. | Đảm bảo thông tin đăng nhập chính xác và tài khoản hoạt động bình thường. |
| ⏫ **Yêu cầu cập nhật (Upgrade Required)** | Bạn đang dùng bản app cũ. | Cập nhật lên bản mới nhất (app tự nhắc khi mở), hoặc tải lại từ Releases. |
| 🌐 **Lỗi kết nối** | Mạng gián đoạn hoặc API đang bảo trì. | Kiểm tra mạng, thử lại sau ít phút. |

---

## 📞 9. Hỗ trợ

* 🛒 Mua hoặc gia hạn tài khoản Roboneo: Liên hệ Admin của bạn.
* 💬 Hỗ trợ / gia hạn key: Liên hệ Admin của bạn.

---
*Chúc bạn bùng nổ doanh số cùng **VibeForge**! 🚀*
