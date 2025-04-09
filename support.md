<a id="top"></a>

<div style="text-align: center;">
  <img src="/assets/images/EBM Calculator Logo Any 3x.png" alt="EBM Calculator Logo" width="200">
  <h1>EBM Calculator</h1>
</div>

<style>
  a {
    color: #073472;
    text-decoration: none;
  }
  
  a:hover {
    text-decoration: none;
  }
  
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
  
  .section-links {
    text-align: center;
    margin-top: 20px;
  }
  .section-links a {
    margin-right: 15px;
    text-decoration: none;
  }
  
  .faq-item {
    margin-bottom: 20px;
  }
  .faq-question {
    font-weight: bold;
    cursor: pointer;
    padding: 10px;
    background: #f7f7f7;
    border: 1px solid #ccc;
  }
  .faq-answer {
    display: none;
    padding: 10px;
    border: 1px solid #ccc;
    border-top: none;
  }
  .back-to-top {
  display: inline-block;
  background-color: #e9e9e9;
  border: 1px solid #ccc;
  border-radius: 3px;
  padding: 4px 8px;
  color: #073472;
  text-decoration: none;
  font-size: 0.8em;
  transition: background-color 0.3s ease;
}
.back-to-top:hover {
  background-color: #dcdcdc;
}

</style>

<div class="tab-bar">
  <a href="/">Home</a>
  <a href="/about">About</a>
  <a href="/support">Support</a>
  <a href="/privacy-policy">Privacy</a>
</div>

<h2 style="text-align: center;">Support</h2>
<div class="section-links">
  <a href="#faq">FAQ</a>
  <a href="#how-to-guide">How-To</a>
  <a href="#versions">Versions</a>
</div>

<div style="max-width: 600px; margin: 20px auto;">
  <!-- FAQ Section Box -->
  <div class="faq-item">
    <div class="faq-question" id="faq" onclick="toggleAnswer(this)">
      <span>&#9654;</span> Frequently Asked Questions
    </div>
    <div class="faq-answer">
      <!-- Individual FAQ items -->
      <div class="faq-item">
        <div class="faq-question" onclick="toggleAnswer(this)">
          <span>&#9654;</span> What devices are compatible?
        </div>
        <div class="faq-answer">
          EBM Calculator is available on iOS devices running iOS 18.1 or later. It is optimized for iPhones, but will also run on iPads and Apple Silicon Macs.
                        <!-- Back toTop Link -->
        <p style="text-align: right; margin: 0.5em 0;">
          <a href="#top" class="back-to-top">⬆ Back to top</a>
        </p>
        </div>
      </div>
      <div class="faq-item">
        <div class="faq-question" onclick="toggleAnswer(this)">
          <span>&#9654;</span> How many results can I save?
        </div>
        <div class="faq-answer">
          You can save up to 50 results.<br><br>
          From the Results tab, you can also reorder results (press and drag), delete individual results (swipe left), share results (swipe right), or delete all saved results (from the menu button).
                        <!-- Back toTop Link -->
        <p style="text-align: right; margin: 0.5em 0;">
          <a href="#top" class="back-to-top">⬆ Back to top</a>
        </p>
        </div>
      </div>
      <div class="faq-item">
        <div class="faq-question" onclick="toggleAnswer(this)">
          <span>&#9654;</span> Why do the calculators have different input options?
        </div>
        <div class="faq-answer">
          Different input methods are available to fit various ways authors report their results. Choose the one that makes the most sense for the study you are appraising.<br><br>
          For example, if you are assessing the performance of a Diagnostic Test and the authors report only the Predictive Values (and not sensitivity or specificity), choose PPV/NPV for your input fields.
                        <!-- Back toTop Link -->
        <p style="text-align: right; margin: 0.5em 0;">
          <a href="#top" class="back-to-top">⬆ Back to top</a>
        </p>
        </div>
      </div>      
      <div class="faq-item">
        <div class="faq-question" onclick="toggleAnswer(this)">
          <span>&#9654;</span> What formulas are used for calculating confidence intervals?
        </div>
        <div class="faq-answer">
          <p>
            <a href="/assets/pdf/Formulas.pdf" target="_blank" rel="noopener noreferrer">Click here to review the formulas</a> used for calculating all metrics and confidence intervals in the app.
          </p>
                        <!-- Back toTop Link -->
        <p style="text-align: right; margin: 0.5em 0;">
          <a href="#top" class="back-to-top">⬆ Back to top</a>
        </p>
        </div>
      </div>        
      <div class="faq-item">
        <div class="faq-question" onclick="toggleAnswer(this)">
          <span>&#9654;</span> Why did you create this app?
        </div>
        <div class="faq-answer">
          I was tired of looking for various online calculators to interpreting study results. I built the EBM Calculator app to streamline this process and to simplify evidence appraisal.<br><br>
          My first version was coded in Python for use on my laptop. I decided to make it an official iOS app to share it easily with colleagues who were also evaluating the medical literature!<br><br>
          It’s come a long way since I started, but it’s still a purposefully simple app: input data from a study to see the strength of association (for studies on a new therapy or exposure), the performance of a diagnostic test, or to calculate the post-test probability.
                        <!-- Back toTop Link -->
        <p style="text-align: right; margin: 0.5em 0;">
          <a href="#top" class="back-to-top">⬆ Back to top</a>
        </p>
        </div>
      </div>
      <div class="faq-item">
        <div class="faq-question" onclick="toggleAnswer(this)">
          <span>&#9654;</span> Are you planning to add more features?
        </div>
        <div class="faq-answer">
          Yes! The more I learn, the more features I want to build into the app. But I also wanted to get it out there ASAP to start helping clinicians.<br><br>
          If you have a suggestion of what would be helpful, please let me know at <a href="mailto:support@ebmcalculator.com">support@ebmcalculator.com</a>!
                        <!-- Back toTop Link -->
        <p style="text-align: right; margin: 0.5em 0;">
          <a href="#top" class="back-to-top">⬆ Back to top</a>
        </p>
        </div>
      </div>
    </div>
  </div>

<!-- How-To Guide Section Box -->
<div class="faq-item">
  <div class="faq-question" id="how-to-guide" onclick="toggleAnswer(this)">
    <span>&#9654;</span> How-To Guide
  </div>
  <div class="faq-answer">
    <!-- Effect Calculator How-To-Guide -->
    <div class="faq-item">
      <div class="faq-question" onclick="toggleAnswer(this)">
        <span>&#9654;</span> Effect Calculator
      </div>
      <div class="faq-answer">
        <p>
          First, select how you would like to input the study data. You can choose either "Event Rates" or "Counts" (the number of participants in each arm of the study).
        </p>
        <p style="text-align: center;">
          Event Rates:
          <a href="assets/images/screenshots/Effect - Screenshot 2a.png" target="_blank" rel="noopener noreferrer">
            <img src="assets/images/screenshots/Effect - Screenshot 2a.png" alt="Effect - Screenshot 2a" style="max-width:50%; height:auto; display:block; margin:0 auto; box-shadow: none;">
          </a>
        </p>
        <p style="text-align: center;">
          or Counts:
          <a href="assets/images/screenshots/Effect - Screenshot 2b.png" target="_blank" rel="noopener noreferrer">
            <img src="assets/images/screenshots/Effect - Screenshot 2b.png" alt="Effect - Screenshot 2b" style="max-width:50%; height:auto; display:block; margin:0 auto; box-shadow: none;">
          </a>
        </p>
        <p>
          Based on how the authors of this study<sup><a href="#ref1" style="text-decoration: none;">[1]</a></sup> presented their results in the table below, you could choose either input method.
        </p>
        <p style="text-align: center;">
          <a href="assets/images/screenshots/Effect - Example Study.png" target="_blank" rel="noopener noreferrer">
            <img src="assets/images/screenshots/Effect - Example Study.png" alt="Effect - Example Study" style="max-width:90%; height:auto; display:block; margin:0 auto; box-shadow: none;">
          </a>
        </p>
        <br>
        <p style="text-align: center;">
          Here, I chose to enter the event rates (EER 90.0%, CER 63.3%):
          <a href="assets/images/screenshots/Effect - Screenshot 3.png" target="_blank" rel="noopener noreferrer">
            <img src="assets/images/screenshots/Effect - Screenshot 3.png" alt="Effect - Screenshot 3" style="max-width:50%; height:auto; display:block; margin:0 auto; box-shadow: none;">
          </a>
        </p>
        <p>
          Press the "Calculate" button to see the relevant effect estimates and their confidence intervals.
        </p>
        <br>
        <p>
          The table above provides the odds ratio (OR), but absolute risk measures offer a clearer understanding of the treatment effect’s magnitude. In this example, EBM Calculator displays the absolute risk increase (ARI) and number needed to treat (NNT) to cause one additional outcome, along with relative risk metrics and their confidence intervals.
        </p>
        <p style="text-align: center;">
          <a href="assets/images/screenshots/Effect - Screenshot 4.png" target="_blank" rel="noopener noreferrer">
            <img src="assets/images/screenshots/Effect - Screenshot 4.png" alt="Effect - Screenshot 4" style="max-width:50%; height:auto; display:block; margin:0 auto; box-shadow: none;">
          </a>
        </p>
        <!-- Reference in smaller text -->
        <p id="ref1" style="font-size:0.8em; text-align:left; margin-top:20px;">
          <a href="https://pubmed.ncbi.nlm.nih.gov/29913001/" target="_blank" rel="noopener noreferrer">
            <sup>[1]</sup>Basu B, Sander A, Roy B, Preussler S, Barua S, Mahapatra TKS, Schaefer F. Efficacy of Rituximab vs Tacrolimus in Pediatric Corticosteroid-Dependent Nephrotic Syndrome: A Randomized Clinical Trial. JAMA Pediatr. 2018 Aug 1;172(8):757-764. doi: 10.1001/jamapediatrics.2018.1323. Erratum in: JAMA Pediatr. 2018 Dec 1;172(12):1205. doi: 10.1001/jamapediatrics.2018.3632. PMID: 29913001; PMCID: PMC6142920.
          </a>
        </p>
                      <!-- Back toTop Link -->
        <p style="text-align: right; margin: 0.5em 0;">
          <a href="#top" class="back-to-top">⬆ Back to top</a>
        </p>
      </div>
    </div>
    <!-- Diagnostic Test Calculator How-To-Guide -->
    <div class="faq-item">
      <div class="faq-question" onclick="toggleAnswer(this)">
        <span>&#9654;</span> Diagnostic Test Calculator
      </div>
      <div class="faq-answer">
        <p>
          First, select how you would like to input the study data. You can choose from "Sens/Spec" (sensitivity and specificity), "PPV/NPV" (positive and negative predictive values), or "Counts" (the number of participants in each arm of the study).
        </p>
        <p style="text-align: center;">
          Sens/Spec:
          <a href="assets/images/screenshots/Diagnostic Test - Screenshot 2a.png" target="_blank" rel="noopener noreferrer">
            <img src="assets/images/screenshots/Diagnostic Test - Screenshot 2a.png" alt="Diagnostic Test - Screenshot 2a" style="max-width:50%; height:auto; display:block; margin:0 auto; box-shadow: none;">
          </a>
        </p>
        <p style="text-align: center;">
          PPV/NPV:
          <a href="assets/images/screenshots/Diagnostic Test - Screenshot 2b.png" target="_blank" rel="noopener noreferrer">
            <img src="assets/images/screenshots/Diagnostic Test - Screenshot 2b.png" alt="Diagnostic Test - Screenshot 2b" style="max-width:50%; height:auto; display:block; margin:0 auto; box-shadow: none;">
          </a>
        </p>
        <p style="text-align: center;">
          or Counts:
          <a href="assets/images/screenshots/Diagnostic Test - Screenshot 2c.png" target="_blank" rel="noopener noreferrer">
            <img src="assets/images/screenshots/Diagnostic Test - Screenshot 2c.png" alt="Diagnostic Test - Screenshot 2c" style="max-width:50%; height:auto; display:block; margin:0 auto; box-shadow: none;">
          </a>
        </p>
        <p>
          Based on how the authors of this study<sup><a href="#ref2" style="text-decoration: none;">[2]</a></sup> presented their results in the table below, it would be easiest to use the "Sens/Spec" input method.
        </p>
        <p style="text-align: center;">
          (click to enlarge)
          <a href="assets/images/screenshots/Diagnostic Test - Example Study.png" target="_blank" rel="noopener noreferrer">
            <img src="assets/images/screenshots/Diagnostic Test - Example Study.png" alt="Diagnostic Test - Example Study" style="max-width:90%; height:auto; display:block; margin:0 auto; box-shadow: none;">
          </a>
        </p>
        <br>
        <p>
          Enter the sensitivity (94.1%), specificity (79.2%), prevalence (20.6%), and total sample size (248).
        </p>
        <p style="text-align: center;">
          <a href="assets/images/screenshots/Diagnostic Test - Screenshot 3.png" target="_blank" rel="noopener noreferrer">
            <img src="assets/images/screenshots/Diagnostic Test - Screenshot 3.png" alt="Diagnostic Test - Screenshot 3" style="max-width:50%; height:auto; display:block; margin:0 auto; box-shadow: none;">
          </a>
        </p>
        <p>
          Press the "Calculate" button to see the relevant diagnostic test metrics and their confidence intervals.<br><br>
          The table above provides sensitivity and specificity. Some authors also report positive and negative predictive values (PPV and NPV). However, because predictive values depend on disease prevalence, they may not apply to your patients if the study population's prevalence differs from your own.<br><br>
          For this reason, we prefer using positive and negative likelihood ratios (LRs) to better understand post-test probability. In this example, EBM Calculator displays LR(+) and LR(–) with confidence intervals, along with an option to calculate post-test probability using a different prevalence.
        </p>
        <p style="text-align: center;">
          <a href="assets/images/screenshots/Diagnostic Test - Screenshot 4.png" target="_blank" rel="noopener noreferrer">
            <img src="assets/images/screenshots/Diagnostic Test - Screenshot 4.png" alt="Diagnostic Test - Screenshot 4" style="max-width:50%; height:auto; display:block; margin:0 auto; box-shadow: none;">
          </a>
        </p>
        <!-- Reference in smaller text -->
        <p id="ref2" style="font-size:0.8em; text-align:left; margin-top:20px;">
          <a href="https://pubmed.ncbi.nlm.nih.gov/24145848/" target="_blank" rel="noopener noreferrer">
            <sup>[2]</sup>Traube C, Silver G, Kearney J, Patel A, Atkinson TM, Yoon MJ, Halpert S, Augenstein J, Sickles LE, Li C, Greenwald B. Cornell Assessment of Pediatric Delirium: a valid, rapid, observational tool for screening delirium in the PICU*. Crit Care Med. 2014 Mar;42(3):656-63. doi: 10.1097/CCM.0b013e3182a66b76. PMID: 24145848; PMCID: PMC5527829.
          </a>
        </p>
                      <!-- Back toTop Link -->
        <p style="text-align: right; margin: 0.5em 0;">
          <a href="#top" class="back-to-top">⬆ Back to top</a>
        </p>
      </div>
    </div>
    <!-- Post-Test Probability Calculator How-To-Guide -->
    <div class="faq-item">
      <div class="faq-question" onclick="toggleAnswer(this)">
        <span>&#9654;</span> Post-Test Probability Calculator
      </div>
      <div class="faq-answer">
        <p>
          First, select how you would like to input the study data. You can choose from either "Sensitivity & Specificity" or "Likelihood Ratios".
        </p>
        <p style="text-align: center;">
          Sensitivity &amp; Specificity:
          <a href="assets/images/screenshots/PostTest Prob - Screenshot 2a.png" target="_blank" rel="noopener noreferrer">
            <img src="assets/images/screenshots/PostTest Prob - Screenshot 2a.png" alt="PostTest Prob - Screenshot 2a" style="max-width:50%; height:auto; display:block; margin:0 auto; box-shadow: none;">
          </a>
        </p>
        <p style="text-align: center;">
          or Likelihood Ratios:
          <a href="assets/images/screenshots/PostTest Prob - Screenshot 2b.png" target="_blank" rel="noopener noreferrer">
            <img src="assets/images/screenshots/PostTest Prob - Screenshot 2b.png" alt="PostTest Prob - Screenshot 2b" style="max-width:50%; height:auto; display:block; margin:0 auto; box-shadow: none;">
          </a>
        </p>
        <p>
          Based on how the authors of this study<sup><a href="#ref3" style="text-decoration: none;">[2]</a></sup> presented their results in the table below, it would be easiest to use the "Sensitivity &amp; Specificity" input method.
        </p>
        <p style="text-align: center;">
          (click to enlarge)
          <a href="assets/images/screenshots/PostTest Prob - Example Study.png" target="_blank" rel="noopener noreferrer">
            <img src="assets/images/screenshots/PostTest Prob - Example Study.png" alt="PostTest Prob - Example Study" style="max-width:90%; height:auto; display:block; margin:0 auto; box-shadow: none;">
          </a>
        </p>
        <br>
        <p>
          Enter the sensitivity (94.1%) and specificity (79.2%) of the diagnostic test. Next, choose your pre-test probability (often the prevalence of disease or condition in your patient population).
        </p>
        <br>
        <p style="text-align: center;">
          In this example, I chose a pre-test probability of 35%:
          <a href="assets/images/screenshots/PostTest Prob - Screenshot 3.png" target="_blank" rel="noopener noreferrer">
            <img src="assets/images/screenshots/PostTest Prob - Screenshot 3.png" alt="PostTest Prob - Screenshot 3" style="max-width:50%; height:auto; display:block; margin:0 auto; box-shadow: none;">
          </a>
        </p>
        <p>
          Press the "Calculate" button to see the post-test probabilities for a positive or negative test result.
        </p>
        <p style="text-align: center;">
          <a href="assets/images/screenshots/PostTest Prob - Screenshot 4.png" target="_blank" rel="noopener noreferrer">
            <img src="assets/images/screenshots/PostTest Prob - Screenshot 4.png" alt="PostTest Prob - Screenshot 4" style="max-width:50%; height:auto; display:block; margin:0 auto; box-shadow: none;">
          </a>
        </p>
        <!-- Interactive Fagan Nomogram Screenshots -->
        <p>
          You can also access an Interactive Fagan Nomogram through the menu button at the top right.
        </p>
        <p style="text-align: center;">
          <a href="assets/images/screenshots/PostTest Prob - Screenshot 5.png" target="_blank" rel="noopener noreferrer">
            <img src="assets/images/screenshots/PostTest Prob - Screenshot 5.png" alt="PostTest Prob - Screenshot 5" style="max-width:50%; height:auto; display:block; margin:0 auto; box-shadow: none;">
          </a>
        </p>
        <p>
          Use the sliders to explore how changes in Pre-Test Probability and Likelihood Ratio influence the Post-Test Probability.
        </p>
        <p style="text-align: center;">
          <a href="assets/images/screenshots/PostTest Prob - Screenshot 6.png" target="_blank" rel="noopener noreferrer">
            <img src="assets/images/screenshots/PostTest Prob - Screenshot 6.png" alt="PostTest Prob - Screenshot 6" style="max-width:50%; height:auto; display:block; margin:0 auto; box-shadow: none;">
          </a>
        </p>
        <!-- Reference in smaller text -->
        <p id="ref3" style="font-size:0.8em; text-align:left; margin-top:20px;">
          <a href="https://pubmed.ncbi.nlm.nih.gov/24145848/" target="_blank" rel="noopener noreferrer">
            <sup>[2]</sup>Traube C, Silver G, Kearney J, Patel A, Atkinson TM, Yoon MJ, Halpert S, Augenstein J, Sickles LE, Li C, Greenwald B. Cornell Assessment of Pediatric Delirium: a valid, rapid, observational tool for screening delirium in the PICU*. Crit Care Med. 2014 Mar;42(3):656-63. doi: 10.1097/CCM.0b013e3182a66b76. PMID: 24145848; PMCID: PMC5527829.
          </a>
        </p>
              <!-- Back toTop Link -->
        <p style="text-align: right; margin: 0.5em 0;">
          <a href="#top" class="back-to-top">⬆ Back to top</a>
        </p>
      </div>
    </div>
    <!-- Viewing Results How-To-Guide -->
    <div class="faq-item">
      <div class="faq-question" onclick="toggleAnswer(this)">
        <span>&#9654;</span> Viewing Results
      </div>
      <div class="faq-answer">
        <p>
          Click on the Results tab to view up to 50 of your saved results. Here you can drag to rearrange, or click on a result to view it individually.
        </p>
        <p style="text-align: center;">
          <a href="assets/images/screenshots/Results - Screenshot 3.png" target="_blank" rel="noopener noreferrer">
            <img src="assets/images/screenshots/Results - Screenshot 3.png" alt="Results - Screenshot 3" style="max-width:50%; height:auto; display:block; margin:0 auto; box-shadow: none;">
          </a>
        </p>
        <p>Swipe right on a result to share, print, or export.</p>
        <p style="text-align: center;">
          <a href="assets/images/screenshots/Results - Screenshot 5.png" target="_blank" rel="noopener noreferrer">
            <img src="assets/images/screenshots/Results - Screenshot 5.png" alt="Results - Screenshot 5" style="max-width:50%; height:auto; display:block; margin:0 auto; box-shadow: none;">
          </a>
        </p>
        <p>Swipe left to edit the original inputs or delete the result.</p>
        <br>
        <p style="text-align: center;">
          <a href="assets/images/screenshots/Results - Screenshot 6.png" target="_blank" rel="noopener noreferrer">
            <img src="assets/images/screenshots/Results - Screenshot 6.png" alt="Results - Screenshot 6" style="max-width:50%; height:auto; display:block; margin:0 auto; box-shadow: none;">
          </a>
        </p>
        <p>Press the menu button to see an option to Delete All results.</p>
        <p style="text-align: center;">
          <a href="assets/images/screenshots/Results - Screenshot 7.png" target="_blank" rel="noopener noreferrer">
            <img src="assets/images/screenshots/Results - Screenshot 7.png" alt="Results - Screenshot 7" style="max-width:50%; height:auto; display:block; margin:0 auto; box-shadow: none;">
          </a>
        </p>
                      <!-- Back toTop Link -->
        <p style="text-align: right; margin: 0.5em 0;">
          <a href="#top" class="back-to-top">⬆ Back to top</a>
        </p>
      </div>
    </div>
  </div>
</div>

  <!-- Versions Section Box -->
  <div class="faq-item">
    <div class="faq-question" id="versions" onclick="toggleAnswer(this)">
      <span>&#9654;</span> Versions
    </div>
    <div class="faq-answer">
      <!-- Individual Version Items -->
      <div class="faq-item">
        <div class="faq-question" onclick="toggleAnswer(this)">
          <span>&#9654;</span> v1.3.0
        </div>
        <div class="faq-answer">
          <ul>
            <li>All new UI with navigation bar and cleaner appearance</li>
            <li>Swipe on results to Share, Edit, Save, or Delete</li>
            <li>Drag and drop results to rearrange in Results section</li>
            <li>Calculate Post-Test Probability from any diagnostic test result</li>
            <li>New Library section with various Lessons in EBM</li>
            <li>Add Interactive Fagan Nomogram</li>
            <li>Debug and refine UI</li>
          </ul>
                        <!-- Back toTop Link -->
        <p style="text-align: right; margin: 0.5em 0;">
          <a href="#top" class="back-to-top">⬆ Back to top</a>
        </p>
        </div>
      </div>
      <div class="faq-item">
        <div class="faq-question" onclick="toggleAnswer(this)">
          <span>&#9654;</span> v1.2.0
        </div>
        <div class="faq-answer">
          <ul>
            <li>Add feature to save, delete, and share results</li>
            <li>Add formula pages</li>
            <li>Update icons and logos</li>
            <li>Debug and refine UI</li>
          </ul>
                        <!-- Back toTop Link -->
        <p style="text-align: right; margin: 0.5em 0;">
          <a href="#top" class="back-to-top">⬆ Back to top</a>
        </p>
        </div>
      </div>
      <div class="faq-item">
        <div class="faq-question" onclick="toggleAnswer(this)">
          <span>&#9654;</span> v1.1.0
        </div>
        <div class="faq-answer">
          <ul>
            <li>Add icons and logos</li>
            <li>Debug and refine UI</li>
          </ul>
                        <!-- Back toTop Link -->
        <p style="text-align: right; margin: 0.5em 0;">
          <a href="#top" class="back-to-top">⬆ Back to top</a>
        </p>
        </div>
      </div>
      <div class="faq-item">
        <div class="faq-question" onclick="toggleAnswer(this)">
          <span>&#9654;</span> v1.0.0
        </div>
        <div class="faq-answer">
          <ul>
            <li>Effect Calculator</li>
            <li>Diagnostic Test Calculator</li>
            <li>Post-Test Probability Calculator</li>
          </ul>
                        <!-- Back toTop Link -->
        <p style="text-align: right; margin: 0.5em 0;">
          <a href="#top" class="back-to-top">⬆ Back to top</a>
        </p>
        </div>
      </div>
    </div>
  </div>
</div>

<div style="text-align: center; margin-top: 40px;">
  &copy; 2024 David A. Stewart, MD
</div>

<script>
function toggleAnswer(element) {
  var answer = element.nextElementSibling;
  if (answer.style.display === "block") {
    answer.style.display = "none";
    element.querySelector("span").innerHTML = "&#9654;";
  } else {
    answer.style.display = "block";
    element.querySelector("span").innerHTML = "&#9660;";
  }
}
</script>
