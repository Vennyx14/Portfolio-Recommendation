# Portfolio Recommendation AI

## Mô tả
Ứng dụng AI cơ bản (Clustering + Heuristic Rule-based) để gợi ý danh mục đầu tư cổ phiếu.

- **Clustering (K-means)**: phân nhóm cổ phiếu theo rủi ro và lợi nhuận.
- **Rule-based heuristic**: đưa ra gợi ý đầu tư dựa trên nhu cầu người dùng.

## Cấu trúc
```bash
Portfolio-Recommendation/
│── data/
│   ├── stocks.csv          # Folder chứa file CSV 
|   └── data_loader.py      # Load & xử lý dữ liệu
│── src/
│   ├── clustering.py       # Sử dụng K-means Clustering
│   ├── rules.py            # Luật heuristic
│   └── app.py              # File chính, chạy toàn bộ
│── README.md
└── requirements.txt        # Thư viện cần cài
```

## Cách chạy
```bash
# Clone repo
git clone https://github.com/Vennyx14/Portfolio-Recommendation.git
cd portfolio-recommendation

# Cài thư viện
pip install -r requirements.txt

# Chạy demo
python src/app.py
