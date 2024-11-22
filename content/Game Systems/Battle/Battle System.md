---
tags:
  - battle
  - system
  - tiennt
  - readyUI
---
# Cấu Trúc
**Gồm 3 phần** 
1. [[Chuẩn Bị Đội Hình]] - người chơi chuẩn bị và sắp xếp đội của mình.
2. Battle - cơ chế [[Turnbased]]. 
3. [[Kết Quả Trận Đấu]].
![[20241112155058.png]]
![[20241122141555.png]]

| ID  | Detail                              | Bấm vào sẽ                                             |
| --- | ----------------------------------- | ------------------------------------------------------ |
| 1   | Nút [[Info Khắc Hệ]]                | Hiện ra [[Pop-up]] [[Info Khắc Hệ]]                    |
| 2   | Số Vòng Đấu                         | -                                                      |
| 3   | Nút tăng tốc [[Battle Speed]]       | Trận đấu sẽ tăng tốc.                                  |
| 4   | Nút [[Skip Trận Đấu]]               | Kết thúc trận đấu luôn, chi tiết: [[Kết Quả Trận Đấu]] |
| 5   | Danh sách các [[Hệ]] trong đội hình | Hiển thị tool-tip (xem bên dưới).                      |
| 6   | Đội hình phe mình                   | -                                                      |
| 7   | Đội hình phe địch                   | -                                                      |
| 8   | Background màn chơi                 | -                                                      |
# UX mong muốn 
![[20241122141056.png]]
![[20241122141017.png]]
Khi tap vào biểu tượng sẽ có [[Tool-tip]] hiện ra.
![[20241122141201.png]]
![[20241122155459.png]]
Các dòng được kích lên sẽ có màu xanh, chi tiết thông tin xem trong [[Kích Dòng Class]].
# Ref ART
![[MuMu12-20241118-170158.png]]
**Video UI Battle**
![[1119.mp4]]