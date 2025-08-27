# 🌍 Sustainable Streetscape with Generative AI

This repository accompanies the study **"Unpacking the ambiguity of ‘sustainable’ streetscapes through contextual vs. generic GPT-4o prompting"**.  
It documents the dataset, experimental design, and prompting strategies used to explore how generative AI interprets and visualizes sustainability in urban streetscapes.  

---

## 📂 Data

Due to size limitations, the **full dataset** is hosted on Google Drive:  
🔗 [Access Data on Google Drive](https://drive.google.com/drive/folders/146fr_X6RyH2bcb7deB25jdutXmJhRlqx?usp=sharing)

---

## 🏙️ Street-View Imagery (SVI)

- **Source:** Google Street View (GSV).  
- **Selection:** 100 unique locations across Jakarta, including Sudirman CBD, Gelora Bung Karno Stadium, and Blok M.  
- **Specifications:** Images were extracted with a fixed **pitch of 0°**, ensuring coverage of the streetscape.  
- **Heading:** Four headings (0–90°, 90–180°, 180–270°, 270–360°) were tested, selecting the one most representative of the streetscape.  
- **Resolution:** All SVIs stored at **640 × 640 px**.  
- To maintain comparability, AI-generated images (originally 1024 × 1024) were **downscaled to 640 × 640 px**.  

---

## 📝 Prompting Strategy

We tested two different prompting strategies to assess how **contextual detail** affects AI-generated representations of sustainable streetscapes.

### With Context
> "Generate a realistic in size of 640x640, high-resolution transformation of the attached street-view image, reimagined as a sustainable streetscape. Preserve the core geometry and perspective of the original view while enhancing it with design interventions aligned with environmental, social, and economic sustainability goals.  
> The image is a street-view image was taken in Jakarta. The street view captures the typical urban character.  
> Enhance the streetscape by widening sidewalks and replacing standard paving with permeable, locally sourced materials that integrate seamlessly with the existing layout. Introduce continuous rows of native trees and landscaped buffers to create shade, reduce urban heat, and improve air quality. Bicycle lanes are added—safely separated from traffic—to support active mobility, while street furniture made from recycled materials provides spaces for resting and social interaction. LED or solar-powered lighting is embedded along pedestrian paths for energy efficiency and safety. Pocket parks or micro public spaces break up the hardscape, encouraging community engagement and biophilic experience. Where appropriate, smart elements like solar-powered benches or environmental sensors may be subtly integrated, contributing to a forward-thinking, inclusive, and ecologically responsive urban street environment."

### Without Context
> "Generate a realistic in size of 640x640 transformation of the attached street-view image with the goal of making the streetscape appear more sustainable. Maintain the original structure and urban layout, but creatively reinterpret the scene through a sustainability-focused lens. Emphasize visual realism and plausible urban design improvements.  
> The image is a street-view photograph taken in Jakarta. The street view captures the typical urban character."

---

## 🖼️ Example Comparison

Below is an example comparison between the original SVI and the AI-generated outputs:  

| Raw SVI | With Context Prompt | Without Context Prompt |  
|---------|---------------------|-------------------------|  
| ![Raw SVI](https://github.com/user-attachments/assets/5acf67d1-bc09-4614-808e-96617d7f4ce6) | ![Context](https://github.com/user-attachments/assets/0ceb6773-533f-4161-aada-33565876113f) | ![Noncontext](https://github.com/user-attachments/assets/bf02b8d8-df57-425b-ab7e-aa2b445ecf11) |  


---

## 📊 Purpose

This repository is meant to **share datasets and methods** used for experimenting with generative AI in urban sustainability research.  
By releasing both the **raw street-view baselines** and the **prompting strategies**, we hope to provide a foundation for further exploration of how AI models

---

## 📄 Copyright and License  

All Street View images are sourced from **Google Street View** and are subject to Google’s [Terms of Service](https://www.google.com/help/terms_maps/).  
The AI-generated images are produced solely for **academic research and non-commercial purposes** in the context of this study.  

© 2025 Mohammad Raditia Pradana. All rights reserved.  
