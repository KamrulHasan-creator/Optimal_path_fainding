# Optimal Path Finding from Kolabagan to UAP using A* Algorithm

## 📌 Introduction
Urban traffic in Dhaka city often creates multiple possible routes between two places. Determining the shortest and optimal route is important for saving time and reducing travel costs.  
This project uses **graph representation in JSON format** and implements the **A* Algorithm** to find the shortest path from **Kolabagan** to **University of Asia Pacific (UAP)**.

## 📊 Project Presentation
You can view the detailed presentation here:  

[➡️ View Canva Slide Presentation]https://www.canva.com/design/DAGw6Uyco9M/IHQNr0B2-vmThLmNlT4M2Q/view?utm_content=DAGw6Uyco9M&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h964c8acf3b

> Click the link above to open the full slide presentation in Canva.


---

## 🗺️ Data Representation (JSON Format)
**Nodes:** Geographical locations: Kolabagan, Panthapath, Rajabazar, Farmgate, Kawran Bazar, UAP. Each node has latitude and longitude coordinates.  

**Edges:** Direct connections between nodes with distance in kilometers.  

**Example JSON snippet:**
```json
"edges": { 
  "Kolabagan": { 
    "Panthapath": 2.0, 
    "Rajabazar": 4.5, 
    "Farmgate": 5.0, 
    "Kawran Bazar": 6.5 
  }, 
  "Panthapath": { 
    "UAP": 2.5 
  } 
}

