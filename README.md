# 🛰️ Large-Scale Datasets

This repository provides a curated collection of **large-scale datasets** focused on **remote sensing**, **semantic segmentation**, and **object detection** from aerial and satellite imagery. It's designed to help researchers, engineers, and enthusiasts quickly find and explore the most relevant datasets for Earth observation tasks.

---

## 📌 Table of Contents

- [Why This Repo?](#why-this-repo)
- [Featured Datasets](#featured-datasets)
  - <a href="#dota">DOTA</a>
  - <a href="#loveDA">LoveDA</a>
  - <a href="#fair">FAIR1M</a>
  - <a href="#aid">AID</a>
- [Comparison Table](#comparison-table)
- [Coming Soon](#coming-soon)
<!-- - [Contributing](#contributing)
- [License](#license) -->

---

## ❓ Why This Repo?

Working with large-scale satellite or aerial imagery data can be overwhelming. This repo:
- Collects the most impactful and widely used datasets.
- Lists key details like tasks, classes, size, and links.
- Aims to save time for people starting new projects or doing research.

---

## 🌍 Featured Datasets

<h3 id="dota"> 1. DOTA (Dataset for Object Detection in Aerial Images) </h3>

- **Task**: Object Detection
- **Images**: ~2,800 high-resolution aerial images
- **Annotations**: ~188,000 object instances
- **Image Resolution**: Ranges from 800×800 to 4000×4000 pixels
- **Classes**: 15 (e.g., plane, ship, storage tank, vehicle, etc.)
- **Annotation Format**: Oriented bounding boxes
- **Split**: Train / Val / Test
- **Published By**: Wuhan University
- **Website**: [https://captain-whu.github.io/DOTA/dataset.html](https://captain-whu.github.io/DOTA/dataset.html)
- **Paper**: [Link to Paper](https://arxiv.org/abs/1711.10398)

---

<h3 id = "loveDA" > 2. LoveDA (Land-cover Classification in Very High Resolution) </h3>

- **Task**: Semantic Segmentation
- **Images**: 5987 image patches (512x512 px)
- **Scenes**: Urban and Rural
- **Classes**: 7 (Background, Building, Road, Water, Barren, Forest, Agricultural)
- **Split**: Train (2522) / Val (1669) / Test (1796)
- **Unique Point**: Designed to evaluate model generalization between urban and rural environments
- **Published By**: Nanjing University
- **Website**: [https://github.com/Junjue-Wang/LoveDA](https://github.com/Junjue-Wang/LoveDA)
- **Paper**: [https://arxiv.org/abs/2108.08874](https://arxiv.org/abs/2108.08874)

---

<h3 id = "fair" > 3. FAIR1M (Fine-Grained Object Recognition in Aerial Images) </h3>

- **Task**: Fine-Grained Object Detection
- **Images**: 15,000+ high-resolution aerial images
- **Annotations**: 1 million+ object instances
- **Classes**: 37 fine-grained categories (e.g., different airplane models, types of ships, etc.)
- **Annotation Format**: Oriented bounding boxes
- **Published By**: Chinese Academy of Sciences (AIR)
- **Website**: [https://www.aircas.ac.cn/databases/FAIR1M/](https://www.aircas.ac.cn/databases/FAIR1M/)
- **Paper**: [https://arxiv.org/abs/2103.05569](https://arxiv.org/abs/2103.05569)

---

<h3 id = "aid" > 4. AID (Aerial Image Dataset) </h3>

- **Task**: Scene Classification
- **Images**: 10,000 RGB aerial images
- **Resolution**: 600 × 600 pixels
- **Classes**: 30 scene types
- **Scene Types**: Urban, rural, industrial, agricultural, etc.
- **Labeling**: Each image has a single scene label
- **Split**: No fixed split — can be customized
- **Published By**: Wuhan University
- **Website**: [AID Dataset](https://captain-whu.github.io/AID/)
- **Paper**: [https://ieeexplore.ieee.org/document/7444843](https://ieeexplore.ieee.org/document/7444843)

---

## 📊 Comparison Table

| Dataset | Task                | # Images | # Classes | Size            | Resolution     | Annotations         | Link |
|---------|---------------------|----------|-----------|------------------|----------------|----------------------|------|
| DOTA    | Object Detection     | 2,806    | 15        | ~188k objects   | up to 4000×4000 | Oriented Bounding Box | [🔗](https://captain-whu.github.io/DOTA/dataset.html) |
| LoveDA  | Semantic Segmentation| 5,987    | 7         | ~1.2 GB         | 512×512         | Per-pixel class map   | [🔗](https://github.com/Junjue-Wang/LoveDA) |
| FAIR1M  | Fine-Grained Detection| 15,000+ | 37        | 1M+ objects     | Very high-res   | Oriented Bounding Box | [🔗](https://www.aircas.ac.cn/databases/FAIR1M/) |
| AID     | Scene Classification | 10,000   | 30        | ~2.2 GB         | 600×600         | Single scene label    | [🔗](https://captain-whu.github.io/AID/) |


---
## 🏷️ Class Lists

---

### 🔹 DOTA – 15 Object Detection Classes

| Class Name           | Description                            |
|----------------------|----------------------------------------|
| plane                | Airplanes of all types (e.g., jets, small planes) |
| baseball-diamond     | Baseball fields seen from above        |
| bridge               | Bridges over water or roads            |
| ground-track-field   | Running tracks                         |
| small-vehicle        | Cars, small trucks                     |
| large-vehicle        | Trucks, buses, large machinery         |
| ship                 | Boats, cargo ships                     |
| tennis-court         | Tennis courts                          |
| basketball-court     | Basketball courts                      |
| storage-tank         | Industrial storage tanks               |
| soccer-ball-field    | Soccer fields                          |
| roundabout           | Circular traffic intersections         |
| harbor               | Ports and docking areas                |
| swimming-pool        | Outdoor pools                          |
| helicopter           | Stationary or flying helicopters       |

---

### 🔹 LoveDA – 7 Land Cover Segmentation Classes

| Class ID | Class Name     | Description                          |
|----------|----------------|--------------------------------------|
| 0        | Background      | Irrelevant or undefined pixels       |
| 1        | Building        | Urban structures                     |
| 2        | Road            | Streets, highways, and paths         |
| 3        | Water           | Rivers, lakes, ponds                 |
| 4        | Barren          | Empty land with no vegetation        |
| 5        | Forest          | Tree-covered green areas             |
| 6        | Agricultural    | Farmland, crop fields                |

---

### 🔹 FAIR1M – 37 Fine-Grained Detection Classes

#### 🚗 Vehicle Categories

| Class Name    | Description               |
|---------------|---------------------------|
| Small car     | Compact private vehicles  |
| Bus           | Public transport buses    |
| Cargo truck   | Large freight trucks      |
| Dump truck    | Heavy-duty construction vehicles |
| Van           | Delivery vans             |
| Trailer       | Attached transport unit   |
| Pickup        | Pickup trucks             |
| Other vehicle | Miscellaneous vehicles    |

#### ✈️ Aircraft Categories

| Class Name        | Description                         |
|-------------------|-------------------------------------|
| Passenger plane   | Commercial airliners                |
| Fighter jet       | Military combat aircraft            |
| Trainer aircraft  | Planes used for pilot training      |
| Bomber            | Military bombing aircraft           |
| Helicopter        | Rotorcraft aircraft                 |
| Other aircraft    | Other flying machines               |

#### 🚢 Ship Categories

| Class Name      | Description                    |
|-----------------|--------------------------------|
| Passenger ship  | Ships for transporting people  |
| Cargo ship      | Ships for transporting goods   |
| Fishing boat    | Boats used for fishing         |
| Warship         | Military ships                 |
| Sailing boat    | Boats powered by wind          |
| Tugboat         | Small, powerful towing boats   |
| Other ship      | Miscellaneous watercraft       |

#### 🏗️ Infrastructure & Facilities

| Class Name      | Description                             |
|-----------------|-----------------------------------------|
| Storage tank    | Industrial storage containers           |
| Oil tank        | Tanks for oil or fuel                   |
| Roundabout      | Circular traffic intersection           |
| Baseball field  | Outdoor sports field                    |
| Basketball court| Outdoor or indoor court for basketball  |
| Tennis court    | Sports court for tennis                 |
| Soccer field    | Sports field for football/soccer        |

#### 🏭 Other Structures

| Class Name             | Description                             |
|------------------------|-----------------------------------------|
| Windmill               | Wind energy turbines                    |
| Expressway toll station| Highway toll booths                     |
| Overpass               | Elevated road segments                  |
| Chimney                | Industrial smokestacks                  |
| Harbor                 | Port or docking area                    |
| Airport runway         | Takeoff and landing strip               |
| Ground track field     | Running tracks                          |
| Bridge                 | Structure connecting two sides over obstacles |

---

### 🔹 AID – 30 Scene Classification Classes

| Class ID | Class Name        | Description                             |
|----------|-------------------|-----------------------------------------|
| 0        | Airport            | Airport runways and terminal buildings  |
| 1        | Bare land          | Unused or barren terrain                |
| 2        | Baseball field     | Outdoor sports field                    |
| 3        | Beach              | Sandy coastal area                      |
| 4        | Bridge             | Bridge structures                       |
| 5        | Center             | City/town center area                   |
| 6        | Church             | Religious buildings                     |
| 7        | Commercial         | Business districts and malls            |
| 8        | Dense residential  | High-density housing                    |
| 9        | Desert             | Arid sandy areas                        |
| 10       | Farmland           | Agricultural land                       |
| 11       | Forest             | Tree-covered land                       |
| 12       | Industrial         | Factories, warehouses                   |
| 13       | Meadow             | Open grassy fields                      |
| 14       | Medium residential | Mid-density housing                     |
| 15       | Mountain           | Mountainous terrain                     |
| 16       | Park               | Recreational green areas                |
| 17       | Parking            | Car parks and lots                      |
| 18       | Playground         | Outdoor play areas                      |
| 19       | Pond               | Small water bodies                      |
| 20       | Port               | Docking areas for ships                 |
| 21       | Railway station    | Train terminals                         |
| 22       | Resort             | Tourist resorts                         |
| 23       | River              | Flowing water channels                  |
| 24       | School             | Educational facilities                  |
| 25       | Sparse residential | Low-density housing                     |
| 26       | Square             | Open public space                       |
| 27       | Stadium            | Sports stadiums                         |
| 28       | Storage tank       | Large circular containers               |
| 29       | Viaduct            | Elevated roads                          |



## 🔜 Coming Soon

More datasets will be added soon, including:

- **xView** – Object detection, 1 million objects
- **SpaceNet** – Building & road extraction
- **DeepGlobe** – Land cover, road, and building segmentation
- **BigEarthNet** – Multi-label classification using Sentinel-2
- **SEN12MS** – Multispectral image dataset for classification and segmentation

---

<!-- ## 🤝 Contributing

Feel free to open issues or pull requests!  
Want to add a new dataset? Please include:

- Dataset name and description
- Main task (e.g., detection, segmentation)
- Link to official page
- Classes and format
- Any paper or reference

---

## 📜 License

This repository is open for **academic and research purposes**.  
Please check each dataset's license before commercial use.

---

## ⭐ If you find this useful, don't forget to star the repo! -->
