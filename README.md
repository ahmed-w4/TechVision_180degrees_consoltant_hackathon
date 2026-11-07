# ☕ Grind & Crumb: Profitability & Ops Optimiser

## 📖 Overview
This repository contains the winning project developed for the **Code & Consult Hackathon** (hosted by 180DC Sheffield, Enactus, and TechVision). 

The challenge was to act as a consultancy for "Grind & Crumb," a fictional coffee chain struggling with high sales but declining profits. The CEO tasked us with strategically allocating a **£1.5 million investment** to fix operational inefficiencies.

As the technical lead, I developed an interactive **Streamlit** application that uses Python, Pandas, and Machine Learning to diagnose the root causes of profit leakage and provide actionable, data-driven solutions.

## 🚀 The Strategic Insights
Through rigorous data analysis and NLP, we identified four major issues bleeding the company dry:
1. **The Flagship Trap:** The highest-revenue store (Manchester Piccadilly) was operating at a loss due to £30.5k/month rent.
2. **The Delivery Black Hole:** Third-party delivery platforms (UberEats/Deliveroo) were taking a 30-35% commission, making delivery orders half as profitable as in-store orders.
3. **The Waste Problem:** The Hull store had a 20% waste rate (double the company average) due to over-ordering.
4. **The Expansion Gamble:** Identifying which candidate sites would actually yield a positive ROI.

## 💻 The Tool: How it Works
The application is designed to be used directly by the CEO and the ops team:

*   **Interactive Dashboards:** Uses `Matplotlib` and `Seaborn` to visualize store profit margins, waste rates, and delivery commission impacts.
*   **Predictive ROI Modeling:** An interactive slider allows the CEO to see the financial payback period of our proposed £1.5m strategy, proving a full return on investment by Year 3.

## 🛠️ Tech Stack
*   **Language:** Python
*   **Frontend/UI:** Streamlit
*   **Data Processing:** Pandas, NumPy
*   **Visualization:** Matplotlib, Seaborn

## 🏆 The £1.5m Allocation Strategy
Our winning pitch utilized the entire £1.5m budget to ensure zero "dead cash":
*   **£600k** - First-Party App & Loyalty Program (bypasses third-party commissions)
*   **£300k** - Manchester Piccadilly Lease Fix (stops the cash bleed)
*   **£200k** - Targeted Marketing (drives footfall in high-margin areas)
*   **£400k** - Buffer Cash for Market Volatility

## 👥 Team
Built in an 8-hour sprint by a multidisciplinary team:
*   Ahmed - Technical Lead / Data Science (Python, Streamlit, ML)
*   Louis - Business Strategy & Financial Modeling
*   Abimbola - Market Research & Presentation
*   Mohammed - Created the application

## ⚙️ How to Run Locally
1. Clone the repo: `git clone https://github.com/yourusername/grind-and-crumb.git`
2. Install requirements: `pip install -r requirements.txt`
3. Run the app: `streamlit run app.py`
