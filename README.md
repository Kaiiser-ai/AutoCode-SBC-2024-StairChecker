# 🏛️ AutoCode Mini – SBC 2024 Staircase Compliance Checker

A rule-based AI-assisted prototype that evaluates **staircase geometry** against **SBC 2024** requirements.  
This tool was developed as part of the "AI Applied to Architecture & Construction" program,  
focusing on converting an AECO Product Requirements Document (PRD) into a working application.

---

## 🚀 Live Application (Lovable Deployment)

A permanent, fully deployed version of the application is available here:

👉 **https://nova-creation-station.lovable.app**

This version is built in Lovable.dev using Vibe Coding and includes:

- User-friendly web interface  
- Real-time compliance checking  
- PASS/FAIL results for each SBC rule  
- Overall compliance summary  

---

## 🧪 Optional Implementation (Google Colab Version)

A second version of the tool was built in Python + Gradio in Google Colab.  
This demonstrates cross-platform reproducibility using the same PRD logic.

👉 Colab App (temporary link):  
**https://7c84edb80622810ea2.gradio.live**

👉 Notebook Source:  
`AutoCode_Mini_(SBC_Stair_Checker).ipynb`

---

## 📘 Project Objective

The goal of this project is to:

- Translate natural-language SBC staircase requirements into structured rule-based logic  
- Implement that logic in an interactive web tool  
- Demonstrate how AI tools (Lovable, Gradio, LLM-assisted coding) streamline AECO automation  
- Provide a fast, reliable way to validate stair geometry early in design  

---

## 📥 Inputs (Geometry Parameters in mm)

The user provides:

- Riser height  
- Tread depth  
- Flight width  
- Landing width  
- Headroom above landings  
- Headroom between flights  
- Handrail height  
- Guardrail height  
- Maximum guard opening  
- Door leaf projection  

---

## ✔ Compliance Logic (SBC 2024)

The following rules are implemented:

| Check | Requirement |
|-------|-------------|
| Riser Height | 150–175 mm |
| Tread Depth | ≥ 275 mm |
| Flight Width | ≥ 1100 mm |
| Landing Width | ≥ 1100 mm |
| Headroom (Landing) | ≥ 2300 mm |
| Headroom (Between Flights) | ≥ 2100 mm |
| Handrail Height | 850–950 mm |
| Guardrail Height | ≥ 1100 mm |
| Max Guard Opening | ≤ 150 mm |
| Door Projection | ≤ 0.5 × landing width |

The app returns a **PASS/FAIL** message for each check, plus a **final compliance verdict**.

---

## 🛠 How to Run Locally (Optional)

### 1. Clone the repository:
```bash
git clone https://github.com/Kaiiser-ai/AutoCode-SBC-2024-StairChecker.git
cd AutoCode-SBC-2024-StairChecker
2. Install dependencies:
pip install -r requirements.txt
3. Open the Colab notebook:

Run the notebook locally or upload it to Google Colab:

AutoCode_Mini_(SBC_Stair_Checker).ipynb

4. Run all cells to start the Gradio app.
📂 Repository Contents
AutoCode-SBC-2024-StairChecker/
│
├── AutoCode_Mini_(SBC_Stair_Checker).ipynb   # Python + Gradio implementation
├── README.md                                  # Project documentation
├── requirements.txt                            # Dependencies for local execution
└── (Optional) Additional screenshots/docs

🪪 License

This project is provided under the MIT License.
You may use, modify, and distribute for educational purposes.

👤 Author

Mohamad Jaber
Architect | BIM Manager | AI for AECO
GitHub: https://github.com/Kaiiser-ai




