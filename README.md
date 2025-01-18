# 1. 繪製折線圖
# 範例資料
months = ['Jan', 'Feb', 'Mar', 'Apr', 'May']
sales = [200, 300, 400, 350, 500]

# 繪製折線圖
plt.plot(months, sales, marker='o', label="Sales")
plt.title("Monthly Sales")  # 圖表標題
plt.xlabel("Month")         # X 軸標籤
plt.ylabel("Sales ($)")     # Y 軸標籤
plt.legend()                # 顯示圖例
plt.grid(True)              # 顯示網格
plt.show()