---
title: "Sự kiện 2"
date: 2026-06-13
weight: 2
chapter: false
pre: " <b> 4.2. </b> "
---

# Báo cáo tổng kết: “FCAJ Meetup – Career, DevOps, AWS Architecture & MNC Culture”

### Mục tiêu sự kiện

- Giúp sinh viên hiểu rõ hơn về định hướng nghề nghiệp trong lĩnh vực công nghệ thông tin và cloud.
- Chia sẻ góc nhìn thực tế về công việc DevOps Engineer trong môi trường doanh nghiệp.
- Giới thiệu cách thiết kế một hệ thống URL Shortening Service có khả năng mở rộng trên AWS.
- Cung cấp thông tin về các chương trình cộng đồng AWS như First Cloud AI Journey, AWS Student Builder Group, AWS Community Builder và AWS Partner.
- Chia sẻ kinh nghiệm thực tế về Data Analytics Engineer, tư duy phát triển nghề nghiệp và văn hóa làm việc tại tập đoàn đa quốc gia.
- Giúp sinh viên chuẩn bị tốt hơn về kỹ năng chuyên môn, tư duy hệ thống, giao tiếp và khả năng thích nghi với môi trường làm việc thực tế.

### Diễn giả

- **Trong H. Truong** – DevOps Engineer @ Endava Vietnam  
- **Đinh Trung Kiên** – Lead Developer at Startup  
- **Nguyễn Minh Thọ** – Student  
- **Danh Hoàng Hiếu Nghị** – AI Engineer, AWS Community Builder, AWS Student Builder Group Leader  
- **Đạt Phạm** – Data Analytics Engineer  
- **Cường Nguyễn** – Process Engineer  

### Nội dung nổi bật

#### Góc nhìn thực tế về công việc DevOps Engineer

Phần chia sẻ về DevOps giúp tôi hiểu rõ hơn rằng DevOps không chỉ đơn giản là người viết pipeline CI/CD, triển khai Docker/Kubernetes hoặc sửa lỗi production lúc nửa đêm. Trong thực tế, DevOps là một vai trò liên quan đến hệ thống, quy trình, tự động hóa, vận hành và hỗ trợ đội ngũ phát triển phần mềm làm việc hiệu quả hơn.

Một số ý chính bao gồm:

- DevOps không chỉ là tập hợp các công cụ như CI/CD, Docker, Kubernetes, Cloud hoặc Monitoring.
- Công việc DevOps cần hiểu cách ứng dụng được build, test, deploy, log và cấu hình trong từng môi trường.
- Những kiến thức nền tảng như Linux, Networking, Git, CI/CD, Python/Golang và Container rất quan trọng.
- DevOps cần biết đặt câu hỏi “tại sao” trước khi hỏi “làm như thế nào”.
- Giao tiếp là một phần quan trọng của công việc, vì DevOps thường phải phối hợp với nhiều nhóm khác nhau.
- Một DevOps tốt không chỉ biết dùng tool, mà còn biết tư duy hệ thống, tự động hóa công việc lặp lại và làm mọi thứ rõ ràng hơn cho team.

#### Thiết kế hệ thống URL Shortening Service trên AWS

Phần trình bày về URL Shortening Service giúp tôi hiểu cách một hệ thống rút gọn URL có thể được thiết kế trên AWS theo hướng có khả năng mở rộng. Từ một luồng đơn giản giữa user, frontend, backend và database, phần trình bày đi sâu hơn vào kiến trúc thực tế với các dịch vụ như CloudFront, AWS WAF, Amazon Amplify, Amazon ECS, Amazon ElastiCache và DynamoDB.

Một số nội dung chính bao gồm:

- URL Shortener giúp chuyển một đường dẫn dài thành một đường dẫn ngắn, dễ chia sẻ hơn.
- Luồng cơ bản gồm người dùng gửi URL, frontend chuyển request đến backend, backend tạo short code và lưu vào database.
- Cách triển khai đơn giản có ưu điểm là dễ làm và chi phí thấp, nhưng có thể gặp vấn đề về bảo mật, độ trễ, single point of failure và khó mở rộng.
- Frontend có thể sử dụng Amazon CloudFront, AWS WAF và Amazon Amplify để phân phối nội dung, bảo vệ hệ thống và triển khai ứng dụng dễ hơn.
- Key Generation Service có thể tạo sẵn short code và lưu vào Redis thông qua Amazon ElastiCache để giảm tải khi có nhiều request.
- Backend Service có thể dùng Amazon ECS, Spring Boot, Redis cache và DynamoDB để xử lý luồng tạo link và điều hướng link.
- Kiến trúc có thể áp dụng cache-aside pattern để đọc dữ liệu nhanh hơn và giảm số lần truy vấn trực tiếp vào database.

#### Hành trình từ First Cloud AI Journey đến AWS Partner

Phần chia sẻ của anh Danh Hoàng Hiếu Nghị giúp tôi có thêm góc nhìn về cách tham gia cộng đồng AWS và phát triển con đường nghề nghiệp trong lĩnh vực cloud. Nội dung cho thấy việc có được công việc đầu tiên chỉ là bước khởi đầu, sau đó mỗi người vẫn cần tiếp tục học hỏi, xây dựng kinh nghiệm và định hướng con đường riêng.

Một số điểm nổi bật bao gồm:

- First Cloud AI Journey là một chương trình giúp sinh viên tiếp cận cloud và AI một cách có định hướng.
- Sau khi bắt đầu sự nghiệp, mỗi người có thể phát triển theo nhiều hướng như Solutions Architect, DevOps Engineer, Platform Engineer hoặc Software Engineer.
- AWS Student Builder Group là một môi trường để sinh viên học tập, kết nối và phát triển cùng cộng đồng AWS.
- AWS Community Builder Program giúp những người yêu thích công nghệ chia sẻ kiến thức và đóng góp cho cộng đồng.
- AWS Partner mở ra cơ hội làm việc chuyên sâu hơn với hệ sinh thái AWS và các doanh nghiệp sử dụng cloud.
- Việc kết nối, học hỏi và xây dựng thương hiệu cá nhân trên LinkedIn cũng là một phần quan trọng trong quá trình phát triển nghề nghiệp.

#### Công việc Data Analytics Engineer trong doanh nghiệp

Phần chia sẻ về Data Analytics Engineer giúp tôi hiểu rằng công việc phân tích dữ liệu không chỉ là làm báo cáo hoặc tạo dashboard. Tùy vào domain, mô hình kinh doanh và phòng ban hỗ trợ, Data Analytics Engineer có thể tham gia vào nhiều bài toán thực tế khác nhau.

Một số ý chính bao gồm:

- Trong doanh nghiệp vận hành, Data Analytics Engineer có thể xây dựng báo cáo theo ngày, tuần, tháng, quý để theo dõi hiệu suất.
- Dashboard giúp doanh nghiệp theo dõi xu hướng dữ liệu, phát hiện bất thường và hỗ trợ ra quyết định.
- Công việc phân tích không chỉ dừng lại ở số liệu, mà còn cần tìm nguyên nhân gốc rễ và đề xuất giải pháp.
- Trong nhà máy hoặc môi trường sản xuất, dữ liệu từ máy móc, vận hành và IoT có thể được phân tích để tối ưu chi phí và nâng cao hiệu suất.
- Data Analytics Engineer cần phối hợp với nhiều phòng ban để giải quyết các bài toán thực tế.

#### Kỹ năng và tư duy cần thiết cho sinh viên năm 3, năm 4

Phần này nhấn mạnh rằng sinh viên sắp bước vào thị trường lao động cần chuẩn bị nhiều hơn ngoài kiến thức chuyên môn. Các kỹ năng như tư duy phản biện, giao tiếp, kể chuyện với dữ liệu và giải quyết vấn đề là những yếu tố rất cần thiết trong môi trường doanh nghiệp.

Một số nội dung quan trọng:

- Tư duy phản biện giúp phân tích thông tin khách quan và đưa ra nhận định hợp lý.
- Kỹ năng giao tiếp giúp truyền đạt ý tưởng và kết quả phân tích rõ ràng cho nhiều đối tượng khác nhau.
- Kể chuyện với dữ liệu giúp biến các con số khô khan thành thông tin có ý nghĩa và có thể thúc đẩy hành động.
- Giải quyết vấn đề yêu cầu sinh viên biết xác định thách thức, phân tích nguyên nhân và đề xuất giải pháp phù hợp.
- Khi làm báo cáo, không chỉ đưa ra số liệu mà còn cần hiểu nguyên nhân biến động và những điểm cần cải thiện.

#### Văn hóa tại tập đoàn đa quốc gia

Phần chia sẻ về văn hóa MNC giúp tôi hiểu hơn về cách các tập đoàn đa quốc gia vận hành, tuyển dụng và xây dựng môi trường làm việc. Văn hóa doanh nghiệp không chỉ là khẩu hiệu, mà là cách con người trong tổ chức suy nghĩ, làm việc và giải quyết vấn đề.

Một số điểm nổi bật:

- Quy trình tuyển dụng tại MNC thường gồm sàng lọc hồ sơ, phỏng vấn sơ bộ, test năng lực, phỏng vấn chuyên môn và đánh giá độ phù hợp văn hóa.
- Văn hóa No-Blame Post-Mortem trong môi trường công nghệ tập trung vào tìm nguyên nhân gốc rễ của lỗi thay vì đổ lỗi cá nhân.
- Văn hóa Caring & Inclusive đặt con người làm trung tâm, tôn trọng sự đa dạng và khuyến khích cải tiến liên tục.
- Sinh viên cần chuẩn bị khả năng tiếng Anh, tư duy logic, kỹ năng trình bày và khả năng làm việc với các chuẩn mực quốc tế.
- Để làm việc tốt trong môi trường toàn cầu, mỗi người cần vừa học hỏi tiêu chuẩn quốc tế vừa giữ được bản sắc và tư duy phù hợp với bản thân.

### Những điều rút ra

#### Tư duy nghề nghiệp

- Công việc trong ngành công nghệ có nhiều hướng phát triển khác nhau như DevOps, Software Engineer, Platform Engineer, Solutions Architect hoặc Data Analytics Engineer.
- Có được công việc đầu tiên chỉ là bước khởi đầu, quan trọng hơn là tiếp tục học hỏi và phát triển năng lực qua từng giai đoạn.
- Sinh viên cần chủ động xây dựng kinh nghiệm thực tế, portfolio và khả năng trình bày những gì mình đã làm.
- Tư duy nghề nghiệp nên tập trung vào việc nâng cao năng lực thay vì chỉ chạy theo chức danh.
- Quá trình phát triển có thể bắt đầu từ người thực thi, sau đó trở thành người học chủ động, người giải quyết vấn đề, người tư duy hệ thống và cuối cùng là người dẫn dắt.

#### DevOps và tư duy hệ thống

- DevOps không chỉ là biết nhiều công cụ mà còn là hiểu hệ thống vận hành như thế nào.
- Kiến thức nền tảng luôn quan trọng vì công cụ có thể thay đổi theo thời gian.
- Tư duy hệ thống giúp nhìn vấn đề rộng hơn thay vì chỉ xử lý từng task nhỏ.
- Tự động hóa các công việc lặp lại giúp giảm sai sót và tăng hiệu quả cho cả team.
- AI có thể hỗ trợ công việc, nhưng không nên dùng AI để thay thế hoàn toàn tư duy của bản thân.

#### Kiến trúc cloud trên AWS

- Một hệ thống đơn giản có thể gặp khó khăn khi mở rộng nếu không có thiết kế phù hợp.
- CloudFront, WAF, Amplify, ECS, ElastiCache và DynamoDB có thể được kết hợp để xây dựng hệ thống có hiệu năng và khả năng mở rộng tốt hơn.
- Cache giúp giảm độ trễ và giảm tải cho database.
- Tạo sẵn short code bằng Key Generation Service giúp backend xử lý request nhanh hơn.
- Khi thiết kế hệ thống, cần cân nhắc bảo mật, hiệu năng, chi phí, độ sẵn sàng và khả năng mở rộng.

#### Data Analytics và văn hóa doanh nghiệp

- Data Analytics không chỉ là trực quan hóa dữ liệu mà còn là tìm insight và đề xuất hành động.
- Kỹ năng kể chuyện với dữ liệu giúp kết quả phân tích dễ hiểu hơn đối với người ra quyết định.
- Môi trường MNC yêu cầu sự chuyên nghiệp, giao tiếp rõ ràng, tư duy phản biện và khả năng thích nghi.
- Văn hóa doanh nghiệp tốt tập trung vào cải tiến hệ thống thay vì đổ lỗi cá nhân.
- Làm việc trong môi trường toàn cầu đòi hỏi khả năng học hỏi liên tục và tuân thủ tiêu chuẩn cao.

### Quy trình phát triển

- Khi xây dựng hệ thống phần mềm, cần bắt đầu từ việc hiểu yêu cầu và luồng người dùng.
- Một kiến trúc đơn giản nên được đánh giá về ưu điểm, nhược điểm và khả năng mở rộng trước khi triển khai thực tế.
- Frontend, backend, cache, database và security layer cần được tách vai trò rõ ràng.
- Với DevOps, quy trình build, test, deploy, logging và monitoring cần được hiểu đầy đủ.
- Trong Data Analytics, quy trình nên bắt đầu từ việc hiểu bài toán kinh doanh, thu thập dữ liệu, phân tích, trực quan hóa và đề xuất giải pháp.
- Trong môi trường doanh nghiệp, quy trình làm việc cần minh bạch, có giao tiếp rõ ràng và có tinh thần cải tiến liên tục.

### Áp dụng vào công việc

- Củng cố kiến thức nền tảng như Linux, Networking, Git, CI/CD, container và cloud để chuẩn bị tốt hơn cho các task kỹ thuật.
- Khi làm frontend hoặc tích hợp API trong dự án GreenLens Kids, cần chú ý đến luồng hệ thống, logging, lỗi và trải nghiệm người dùng.
- Áp dụng tư duy DevOps bằng cách hiểu rõ cách ứng dụng được build, chạy, cấu hình và triển khai.
- Tham khảo kiến trúc URL Shortening Service để học cách thiết kế hệ thống có frontend, backend, cache và database rõ ràng.
- Khi làm việc với dữ liệu hoặc báo cáo tiến độ, cần không chỉ ghi nhận kết quả mà còn phân tích nguyên nhân và đề xuất hướng cải thiện.
- Rèn luyện kỹ năng giao tiếp, làm việc nhóm và trình bày dự án để chuẩn bị cho môi trường doanh nghiệp.
- Tận dụng các chương trình cộng đồng AWS để tiếp tục học hỏi, kết nối và mở rộng định hướng nghề nghiệp.

### Trải nghiệm sự kiện

Việc tham gia buổi **“FCAJ Meetup – Career, DevOps, AWS Architecture & MNC Culture”** là một trải nghiệm rất hữu ích đối với tôi. Sự kiện không chỉ cung cấp kiến thức kỹ thuật về DevOps, cloud architecture và data analytics, mà còn giúp tôi hiểu rõ hơn về con đường nghề nghiệp, văn hóa doanh nghiệp và những kỹ năng cần chuẩn bị trước khi đi làm.

#### Học hỏi từ các diễn giả có kinh nghiệm

- Các diễn giả chia sẻ nhiều kinh nghiệm thực tế từ công việc DevOps, AI, cloud, data analytics và môi trường doanh nghiệp.
- Những nội dung chia sẻ giúp tôi hiểu rõ hơn về sự khác nhau giữa lý thuyết học ở trường và công việc thực tế.
- Các ví dụ về DevOps, URL Shortener trên AWS và Data Analytics giúp tôi hình dung rõ hơn cách kiến thức kỹ thuật được áp dụng trong doanh nghiệp.
- Phần chia sẻ về hành trình cộng đồng AWS giúp tôi có thêm động lực để tiếp tục học và tham gia các hoạt động công nghệ.

#### Tiếp cận kiến thức kỹ thuật thực tế

- Tôi hiểu rõ hơn DevOps không chỉ là deploy code mà còn liên quan đến hệ thống, tự động hóa, monitoring và giao tiếp với team.
- Tôi học được cách một hệ thống URL Shortening Service có thể được thiết kế trên AWS với nhiều thành phần như CloudFront, WAF, Amplify, ECS, ElastiCache và DynamoDB.
- Tôi nhận ra vai trò của cache, pre-computation và separation of concerns trong việc xây dựng hệ thống có khả năng mở rộng.
- Phần Data Analytics giúp tôi hiểu rằng báo cáo dữ liệu cần đi kèm phân tích nguyên nhân và đề xuất giải pháp.

#### Tận dụng công cụ và nền tảng hiện đại

- Sự kiện giúp tôi thấy rõ hơn vai trò của các dịch vụ AWS trong việc xây dựng hệ thống thực tế.
- Các công cụ và nền tảng cloud không chỉ phục vụ triển khai, mà còn hỗ trợ bảo mật, tối ưu hiệu năng và mở rộng hệ thống.
- Những chương trình như AWS Student Builder Group và AWS Community Builder có thể giúp sinh viên tiếp tục học hỏi và kết nối với cộng đồng.
- Việc hiểu nhiều vai trò khác nhau trong ngành giúp tôi có thêm định hướng khi lựa chọn con đường phát triển sau này.

#### Kết nối và trao đổi

- Buổi meetup tạo cơ hội để lắng nghe nhiều góc nhìn khác nhau từ các anh chị đã có kinh nghiệm trong ngành.
- Các nội dung về nghề nghiệp và MNC giúp tôi hiểu rõ hơn cách chuẩn bị CV, portfolio, phỏng vấn và kỹ năng giao tiếp.
- Sự kiện nhấn mạnh tầm quan trọng của việc học hỏi từ cộng đồng và xây dựng kết nối nghề nghiệp.
- Tôi nhận ra rằng việc trao đổi với người đi trước có thể giúp sinh viên tránh nhiều sai lầm và định hướng tốt hơn.

#### Bài học rút ra

- Nền tảng kỹ thuật vững chắc quan trọng hơn việc chỉ biết sử dụng nhiều công cụ.
- DevOps cần tư duy hệ thống, khả năng giao tiếp và tinh thần tự động hóa các công việc lặp lại.
- Thiết kế kiến trúc cloud cần cân nhắc bảo mật, hiệu năng, chi phí và khả năng mở rộng.
- Data Analytics cần kết hợp tư duy phản biện, giao tiếp và khả năng kể chuyện với dữ liệu.
- Môi trường doanh nghiệp đa quốc gia đòi hỏi sự chuyên nghiệp, khả năng thích nghi và tư duy cải tiến liên tục.
- Sinh viên nên chủ động học tập, tham gia cộng đồng và xây dựng kinh nghiệm thực tế từ sớm.

> Nhìn chung, buổi **FCAJ Meetup – Career, DevOps, AWS Architecture & MNC Culture** đã giúp tôi có thêm nhiều góc nhìn thực tế về ngành công nghệ. Sau sự kiện, tôi hiểu rõ hơn rằng để phát triển trong lĩnh vực này, sinh viên không chỉ cần học công nghệ mới mà còn phải xây dựng nền tảng vững chắc, biết tư duy hệ thống, giao tiếp hiệu quả và liên tục cải thiện bản thân. Những bài học từ sự kiện có thể áp dụng trực tiếp vào quá trình thực tập, dự án GreenLens Kids và định hướng nghề nghiệp lâu dài của tôi.