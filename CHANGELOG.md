# Lịch sử phiên bản

## 1.0.2 – góp ý của người dùng sau ngày phát hành (18/11/2026)
- **Mã NV nhập linh hoạt**: bỏ quy định dạng "chữ cái + số" – dùng đúng mã đơn vị đang có (VD: 0001, HĐ-01/A, KT 001.B), tối đa 20 ký tự, phần mềm tự viết hoa; chỉ không dùng các ký tự < > " ' ` \. App nhân viên đăng nhập được với mọi mã hợp lệ.
- **Số sổ BHXH nhập linh hoạt**: bỏ bắt buộc đủ 10 chữ số – nhập đúng như trên sổ / tờ khai (tối đa 30 ký tự).
- **Tự động đồng bộ máy chủ và app nhân viên** (bản đầy đủ): không cần bấm "Đồng bộ ngay". Phần mềm tự đồng bộ khi mở / vừa thiết lập máy chủ, khoảng 15 giây sau mỗi thay đổi dữ liệu và 5 phút một lần khi đang mở – đẩy danh sách nhân viên, tài khoản, hồ sơ, lịch làm lên máy chủ; lấy lượt chấm, đơn từ về phần mềm. Nút "Đồng bộ ngay" vẫn giữ khi cần lấy dữ liệu tức thì. Nhiều người quản trị cùng mở phần mềm: phần dữ liệu do đồng bộ tự sinh được tự gộp, không hỏi "giữ bản của ai".
- **Sửa lỗi đánh dấu "Đã nộp" vẫn hiện "Còn thiếu"** ở Hồ sơ nhân sự → Tổng hợp giấy tờ (xảy ra với người chưa có dòng giấy tờ nào); dữ liệu đã đánh dấu trước đây tự được khôi phục, không phải làm lại.
- **Sửa lỗi danh mục giấy tờ tự rút còn 1–2 loại** sau khi bấm Lưu một ô; danh mục đầy đủ tự hiện lại.
- **Đánh dấu "Đã nộp" là đủ**, không bắt buộc tải file. Ô đã nộp nhưng chưa có file scan trong Kho có thêm chấm cam nhỏ ở góc (rê chuột thấy "chưa có file scan") – file scan chỉ để lưu trữ, xem lại.

## 1.0.1 – sửa lỗi, cải thiện sau thử nghiệm thực tế (18/11/2026)
- **Thêm công ty** (đổi tên từ "Thêm đơn vị"): tạo công ty trống không cần chọn file; chọn file / thư mục từ nút này thì dữ liệu vào một công ty mới, không lẫn vào công ty đang xem; thêm xong vẫn ở trang Cài đặt.
- **Thương hiệu riêng từng công ty**: logo, tên, màu. Xem một công ty: cả phần mềm theo thương hiệu công ty đó; xem Tổng các công ty: khung theo thương hiệu chung, mỗi nhân sự có chấm màu và logo nhỏ của công ty mình (danh sách, hồ sơ, sơ đồ tổ chức).
- **Hồ sơ nhân sự → Tài khoản app nhân viên**: tên đăng nhập, tình trạng, ngày cấp, đăng nhập lần cuối; chưa có thì nút **Tạo tài khoản**.
- **Sửa Mã NV**: mọi dữ liệu liên quan đổi theo (hồ sơ, hợp đồng, chấm công, lương, đơn, hội nhập, đào tạo, tài sản, file đính kèm, dữ liệu trên máy chủ); không cho đổi sang mã đang có hoặc đã từng có; tài khoản app đăng nhập lại bằng mã mới, mã PIN giữ nguyên.
- **Mã NV trùng giữa các công ty dùng chung máy chủ**: cảnh báo ở Danh sách nhân sự, Ứng dụng nhân viên, hồ sơ; chặn cấp tài khoản app cho người trùng mã (tránh lẫn chấm công, phiếu lương); mã tự sinh khi nhập file không trùng công ty khác.
- **Sơ đồ tổ chức**: ô phòng ban trình bày cân đối (tên, số người, nhân sự căn giữa); kéo người vào ô Trưởng bộ phận đang trống (hoặc bấm ô để chọn); đủ định biên thì không hiện nút thêm người.
- **Kiêm nhiệm ở mọi bộ phận, cả khác công ty**: bấm ô Còn trống (hoặc "+ Thêm người") để chọn người trong toàn hệ thống, ghi vị trí kiêm nhiệm (VD: Kế toán trưởng); kéo người từ công ty khác sang cũng được. Người kiêm nhiệm lấp vị trí theo định biên nhưng không tính vào số người đang làm, lương, bảo hiểm của công ty đó; hồ sơ gốc giữ nguyên. Hồ sơ nhân sự (phần Công việc) có trường **Kiêm nhiệm** liệt kê mọi vị trí kiêm nhiệm, thêm / bỏ ở đây thì sơ đồ đổi theo và ngược lại.
- **Nghỉ phép – phép tồn và sửa tay** (góp ý người dùng): Quy định phép năm có tùy chọn **cho chuyển phép chưa nghỉ sang năm sau**, chọn hạn dùng (VD đến hết 31/03 năm sau) và số ngày tối đa được chuyển. Đầu năm phần mềm tự tính phép tồn, ngày nghỉ phép trừ vào phép tồn trước, quá hạn thì phần chưa dùng hết hiệu lực. Bảng Quỹ phép năm có cột Phép tồn năm trước (còn bao nhiêu, hạn đến ngày nào) và nút **Sửa** để nhập tay số ngày phép còn lại, phép tồn – dùng khi bắt đầu dùng phần mềm giữa năm; có ghi lý do, người sửa, thời điểm.
- **Dữ liệu trên Google Drive** (mục Nhập dữ liệu): hướng dẫn dùng **Google Drive cho máy tính** – Drive hiện như ổ đĩa, chọn thư mục như bình thường, không phải chia sẻ công khai (khuyên dùng). Bản đầy đủ thêm **Dán link Google Drive / Google Sheets**: máy chủ tải hộ file (Google Sheets tự chuyển sang Excel, tối đa 15 MB); file phải bật chia sẻ "Bất kỳ ai có đường liên kết" nên có cảnh báo bảo mật dữ liệu cá nhân (Luật 91/2025), bắt buộc tích đã hiểu, tải xong nhắc chuyển về "Bị hạn chế".
- **Gửi email tự động** (bản đầy đủ): Cài đặt → Gửi email tự động – kết nối dịch vụ Resend bằng email công ty, có hướng dẫn 5 bước, nút gửi thử. Nút **Gửi qua email** ở Tuyển dụng (thư mời phỏng vấn, mời nhận việc, thông báo kết quả…) gửi thật và ghi vào lịch sử ứng viên. Khóa API lưu trên máy chủ riêng của đơn vị, chỉ Quản trị hệ thống thiết lập.
- **Giao diện**: thanh đầu trang cân đối 2 dòng (dòng 1: đơn vị, công ty, ngày tính bên trái – tài khoản, nút công cụ bên phải; dòng 2: ô tìm kiếm – trạng thái lưu máy chủ thành dòng chữ nhỏ); nút **thu gọn danh sách chức năng** để trang rộng hết màn hình, bấm lại để mở ra (nhớ trên máy); tab chọn công ty ở mọi trang nổi bật, dễ thấy đang xem công ty nào; trang Tổng hợp công gom bộ lọc thành một thanh, báo cáo thành hàng tab, bảng công lên gần đầu trang; Đội ngũ ở Bảng điều hành xếp Ban Giám đốc lên đầu.
- Bản đầy đủ không còn hiện thanh "Đã sửa … dòng dữ liệu, chưa ghi ra file Excel gốc" – mọi thay đổi đã tự lưu trên máy chủ.
- **Lịch sử điều chuyển có ngày hiệu lực**: chuyển phòng ban (kéo thả trên sơ đồ) hoặc đổi phòng ban, chức danh ở Sửa thông tin đều hỏi ngày hiệu lực, số quyết định. Hồ sơ có tab **Quá trình công tác** (từ ngày, đến ngày, phòng ban, chức danh, căn cứ), thêm được các lần điều chuyển trước khi dùng phần mềm. Cơ cấu nhân sự, bảng lương, bảng công theo tháng xếp người vào đúng phòng ban của tháng đó.
- **Nhập chấm công từ máy vân tay**: chọn **tháng chấm công** (ngày ngoài tháng tự bỏ qua, có báo); bảng **Khớp người trên máy chấm công** – mã và tên trên máy khớp với nhân viên nào, theo cách nào (Mã NV, mã chấm công, họ tên, tên gần giống), chọn tay người chưa khớp; mã máy được lưu vào ô Mã chấm công trong hồ sơ, tháng sau tự khớp theo mã. File nhiều trang tính (mỗi trang một đơn vị): chọn công ty cho từng trang tính, tự gợi ý theo tên trang tính. Ngày thiếu giờ vào hoặc giờ ra hiện "?" chờ người phụ trách xác nhận.
- **Chấm công Wi‑Fi cho công ty thứ 2 trở đi** (trước đây không kết nối được): chọn **Dùng chung máy chủ này** (cùng văn phòng, cùng Wi‑Fi – chung Wi‑Fi văn phòng, app nhân viên, trang quản lý máy chủ; trang quản lý có ô chọn xem từng công ty) hoặc **Máy chủ riêng của công ty** (công ty độc lập – dán địa chỉ và mã kết nối của máy chủ riêng). Khi dùng chung, mỗi công ty chỉ nhận lượt chấm, đơn từ của nhân viên mình.
- **Cổng tuyển dụng của công ty** (bản đầy đủ): trang tuyển dụng ngay trên tên miền công ty – `<địa chỉ máy chủ>/tuyen-dung/<tên công ty>`, mỗi vị trí một link riêng; ứng viên nộp CV (PDF/ảnh ≤ 5 MB) trên điện thoại, phần mềm tự lấy hồ sơ về Ngân hàng ứng viên mỗi 45 giây khi đang mở, lấy xong máy chủ xóa bản tạm. Không còn dùng cổng thử 24 giờ. Mở/cập nhật/đóng cổng ở Tuyển dụng → Cổng tuyển dụng.
- **Gửi thông báo nội bộ** tách thành mục riêng (trước nằm trong "Thông tin chung toàn công ty", nay đổi tên **Kho văn bản chung**). Có **thời gian lưu thông báo** (6 / 12 / 24 tháng / không giới hạn, mặc định 12 tháng; quá hạn máy chủ tự xóa mỗi ngày) và thanh **dung lượng dữ liệu máy chủ**, cảnh báo khi đạt 80% hạn mức gói miễn phí Cloudflare D1 (500 MB).
- **App nhân viên – Chuông thông báo** có thêm mục **Lưu trữ thông báo nội bộ**: mọi thông báo đã nhận, kể cả đã xóa khỏi danh sách Mới; gõ từ để tìm (không cần gõ dấu).
- **Gửi email tự động**: email gửi đi bắt buộc thuộc tên miền của đơn vị (tự nhận từ địa chỉ máy chủ; máy chủ chạy trên workers.dev thì nhập tên miền ở ô **Tên miền của đơn vị**); nhập email khác tên miền (Gmail, Yahoo…) phần mềm báo và không cho lưu.
- **Bỏ mục Danh mục** trong Hệ thống: Phòng ban xem ở Sơ đồ tổ chức → Bảng phòng ban; **Chức vụ** chuyển thành nút thứ 3 trong Sơ đồ tổ chức.
- Sửa lỗi cấp tài khoản hàng loạt có thể mất mã PIN trên máy chủ (báo "chưa có PIN trên máy chủ").
- **Nhập file**: cột tiền (Lương cơ bản, Phụ cấp điện thoại…) không còn bị ghép nhầm vào Phòng ban, Số điện thoại; danh sách nhân sự kèm mức lương (có CCCD) được nhận là Hồ sơ nhân viên.
- Bản đầy đủ ghi đúng nơi lưu dữ liệu (máy chủ riêng của công ty) thay cho câu "xử lý ngay trên máy"; hồ sơ hiện "Thâm niên: —" khi chưa có ngày vào làm.

## 1.0.0 – bản chính thức đầu tiên (16/11/2026)
- Phát hành mã nguồn mở theo giấy phép GNU AGPL-3.0.
- Hai phiên bản: **bản rút gọn** (1 người dùng, chạy trên trình duyệt, không cần máy chủ) và **bản đầy đủ** (máy chủ Cloudflare riêng của đơn vị, app cho nhân viên, nhiều tài khoản).
- Dữ liệu trống hoàn toàn, màn hình khởi tạo lần đầu: tạo công ty, tải logo, nạp file hoặc khôi phục bản sao lưu.
- Cài đặt → **Thương hiệu**: tải logo, đổi tên hiển thị, dòng phụ, chọn hình minh họa (Đốm, logo của đơn vị hoặc không dùng hình); bản đầy đủ áp dụng cả tên và biểu tượng app nhân viên.
- Cài đặt → **Dữ liệu & sao lưu**: dữ liệu đang lưu ở đâu, thư mục trên máy, dung lượng, trạng thái Lưu bền, lần sao lưu gần nhất; Bảng điều hành nhắc khi quá 7 ngày chưa sao lưu.
- Bản rút gọn ghi rõ các phần chỉ có ở bản đầy đủ (Chấm công Wi‑Fi, Ứng dụng nhân viên, Phân quyền tài khoản, Gửi báo cáo định kỳ, cổng ứng tuyển trực tuyến).
- Phông chữ đóng kèm trong phần mềm, không tải từ Google Fonts.
- Dòng "Tác giả: Quản trị tử tế" ở chân thanh bên trái và cuối trang Cài đặt.

## Các bản dùng thử trước bản chính thức
Dữ liệu mẫu hư cấu, chạy trên quantritute.com.

- **1.0.1** (18/11/2026) – Bản chính thức · Nhiều công ty, thương hiệu riêng · Kiêm nhiệm · Lịch sử điều chuyển · Phép tồn · Nhập chấm công máy vân tay · Gửi email tự động · Dữ liệu trên Google Drive · Cổng tuyển dụng của công ty · Gửi thông báo nội bộ, lưu trữ thông báo
- **0.8.1** (16/11/2026) – Một tài khoản cho app và trang quản trị · App nhân viên trên máy tính · Đơn xin đi muộn, về sớm · Báo cáo đi muộn, về sớm · Thiết bị, tài sản · Thông tin chung toàn công ty · Gửi thông báo, chuông thông báo trên app · Gửi báo cáo định kỳ
- **0.7.1** (13/11/2026) – Phân quyền tài khoản: Tài khoản, Vai trò và quyền, Người duyệt đơn · Nhập dữ liệu theo từng bước · Ghép cột từ file bất kỳ · Bảng phân loại nhiều file · Lịch sử nhập và hoàn tác · Bộ phận của tôi trên app nhân viên
- **0.6.1** (12/11/2026) – Hội nhập nhân sự mới · Thiết lập hành trình · Hành trình hội nhập trên app nhân viên · Kho khóa học · Theo dõi học tập · Học trên app nhân viên · Bảo hiểm xã hội: Danh sách đóng BH, Đối chiếu C12, Thiết lập BHXH
- **0.5.1** (11/11/2026) – Nhu cầu tuyển dụng · Ngân hàng ứng viên · Lịch phỏng vấn · Kết quả phỏng vấn · Cổng tuyển dụng
- **0.4.1** (10/11/2026) – Cơ cấu nhân sự · Bảng lương · Phiếu lương · Bảng chi lương · Thiết lập tính lương
- **0.3.1** (08/11/2026) – Thiết lập chấm công · Tổng hợp công · Nghỉ phép · Chấm công Wi‑Fi
- **0.2.1** (07/11/2026) – Sơ đồ tổ chức · Danh sách nhân sự · Hồ sơ nhân sự · Hợp đồng
- **0.1.1** (06/11/2026) – Bảng điều hành · Việc cần xử lý · Việc định kỳ
