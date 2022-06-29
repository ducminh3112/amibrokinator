# amibrokinator
A. RSI
OverBuy  | RSI >= 70
OverSold | RSI <=30
Bear     | RSI < MA(RSI(7))
Bull     | RSI > MA(RSI(7))
Điểm mua | OverSold + RSI cắt lên MA(RSI(7)) (Bear => Bull)
         | RSI từ dưới cắt lên 30
Điểm bán | OverBuy + RSI cắt xuống MA(RSI(7)) (Bull => Bear)
         | RSI cắt xuống 70
Cảnh báo | RSI hiện tại chạm ngưỡng (biên độ 5%) HHV (highest high value) RSI cao nhất trong 6 tháng/ 1 năm / 3 năm
Cơ hội   | RSI hiện tại chạm ngưỡng (biên độ 5%) LLV (highest high value) RSI thấp nhất trong 6 tháng/ 1 năm / 3 năm

B. STOCHASTIC (S)
Chu kỳ (14, 7, 3) và (14, 3, 3)

OverBuy  | Thận trọng | S >= 80
OverSold | Cơ hội	  | S <= 20
Neutral  |            | 20 < S < 80
Bull     |            | Dây nhanh > Dây chậm
Bear     |            | Dây nhanh < Dây chậm
____________________________________________
         | Điểm bán   | OverBuy + Bear 
         |            | HOẶC S từ trên cắt xuống 80
         | Điểm mua   | OverSold + Bull
         |            | HOẶC S từ dưới cắt lên 20

C. ICHIMOKU (I)
Chu kỳ 9 22 45 23
- Vị trí giá: 
	Trên mây
	Trong mây
	Dưới mây
- Các loại giao cắt cho mua/bán:
	Tenkan vs Kijun
	Chikou cắt giá
	Đổi màu mây: Đỏ <=> Xanh
	Giá vượt mây

D. ADX