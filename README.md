# Davido Music Sales & Streams Analysis with Predictive Modeling  

##  Project Overview  
This project analyzes **Davido’s music sales and streaming performance** across key countries.  
Using **descriptive, diagnostic, predictive, and prescriptive analytics**, the study identifies conversion gaps, forecasts potential sales uplift, and optimizes marketing spend across different regions.  

The goal is to address the business problem of **low and uneven conversion rates** (streams → sales) across countries, and provide a **data-driven strategy** for improved performance.  

---

##  Business Problem  
Millions of streams are generated across countries, but only a small fraction convert into sales (downloads, merchandise, or concert tickets). Conversion rates vary significantly by country, making it difficult to allocate marketing budgets effectively.  

---

## 🔍 Methods Applied  
1. **Descriptive Analytics**  
   - Summarized streams and sales across countries.  
   - Computed conversion rates (Sales ÷ Streams).  
   - Highlighted gaps (e.g., Nigeria: 2% vs. USA: 3%).  

2. **Diagnostic Analytics (OLS Regression)**  
   - Modeled log(Sales) as a function of:  
     - log(Streams)  
     - Marketing Score  
     - Social Media Score  
     - GDP per Capita  
     - Smartphone Penetration  
   - Found that **Streams + Social Media Reach** were the strongest predictors of sales.  

3. **Predictive Analytics (Simulation)**  
   - Forecasted sales impact if marketing scores improved.  
   - Example: Nigeria baseline sales (72,000) projected to increase under higher marketing investment.  

4. **Prescriptive Analytics (Heuristic Allocation)**  
   - Developed a priority-based budget allocation model.  
   - Allocated more budget to **high-stream but low-conversion** countries (e.g., Nigeria, South Africa).  
   - Estimated **13K+ uplift in Nigeria** alone.  

---

## Key Insights  
- **Nigeria** → Highest streams (3.6M) but only 2% conversion. Biggest growth opportunity.  
- **USA & UK** → Fewer streams but stronger conversion (3% and 2.5%). High-value markets.  
- **South Africa, Ghana, Kenya** → Weak conversion rates (<1.5%). Require targeted campaigns.  
- Sales are **driven by streams + social media engagement**, not by GDP or smartphone penetration.  

---

##Tools & Technologies  
- **Python** (Google Colab / Jupyter Notebook)  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `statsmodels`  
- Data Sources:  
  - Spotify Monthly Listeners (via Kworb.net, Chartmetric)  
  - Billboard Digital Song Sales (US), Official Charts (UK), Apple Music Charts  
  - Social Media: Twitter/X API, Instagram engagement (via SocialBlade)  
  - Macroeconomic Data: World Bank (GDP), GSMA Mobile Economy (smartphone penetration)
  - 

 📈 Results

Regression model achieved R² = 0.996, showing excellent fit.

Streams + Social Media Reach = strongest drivers of sales.

Prescriptive budget allocation suggested Nigeria, USA, and UK as top priority markets.

📜 License

This project is licensed under the MIT License – feel free to use and adapt with attribution.

👤 Author

Bright Egho

Business Intelligence & Data Analyst

Skilled in Python, SQL, Machine Learning, ETL, and Predictive Analytics,BI Tools(visualizations)

Also experienced in SEO, SMO, and WordPress Management
