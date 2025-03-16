# AI-CNC-8D11D-AutoMach

## 🚀 AI-Powered CNC 8D/11D Automation Web App

This project integrates AI and CNC (Computer Numerical Control) machining with **8D and 11D** movement capabilities, enhancing precision for **future-ready automated manufacturing**.

---

## 🛠 Features

- **Supports 8D & 11D CNC operations** 🚀
- **AI-based movement optimization** for efficient machining 🤖
- **Real-time API integration** using **ASP.NET Core Web API** 🌐
- **Machine Learning model deployment** on **Google Vertex AI** ☁️
- **Secure and Scalable Architecture** 🔐

---

## 📌 Technology Stack

- **Programming:** Python 🐍, C# .NET ⚙️
- **AI/ML:** TensorFlow, Keras 🤖
- **Backend:** ASP.NET Core Web API 🌐
- **Database:** MSSQL Server 🛢
- **Cloud:** Google Vertex AI ☁️, Azure

---

## 🔧 Installation & Setup

### 1️⃣ **Clone the Repository**

```sh
git clone https://github.com/PSivaMallikarjun/AI-CNC-8D11D-AutoMach.git
cd AI-CNC-8D11D-AutoMach
```

### 2️⃣ **Setup Python Environment & Install Dependencies**

```sh
pip install tensorflow pandas numpy requests
```

### 3️⃣ **Train AI Model**

```sh
python train_cnc_model.py
```

### 4️⃣ **Run ASP.NET Web API**

```sh
dotnet run
```

### 5️⃣ **Test API with Postman or Curl**

```sh
curl -X POST "http://localhost:5000/api/cnc/optimize" -H "Content-Type: application/json" -d '{"Dimensions": 8, "Movements": [10, -5, 7, 3, 8, -4, 2, 1]}'
```

---

## 📌 API Endpoints

| Method | Endpoint            | Description                                              |
| ------ | ------------------- | -------------------------------------------------------- |
| POST   | `/api/cnc/optimize` | Sends CNC movement data & receives AI-optimized response |

---

## 🚀 Next Steps

✅ Enhance AI model for **real-time CNC IoT integration**

✅ Deploy API on **Azure for cloud-based CNC automation**


✅ Add **Power BI dashboards** for analytics

🔗 **Contribute & Star** ⭐ the repo to support the project!

