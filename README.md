## Rep-Review: Fine-Grained Sentiment Analysis for Gym Customer Feedback
Analyzing customer feedback is essential for businesses to understand preferences, improve services, and enhance customer satisfaction. <br>
Aspect-Based Sentiment Analysis (ABSA) enables a more precise evaluation by identifying specific aspects in reviews and determining the sentiment associated with each. This project leverages NLP techniques to automatically extract aspects and classify their sentiments, providing detailed insights from unstructured gym-related reviews. <br>
While focused on gym feedback, the approach is adaptable to any domain with customer reviews, empowering businesses to refine services, enhance marketing strategies, and optimize customer experiences.


### **Aspect-Based Sentiment Analysis (ABSA) for Gym Reviews**

#### **Project Overview**
This project focuses on **Aspect-Based Sentiment Analysis (ABSA)** using **instruction-tuned fine-tuning** and **multi-domain training** to extract and analyze customer feedback in gym reviews. The pipeline includes:
✅ **Aspect Term Extraction** (Instruction-Tuned Fine-Tuning)  
✅ **Aspect Term Sentiment Classification** (Pretrained Model)  
✅ **Aggregation of Insights Across Reviews** (Actionable Decision-Making) 

---
#### **1️⃣ Aspect Term Extraction – Instruction-Based Fine-Tuning**
Generate a small instruction-tuned dataset (GYM dataset), Combined with SemEval datasets (Restaurants + Laptops).
-**Instruction tuning** improves **generalization** and enhances **out-of-domain performance.**
- **Multi-domain training** captures **aspect variations** across different contexts (e.g., **"equipment" in gyms vs. "laptops" in electronics**).
##### **Results:**
- **Joint training improved precision by ~10%** compared to:
  - Cross-validation on GYM data only
  - Training on GYM data alone
---
## **2️⃣ Aspect Term Sentiment Classification**
- **Pretrained model used for sentiment classification after aspect extraction.** Given that sentiment classification is usually **more domain-agnostic** compared to aspect extraction.
---
#### **3️⃣ Aggregation of Insights Across All Reviews**
- **Turning raw ABSA outputs into actionable insights for decision-making.**
---



### Final Results of the Aspect-Based Sentiment Analysis (ABSA)
The tables presented here provide insights into the aspects that customers noticed most, categorized by sentiment.

#### Key Insights:
- **Positive Aspects**: These features of the gym received the most favorable feedback. Highlighting these aspects helps the gym owner understand what customers value, allowing them to emphasize these strengths in future marketing campaigns.
  ![Positive_Aspects_CustomerRated](https://github.com/user-attachments/assets/3955bbd4-29b0-48dc-b834-1733395f3ef9)
- **Negative Aspects**: These reflect areas requiring improvement. By focusing on these aspects, the gym can work toward creating a better overall experience for its members.
  ![Negative_Aspects_CustomerRated](https://github.com/user-attachments/assets/4e64237f-0e91-43f5-b465-1208653ad667)

#### Customer-Centric Approach:
For prospective gym members considering a subscription, these tables offer a concise summary of the feedback they are likely to encounter in reviews. The insights into both positive and negative aspects provide a quick overview of what current customers appreciate and what areas need attention. This enables potential members to assess whether the gym meets their expectations, helping them gain a clearer understanding of the overall experience. By reviewing these tables, they can quickly identify if the aspects they care about, such as equipment quality or customer service, are reflected in the positive or negative categories.

#### Recommendations for the Gym Owner:
- **Leverage Positive Feedback**: Use the positive aspects as key selling points in your marketing strategy. Highlight these features in ads, promotions, and social media campaigns to attract new customers and build loyalty among existing ones.
- **Address Negative Feedback**: Investigate and resolve the negative aspects identified in the analysis. This may involve improving changing rooms, upgrading gym equipment, or revising membership deals. Addressing these areas will enhance the overall customer experience and reduce the risk of losing members due to dissatisfaction.
By effectively utilizing this data, the gym owner can strategically enhance both customer retention and acquisition, optimizing both operational quality and marketing efforts.
