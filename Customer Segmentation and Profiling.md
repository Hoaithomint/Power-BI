# CUSTOMER SEGMENTATION AND PROFILING
<p align="center">
<img src="https://github.com/Hoaithomint/Power-BI/assets/141213880/713cd937-3ba5-401d-b318-d8f4ea2a5758" alt="Image">

## Table Of Contents
  
  - [Database](#database)
  - [Business Context](#business-context)
  - [Problem Statement](#problem-statement)
  - [Visualization using Power BI](#visualization-using-power-bi)

## Database
The AdventureWorks database supports standard online transaction processing scenarios for a fictitious bicycle manufacturer (Adventure Works Cycles). Scenarios include Purchasing, Product Management, Sales, and Human Resources.

- You could explore data [here](https://console.cloud.google.com/bigquery?authuser=0&project=adventureworks2019&ws=!1m0&pli=1)

- Data Dictionary [here](https://drive.google.com/file/d/15kCAbYbG0pchpVHmkV_2CeLfAFe1D9_5/view?usp=sharing)

## Business Context

Adventure Works Cycles, a large, multinational manufacturing company,  produces and distributes metal and composite bicycles to North American, European,  and Asian commercial markets. While its base operation is located in Bothell,   Washington, and employs 500 people, several regional sales teams are located throughout the company’s market region. In 2000, Adventure Works Cycles bought a   small manufacturing plant, Wide World Importers, which is located in Mexico City,  Mexico. Wide World Importers manufactures several critical subcomponents for the  Adventure Works Cycles product line. These subcomponents are shipped to the Bothell  location for final product assembly. In 2001, Wide World Importers became the sole  manufacturer and distributor of the touring bicycle product group. 

After a successful fiscal year, Adventure Works Cycles is looking to broaden its  market share by focusing its sales efforts on the company’s best customers, and reducing the cost  of sales by reducing production costs.

## Problem Statement

Sales representatives from regional sales offices have assigned sales territories in the United States, Canada, England, Australia, Germany, and France. Each regional office consists of several sales representatives and a team manager. In their daily sales activities, sales representatives use both laptops and Handheld PCs that run Microsoft® Windows CE. A typical work day for a sales representative starts with the representative dialing in to the regional office and downloading current data such as inventory, product, and promotional information. During customer visits, the sales representative takes orders on the laptop or Handheld PC. At the end of each day, the sales representative sets up appointments for the following day or week, checks the appointments of other representatives in the area for possible collaboration, and updates the contact list. The sales representative dials back into the regional office, sends updated information, and receives any new internal communications from the base office or regional office. The company currently uses Microsoft Outlook® for email. 

The sales teams have identified the following requirements that will enable them to perform their jobs better: 

#### Customer segmentation and profiling: 
The sales team needs to be able to extract valuable information from raw data available in the databases to answer questions such as the following: 
- What are the early warning signs of problems? 
- Who are the best customers across all product lines? With whom should the sales team focus its efforts for building long-term relationships? 
- What are customers’s issues, categorized according to demographic groups (geographic location, revenue history, and so on)? 
- What products are the customers buying and at what rate?

## Visualization using Power BI
![AdventureWorkCycleImage](https://github.com/Hoaithomint/Power-BI/assets/141213880/f1e0a0c9-db25-453b-bca5-c4e708e7c89a)
### Insights:
Chính sách về giá chính là nhân tố chính lý do khách mua sản phẩm bike của Adventureworks

Trên cơ sở phân tích RFM để phân tích và phân khúc khách hàng theo theo các đặc điểm hành vi tiêu dùng dựa trên các dữ liệu giao dịch trên lịch sử (được tính trên cả chu kỳ kinh doanh của công ty từ 2011 - 2014), Adventureworks đang có các khía cạnh cần xem xét biện pháp cải thiện:
- Lượng khách hàng Hibernating chiếm 1/3 trên tổng khách: Là những khách hàng đã khá lâu không quay lại, sức mua yếu (tần suất mua thấp và giá trị giỏ hàng không cao)
- Lost customer chiếm 11%:Là những khách hàng đã rất lâu không quay lại, tần suất mua và giá trị giỏ hàng cũng rất thấp. Nhóm này thường là những khách hàng có hành vi mua tìm kiếm sự đa dạng hoặc chỉ mua suy nhất một lần để trải nghiệm và so sánh với các sản phẩm/dịch vụ khác.

Nhưng trên tích cực, tính từ mốc ngày giao dịch gần nhất công ty thành công thu hút 24% lượng khách mới (Những khách hàng mới mua gần đây nhất, giá trị giỏ hàng thấp và không mua hàng thường xuyên), 8% khách promising và lượng khách champions và loyals (mua thường xuyên, chi tiêu mức trung bình và hào phóng) chiếm tổng 23%."

- Sản phẩm: bike là dòng sản phẩm chủ lực khi xếp top đầu doanh thu mặc dù vậy lượng đơn hàng lại tập trung nhiều hơn ở dòng accessories.
Road, Mountain,  touring bikes là top các sản phẩm dòng bike sinh lợi.."

Theo phân khúc nhân khẩu học:
- Nguồn khách tập trung ở hai khu vực chính là Mỹ và Úc, lần lượt 32% và 31%
- Nhóm tuổi chính từ 45 - 65 tuổi
- Chân dung khách hàng với bằng đại học, làm việc ở các vị trí professional và thu nhập trung bình năm từ $50k - $70k, sở hữu nhà, chưa có con đem lại doanh thu cao nhất. "

### Recommendations
- Tăng cường tiếp thị, tập trung các dòng sản phẩm được ưa chuộng như road, mountain, touring bike, có thể phối kết hợp với phụ kiện để thu hút sự quan tâm của khách hàng
- Tập trung khách hàng ở 02 thị trường chính tiềm năng: Úc và Mỹ bởi dân số đông và văn hoá xe đạp phổ biến.
- Các ưu đãi và phần thưởng cho khách hàng đang có và tiềm năng, vì trên thực tế chi phí để giữ chân khách hàng trung thành đang có thấp hơn chi phí để thu hút khách hàng mới. 
Chuẩn hoá quy trình chăm sóc khách hàng mới để giảm thiểu tỉ lệ rời bỏ, tặng welcome coupon.
Flash sale cuối tuần, freeship vào một khoảng thời gian, new product coupon để khuyến khích khách mua hàng.
Email gợi nhắc cho các loại khách hàng about to sleep, need attention, ... "

Cụ thể chi tiết ứng dụng:
- Hibernating và Lost: làm thế nào để họ quay lại mua hàng lần nữa và khiến họ mua hàng thường xuyên hơn?
Thường những quyết định không tiếp tục mua hàng đến từ những đánh giá tiêu cực về trải nghiệm với sản phẩm/dịch vụ hoặc họ đã trung thành với những sản phẩm/dịch thay thế khác -> có thể gửi email cá nhân, tương tác trực tiếp qua social media hoặc gọi điện để kết nối lại với những khách hàng này.
Thực hiện các chiến dịch retargeting, chương trình xúc tiến ngắn hạn ( voucher, discount giảm giá, ưu đãi độc quyền,…)

- New Customers và Promising: làm thế nào để họ giúp họ hài lòng ở những giao dịch đầu tiên này và quay lại mua hàng nhiều lần hơn, với giá trị giỏ hàng lớn hơn?
Xaay dựng  quy trình chăm sóc bài bản, được cá nhân hóa đủ cao -> bước đầu tạo dựng mối quan hệ.
Lời cảm ơn và lấy ý kiến về trải nghiệm mua hàng ở đơn hàng đầu tiên của khách hàng, đồng thời tặng kèm voucher chào mừng giảm giá, welcome coupon cho những lần mua hàng tiếp theo. Sau đó, đảm bảo tần suất tương tác và đề xuất thông tin về các sản phẩm tương tự với giỏ hàng đầu tiên và cross-sell/upsell với combo và các sản phẩm có size lớn hơn.

- Champion: làm thế nào để giữ chân những khách hàng này bằng mọi giá?
Đề xuất chương trình khách hàng thân thiết với những giá trị khác biệt và được cá nhân hóa cao (ưu đãi, khuyến mại và chương trình tích điểm, đổi điểm và các ưu đãi riêng cho hạng mức khác nhau)
Bên cạnh đó, bởi nhóm khách hàng này đã có sự tin tưởng và cam kết cao với thương hiệu, upsell các mặt hàng có giá trị lớn hơn, các combo sản phẩm dựa trên dự đoán từ những lịch sử đơn hàng.

- Loyal Customers: làm thế nào để họ nâng giá trị giỏ hàng mỗi lần mua hàng?
Đề xuất các chương trình ưu đãi gắn liền với các ngưỡng chi tiêu

