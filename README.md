# 🌐 Social Network Analysis (SNA) Project


Энэхүү төслийн зорилго нь Python болон NetworkX, LinkPred, Powerlaw зэрэг сангуудыг ашиглан 
нийгмийн сүлжээний бүтэц, зангилааны шинж чанар, ирээдүйн холбоосуудын магадлал, төвлөрөл болон хуваагдлын шинжилгээ хийх юм.

---

## 📁 Төслийн бүтэц

```bash
SNA-Project/
│
├── data/                  # CSV өгөгдлүүд (ж: Game of Thrones, Twitter гэх мэт)
├── scripts/               # Анализ хийдэг скриптүүд
│   ├── scale_free_analysis.py
│   ├── centrality_analysis.py
│   └── link_prediction.py
├── results/               # График, .txt үр дүн
│   └── (зураг болон үнэлгээний үр дүн)
├── requirements.txt       # Хэрэглэгдэх сангууд
├── setup.sh               # Автомат суулгалт
├── run.sh                 # Бүх анализийг гүйцэтгэх скрипт
└── README.md              # Төслийн танилцуулга
