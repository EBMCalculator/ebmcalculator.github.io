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
  
  /* Box styling for collapsible sections */
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
    display: none; /* Collapsed by default */
    padding: 10px;
    border: 1px solid #ccc;
    border-top: none;
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
    <div class="faq-question" id="faq" onclick="toggleAnswer(this)"><span>&#9654;</span> Frequently Asked Questions</div>
    <div class="faq-answer">
      <!-- Individual FAQ items -->
      <div class="faq-item">
        <div class="faq-question" onclick="toggleAnswer(this)"><span>&#9654;</span> What devices are compatible?</div>
        <div class="faq-answer">EBM Calculator is available on iOS devices running iOS 18.1 or later. It is optimized for iPhones, but will also run on iPads and Apple Silicon Macs.</div>
      </div>
      <div class="faq-item">
        <div class="faq-question" onclick="toggleAnswer(this)"><span>&#9654;</span> How many results can I save?</div>
        <div class="faq-answer">You can save up to 50 results.<br>
          <br>
          From the Results tab, you can also reorder results (press and drag), delete individual results (swipe left), share results (swipe right), or delete all saved results (from the menu button).</div>
      </div>
      <div class="faq-item">
        <div class="faq-question" onclick="toggleAnswer(this)"><span>&#9654;</span> Why do the calculators have different input options?</div>
        <div class="faq-answer">
          Different input methods are available to fit various ways authors report their results. Choose the one that makes the most sense for the study you are appraising.<br>
          <br>
          For example, if you are assessing the performance of a Diagnostic Test and the authors report only the Predictive Values (and not sensitivity or specificity), choose PPV/NPV for your input fields.
        </div>
      </div>      
      <div class="faq-item">
        <div class="faq-question" onclick="toggleAnswer(this)"><span>&#9654;</span> What formulas are used for calculating confidence intervals?</div>
        <div class="faq-answer">
          <p><a href="/assets/pdf/Formulas.pdf" target="_blank" rel="noopener noreferrer">Click here to review the formulas</a> used for calculating all metrics and confidence intervals in the app.</p>
        </div>
      </div>        
      <div class="faq-item">
        <div class="faq-question" onclick="toggleAnswer(this)"><span>&#9654;</span> Why did you create this app?</div>
        <div class="faq-answer">I was frustrated by constantly having to switch between various websites to find online calculators for interpreting study results. I built the EBM Calculator app to streamline this process and to simplify evidence appraisal.<br>
          <br>
          My first version was coded in Python for use on my laptop. I decided to make it an official iOS app to share it easily with colleagues who were also evaluating the medical literature!<br>
        <br>
          It’s come a long way since I started, but it’s still a purposefully simple app: input data from a study to see the strength of association (for studies on a new therapy or exposure), the performance of a diagnostic test, or to calculate the post-test probability.
        </div>
      </div>
      <div class="faq-item">
        <div class="faq-question" onclick="toggleAnswer(this)"><span>&#9654;</span> Are you planning to add more features?</div>
        <div class="faq-answer">Yes! The more I learn, the more features I want to build into the app. But I also wanted to get it out there ASAP to start helping clinicians.<br>
          <br>
          If you have a suggestion of what would be helpful, please let me know at <a href="mailto:support@ebmcalculator.com">support@ebmcalculator.com</a>!</div>
      </div>
    </div>
  </div>

  <!-- How-To Guide Section Box -->
  <div class="faq-item">
    <div class="faq-question" id="how-to-guide" onclick="toggleAnswer(this)"><span>&#9654;</span> How-To Guide</div>
    <div class="faq-answer">
      <!-- Individual How-To items -->
<div class="faq-item">
  <div class="faq-question" onclick="toggleAnswer(this)"><span>&#9654;</span> Effect Calculator</div>
  <div class="faq-answer">
    <p>Choose to input data as event rates or as the numbers of participants in each arm of the study.</p>
    <!-- Screenshots 2a and 2b with centered "or" -->
    <p style="text-align: center;">
      <a href="assets/images/screenshots/Effect - Screenshot 2a.png" target="_blank" rel="noopener noreferrer">
        <img src="assets/images/screenshots/Effect - Screenshot 2a.png" alt="Effect - Screenshot 2a" style="max-width:50%; height:auto; display:block; margin:0 auto; box-shadow: none;">
      </a>
    </p>
    <p style="text-align: center;">or</p>
    <p style="text-align: center;">
      <a href="assets/images/screenshots/Effect - Screenshot 2b.png" target="_blank" rel="noopener noreferrer">
        <img src="assets/images/screenshots/Effect - Screenshot 2b.png" alt="Effect - Screenshot 2b" style="max-width:50%; height:auto; display:block; margin:0 auto; box-shadow: none;">
      </a>
    </p>
    <p>The way the study results are presented below<sup><a href="#ref1" style="text-decoration: none;">[1]</a></sup>, you could choose either. I chose to enter the event rates:</p>
    <p style="text-align: center;">
      <a href="assets/images/screenshots/Effect - Example Study.png" target="_blank" rel="noopener noreferrer">
        <img src="assets/images/screenshots/Effect - Example Study.png" alt="Effect - Example Study" style="max-width:90%; height:auto; display:block; margin:0 auto; box-shadow: none;">
      </a>
    </p>
    <!-- Screenshot 3 repeated with downward arrow -->
    <p style="text-align: center;">
      <a href="assets/images/screenshots/Effect - Screenshot 3.png" target="_blank" rel="noopener noreferrer">
        <img src="assets/images/screenshots/Effect - Screenshot 3.png" alt="Effect - Screenshot 3" style="max-width:50%; height:auto; display:block; margin:0 auto; box-shadow: none;">
      </a>
    </p>
    <p style="text-align: center;">&#x2193;</p>
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
  </div>
</div>
      <div class="faq-item">
        <div class="faq-question" onclick="toggleAnswer(this)"><span>&#9654;</span> Diagnostic Test Calculator</div>
        <div class="faq-answer">
          Placeholder text: a step-by-step guide for using the Diagnostic Test Calculator will be available soon.
        </div>
      </div>
      <div class="faq-item">
        <div class="faq-question" onclick="toggleAnswer(this)"><span>&#9654;</span> Post-Test Probability Calculator</div>
        <div class="faq-answer">
          Placeholder text: details on how to use the Post-Test Probability Calculator will be added here shortly.
        </div>
      </div>
      <div class="faq-item">
        <div class="faq-question" onclick="toggleAnswer(this)"><span>&#9654;</span> Viewing Results</div>
        <div class="faq-answer">
          Placeholder text: instructions for viewing, sharing, editing, and deleting results will appear here.
        </div>
      </div>
    </div>
  </div>

  <!-- Versions Section Box -->
  <div class="faq-item">
    <div class="faq-question" id="versions" onclick="toggleAnswer(this)"><span>&#9654;</span> Versions</div>
    <div class="faq-answer">
      <!-- Individual Version Items -->
      <div class="faq-item">
        <div class="faq-question" onclick="toggleAnswer(this)"><span>&#9654;</span> v1.3.0</div>
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
        </div>
      </div>
      <div class="faq-item">
        <div class="faq-question" onclick="toggleAnswer(this)"><span>&#9654;</span> v1.2.0</div>
        <div class="faq-answer">
          <ul>
            <li>Add feature to save, delete, and share results</li>
            <li>Add formula pages</li>
            <li>Update icons and logos</li>
            <li>Debug and refine UI</li>
          </ul>
        </div>
      </div>
      <div class="faq-item">
        <div class="faq-question" onclick="toggleAnswer(this)"><span>&#9654;</span> v1.1.0</div>
        <div class="faq-answer">
          <ul>
            <li>Add icons and logos</li>
            <li>Debug and refine UI</li>
          </ul>
        </div>
      </div>
      <div class="faq-item">
        <div class="faq-question" onclick="toggleAnswer(this)"><span>&#9654;</span> v1.0.0</div>
        <div class="faq-answer">
          <ul>
            <li>Effect Calculator</li>
            <li>Diagnostic Test Calculator</li>
            <li>Post-Test Probability Calculator</li>
          </ul>
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
