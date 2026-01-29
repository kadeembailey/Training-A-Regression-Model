# Training-A-Regression-Model
Training a regression model using ML lite platform
---

# 🧊 Part 1 — Train a Regression Model (Predict Ice Cream Sales)

### **1. Download the data**
- Go to **https://aka.ms/mslearn-ai-data**
- Download **ml-data.zip**
- Extract it somewhere on your computer  
  (you’ll see files like *ice-cream.csv*, *penguins.csv*, *customers.csv*, etc.)

### **2. Open ML Lite**
- Go to **https://aka.ms/ml-lite**
- Wait a few seconds for the ML engine to load.

### **3. Choose model type + upload data**
- On the first page:
  - Select **Regression**
  - Upload **ice-cream.csv**
  - You’ll see a preview of the data.



<img width="1352" height="719" alt="ML Lite start" src="https://github.com/user-attachments/assets/8fcda30c-3453-4c07-99c8-399a0fffd718" />


### **4. Configure training**
- Set **Target column** → **IceCreamsSold**  
  (this is what you want the model to predict)
- **Deselect Date**  
  (it’s unique every day, so it doesn’t help prediction)
- Keep all other columns selected as features.
- Review the **Training/Testing split**  
  (usually 70% training, 30% testing)


<img width="1364" height="726" alt="Training Settings" src="https://github.com/user-attachments/assets/ffd86bc0-0134-4f89-89a3-04b97c9c1a1e" />

### **5. Train the model**
- Go to the Training Process page.
- Review settings.
- Click **Train**.
- When finished, you can:
  - Save the model locally
  - View logs
  - View model details

<img width="1336" height="571" alt="TP" src="https://github.com/user-attachments/assets/f224aac8-d7b7-4ee3-846c-5b1b7d0f635c" />
<img width="965" height="367" alt="TL" src="https://github.com/user-attachments/assets/4011f372-52e2-44c3-84db-d748bbbda638" />


### **6. Review results**
- On the Training Results page:
  - Look at the metrics (how accurate the model is)
  - Look at the chart comparing **predicted vs actual** sales  
    (a good model shows a straight-line trend)
<img width="1349" height="597" alt="TR" src="https://github.com/user-attachments/assets/b7a8ef60-cd9f-4577-aeb6-9e9aa5402cb7" />



### **7. Test the model**
Use the Test Model page to try predictions.

<img width="1348" height="619" alt="TMR" src="https://github.com/user-attachments/assets/0e447abb-bbca-4acd-bd3e-b38f0f621da5" />




Just tell me what format helps you learn best.
