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
 
  .faq-block {
    display: block; /* Always visible */
    padding: 10px;
    border: 1px solid #ccc;
    border-top: none;
  } 
  .faq-answer {
    display: none; /* Collapsible */
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

<h2 style="text-align: center;">About</h2>

<div style="max-width: 600px; margin: 20px auto;">
  <!-- Disclaimer Box -->
  <div class="faq-item">
    <div class="faq-question">Disclaimer</div>
    <div class="faq-block">
      <p>This app was created for educational use. The content provided should not replace clinical judgement and results should be interpreted within the context of statistical and study limitations. Medical decisions should <strong>NOT</strong> be based solely on results from this app.</p>
    </div>
  </div>
</div>

<div style="max-width: 600px; margin: 20px auto; text-align: center;" markdown="1">
  I hope my app helps your ongoing learning and appraisal of medical literature!
  
  **Questions or Feedback?** <br>
  <a href="mailto:support@ebmcalculator.com" style="display: inline-flex; align-items: center; gap: 5px;">
    <span style="font-size: 30px; line-height: 1; vertical-align: top;">&#x2709;&#xFE0E;</span>
    <span style="line-height: 1; vertical-align: middle;">Send me an email</span>
  </a>  

  **Enjoying the app?** <br>
  <a href="https://buymeacoffee.com/davidstewart" target="_blank" rel="noopener noreferrer">
    <img src="/assets/images/EBMCalculator-any-bmc-logo 3x.png" alt="Buy Me a Coffee" style="height: 25px; object-fit: contain; margin-top: 5px">
  </a>
</div>

<br>
<div style="max-width: 600px; margin: 20px auto;">
  <!-- How-To Guide Section Box -->
  <div class="faq-item">
    <div class="faq-question" id="Formulas" onclick="toggleAnswer(this)"><span>&#9654;</span> Formulas</div>
    <div class="faq-answer">
      <p><a href="/assets/pdf/Formulas.pdf" target="_blank" rel="noopener noreferrer">Click here to review the formulas</a> used for calculating metrics and confidence intervals in the app.</p>
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
