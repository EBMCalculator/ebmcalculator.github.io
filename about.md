<div style="text-align: center;">
  <img src="/assets/images/EBM Calculator Logo Any 3x.png" alt="EBM Calculator Logo" width="200">
  <h1>EBM Calculator</h1>
</div>

<style>
  .tab-bar {
    display: flex;
    justify-content: center;
    border-bottom: 2px solid #ccc;
    padding-bottom: 10px;
    margin-top: 20px;
  }
  .tab-bar a {
    padding: 10px 20px;
    text-decoration: none;
    white-space: nowrap;
    transition: padding 0.3s ease;
  }
  @media (max-width: 480px) {
    .tab-bar a {
      padding: 10px 10px;
    }
  }
  /* Box styling for non-collapsible sections */
  .faq-item {
    margin-bottom: 20px;
  }
  .faq-question {
    font-weight: bold;
    padding: 10px;
    background: #f7f7f7;
    border: 1px solid #ccc;
  }
  .faq-answer {
    display: block; /* Always visible */
    padding: 10px;
    border: 1px solid #ccc;
    border-top: none;
  }
    /* Additional styling for the collapsible formulas box */
  details {
    margin: 20px auto;
    max-width: 600px;
    border: 1px solid #ccc;
  }
  details summary {
    font-weight: bold;
    padding: 10px;
    background: #f7f7f7;
    border-bottom: 1px solid #ccc;
    cursor: pointer;
  }
  details div {
    padding: 10px;
  }
  pre {
    white-space: pre-wrap; /* Allow line wrapping */
    word-wrap: break-word;
  }
</style>

<div class="tab-bar">
  <a href="/">Home</a>
  <a href="/about">About</a>
  <a href="/support">Support</a>
  <a href="/privacy-policy">Privacy</a>
</div>

<h2 style="text-align: center;">About</h2>

<div style="max-width: 600px; margin: 20px auto;">
  <!-- Disclaimer Box -->
  <div class="faq-item">
    <div class="faq-question">Disclaimer</div>
    <div class="faq-answer">
      <p>This app was created for educational use. The content provided should not replace clinical judgement and results should be interpreted within the context of statistical and study limitations. Medical decisions should <strong>NOT</strong> be based solely on results from this app.</p>
    </div>
  </div>
</div>

<div style="max-width: 600px; margin: 20px auto; text-align: center;" markdown="1">
  I hope my app helps your ongoing learning and appraisal of medical literature!
  
  **Questions or Feedback?** <br>
  [support@ebmcalculator.com](mailto:support@ebmcalculator.com)  
</div>

<div style="text-align: center; margin-top: 40px;">
  &copy; 2024 David A. Stewart, MD
</div>

<!-- Collapsible Formulas Box -->
<details>
  <summary>Formulas</summary>
  <div>
    <pre>
\documentclass[fleqn,12pt]{article}
\usepackage[margin=1in]{geometry}
\usepackage{xcolor}
\usepackage{amsmath}
\usepackage{amssymb}
\usepackage{array}
\usepackage{multicol}
\usepackage{fancyhdr}
\usepackage{lscape}
\usepackage{graphicx}
\usepackage{longtable}
\usepackage{titlesec}
\usepackage{url}

\titleformat{\subsection}[runin]{\large\bfseries}{}{0pt}{}[\\]
\titleformat{\paragraph}[runin]{\bfseries}{}{0pt}{}[\\]

\begin{document}

\begin{center}
\LARGE \textbf{Formulas for Effect Estimates}
\end{center}
\vspace{0.5cm}

% --- 2x2 Table for Effect Estimates ---
\begin{center}
\renewcommand{\arraystretch}{2.0} % controls vertical spacing (default is 1.0)
\begin{math}
\begin{array}{c c c c}
 & \text{Outcome} & \shortstack{No\\Outcome} & \text{Total} \\
\cline{2-3}
(+) & \multicolumn{1}{|c|}{a} & \multicolumn{1}{c|}{b} & a + b \\
\cline{2-3}
(-) & \multicolumn{1}{|c|}{c} & \multicolumn{1}{c|}{d} & c + d \\
\cline{2-3}
\text{Total} & a + c & b + d & a + b + c + d \\
\end{array}
\end{math}
\end{center}
\medskip

\begin{center}
\text{z = 1.959964 for 95\% CI}
\end{center}


% --- Effect Estimates ---

\subsection*{Experimental Event Rate}
\[
\text{EER} = \frac{a}{a + b}
\]

\vspace{0.5cm}
\subsection*{Control Event Rate}
\[
\text{CER} = \frac{c}{c + d}
\]

\vspace{0.5cm}
\subsection*{Absolute Risk Reduction}
\[
\text{ARR} = \text{CER} - \text{EER}
\]

\paragraph{Confidence Interval (Wilson score bounds with error propagation)}
\[
\text{Lower Bound: } \text{ARR} - z \cdot \sqrt{ \frac{u_2 (1 - u_2)}{r_1} + \frac{w_1 (1 - w_1)}{r_2} }
\]
\[
\text{Upper Bound: } \text{ARR} + z \cdot \sqrt{ \frac{u_1 (1 - u_1)}{r_2} + \frac{w_2 (1 - w_2)}{r_1} }
\]

\vspace{0.3cm}
\[
\text{where... }
\]
\[
r_1 = a + b, \quad r_2 = c + d
\]
\[
u_1 = \frac{2c + z^2 + z \sqrt{ \frac{4(c \cdot d)}{r_2} + z^2 }}{2r_2 + 2z^2}
\]
\[
u_2 = \frac{2a + z^2 + z \sqrt{ \frac{4(a \cdot b)}{r_1} + z^2 }}{2r_1 + 2z^2}
\]
\[
w_1 = \frac{2c + z^2 - z \sqrt{ \frac{4(c \cdot d)}{r_2} + z^2 }}{2r_2 + 2z^2}
\]
\[
w_2 = \frac{2a + z^2 - z \sqrt{ \frac{4(a \cdot b)}{r_1} + z^2 }}{2r_1 + 2z^2}
\]

\vspace{0.5cm}
\subsection*{Risk Ratio}
\[
\text{RR} = \frac{\text{EER}}{\text{CER}}
\]

\paragraph{Confidence Interval (Log-normal, Zhou)}
\[
\text{Lower Bound: } \exp \left( \ln(\text{RR}) - z \cdot \sqrt{ \left( \frac{1}{a} - \frac{1}{a + b} \right) + \left( \frac{1}{c} - \frac{1}{c + d} \right) } \right)
\]
\[
\text{Upper Bound: } \exp \left( \ln(\text{RR}) + z \cdot \sqrt{ \left( \frac{1}{a} - \frac{1}{a + b} \right) + \left( \frac{1}{c} - \frac{1}{c + d} \right) } \right)
\]

\vspace{0.5cm}
\subsection*{Relative Risk Reduction}
\[
\text{RRR} = 1 - \text{RR}
\]

\paragraph{Confidence Interval (Derived from Log-normal RR)}
\[
\text{Lower Bound: } 1 - \exp \left( \ln(\text{RR}) + z \cdot \sqrt{ \left( \frac{1}{a} - \frac{1}{a + b} \right) + \left( \frac{1}{c} - \frac{1}{c + d} \right) } \right)
\]
\[
\text{Upper Bound: } 1 - \exp \left( \ln(\text{RR}) - z \cdot \sqrt{ \left( \frac{1}{a} - \frac{1}{a + b} \right) + \left( \frac{1}{c} - \frac{1}{c + d} \right) } \right)
\]

\newpage
\subsection*{Odds Ratio}
\[
\text{OR} = \frac{ad}{cb}
\]

\paragraph{Confidence Interval (Log-normal)}
\[
\text{Lower Bound: } \exp \left( \ln(\text{OR}) - z \cdot \sqrt{ \frac{1}{a} + \frac{1}{b} + \frac{1}{c} + \frac{1}{d} } \right)
\]
\[
\text{Upper Bound: } \exp \left( \ln(\text{OR}) + z \cdot \sqrt{ \frac{1}{a} + \frac{1}{b} + \frac{1}{c} + \frac{1}{d} } \right)
\]

\vspace{1cm}
\section*{References}
\begin{flushleft}
\small

1. Altman DG. Confidence intervals for the number needed to treat. \textit{BMJ}. 1998 Nov 7;317(7168):1309–1312. \\
doi: \texttt{10.1136/bmj.317.7168.1309}. PMID: 9804726; PMCID: PMC1114210. \\
\url{https://pubmed.ncbi.nlm.nih.gov/9804726/}

\vspace{0.5em}

2. Bender R. Calculating confidence intervals for the number needed to treat. \textit{Control Clin Trials}. 2001 Apr;22(2):102–110. \\
doi: \texttt{10.1016/s0197-2456(00)00134-3}. PMID: 11306148. \\
\url{https://pubmed.ncbi.nlm.nih.gov/11306148/}

\vspace{0.5em}

3. Fleiss JL, Levin B, Paik MC. (2003). \textit{Statistical Methods for Rates and Proportions} (3rd ed.). Wiley. \\
ISBN: 978-0-471-52629-2. \\
\url{https://www.wiley.com/en-us/Statistical+Methods+for+Rates+and+Proportions%2C+3rd+Edition-p-9780471526292}

\vspace{0.5em}

4. Mercaldo ND, Lau KF, Zhou XH. Confidence intervals for predictive values with an emphasis to case-control studies. \textit{Stat Med}. 2007 May 10;26(10):2170–2183. \\
doi: \texttt{10.1002/sim.2677}. PMID: 16927452. \\
\url{https://pubmed.ncbi.nlm.nih.gov/16927452/}

\vspace{0.5em}

5. Julious SA. Two-sided confidence intervals for the single proportion: comparison of seven methods by Robert G. Newcombe, \textit{Stat Med}. 2005 Nov 15;24(21):3383–3384. \\
doi: \texttt{10.1002/sim.2164}. PMID: 16206245. \\
\url{https://pubmed.ncbi.nlm.nih.gov/16206245/}

\vspace{0.5em}

6. Zhou XH, Obuchowski NA, McClish DK. (2011). \textit{Statistical Methods in Diagnostic Medicine} (2nd ed.). Wiley. \\
Print ISBN: 9780470183144. Online ISBN: 9780470906514. \\
\url{https://onlinelibrary.wiley.com/doi/book/10.1002/9780470906514}

\end{flushleft}


\newpage
\begin{center}
\LARGE \textbf{Formulas for Diagnostic Tests}
\end{center}
\vspace{0.5cm}

% --- 2x2 Table for Diagnostic Tests ---
\begin{center}
\renewcommand{\arraystretch}{2.0} % controls vertical spacing (default is 1.0)
\begin{math}
\begin{array}{c c c c}
 & \text{Outcome} & \shortstack{No\\Disease} & \text{Total} \\
\cline{2-3}
(+) & \multicolumn{1}{|c|}{a} & \multicolumn{1}{c|}{b} & a + b \\
\cline{2-3}
(-) & \multicolumn{1}{|c|}{c} & \multicolumn{1}{c|}{d} & c + d \\
\cline{2-3}
\text{Total} & a + c & b + d & a + b + c + d \\
\end{array}
\end{math}
\end{center}
\medskip

\begin{center}
\text{z = 1.959964 for 95\% CI}
\end{center}


\subsection*{Sensitivity}
\[
\text{Sensitivity} = \frac{a}{a + c}
\]

\paragraph{Confidence Interval (Wilson Score)}
\[
\text{Lower Bound: } \frac{(2 \cdot a) + z^2 - z \cdot \sqrt{ \left( \frac{4ac}{a + c} \right) + z^2 }}{2 \cdot (a + c) + 2z^2}
\]
\[
\text{Upper Bound: } \frac{(2 \cdot a) + z^2 + z \cdot \sqrt{ \left( \frac{4ac}{a + c} \right) + z^2 }}{2 \cdot (a + c) + 2z^2}
\]

\vspace{0.5cm}
\subsection*{Specificity}
\[
\text{Specificity} = \frac{d}{b + d}
\]

\paragraph{Confidence Interval (Wilson Score)}
\[
\text{Lower Bound: } \frac{(2 \cdot d) + z^2 - z \cdot \sqrt{ \left( \frac{4db}{b + d} \right) + z^2 }}{2 \cdot (b + d) + 2z^2}
\]
\[
\text{Upper Bound: } \frac{(2 \cdot d) + z^2 + z \cdot \sqrt{ \left( \frac{4db}{b + d} \right) + z^2 }}{2 \cdot (b + d) + 2z^2}
\]

\vspace{0.5cm}
\subsection*{Positive Likelihood Ratio}
\[
\text{LR(+)} = \frac{\text{Sensitivity}}{1 - \text{Specificity}} = \frac{a / (a + c)}{b / (b + d)}
\]

\paragraph{Confidence Interval (Log-normal, Zhou)}
\[
\text{Lower Bound: } 
\exp\left( \ln\left( \frac{(b + d) \cdot a}{(a + c) \cdot b} \right) 
- z \cdot \sqrt{ \left( \frac{c}{a \cdot (a + c)} \right) + \left( \frac{d}{b \cdot (b + d)} \right) } \right)
\]

\[
\text{Upper Bound: } 
\exp\left( \ln\left( \frac{(b + d) \cdot a}{(a + c) \cdot b} \right) 
+ z \cdot \sqrt{ \left( \frac{c}{a \cdot (a + c)} \right) + \left( \frac{d}{b \cdot (b + d)} \right) } \right)
\]

\vspace{0.5cm}
\subsection*{Negative Likelihood Ratio}
\[
\text{LR(–)} = \frac{1 - \text{Sensitivity}}{\text{Specificity}} = \frac{c / (a + c)}{d / (b + d)}
\]

\paragraph{Confidence Interval (Log-normal, Zhou)}
\[
\text{Lower Bound: } 
\exp\left( \ln\left( \frac{(b + d) \cdot c}{(a + c) \cdot d} \right) 
- z \cdot \sqrt{ \left( \frac{a}{c \cdot (a + c)} \right) + \left( \frac{b}{d \cdot (b + d)} \right) } \right)
\]

\[
\text{Upper Bound: } 
\exp\left( \ln\left( \frac{(b + d) \cdot c}{(a + c) \cdot d} \right) 
+ z \cdot \sqrt{ \left( \frac{a}{c \cdot (a + c)} \right) + \left( \frac{b}{d \cdot (b + d)} \right) } \right)
\]


\vspace{0.5cm}
\subsection*{Positive Predictive Value}
\[
\text{PPV} = \frac{a}{a + b}
\]

\paragraph{Confidence Interval (Wilson Score)}
\[
\text{Lower Bound: } \frac{(2 \cdot a) + z^2 - z \cdot \sqrt{ \left( \frac{4ab}{a + b} \right) + z^2 }}{2 \cdot (a + b) + 2z^2}
\]
\[
\text{Upper Bound: } \frac{(2 \cdot a) + z^2 + z \cdot \sqrt{ \left( \frac{4ab}{a + b} \right) + z^2 }}{2 \cdot (a + b) + 2z^2}
\]

\vspace{0.5cm}
\subsection*{Negative Predictive Value}
\[
\text{NPV} = \frac{d}{c + d}
\]

\paragraph{Confidence Interval (Wilson Score)}
\[
\text{Lower Bound: } \frac{(2 \cdot d) + z^2 - z \cdot \sqrt{ \left( \frac{4dc}{c + d} \right) + z^2 }}{2 \cdot (c + d) + 2z^2}
\]
\[
\text{Upper Bound: } \frac{(2 \cdot d) + z^2 + z \cdot \sqrt{ \left( \frac{4dc}{c + d} \right) + z^2 }}{2 \cdot (c + d) + 2z^2}
\]

\vspace{1cm}
\section*{References}
\begin{flushleft}
\small

1. Altman DG. Confidence intervals for the number needed to treat. \textit{BMJ}. 1998 Nov 7;317(7168):1309–1312. \\
doi: \texttt{10.1136/bmj.317.7168.1309}. PMID: 9804726; PMCID: PMC1114210. \\
\url{https://pubmed.ncbi.nlm.nih.gov/9804726/}

\vspace{0.5em}

2. Bender R. Calculating confidence intervals for the number needed to treat. \textit{Control Clin Trials}. 2001 Apr;22(2):102–110. \\
doi: \texttt{10.1016/s0197-2456(00)00134-3}. PMID: 11306148. \\
\url{https://pubmed.ncbi.nlm.nih.gov/11306148/}

\vspace{0.5em}

3. Fleiss JL, Levin B, Paik MC. (2003). \textit{Statistical Methods for Rates and Proportions} (3rd ed.). Wiley. \\
ISBN: 978-0-471-52629-2. \\
\url{https://www.wiley.com/en-us/Statistical+Methods+for+Rates+and+Proportions%2C+3rd+Edition-p-9780471526292}

\vspace{0.5em}

4. Mercaldo ND, Lau KF, Zhou XH. Confidence intervals for predictive values with an emphasis to case-control studies. \textit{Stat Med}. 2007 May 10;26(10):2170–2183. \\
doi: \texttt{10.1002/sim.2677}. PMID: 16927452. \\
\url{https://pubmed.ncbi.nlm.nih.gov/16927452/}

\vspace{0.5em}

5. Julious SA. Two-sided confidence intervals for the single proportion: comparison of seven methods by Robert G. Newcombe, \textit{Stat Med}. 2005 Nov 15;24(21):3383–3384. \\
doi: \texttt{10.1002/sim.2164}. PMID: 16206245. \\
\url{https://pubmed.ncbi.nlm.nih.gov/16206245/}

\vspace{0.5em}

6. Zhou XH, Obuchowski NA, McClish DK. (2011). \textit{Statistical Methods in Diagnostic Medicine} (2nd ed.). Wiley. \\
Print ISBN: 9780470183144. Online ISBN: 9780470906514. \\
\url{https://onlinelibrary.wiley.com/doi/book/10.1002/9780470906514}

\end{flushleft}


\end{document}
    </pre>
  </div>
</details>
