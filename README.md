# **Datasets for Food Domain and AI Applications**

This repository provides a curated list of datasets for research in the food domain, covering recipes, ingredients, food ordering, nutritional information, flavor data, and user interactions. These datasets are valuable for applications in machine learning, AI, and computational gastronomy.

---

## **Datasets Overview**

### **Recipe1M+**
- **Description**:  
  Recipe1M+ is a large-scale, multimodal dataset containing over **1 million structured cooking recipes** and **13 million food images**. It was designed for cross-modal research, particularly learning embeddings that integrate recipe text (ingredients and instructions) with food images. It expands upon Recipe1M by significantly increasing the number of images via web searches.
- **Paper**: [Link to Paper](https://im2recipe.csail.mit.edu/tpami19.pdf)  
  Citation: Marín, J., Biswas, A., Ofli, F., Hynes, N., Salvador, A., Aytar, Y., Weber, I., & Torralba, A. (2019). Recipe1M+: A Dataset for Learning Cross-Modal Embeddings for Cooking Recipes and Food Images. IEEE Transactions on Pattern Analysis and Machine Intelligence
- **Dataset**: [Link to Dataset](https://github.com/torralba-lab/im2recipe)  

#### **Key Features**:
- **Image Data**: Yes  
- **Nutritional Data**: Yes (50,637 recipes with mapped details sourced from the USDA database)  
- **Flavor or Taste Data**: No  
- **Recipe Data**: Yes  
  - Title  
  - List of ingredients (with quantities and units parsed when available)  
  - Instructions  
  - Course labels  

---

### **RecipeNLG**
- **Description**:  
  RecipeNLG is a dataset with **2.2 million recipes**, derived from Recipe1M+ and additional data scraped from cooking websites. It is designed for semi-structured text generation tasks like recipe generation, leveraging Named Entity Recognition (NER) for extracting food entities.
- **Paper**: [Link to Paper](https://aclanthology.org/2020.inlg-1.4.pdf)  
  Citation: Bień, M., Gilski, M., Maciejewska, M., Taisner, W., Wiśniewski, D., & Ławrynowicz, A. (2020). RecipeNLG: A Cooking Recipes Dataset for Semi-Structured Text Generation. Proceedings of the 13th International Conference on Natural Language Generation, 22–28. Association for Computational Linguistics.
- **Dataset**: [Link to Dataset](https://recipenlg.cs.put.poznan.pl/)  

#### **Key Features**:
- **Image Data**: No  
- **Nutritional Data**: No  
- **Flavor or Taste Data**: No  
- **Recipe Data**: Yes  
  - Title  
  - List of ingredients (quantities and units preserved)  
  - Step-by-step instructions  

---

### **FooDI-ML**
- **Description**:  
  FooDI-ML is a multilingual visio-linguistic dataset containing **2.8 million images** and **9.5 million text samples**, spanning **37 countries** and **33 languages**. It is tailored for text-image retrieval and conditional image generation.
- **Paper**: [Link to Paper](https://arxiv.org/pdf/2110.02035)  
  Citation: Amat Olondriz, D., Palau Puigdevall, P., & Salvador Palau, A. (n.d.). FooDI-ML: A Large Multi-Language Dataset of Food, Drinks, and Groceries Images and Descriptions. Glovoapp. 
- **Dataset**: [Link to Dataset](https://github.com/Glovo/foodi-ml-dataset)  

#### **Key Features**:
- **Image Data**: Yes  
  - 2.8M images (1.5M unique) linked to food, drink, and grocery products.  
- **Textual Data**:
  - Product names (e.g., "Spicy Tuna Roll")  
  - Product descriptions (e.g., "Tender marinated fillet cooked golden-brown")  
  - Store names and menu categories  
- **Nutritional Data**: No  
- **Flavor or Taste Data**: No  

---

### **Allrecipes.com**
- **Description**:  
  A dataset with over **1 million user-recipe interactions** from **2000 to 2018**, featuring **52,821 recipes** in **27 categories**, collected from AllRecipes.com. It supports research in food recommendation systems.
- **Paper**: [Link to Paper](https://arxiv.org/pdf/1810.05032)  
  Citation: Gao, Xiaoyan, et al. "Hierarchical Attention Network for Visually-aware Food Recommendation." IEEE Transactions on Multimedia
- **Dataset**: [Link to Dataset](https://www.kaggle.com/datasets/elisaxxygao/foodrecsysv1)  

#### **Key Features**:
- **Image Data**: Yes  
- **Nutritional Data**: No  
- **Flavor or Taste Data**: No  
- **Recipe Data**: Yes  
  - Title  
  - List of ingredients (multi-hot encoding)  
  - Recipe category (e.g., dessert, main dish)  
- **Interactions Dataset**: Yes  
  - Over **1 million user-recipe interactions** (2000–2018).  

---

### **Food.com**
- **Description**:  
  Contains **230,000 recipes** and **1.1 million user-recipe interactions (reviews)** spanning **18 years (2000–2018)**. It is designed for personalized recipe generation and recommendation.
- **Paper**: [Link to Paper](https://www.aclweb.org/anthology/D19-1613/)  
  Citation: Bodhisattwa Prasad Majumder, Shuyang Li, Jianmo Ni, and Julian McAuley. 2019. Generating Personalized Recipes from Historical User Preferences. In Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing (EMNLP-IJCNLP), pages 5976–5982, Hong Kong, China. Association for Computational Linguistics.
- **Dataset**: [Link to Dataset](https://www.kaggle.com/datasets/shuyangli94/food-com-recipes-and-user-interactions)  

#### **Key Features**:
- **Image Data**: No  
- **Nutritional Data**: No  
- **Flavor or Taste Data**: No  
- **Recipe Data**: Yes  
  - Title  
  - List of ingredients (4–20 per recipe)  
  - Step-by-step instructions (minimum 3 steps)  
  - Calorie levels (low, medium, high)  
- **Interactions Dataset**: Yes  
  - 1.1 million user-recipe interactions (reviews).  

---

### **HUMMUS Dataset**
- **Description**:  
  The HUMMUS dataset combines **507,335 recipes** and **1.9 million user-recipe interactions**, enriched with health-awareness metrics and semantic data linking for hybrid food recommendations. The dataset enables personalized, explainable, and health-conscious recipe suggestions.
- **Paper**: [Link to Paper](https://hal.science/hal-04220182/document)  
  Citation: Felix Bölz, Diana Nurbakova, Sylvie Calabretto, Lionel Brunie, Armin Gerl, and Harald Kosch. "HUMMUS: A Linked, Healthiness-Aware, User-centered and Argument-Enabling Recipe Data Set for Recommendation." Proceedings of the 17th ACM Conference on Recommender Systems (RecSys ’23), September 18–22, 2023, Singapore.
- **Dataset**: [Link to Dataset](https://gitlab.com/felix134/connected-recipe-data-set)  

#### **Key Features**:
- **Image Data**: No  
- **Nutritional Data**: Yes  
- **Flavor or Taste Data**: No  
- **Recipe Data**: Yes  
  - Title  
  - Ingredients  
  - Instructions  
- **Interactions Dataset**: Yes  
  - 1.9 million user-recipe interactions  

---

