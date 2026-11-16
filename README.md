<p align="center">
  <img src="assets/tobiai.png" alt="Logo TobiAI" width="180">
</p>

# TobiAI — Làm phụ đề, dịch và lồng tiếng video

**TobiAI là ứng dụng desktop dành cho Windows, tập hợp công cụ OCR phụ đề, dịch thuật AI, tạo giọng đọc và xuất video trong cùng một không gian làm việc.** Bạn có thể bắt đầu từ video có chữ sẵn trên hình hoặc một file SRT, chỉnh nội dung, tạo bản dịch, lồng tiếng rồi xuất thành video hoàn chỉnh.

Ứng dụng hướng đến người làm Vietsub, biên tập video, bản địa hóa nội dung và xử lý nhiều tập phim hoặc video mà mình có quyền sử dụng.

**[Tải bộ cài beta.29](https://github.com/sinoisme2005-a11y/tobiai/releases/download/v1.2.0-beta.29/TobiAI-Setup-1.2.0-beta.29.exe)** · **[Xem các bản phát hành](https://github.com/sinoisme2005-a11y/tobiai/releases)** · **[Gửi phản hồi](https://github.com/sinoisme2005-a11y/tobiai/issues)**

> Phiên bản được giới thiệu: **1.2.0-beta.29**, phát hành ngày **16/11/2026**. Đây là kênh giới thiệu, tải ứng dụng và phân phối bản cập nhật TobiAI; mã nguồn ứng dụng không được cung cấp trong repository này.

## TobiAI giúp bạn làm gì?

- **Tách chữ phụ đề có sẵn trên hình:** chọn vùng OCR và nhận diện chữ để lấy nội dung kèm thời gian.
- **Dịch phụ đề có ngữ cảnh:** chọn ngôn ngữ đích, thể loại nội dung, tên nhân vật và cách xưng hô cần giữ thống nhất.
- **Tạo giọng đọc từ phụ đề:** chọn giọng, nghe thử, chỉnh tốc độ và ghép lời đọc theo thời gian câu.
- **Làm lại hình thức video:** bố trí phụ đề mới, che phụ đề gốc, thêm watermark và xem trước kết quả.
- **Quản lý công việc theo lô:** lưu cấu hình video, dùng preset và xếp nhiều video vào hàng chờ xử lý.
- **Tải và tổ chức video:** đưa nội dung được phép truy cập vào kho video, quản lý tập và chuyển sang Studio để xử lý.

## Tính năng chi tiết

### 1. Studio phụ đề và video

Studio kết hợp khung xem trước, vùng chọn trên video, bảng phụ đề và các điều khiển xử lý. Bạn có thể mở video từ máy hoặc từ kho video của ứng dụng, kiểm tra nội dung rồi điều chỉnh cấu hình cho từng video.

- Mở các định dạng video thông dụng như **MP4, MKV, MOV, AVI, TS**; khả năng giải mã còn phụ thuộc codec bên trong file.
- Nhập **SRT** có sẵn để tiếp tục biên tập. Bộ chọn file cũng nhận `.txt` nếu nội dung tuân theo cấu trúc phụ đề SRT có mốc thời gian.
- Kiểm tra, sửa nội dung phụ đề trước khi xuất và xuất file **SRT** để dùng ở công cụ khác.
- Chỉnh nội dung và thời điểm câu trên timeline; tìm/thay thế hoặc dịch mốc thời gian đồng loạt khi cần căn lại phụ đề.
- Lưu cấu hình riêng cho video và dùng preset cho những video có bố cục tương tự.
- Thêm video từ kho vào **hàng chờ Reup**, kéo thả để đổi thứ tự và xử lý lần lượt.

### 2. OCR: lấy phụ đề từ chữ trên hình

OCR phù hợp với video có phụ đề được ghép trực tiếp vào khung hình, thường gọi là phụ đề cứng hoặc hardsub.

- Kéo và chỉnh kích thước **khung quét OCR** để tập trung vào vùng phụ đề.
- Chọn chế độ **chữ Hán/Trung**, **chữ Latin/Anh**, tự nhận diện hoặc ngôn ngữ có tài nguyên nhận diện tương ứng.
- Chọn model OCR trong cài đặt; kiểm tra và tải thành phần còn thiếu qua **Trung tâm tài nguyên**.
- Tắt **Quét OCR** khi đã có SRT để dùng phụ đề nhập vào và bỏ qua bước nhận diện chữ.

Khung OCR, vùng **CHE SUB** và vị trí phụ đề mới được điều chỉnh riêng. Việc đổi vùng nhận diện không bắt buộc phải đổi vùng che hoặc vị trí hiển thị Vietsub.

OCR đọc chữ xuất hiện trên hình, không phải chức năng tự nghe lời thoại để tạo phụ đề. Chất lượng nhận diện phụ thuộc độ rõ của chữ, ngôn ngữ, chuyển động và vùng quét đã chọn.

### 3. Dịch phụ đề bằng AI

Phần dịch cho phép cấu hình nhiều nguồn và sắp xếp thứ tự ưu tiên để phù hợp với tài khoản, model và hạn mức bạn sử dụng.

- Tích hợp API **Google Gemini** và các API tương thích OpenAI, gồm cấu hình cho **OpenAI, DeepSeek, Grok** hoặc máy chủ tùy chỉnh.
- Nhập API key, chọn model và cấu hình nguồn trong ứng dụng. Tài khoản/API của nhà cung cấp do bạn tự chuẩn bị.
- Ngôn ngữ đích trong giao diện gồm **tiếng Việt, tiếng Anh, tiếng Trung, tiếng Nhật và tiếng Hàn**.
- Chọn ngữ cảnh như **tu tiên, cổ trang, đô thị, ngôn tình, kinh dị** hoặc tự quản lý danh sách ngữ cảnh.
- Khóa cách dịch **tên nhân vật, thuật ngữ và xưng hô** để các câu dùng nhất quán hơn.
- Có tùy chọn phân tích nội dung/xưng hô và giới hạn độ dài bản dịch.
- Dịch theo nhóm câu; giữ cấu trúc phụ đề và tái sử dụng phần đã xử lý khi phù hợp.
- Dùng **Dịch thử kiểm tra** để kiểm tra cấu hình trước khi xử lý video dài.

Một số lựa chọn Web/gateway còn có trong bản beta, nhưng tên lựa chọn không đồng nghĩa với kết nối chính thức đến từng dịch vụ hoặc bảo đảm một model cụ thể. Khi cần kiểm soát nhà cung cấp và model, hãy cấu hình API tương ứng. Hạn mức, phí API và khả năng đáp ứng do nhà cung cấp quyết định.

### 4. Tạo giọng đọc và lồng tiếng

TobiAI tạo lời đọc từ nội dung phụ đề rồi sắp xếp âm thanh theo thời gian của từng câu.

- **CapCut:** nguồn giọng đọc trực tuyến; danh sách giọng và khả năng sử dụng phụ thuộc dịch vụ.
- **VieNeu:** lựa chọn tạo giọng tiếng Việt trên máy sau khi đã có model và môi trường tương thích.
- Chọn giọng, làm mới danh sách, **nghe thử** và điều chỉnh tốc độ đọc.
- Xử lý âm thanh theo thời lượng câu để hỗ trợ khớp lời đọc với phụ đề.
- Tái sử dụng âm thanh đã tạo khi nội dung và cấu hình tương ứng không đổi.
- Điều chỉnh âm lượng tiếng gốc, giọng lồng và thêm âm thanh nền cho video.

Nên nghe thử một đoạn ngắn trước khi chạy cả video, nhất là đoạn có tên riêng, số hoặc câu dài. Phần tạo giọng VieNeu có thể chạy cục bộ; việc đăng nhập, xác thực bản quyền và các nguồn dịch/giọng trực tuyến vẫn cần mạng.

### 5. Phụ đề, che chữ và xuất video

- Tùy chỉnh **phông chữ, cỡ chữ, màu chữ, viền, nền và vị trí** phụ đề.
- Dùng **CHE SUB** để đặt vùng che/làm mờ phụ đề gốc.
- Chèn ảnh logo; thêm **watermark chữ** cố định hoặc chuyển động và điều chỉnh theo bố cục video.
- Xem trước bố cục trước khi xuất để kiểm tra vùng che, chữ và khung hình.
- Xuất video **MP4/H.264** cùng phụ đề và âm thanh theo cấu hình đã chọn.
- Chọn mã hóa bằng **CPU**, **NVIDIA NVENC**, **AMD AMF** hoặc **Intel Quick Sync**, tùy phần cứng, driver và kết quả kiểm tra thực tế.
- Có tùy chọn chuyển/render lại bằng CPU khi bộ mã hóa GPU gặp lỗi.

GPU hỗ trợ bước mã hóa tương thích; các bước xử lý hình ảnh, phụ đề hoặc âm thanh vẫn có thể dùng CPU. Chọn GPU không có nghĩa là toàn bộ quy trình đều chạy trên GPU.

### 6. Tải video và quản lý thư viện

Khu vực **Tải & quản lý video** giúp gom nội dung đầu vào và đưa trực tiếp sang Studio.

- Tìm/duyệt nội dung từ các nguồn có trong giao diện, gồm **Mạn kịch, Hồng quả (Hongguo), Hỏa long và Bilibili**.
- Tích hợp **Douyin** qua dịch vụ phân tích link có thể cấu hình.
- Quản lý hàng đợi tải, thư mục lưu và kho video.
- Xem các tập đã có, mở tập vào Studio và ghép các tập tương thích theo khoảng hoặc toàn bộ tập đã tải.
- Có công cụ kiểm tra dịch vụ tải để phân biệt thiếu tài nguyên cục bộ với lỗi kết nối hoặc phân tích link.

Khả năng tải phụ thuộc nền tảng, dịch vụ trung gian và quyền truy cập nội dung; không bảo đảm mọi liên kết đều tải được. Chỉ sử dụng với nội dung bạn sở hữu hoặc được phép tải và biên tập.

### 7. Trung tâm tài nguyên

Trung tâm tài nguyên tập hợp trạng thái các thành phần cần cho OCR, giọng đọc và xử lý video.

- Kiểm tra model/thành phần đang có và tải hoặc sửa phần còn thiếu.
- Tải thành phần cần cho lựa chọn hiện tại, tránh phải tải mọi model tùy chọn.
- Kiểm tra **GPU/FFmpeg** và khả năng khởi tạo bộ mã hóa.
- Mở trang driver chính hãng khi cần cập nhật driver.

Có thể dùng chế độ CPU mà không cài CUDA. Các chế độ tăng tốc hoặc model tùy chọn có yêu cầu riêng; hãy xem trạng thái tài nguyên ngay trong ứng dụng.

## Cài đặt và bắt đầu

### Chuẩn bị

- Máy chạy **Windows x64**; bản phát hành này không có bộ cài macOS hoặc Linux.
- Dung lượng trống cho ứng dụng, model tùy chọn, video đầu vào, file tạm và video xuất.
- Kết nối Internet cho đăng nhập, bản quyền, tải tài nguyên, cập nhật và dịch vụ AI trực tuyến.
- API key/tài khoản của nguồn dịch nếu bạn chọn nguồn yêu cầu chúng.

Bộ cài đã kèm runtime cần thiết; người dùng không cần tự cài Python. Mức RAM, dung lượng và thời gian xử lý phụ thuộc độ phân giải, độ dài video, model và số tác vụ. Chưa có cấu hình tối thiểu được xác nhận trên đầy đủ các loại máy.

### Cài ứng dụng

1. Tải **`TobiAI-Setup-1.2.0-beta.29.exe`** từ [bản phát hành beta.29](https://github.com/sinoisme2005-a11y/tobiai/releases/tag/v1.2.0-beta.29).
2. Chạy bộ cài và làm theo hướng dẫn. Mặc định ứng dụng được cài theo người dùng Windows, trong thư mục LocalAppData.
3. Mở **TobiAI** từ Start Menu hoặc lối tắt trên Desktop nếu đã chọn tạo lối tắt.
4. Hoàn tất đăng nhập và kiểm tra bản quyền theo hướng dẫn trong ứng dụng.
5. Vào **Tài nguyên** để kiểm tra thành phần cần cho OCR/giọng đọc bạn chọn.
6. Mở **Cấu hình chung**, thiết lập nguồn dịch và giọng đọc, rồi thử một video ngắn.

Trong mục Assets của release, file ZIP có tên là một chuỗi hash và `release-envelope.json` phục vụ bộ cập nhật tự động. Người cài lần đầu nên dùng file **Setup.exe**. Mục **Source code** do GitHub tạo không phải bộ cài TobiAI.

### Quy trình làm một video

1. **Mở video:** chọn file trên máy hoặc đưa video từ kho vào Studio.
2. **Chuẩn bị phụ đề:** chỉnh khung OCR nếu video có chữ sẵn; nếu đã có SRT, nhập SRT và tắt Quét OCR.
3. **Cấu hình dịch:** chọn ngôn ngữ đích, ngữ cảnh, nguồn dịch và các tên/thuật ngữ cần giữ.
4. **Cấu hình giọng đọc:** chọn nguồn, giọng và tốc độ cho quy trình lồng tiếng/xuất video.
5. **Bố trí hình ảnh:** chỉnh Vietsub, CHE SUB và watermark; xem trước để tránh che nhầm nội dung.
6. **Xử lý và kiểm tra:** chạy tác vụ, rà lại nội dung phụ đề và lời đọc; chỉnh khi cần trước khi xuất.
7. **Xuất kết quả:** lưu SRT hoặc xuất video theo nhu cầu. Khi cấu hình ổn, dùng preset/hàng chờ cho các video tiếp theo.

## Tài khoản và bản quyền

TobiAI có đăng nhập Google và khu vực quản lý bản quyền trong ứng dụng. Phiên đăng nhập và key được lưu bằng cơ chế bảo vệ **Windows DPAPI**, gắn với môi trường người dùng Windows. Ứng dụng vẫn cần liên hệ máy chủ để xác thực; không nên coi key đã lưu là chế độ sử dụng ngoại tuyến vĩnh viễn.

### Get Key miễn phí 24 giờ

Dịch vụ Get Key hiện dùng **Link4M**. Việc chuyển nhà cung cấp đã triển khai trên
máy chủ; người dùng beta.29 không cần cài lại ứng dụng. Tạo link Link4M đã được
kiểm tra online thành công với phản hồi HTTPS hợp lệ.

1. Mở khu vực bản quyền và bấm **Get Key 24h (miễn phí)**.
2. Trình duyệt mở link Link4M; thực hiện các bước được hiển thị để đến trang kết quả.
3. Sao chép mã xác minh dạng **`XXXX-XXXX`**.
4. Quay lại TobiAI, nhập mã và bấm **Nhận key**.
5. Chờ máy chủ xác thực thành công; trạng thái và thời hạn key hiển thị trong ứng dụng.

Ở beta.29, nếu máy chủ đã cấp key nhưng lần xác thực tiếp theo lỗi mạng, ứng dụng giữ key ở trạng thái chờ để thử lại. Bạn có thể thử lại cùng mã hoặc mở lại app; key chỉ được kích hoạt sau khi xác thực thành công. Nếu trình duyệt không mở, ứng dụng báo lỗi; bấm Get Key lại sẽ dùng link còn hạn hoặc tạo link mới khi link cũ đã hết hạn.

### Bản quyền vĩnh viễn

Giao diện hiện có tùy chọn **Mua vĩnh viễn — 200.000đ** và **Khôi phục key đã mua**. Hãy xem thông tin đơn hàng và trạng thái thực tế trong ứng dụng trước khi thanh toán. Giá và điều kiện áp dụng theo thông tin tại thời điểm mua; phí dịch vụ AI bên ngoài, nếu có, được tính riêng theo nhà cung cấp.

## Cập nhật ứng dụng

TobiAI kiểm tra kênh phát hành GitHub khi mở ứng dụng và có thao tác kiểm tra cập nhật trong giao diện. Gói cập nhật được kiểm tra chữ ký **Ed25519** và hash trước khi áp dụng.

- Lưu công việc đang làm trước khi cập nhật và làm theo thông báo khởi động lại.
- Nếu cần cài đầy đủ runtime hoặc cài lần đầu, sử dụng bộ cài từ trang Releases.
- Bản cập nhật được thông báo khi ứng dụng hoạt động; không có dịch vụ thông báo chạy khi app đã đóng.

Chữ ký gói cập nhật là cơ chế riêng với chữ ký Windows: bộ cài và launcher hiện **chưa có chữ ký Authenticode**.

### Điểm mới của beta.29

- Khôi phục key đã cấp nhưng chưa xác thực thành công khi gặp lỗi mạng.
- Báo đúng lỗi mở trình duyệt và cho mở lại link Get Key còn hạn.
- Giữ key/phiên bản quyền đang dùng nếu lần kích hoạt mới thất bại.
- Sửa việc launcher cũ nạp module license cũ sau khi nâng cấp.

Bản phát hành đã đạt **326 kiểm thử native**, kiểm tra khởi động EXE và nâng cấp từ beta.28 trên bản sao môi trường kiểm thử. Các file đã đăng được đối chiếu hash; gói cập nhật tải lại đã được xác minh chữ ký và giải nén.

Khi phát hành beta.29, tạo link YeuMoney đã được kiểm tra online thành công. Sau đó
dịch vụ Get Key chuyển sang Link4M và tạo link Link4M cũng đã được kiểm tra online
thành công. Toàn bộ bước quảng cáo → nhập mã → nhận key bằng tài khoản thật, thanh
toán thật và cài đặt trên máy sạch vẫn cần kiểm thử riêng; các kiểm tra tự động
không thay thế những bước này.

## Câu hỏi thường gặp

### Có cần GPU rời không?

Không bắt buộc cho chế độ CPU. GPU phù hợp có thể hỗ trợ một số bước, nhưng cần driver và tài nguyên tương thích. Vào **Tài nguyên → Kiểm tra GPU / FFmpeg** để xem khả năng trên máy của bạn.

### Có dùng hoàn toàn offline được không?

Không. OCR, xử lý hình ảnh, render và VieNeu có thể xử lý cục bộ khi đủ tài nguyên, nhưng tài khoản/bản quyền và các dịch vụ trực tuyến vẫn cần kết nối mạng.

### Video không có chữ sẵn thì OCR có tạo phụ đề không?

OCR nhận diện chữ trên hình. Nếu video không có phụ đề cứng, hãy chuẩn bị SRT phù hợp rồi nhập vào; tính năng OCR không thay cho nhận dạng lời nói.

### Đã có SRT thì có cần quét OCR lại không?

Không. Nhập SRT và tắt **Quét OCR**. Kiểm tra mốc thời gian của file khớp với video trước khi dịch hoặc tạo giọng.

### Vì sao dịch hoặc tạo giọng bị lỗi?

Kiểm tra kết nối, API key, model, hạn mức và tình trạng nhà cung cấp. Với VieNeu, kiểm tra model/tài nguyên trên máy. Dùng **Dịch thử kiểm tra** hoặc **Nghe thử** để thử riêng từng dịch vụ.

### Get Key báo tạm thời không khả dụng thì làm gì?

Kiểm tra mạng và thử lại sau. Nếu vừa nhận key nhưng xác thực bị gián đoạn, thử lại cùng mã hoặc mở lại ứng dụng. Không gửi key, mã xác minh hoặc thông tin tài khoản lên Issues công khai.

### Tải video lỗi thì làm gì?

Kiểm tra liên kết và quyền truy cập, dùng chức năng kiểm tra dịch vụ tải, rồi xem trạng thái tài nguyên hoặc máy chủ nguồn. Một số lỗi phát sinh từ phía nền tảng/dịch vụ và không thể giải quyết chỉ bằng cài lại ứng dụng.

## Dữ liệu và phản hồi

Video và các bước xử lý cục bộ được thực hiện trên máy. Khi dùng nguồn dịch hoặc giọng đọc online, nội dung cần xử lý được gửi tới dịch vụ bạn chọn; các tính năng đăng nhập, bản quyền và tải video cũng liên hệ dịch vụ tương ứng. Việc dùng TobiAI không đồng nghĩa mọi dữ liệu đều ở chế độ offline.

Bạn có thể dùng nút phản hồi trong ứng dụng hoặc [tạo Issue](https://github.com/sinoisme2005-a11y/tobiai/issues). Để dễ kiểm tra lỗi, hãy cung cấp:

- Phiên bản TobiAI, phiên bản Windows và cấu hình CPU/GPU liên quan.
- Các bước tái hiện, điều mong đợi và lỗi thực tế.
- Nguồn dịch/giọng hoặc loại tác vụ đang dùng; **không kèm API key**.
- Ảnh giao diện hoặc đoạn thông báo lỗi đã che thông tin riêng tư.

Không đăng key bản quyền, token, cookie, mã xác minh hoặc toàn bộ file cấu hình cá nhân. Chỉ chia sẻ video, giọng nói và phụ đề mà bạn có quyền cung cấp.
