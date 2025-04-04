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

<!-- Include MathJax if not already present -->
<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
</script>

<!-- Collapsible Formulas Box -->
<details>
  <summary>Formulas</summary>
  <div style="max-width: 800px; margin: auto; text-align: left;">

    <!-- Formulas for Effect Estimates -->
    <p style="text-align: center; font-size: 1.5em;"><strong>Formulas for Effect Estimates</strong></p>
    
    <!-- 2x2 Table -->
    <p style="text-align: center;">
      $$\renewcommand{\arraystretch}{2.0}
      \begin{array}{c c c c}
       & \text{Outcome} & \shortstack{No\\Outcome} & \text{Total} \\
      \cline{2-3}
      (+) & \multicolumn{1}{|c|}{a} & \multicolumn{1}{c|}{b} & a+b \\
      \cline{2-3}
      (-) & \multicolumn{1}{|c|}{c} & \multicolumn{1}{c|}{d} & c+d \\
      \cline{2-3}
      \text{Total} & a+c & b+d & a+b+c+d \\
      \end{array}$$
    </p>
    <p style="text-align: center;">$$ \text{z = 1.959964 for 95\% CI} $$</p>
    
    <!-- Effect Estimates -->
    <h3>Effect Estimates</h3>
    
    <p><strong>Experimental Event Rate:</strong></p>
    <p>$$ \text{EER} = \frac{a}{a+b} $$</p>
    
    <p><strong>Control Event Rate:</strong></p>
    <p>$$ \text{CER} = \frac{c}{c+d} $$</p>
    
    <p><strong>Absolute Risk Reduction:</strong></p>
    <p>$$ \text{ARR} = \text{CER} - \text{EER} $$</p>
    
    <p><strong>Confidence Interval (Wilson score bounds with error propagation):</strong></p>
    <p>$$ \text{Lower Bound: } \text{ARR} - z\sqrt{\frac{u_2(1-u_2)}{r_1}+\frac{w_1(1-w_1)}{r_2}} $$</p>
    <p>$$ \text{Upper Bound: } \text{ARR} + z\sqrt{\frac{u_1(1-u_1)}{r_2}+\frac{w_2(1-w_2)}{r_1}} $$</p>
    
    <p>where</p>
    <p>$$ r_1 = a+b,\quad r_2 = c+d $$</p>
    <p>$$ u_1 = \frac{2c+z^2+z\sqrt{\frac{4(c\cdot d)}{r_2}+z^2}}{2r_2+2z^2},\quad
       u_2 = \frac{2a+z^2+z\sqrt{\frac{4(a\cdot b)}{r_1}+z^2}}{2r_1+2z^2} $$</p>
    <p>$$ w_1 = \frac{2c+z^2-z\sqrt{\frac{4(c\cdot d)}{r_2}+z^2}}{2r_2+2z^2},\quad
       w_2 = \frac{2a+z^2-z\sqrt{\frac{4(a\cdot b)}{r_1}+z^2}}{2r_1+2z^2} $$</p>
    
    <p><strong>Risk Ratio:</strong></p>
    <p>$$ \text{RR} = \frac{\text{EER}}{\text{CER}} $$</p>
    <p><strong>Confidence Interval (Log-normal, Zhou):</strong></p>
    <p>$$ \text{Lower Bound: } \exp\Biggl(\ln(\text{RR}) - z\sqrt{\Bigl(\frac{1}{a}-\frac{1}{a+b}\Bigr)+\Bigl(\frac{1}{c}-\frac{1}{c+d}\Bigr)}\Biggr) $$</p>
    <p>$$ \text{Upper Bound: } \exp\Biggl(\ln(\text{RR}) + z\sqrt{\Bigl(\frac{1}{a}-\frac{1}{a+b}\Bigr)+\Bigl(\frac{1}{c}-\frac{1}{c+d}\Bigr)}\Biggr) $$</p>
    
    <p><strong>Relative Risk Reduction:</strong></p>
    <p>$$ \text{RRR} = 1-\text{RR} $$</p>
    <p><strong>Confidence Interval (Derived from Log-normal RR):</strong></p>
    <p>$$ \text{Lower Bound: } 1-\exp\Biggl(\ln(\text{RR}) + z\sqrt{\Bigl(\frac{1}{a}-\frac{1}{a+b}\Bigr)+\Bigl(\frac{1}{c}-\frac{1}{c+d}\Bigr)}\Biggr) $$</p>
    <p>$$ \text{Upper Bound: } 1-\exp\Biggl(\ln(\text{RR}) - z\sqrt{\Bigl(\frac{1}{a}-\frac{1}{a+b}\Bigr)+\Bigl(\frac{1}{c}-\frac{1}{c+d}\Bigr)}\Biggr) $$</p>
    
    <p><strong>Odds Ratio:</strong></p>
    <p>$$ \text{OR} = \frac{ad}{cb} $$</p>
    <p><strong>Confidence Interval (Log-normal):</strong></p>
    <p>$$ \text{Lower Bound: } \exp\Biggl(\ln(\text{OR}) - z\sqrt{\frac{1}{a}+\frac{1}{b}+\frac{1}{c}+\frac{1}{d}}\Biggr) $$</p>
    <p>$$ \text{Upper Bound: } \exp\Biggl(\ln(\text{OR}) + z\sqrt{\frac{1}{a}+\frac{1}{b}+\frac{1}{c}+\frac{1}{d}}\Biggr) $$</p>
    
    <h3>References</h3>
    <p style="font-size: 0.9em;">
      1. Altman DG. Confidence intervals for the number needed to treat. <em>BMJ</em> 1998;317:1309–1312. <br>
      doi: 10.1136/bmj.317.7168.1309. <br>
      <a href="https://pubmed.ncbi.nlm.nih.gov/9804726/">https://pubmed.ncbi.nlm.nih.gov/9804726/</a>
    </p>
    <!-- (Add the remaining references in a similar manner) -->
    
    <hr>
    
    <!-- Formulas for Diagnostic Tests -->
    <p style="text-align: center; font-size: 1.5em;"><strong>Formulas for Diagnostic Tests</strong></p>
    
    <!-- 2x2 Table -->
    <p style="text-align: center;">
      $$\renewcommand{\arraystretch}{2.0}
      \begin{array}{c c c c}
       & \text{Outcome} & \shortstack{No\\Disease} & \text{Total} \\
      \cline{2-3}
      (+) & \multicolumn{1}{|c|}{a} & \multicolumn{1}{c|}{b} & a+b \\
      \cline{2-3}
      (-) & \multicolumn{1}{|c|}{c} & \multicolumn{1}{c|}{d} & c+d \\
      \cline{2-3}
      \text{Total} & a+c & b+d & a+b+c+d \\
      \end{array}$$
    </p>
    <p style="text-align: center;">$$ \text{z = 1.959964 for 95\% CI} $$</p>
    
    <h3>Diagnostic Test Metrics</h3>
    
    <p><strong>Sensitivity:</strong></p>
    <p>$$ \text{Sensitivity} = \frac{a}{a+c} $$</p>
    <p><strong>Confidence Interval (Wilson Score):</strong></p>
    <p>$$ \text{Lower Bound: } \frac{(2a)+z^2-z\sqrt{\frac{4ac}{a+c}+z^2}}{2(a+c)+2z^2} $$</p>
    <p>$$ \text{Upper Bound: } \frac{(2a)+z^2+z\sqrt{\frac{4ac}{a+c}+z^2}}{2(a+c)+2z^2} $$</p>
    
    <p><strong>Specificity:</strong></p>
    <p>$$ \text{Specificity} = \frac{d}{b+d} $$</p>
    <p><strong>Confidence Interval (Wilson Score):</strong></p>
    <p>$$ \text{Lower Bound: } \frac{(2d)+z^2-z\sqrt{\frac{4db}{b+d}+z^2}}{2(b+d)+2z^2} $$</p>
    <p>$$ \text{Upper Bound: } \frac{(2d)+z^2+z\sqrt{\frac{4db}{b+d}+z^2}}{2(b+d)+2z^2} $$</p>
    
    <p><strong>Positive Likelihood Ratio:</strong></p>
    <p>$$ \text{LR(+)} = \frac{\text{Sensitivity}}{1-\text{Specificity}} = \frac{a/(a+c)}{b/(b+d)} $$</p>
    <p><strong>Confidence Interval (Log-normal, Zhou):</strong></p>
    <p>$$ \text{Lower Bound: } \exp\Biggl(\ln\Bigl(\frac{(b+d)a}{(a+c)b}\Bigr)-z\sqrt{\frac{c}{a(a+c)}+\frac{d}{b(b+d)}}\Biggr) $$</p>
    <p>$$ \text{Upper Bound: } \exp\Biggl(\ln\Bigl(\frac{(b+d)a}{(a+c)b}\Bigr)+z\sqrt{\frac{c}{a(a+c)}+\frac{d}{b(b+d)}}\Biggr) $$</p>
    
    <p><strong>Negative Likelihood Ratio:</strong></p>
    <p>$$ \text{LR(–)} = \frac{1-\text{Sensitivity}}{\text{Specificity}} = \frac{c/(a+c)}{d/(b+d)} $$</p>
    <p><strong>Confidence Interval (Log-normal, Zhou):</strong></p>
    <p>$$ \text{Lower Bound: } \exp\Biggl(\ln\Bigl(\frac{(b+d)c}{(a+c)d}\Bigr)-z\sqrt{\frac{a}{c(a+c)}+\frac{b}{d(b+d)}}\Biggr) $$</p>
    <p>$$ \text{Upper Bound: } \exp\Biggl(\ln\Bigl(\frac{(b+d)c}{(a+c)d}\Bigr)+z\sqrt{\frac{a}{c(a+c)}+\frac{b}{d(b+d)}}\Biggr) $$</p>
    
    <p><strong>Positive Predictive Value:</strong></p>
    <p>$$ \text{PPV} = \frac{a}{a+b} $$</p>
    <p><strong>Confidence Interval (Wilson Score):</strong></p>
    <p>$$ \text{Lower Bound: } \frac{(2a)+z^2-z\sqrt{\frac{4ab}{a+b}+z^2}}{2(a+b)+2z^2} $$</p>
    <p>$$ \text{Upper Bound: } \frac{(2a)+z^2+z\sqrt{\frac{4ab}{a+b}+z^2}}{2(a+b)+2z^2} $$</p>
    
    <p><strong>Negative Predictive Value:</strong></p>
    <p>$$ \text{NPV} = \frac{d}{c+d} $$</p>
    <p><strong>Confidence Interval (Wilson Score):</strong></p>
    <p>$$ \text{Lower Bound: } \frac{(2d)+z^2-z\sqrt{\frac{4dc}{c+d}+z^2}}{2(c+d)+2z^2} $$</p>
    <p>$$ \text{Upper Bound: } \frac{(2d)+z^2+z\sqrt{\frac{4dc}{c+d}+z^2}}{2(c+d)+2z^2} $$</p>
    
    <h3>References</h3>
    <p style="font-size: 0.9em;">
      1. Altman DG. Confidence intervals for the number needed to treat. <em>BMJ</em> 1998;317:1309–1312. <br>
      doi: 10.1136/bmj.317.7168.1309. <br>
      <a href="https://pubmed.ncbi.nlm.nih.gov/9804726/">https://pubmed.ncbi.nlm.nih.gov/9804726/</a>
    </p>
    <!-- (Add remaining references as needed) -->
    
  </div>
</details>
