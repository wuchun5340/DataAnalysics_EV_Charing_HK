# ⚡ Hong Kong EV Charging Station Finder
<img width="1625" height="1236" alt="image" src="https://github.com/user-attachments/assets/cf5ad7c2-5609-48c0-bd52-4c3802505b6d" />

An interactive web application designed to help electric vehicle (EV) drivers find charging stations across various districts in Hong Kong.
This tool maps out charger locations and categorizes them by charging speeds (Medium, Quick, and Fast) to make tracking down your next charge completely seamless.

---

## 🚀 Features

* **District-Based Filtering:** Easily search and filter charging locations by HK districts (e.g., Central & Western, Kwun Tong, Sha Tin).
* **Detailed Station Breakdown:** View the total number of chargers available at each location, broken down by type:
  * **Medium Chargers**
  * **Quick Chargers**
  * **Fast Chargers**
* **Geographic Mapping:** Includes precise latitude and longitude coordinates for integration with map services (like Google Maps or Leaflet.js).
* **User-Friendly UI:** Simple HTML/CSS interface optimized for scannability and quick reference on the go.

---
🛠️ Tech Stack
Frontend: HTML5, CSS3, JavaScript (ES6+)

Data Format: JSON

---
## 📊 Dataset Overview

The application utilizes a comprehensive JSON dataset containing structured information on government and private EV charging facilities.

### Example Data Structure
```json
{
  "district": "Central & Western",
  "location": "Rumsey Street Car Park",
  "address": "2 Rumsey Street, Sheung Wan, Hong Kong",
  "longitude": 114.153227,
  "latitude": 22.287408,
  "total_chargers": 114,
  "medium_total": 110,
  "quick_total": 0,
  "fast_total": 4
}

