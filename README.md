# Deductive and Simple Interest — Interactive Educational Website

An interactive, editorial-style educational resource on **Deductive and Simple Interest** designed for college students in **Mathematics in the Modern World (MMW)** and business mathematics in the Philippines.

The website is a self-contained, single-file web application (`index.html`) built with HTML5, CSS3, and vanilla JavaScript. It requires no frameworks, build tools, backend server, or external CDN dependencies.

---

## 🌟 Key Features

1. **Editorial Design & Identity:**
   - Palette inspired by academic textbooks: warm ivory background, soft cream sections, muted sage green interactive accents, and pale yellow highlights.
   - High text contrast and readable system typography (`Charter`, `Bitstream Charter`, `Georgia`, and system sans-serif).
   - Fully responsive across desktop, tablet, and mobile devices with smooth scrolling and reduced-motion support.

2. **Core Concepts & Theory:**
   - Clear distinction between **Ordinary Simple Interest** (added at maturity: $A = P + I$) and **Deductive Interest** (discounted upfront: $\text{Proceeds} = P - I$).
   - Rigorous explanation of the **Effective Interest Rate (EIR)**: why upfront deductions raise the true borrowing cost.
   - Philippine context including Republic Act No. 3765 (*Truth in Lending Act*) and Bangko Sentral ng Pilipinas (BSP) disclosure requirements.

3. **Formula Reference:**
   - Simple Interest: $I = P \cdot r \cdot t$
   - Total Maturity Amount: $A = P + I = P(1 + rt)$
   - Deductive Net Proceeds: $\text{Proceeds} = P - I = P(1 - rt)$
   - Effective Interest Rate: $r_{\text{eff}} = \frac{I}{\text{Proceeds} \times t}$
   - Algebraic rearrangements solving for unknown $P$, $r$, and $t$.

4. **Step-by-Step Worked Solutions:**
   - **Maria's Savings Deposit:** Standard benchmark calculating interest ($I = ₱400$) and total balance ($A = ₱5,400$) on ₱5,000 at 4% for 2 years.
   - **Angelo's Deductive Loan:** ₱20,000 borrowed at 8% deductive interest for 1 year, detailing the ₱1,600 upfront deduction, ₱18,400 net proceeds, ₱20,000 repayment, and 8.70% effective rate.
   - **Time Deposit in Months:** Proper time unit conversion ($t = 9/12 = 0.75\text{ years}$).

5. **Interactive Example Explorer:**
   - 4 tab-switchable real-world Philippine case studies (Sari-sari store loan, missing interest rate, tuition promissory note, finding required initial deposit) with revealable step-by-step solutions.

6. **Dual-Mode Financial Calculator:**
   - Calculate either **Ordinary (Add-On)** or **Deductive (In Advance)** interest.
   - Automatic unit conversion between years and months.
   - Real-time input validation, formatted Philippine pesos (`₱XX,XXX.XX`), and dynamic formula explanations.
   - Quick-load preset scenarios.

7. **Practice Activities & Comprehensive Final Quiz:**
   - 5 guided practice questions with instant remedial explanations and retry options.
   - 10-question final examination with live progress, real-time score tracking, performance assessment, and full question-by-question review table.

8. **Error Prevention & Real-World Applications:**
   - 5 common student traps (percentage vs. decimal, month conversion, interest vs. balance, face value vs. net proceeds, nominal vs. effective rate).
   - Practical Philippine applications (time deposits, salary loans, SME financing, and consumer protection).

---

## 🚀 How to Run Locally

Simply double-click `index.html` or open it in any modern web browser:
- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Apple Safari

No server, installation, or internet connection is required.

---

## 🌐 Enable GitHub Pages (To View Online)

To publish this website live for free on GitHub Pages:
1. Go to your repository settings: [AkiraJade/mmwProject Settings](https://github.com/AkiraJade/mmwProject/settings/pages).
2. Under **Build and deployment** > **Branch**, select `main` and `/ (root)`.
3. Click **Save**.
4. Within a few moments, your interactive site will be live at:
   `https://akirajade.github.io/mmwProject/`

---

## 📄 License

This educational project is created for academic and personal learning purposes under the CHED General Education Mathematics in the Modern World (MMW) curriculum.
