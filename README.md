# 🌟 **Datasets for Food Domain and AI Applications** 🌟

This repository provides a curated list of datasets for research in the **food domain**, covering **recipes**, **ingredients**, **food ordering**, **nutritional information**, **flavor data**, and **user interactions**. These datasets are valuable for applications in **machine learning**, **AI**, and **computational gastronomy**.

---

## 🔍 **Datasets Overview**

### 🍽️ **Recipe1M+**
- **Description**:  
  Recipe1M+ is a large-scale, multimodal dataset containing over **1 million structured cooking recipes** and **13 million food images**. It was designed for cross-modal research, particularly learning embeddings that integrate recipe text (ingredients and instructions) with food images.  
  Expands upon Recipe1M by significantly increasing the number of images via web searches.

- 📄 **Paper**: [Link to Paper](https://im2recipe.csail.mit.edu/tpami19.pdf)  
  📚 **Citation**: Marín, J., Biswas, A., Ofli, F., et al. (2019). Recipe1M+: A Dataset for Learning Cross-Modal Embeddings for Cooking Recipes and Food Images. IEEE TPAMI.

- 📂 **Dataset**: [Link to Dataset](https://github.com/torralba-lab/im2recipe)  

#### ⭐ **Key Features**:
- **Image Data**: ✔️  
- **Nutritional Data**: ✔️ (50,637 recipes with mapped details from the USDA database)  
- **Flavor or Taste Data**: ❌  
- **Recipe Data**: ✔️  
  - Title  
  - List of ingredients (with quantities and units parsed)  
  - Instructions  
  - Course labels  

---

### ✨ **RecipeNLG**
- **Description**:  
  RecipeNLG is a dataset with **2.2 million recipes**, designed for semi-structured text generation tasks like **recipe generation**. It leverages **Named Entity Recognition (NER)** to extract food entities.

- 📄 **Paper**: [Link to Paper](https://aclanthology.org/2020.inlg-1.4.pdf)  
  📚 **Citation**: Bień, M., Gilski, M., Maciejewska, M., et al. (2020). RecipeNLG: A Cooking Recipes Dataset for Semi-Structured Text Generation.

- 📂 **Dataset**: [Link to Dataset](https://recipenlg.cs.put.poznan.pl/)  

#### ⭐ **Key Features**:
- **Image Data**: ❌  
- **Nutritional Data**: ❌  
- **Flavor or Taste Data**: ❌  
- **Recipe Data**: ✔️  
  - Title  
  - List of ingredients (with quantities and units)  
  - Step-by-step instructions  

---

### 🌍 **FooDI-ML**
- **Description**:  
  A multilingual, visio-linguistic dataset containing **2.8 million images** and **9.5 million text samples** spanning **37 countries** and **33 languages**. Ideal for **text-image retrieval** and **conditional image generation**.

- 📄 **Paper**: [Link to Paper](https://arxiv.org/pdf/2110.02035)  
  📚 **Citation**: Amat Olondriz, D., Palau Puigdevall, P., Salvador Palau, A.

- 📂 **Dataset**: [Link to Dataset](https://github.com/Glovo/foodi-ml-dataset)  

#### ⭐ **Key Features**:
- **Image Data**: ✔️ (2.8M images)  
- **Textual Data**: ✔️ (product names, descriptions)  
- **Nutritional Data**: ❌  
- **Flavor or Taste Data**: ❌  

---

### 📖 **Allrecipes.com**
- **Description**:  
  A dataset containing over **1 million user-recipe interactions** from **2000 to 2018**, featuring **52,821 recipes** across **27 categories**.

- 📄 **Paper**: [Link to Paper](https://arxiv.org/pdf/1810.05032)  
  📚 **Citation**: Gao, Xiaoyan, et al. "Hierarchical Attention Network for Visually-aware Food Recommendation."

- 📂 **Dataset**: [Link to Dataset](https://www.kaggle.com/datasets/elisaxxygao/foodrecsysv1)  

#### ⭐ **Key Features**:
- **Image Data**: ✔️  
- **Nutritional Data**: ❌  
- **Flavor or Taste Data**: ❌  
- **Recipe Data**: ✔️  
  - Title  
  - List of ingredients
  - Instructions  
  - Recipe category  

---

### 🍲 **Food.com**
- **Description**:  
  Contains **230,000 recipes** and **1.1 million user-recipe interactions (reviews)** spanning **18 years**. Useful for **personalized recipe recommendation**.

- 📄 **Paper**: [Link to Paper](https://www.aclweb.org/anthology/D19-1613/)  
  📚 **Citation**: Bodhisattwa Prasad Majumder, et al. (2019).

- 📂 **Dataset**: [Link to Dataset](https://www.kaggle.com/datasets/shuyangli94/food-com-recipes-and-user-interactions)  

#### ⭐ **Key Features**:
- **Image Data**: ❌  
- **Nutritional Data**: ❌  
- **Flavor or Taste Data**: ❌  
- **Recipe Data**: ✔️  
  - Title  
  - Ingredients
  - Tags
  - Step-by-step instructions
     

---

### 🍥 **FlavorDB2**
- **Description**:  
  A database of **25,595 flavor molecules** and **936 ingredients**, providing **molecular flavor profiles**.

- 📄 **Paper**: [Kumar et al. (2022)](https://arxiv.org/pdf/2205.05451)  
  📚 **Citation**: Goel M, Grover N, et al. (2024). FlavorDB2: An updated database of flavor molecules.

- 📂 **Dataset**: [Link to Dataset](https://cosylab.iiitd.edu.in/flavordb2/)  

#### ⭐ **Key Features**:
- **Image Data**: ❌  
- **Nutritional Data**: ❌  
- **Flavor or Taste Data**: ✔️  
  - Molecular flavor profiles  

---

### 🍕 **FoodOrdering Dataset**
- **Description**:  
  A collection of **synthetic and human-generated food order examples** for building **task-oriented systems**.

- 📄 **Paper**: [Link to Paper](https://arxiv.org/pdf/2206.05352)  
  📚 **Citation**: Rubino, M., Guenon des Mesnards, N., et al. (2022).

- 📂 **Dataset**: [Link to Dataset](https://github.com/amazon-science/food-ordering-semantic-parsing-dataset)  

#### ⭐ **Key Features**:
- **Image Data**: ❌  
- **Nutritional Data**: ❌  
- **Flavor or Taste Data**: ❌  
- **Textual Data**: ✔️ (includes food orders with semantic parsing annotations)  

---

### 🍜 **RecipeDB**
- **Description**:  
  A structured database of **118,171 recipes** integrating **nutritional profiles** and **flavor molecules**.

- 📄 **Paper**: [Sethi et al. (2020)](https://academic.oup.com/database/article/doi/10.1093/database/baaa077/6006228)  
  📚 **Citation**: Devansh Batra, Nirav Diwan, et al. (2020).

- 📂 **Dataset**: [Link to Dataset](https://cosylab.iiitd.edu.in/recipedb/)  

#### ⭐ **Key Features**:
- **Image Data**: ❌  
- **Nutritional Data**: ✔️  
- **Flavor or Taste Data**: ✔️  
- **Recipe Data**: ✔️  

---

### 🥗 **HUMMUS Dataset**
- **Description**:  
  The HUMMUS dataset combines **507,335 recipes** and **1.9 million user-recipe interactions**, enriched with **health-awareness metrics**.

- 📄 **Paper**: [Link to Paper](https://hal.science/hal-04220182/document)  
  📚 **Citation**: Felix Bölz, et al. (2023).

- 📂 **Dataset**: [Link to Dataset](https://gitlab.com/felix134/connected-recipe-data-set)  

#### ⭐ **Key Features**:
- **Image Data**: ❌  
- **Nutritional Data**: ✔️  
- **Flavor or Taste Data**: ❌  
- **Recipe Data**: ✔️  
