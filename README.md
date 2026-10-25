# NEXA Shot — bản cài đặt · Releases

Công cụ chụp màn hình, ghi chú và **quay video màn hình** của **StarteeX** cho Windows 10/11.
Trang này chỉ chứa bộ cài và tệp cập nhật; mã nguồn được lưu riêng.

**[⬇ Tải bản mới nhất](https://github.com/Roccat92/nexa-shot-releases/releases/latest)** →
chọn tệp `NEXA-Shot_x.y.z_x64-setup.exe`.

---

## Cài đặt (Tiếng Việt)

1. Tải `NEXA-Shot_…_x64-setup.exe` ở trang Releases rồi mở.
2. **Nếu Windows hiện "Windows protected your PC" (SmartScreen):** bấm
   **More info** → **Run anyway**. Cảnh báo này xuất hiện vì bộ cài chưa có
   chứng chỉ ký mã thương mại — không phải do có virus. Chỉ chạy bộ cài tải
   từ đúng trang này.
3. Cài đặt không cần quyền quản trị (cài cho tài khoản hiện tại).
4. Xong. NEXA Shot **chạy ngầm ở khay hệ thống** giống Lightshot (biểu tượng
   chữ X vàng ở góc phải thanh tác vụ, có thể nằm trong mũi tên ^), **tự khởi
   động cùng Windows** và không mở cửa sổ nào. Lần đầu sẽ có một thông báo
   Windows báo app đang chạy.
5. Muốn xem cài đặt: chuột phải biểu tượng ở khay → **Mở NEXA Shot**
   (hoặc mở lại app từ Start menu) → biểu tượng bánh răng.

### Dùng hằng ngày
- **PrintScreen** → kéo chọn vùng → vẽ / gõ chữ → **Ctrl+C** → dán vào Zalo, Word…
- Rê chuột lên một cửa sổ rồi bấm một lần để chụp đúng cửa sổ đó.
- Nếu PrintScreen không phản hồi: thoát Lightshot (chuột phải biểu tượng
  Lightshot ở khay → **Exit**, hoặc gỡ Lightshot), rồi mở NEXA Shot → **Thử lại**.
  Trong lúc đó vẫn chụp được bằng **Ctrl+Shift+S**.
- Phím công cụ: V chọn · A mũi tên · R hình chữ nhật · T chữ · N đánh số ·
  B làm mờ · X pixel hoá · **O** trích chữ (OCR) · **Ctrl+P** ghim ảnh.
  **Esc** để thoát. **Ctrl+Shift+H** mở lịch sử ảnh.
- **Quay video màn hình** (từ 0.5.0): nhấn **Shift+PrintScreen** → kéo chọn vùng
  (hoặc bấm vào một cửa sổ) → chọn âm thanh (không tiếng / âm thanh máy / micro /
  cả hai) → **Bắt đầu quay**. Khung đỏ cho biết vùng đang quay; thanh nhỏ có
  tạm dừng, dừng, huỷ. Nhấn lại Shift+PrintScreen để dừng. Video MP4 lưu trong
  **Videos\NEXA Shot** và được sao chép sẵn — **Ctrl+V** để gửi qua Zalo, email.
  Khung đỏ và thanh điều khiển không lọt vào video.
- **Tách vật thể bằng AI** (từ 0.6.0): chọn vùng → nhấn **Q** (hoặc nút ✨) →
  bấm vào vật thể cần lấy. Bấm thêm để lấy thêm phần, **Alt+bấm** hoặc chuột
  phải để bỏ bớt. **Ctrl+C** chép vật thể với nền trong suốt, **Ctrl+S** lưu PNG,
  **Ctrl+P** ghim. Chạy ngay trên máy, không gửi ảnh đi đâu. Lần đầu dùng app tải
  model AI khoảng 43 MB (một lần duy nhất).
- **Hỏi AI** (từ 0.6.0): chọn vùng → nhấn **I** (hoặc nút 💬) → chọn **Đây là gì?**,
  **Mô tả, gợi ý in**, **Dịch chữ**, hoặc gõ câu hỏi riêng. Khi đang tách vật thể có
  nút "Hỏi AI về vật thể". Ảnh được gửi tới trợ lý AI của StarteeX để trả lời và
  không được lưu lại; đừng hỏi về ảnh có mật khẩu hay thông tin khách hàng.
- **Tìm ảnh** (Google Lens / Bing / Yandex / TinEye): bấm là mở thẳng trang kết
  quả kèm ảnh. Ảnh đi qua link tạm trên máy chủ StarteeX và **tự xoá sau 24
  giờ**; có thể tắt trong Cài đặt (khi đó tự dán ảnh vào trang).

### Cập nhật
Hoàn toàn tự động: khoảng 30 giây sau khi máy khởi động, NEXA Shot kiểm tra
bản mới, hiện thông báo "Đang cập nhật…", tự cài và tự mở lại (không cắt ngang
khi đang chụp). Mỗi bản cập nhật được ký số và được kiểm tra trước khi cài.

### Gỡ cài đặt
Settings → Apps → **NEXA Shot** → Uninstall. Cài đặt cá nhân được giữ lại.

---

## Install (English)

1. Download `NEXA-Shot_…_x64-setup.exe` from the latest release and run it.
2. If SmartScreen shows "Windows protected your PC", click **More info → Run
   anyway** (the installer is not commercially code-signed yet).
3. No admin rights needed. Press **PrintScreen** (or **Ctrl+Shift+S**) to
   capture, **Ctrl+C** to copy. Updates install from inside the app.
4. **Screen recording** (0.5.0+): **Shift+PrintScreen** → select an area →
   choose the sound → **Start recording**; press it again to stop. The MP4 is
   saved in Videos\NEXA Shot and copied — **Ctrl+V** to send it.
5. **AI object cut-out** (0.6.0+): select an area → **Q** → click the object →
   **Ctrl+C** copies it with a transparent background. Runs on the PC; the AI
   model (~43 MB) downloads once on first use.
6. **Ask AI** (0.6.0+): select an area → **I** → "What is it?", "Describe",
   "Translate" or your own question. The image is sent to StarteeX's AI
   assistant for the answer and is not stored.
