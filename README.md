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

### **FlavorDB2**
- **Description**:  
  A database of **25,595 flavor molecules**, **936 ingredients**, and **34 ingredient categories**, providing molecular flavor profiles and sensory attributes.
- **Paper**: [Kumar et al. (2022)](https://arxiv.org/pdf/2205.05451)  
  Citation: Goel M, Grover N, Batra D, Garg N, Tuwani R, Sethupathy A, Bagler G. FlavorDB2: An updated database of flavor molecules. J Food Sci. 2024 Nov;89(11):7076-7082. doi: 10.1111/1750-3841.17298. Epub 2024 Sep 24. PMID: 39318152
- **Dataset**: [Link to Dataset](https://cosylab.iiitd.edu.in/flavordb2/)  

#### **Key Features**:
- **Image Data**: No  
- **Nutritional Data**: No  
- **Flavor or Taste Data**: Yes  
  - Molecular flavor profiles  
  - Taste/aroma threshold values  
- **Recipe Data**: No  
- **Interactions Dataset**: No  

---

### **FoodOrdering Dataset**
- **Description**:  
  The FoodOrdering Dataset is a collection of **synthetic and human-generated food order examples** designed for building task-oriented systems (like virtual assistants) in the food-ordering domain. It provides annotated text data for parsing user food orders into structured representations (intents, slots, and values). The dataset is specifically designed to evaluate **cross-schema parsing** and **zero-shot learning** across different restaurant menus.
- **Paper**: [Link to Paper](https://arxiv.org/pdf/2206.05352)  
  Citation: [Rubino, M., Guenon des Mesnards, N., Shah, U., Jiang, N., Sun, W., & Arkoudas, K. (2022). Cross-TOP: Zero-Shot Cross-Schema Task-Oriented Parsing. arXiv preprint arXiv:2206.05352. https://arxiv.org/abs/2206.05352.]
- **Dataset**: [Link to Dataset](https://github.com/amazon-science/food-ordering-semantic-parsing-dataset)  

#### **Key Features**:
- **Image Data**: No  
- **Nutritional Data**: No  
- **Flavor or Taste Data**: No  
- **Textual Data**: Yes  
  - Includes **utterances** of food orders with semantic parsing annotations.
  - Examples: Orders for pizzas, sandwiches, drinks, and sides with detailed slot value annotations for menu items, sizes, toppings, and quantities.
- **Interactions Dataset**: No  

---

### **RecipeDB**
- **Description**:  
  A structured database of **118,171 recipes**, integrating recipes with **nutritional profiles**, **flavor molecules**, and **health associations**.
- **Paper**: [Sethi et al. (2020)](https://academic.oup.com/database/article/doi/10.1093/database/baaa077/6006228)  
  Citation: Devansh Batra, Nirav Diwan, Utkarsh Upadhyay, Jushaan Singh Kalra, Tript Sharma, Aman Kumar Sharma, Dheeraj Khanna, Jaspreet Singh Marwah, Srilakshmi Kalathil, Navjot Singh, Rudraksh Tuwani, Ganesh Bagler, RecipeDB: a resource for exploring recipes, Database, Volume 2020, 2020, baaa077, https://doi.org/10.1093/database/baaa077
- **Dataset**: [Link to Dataset](https://cosylab.iiitd.edu.in/recipedb/)  

#### **Key Features**:
- **Image Data**: No  
- **Nutritional Data**: Yes  
- **Flavor or Taste Data**: Yes  
- **Recipe Data**: Yes  
  - Title  
  - List of ingredients (with quantity, unit, state, size, and temperature)  
  - Instructions  
  - Cooking processes and dietary styles  
- **Interactions Dataset**: No  

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
