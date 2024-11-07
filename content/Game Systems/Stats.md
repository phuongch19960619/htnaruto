---
tags:
  - character
---
# Công
Là chỉ số sát thương của [[Character]].
Sát thương gây ra = **Sát thương lý thuyết** - **Phòng thủ lý thuyết** - **Giảm sát thương**
Với đòn đánh thường, **Sát thương lý thuyết** là Công * Buff. 
Với đòn đánh kĩ năng, Sát thương lý thuyết sẽ tính theo %Công. VD: 150% Công. 
Phòng thủ lý thuyết là Thủ * Buff.
Với Buff là các hiệu ứng đội hình, khắc hệ.
# Máu
Lượng máu của nhân vật.
# Thủ
Là chỉ số phòng thủ của mục tiêu. Chỉ số này giúp giảm bớt lượng sát thương nhận vào.
VD: nhân vật có thủ là 400. Bị một nhân vật có công là 1000 tấn công, thì nhân vật đó sẽ chịu 1000 - 400 = 600 sát thương.
# Tốc độ
Tốc độ của các nhân vật trong team quyết định nhân vật nào được thực hiện hành động trước.
Nếu 2 nhân vật cùng tốc độ, ưu tiên theo thứ tự trong sắp xếp đội hình.
![[20241106162748.png]]
# Nộ
Nhân vật có thể dùng kĩ năng nếu nộ của nhân vật >= 100.
Khi dùng kĩ năng, nộ của nhân vật reset về 0.
Mọi nhân vật đều có nộ khởi đầu = 50. 

# Sát thương kĩ năng %
Tăng sát thương kĩ năng. VD: Sát thương kĩ năng là 15%. Skill là gây 150% Công thì skill sẽ gây ra 150% * 115% = 172.5% Công.
# Chính xác %
Tỉ lệ gây sát thương chính xác của nhân vật, dành cho cả đòn đánh thường lẫn đòn đánh kĩ năng.
# Chặn %
Tỉ lệ chặn sát thương. 
Khi đòn đánh thường bị chặn, nhân vật tấn công không hồi nộ, nhân vật chặn được hồi nộ.
Khi đòn đánh kĩ năng bị chặn, nhân vật chặn được hồi nộ.

Tỉ lệ chặn đứng sát thương = Tỉ lệ Chặn - Tỉ lệ chính xác.
Nếu kết quả > 0, nhân vật có khả năng chặn được sát thương.
Nếu kết quà <=0, nhân vật không có khả năng chặn sát thương.
# Chí mạng %
Tỉ lệ chí mạng đòn đánh thường.
# Sát thương chí mạng %
Sát thương đòn đánh khi chí mạng. 
Trước mỗi đòn đánh thường sẽ check chí mạng. Nếu chí mạng sẽ tấn công với sát thương chí mạng.
# Phá giáp %
Tỉ lệ giảm thủ của kẻ địch.
# Miễn chống %
Tỉ lệ kháng hoàn toàn hiệu ứng xấu.
# Giảm sát thương %
Chỉ số giảm sát thương nhận vào **cuối cùng**. 
VD: Giảm sát thương là 10%. Sau khi trừ thủ là 500 sát thương, như vậy nhân vật sẽ nhận 500 * 90% = 450 sát thương.
# Sát thương chuẩn %
**Sát thương chuẩn** thì bỏ qua phòng thủ và giảm sát thương.
VD: sát thương chuẩn là 5% thì 5% Công sẽ bỏ qua phòng thủ và giảm sát thương.

# Một số thí dụ tính toán về chỉ số
{Bổ sung sau}