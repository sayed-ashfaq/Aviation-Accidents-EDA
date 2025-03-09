# **Aviation Accident Data Analysis**  

## **Overview**  
This project analyzes aviation accident data to identify trends, contributing factors, and patterns that impact flight safety. The goal is to derive insights that can help improve aviation safety and reduce the likelihood of accidents.  

## **Dataset**  
The dataset is sourced from the **NTSB aviation accident database** and contains accident records from **1962 to 2023**. It includes details such as:  
- **Aircraft Type & Model**  
- **Accident Date & Location**  
- **Weather Conditions**  
- **Phase of Flight at Accident**  
- **Injury Severity & Fatalities**  

### **Dataset Information:**  
- **Total Records:** 88,889  
- **Total Features:** 31  

## **Objectives**  
- **Trend Analysis:** Identify patterns in accident frequency over time.  
- **Geographical Analysis:** Determine accident-prone regions.  
- **Aircraft Safety Evaluation:** Analyze which aircraft types and engine types are more prone to accidents.  
- **Weather & Flight Phase Impact:** Understand how weather conditions and flight phases affect accident rates.  

## **Exploratory Data Analysis (EDA)**  
### **Key Insights from EDA:**  
1. **Accident Trends:**  
   - Accidents increased significantly after 1980 due to mass production of aircraft.  
   - Over time, accident rates have declined, but incidents still occur frequently.  

2. **Monthly Trends:**  
   - Most accidents occur in **June, July, and August**, aligning with heavy travel and monsoon seasons.  
   - Suggests extra safety measures should be implemented during these months.  

3. **Accident Distribution by Aircraft Type:**  
   - **Airplanes** have the highest number of accidents, followed by **helicopters and gliders**.  

4. **Impact of Weather Conditions:**  
   - Accidents occur more frequently in **Visual Meteorological Conditions (VMC)** than **Instrument Meteorological Conditions (IMC)**.  
   - Suggests reliance on **instrumentation** can enhance safety.  

5. **Flight Phases Prone to Accidents:**  
   - **Landing and takeoff** phases see the most accidents.  
   - Indicates that advanced **automated landing systems** could reduce risks.  

## **Machine Learning Scope**  
We plan to use **predictive modeling** to estimate accident probability based on historical patterns. Potential models include:  
- **Logistic Regression**  
- **Random Forest Classifier**  
- **Gradient Boosting**  

## **Files in Repository**  
- `AviationAccidents-EDA.ipynb` → Jupyter Notebook with full analysis  
- `AviationData.csv` → Raw dataset  
- `USState_Codes.csv` → Mapping file for state-level analysis  

## **Technologies Used**  
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn)  
- **Jupyter Notebook**  
- **Git & GitHub**  

## **How to Run the Project**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/sayed-ashfaq/Aviation-Accident-EDA.git
   cd Aviation-Accident-EDA
   ```
2. Install required libraries:  
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Open the Jupyter Notebook:  
   ```bash
   jupyter notebook
   ```
4. Run `AviationAccidents-EDA.ipynb` to explore the analysis.  

## **Conclusion & Recommendations**  
- **Weather plays a significant role in accidents.** Airlines should enforce stricter rules for flights during high-risk months.  
- **Automated Instrumentation Systems (IMC) reduce accidents.** Encouraging the use of advanced avionics in small aircraft can improve safety.  
- **Takeoff and landing remain critical.** Investing in better pilot training and automated landing assistance is crucial.  
- **Personal aircraft accidents are high.** Stricter maintenance and licensing regulations for private aircraft can mitigate risks.  

## **Disclaimer / Note**  
This project is a result of extensive **independent analysis and research**. The **initial observations, trend analysis, and insights were derived through detailed EDA performed by me**. To ensure clarity and a structured presentation, **ChatGPT was used for fact-checking, formatting, and refining the observations into a well-organized report**. This approach allowed me to focus on deep data exploration while leveraging AI to improve readability and structure.
