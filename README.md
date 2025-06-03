# Review Dashboard Assessment

## 📝 Task Description
Using the provided dataset, build a small, functional app or dashboard that summarizes review scores for employees, based on feedback from peers, managers, and direct reports.

The dashboard should allow users to:
- ✅ Filter by one or more populations
- ✅ Select users within those populations
- ✅ View behavioural scores from different review sources (self, peer, manager, direct report)

**Estimated time to complete:** 3–4 hours

_Focus on clear thinking, usability, and maintainable code. It’s okay to skip polish—just add a note on what you'd do with more time._

---

## 🔧 Tools Used

> ⚠️ **Note:**  
> While we’re open to Python submissions, our core platform is built in **R and Shiny**, so **submissions using R/Shiny will be prioritised** in the review process.  
>  
> That said, if another tool better showcases your strengths, please feel free to use it—we value thoughtful, well-structured work above all.


We encourage using tools you're most comfortable with while meeting the core goal: creating a clear, insightful, and maintainable summary dashboard.

---

## 📊 Key Features

- Filter by one or more populations
- Select users within those populations
- View behavioural scores from different review types (self, peer, manager)
- Simple and maintainable code structure

---

## 🧭 Running the App

> 👇 Please complete the relevant section depending on your tool choice.

### **For R / Shiny:**

1. Clone this repo or download the zip
2. Open `app.R` in RStudio
3. Install packages:
   ```r
   install.packages(c("shiny", "tidyverse"))
   ```
4. Run:
   ```r
   shiny::runApp()
   ```

### **For Streamlit (Python):**

1. Install Python 3.8+ and `pip install -r requirements.txt`
2. Run the app:
   ```bash
   streamlit run app.py
   ```

---

## 🧩 Answers to Assessment Questions

1. **Design choices:**  
   Briefly explain your approach to layout, interactivity, and maintainability.

2. **Extensions:**  
   What additional insights or charts would you add next?

3. **Clarifying stakeholder needs:**  
   What would you ask before comparing self vs. peer reviews?

---

## 🌐 Optional: Live Demo

If deployed:
- [View Shiny app](https://your-shinyapp-url.shinyapps.io/app-name/)
- [View Streamlit app](https://your-username.streamlit.app/app-name/)

---

## 📂 Folder Structure (Example)

```
project/
├── data/
│   └── review_scores.csv
├── app.R / app.py 
├── README.md
├── requirements.txt (if Python)
└── screenshots/
```

---

## 📬 How to Submit

You may submit your work in **one of the following formats**:
- A public GitHub or GitLab repository (recommended)
- A zipped folder with files and instructions
- A link to a hosted dashboard with a downloadable package
