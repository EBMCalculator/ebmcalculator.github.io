---
layout: default
title: About
---

<h2 style="text-align: center;">About</h2>

<!-- 
  The following style makes the disclaimer section always open:
  - Ensures that .faq-answer elements are always displayed.
  - Changes the pointer style on .faq-question so they're not clickable.
-->
<style>
  .static-about .faq-answer { 
    display: block !important; 
  }
  .static-about .faq-question { 
    cursor: default; 
  }
</style>

<div class="static-about" style="max-width: 600px; margin: 20px auto;">
  <!-- Disclaimer -->
  <div class="faq-item">
    <div class="faq-question">
      Disclaimer
    </div>
    <div class="faq-answer">
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
    <picture>
      <source srcset="/assets/images/EBMCalculator-dark-bmc-logo-3x.png" media="(prefers-color-scheme: dark)">
      <img src="/assets/images/EBMCalculator-any-bmc-logo 3x.png" alt="Buy Me a Coffee" style="height: 25px; object-fit: contain; margin-top: 5px">
    </picture>
  </a>
</div>

<br>

<!-- Versions Section -->
<div style="max-width: 600px; margin: 20px auto;">
  <!-- Outer Versions container: always expanded -->
  <div class="faq-item">
    <div class="faq-question" id="versions" style="cursor: default;">
      Versions
    </div>
    <!-- Force the outer faq-answer to always display -->
    <div class="faq-answer" style="display: block;">
      <!-- Most recent version: v1.4.0 (expanded by default) -->
      <div class="faq-item">
        <div class="faq-question" onclick="toggleAnswer(this)">
          <span>&#9660;</span> v1.4.0
        </div>
        <div class="faq-answer" style="display: block;">
          <ul>
            <li>Citations now supported in all calculators!</li>
            <li>Enter a PMID to automatically fetch the full citation or manually enter your own citation</li>
            <li>Tap to view, copy, or open the citation in PubMed</li>
            <li>Citations are searchable within saved results</li>
            <li>You can now save up to 100 results</li>
            <li>Case-Control inputs and results redesigned for better clarity and ease of use</li>
            <li>Results are now better formatted when printed, emailed, or shared via messages</li>
            <li>Bug fixes and UI polish</li>
          </ul>
        </div>
      </div>      
      <!-- Version: v1.3.0  -->
      <div class="faq-item">
        <div class="faq-question" onclick="toggleAnswer(this)">
          <span>&#9654;</span> v1.3.0
        </div>
        <div class="faq-answer">
          <ul>
            <li>All new UI with navigation bar and cleaner appearance</li>
            <li>Swipe on results to Share, Edit, Save, or Delete</li>
            <li>Save up to 50 results</li>
            <li>Drag and drop results to rearrange in Results section</li>
            <li>Search through saved results using keywords, test names, interventions, or outcomes</li>
            <li>Calculate Post-Test Probability from any diagnostic test result</li>
            <li>See results in a new interactive Fagan Nomogram</li>
            <li>New Library section with various Lessons in EBM</li>
            <li>Links to Support email, How-To Guide, and FAQ added to About screen</li>
            <li>Added statistical method and references for each CI on Formula pages</li>
            <li>Bug fixes and UI refinements</li>
          </ul>
        </div>
      </div>
      <!-- Version: v1.2.0 -->
      <div class="faq-item">
        <div class="faq-question" onclick="toggleAnswer(this)">
          <span>&#9654;</span> v1.2.0
        </div>
        <div class="faq-answer">
          <ul>
            <li>New feature to save, delete, and share results</li>
            <li>New formula pages</li>
            <li>Updates for icons and logos</li>
            <li>Works in light and dark mode</li>
            <li>Bug fixes and UI refinements</li>
          </ul>
        </div>
      </div>
      <!-- Version: v1.1.0 -->
      <div class="faq-item">
        <div class="faq-question" onclick="toggleAnswer(this)">
          <span>&#9654;</span> v1.1.0
        </div>
        <div class="faq-answer">
          <ul>
            <li>New icons and logos</li>
            <li>Bug fixes and UI refinements</li>
          </ul>
        </div>
      </div>
      <!-- Version: v1.0.0 -->
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
        </div>
      </div>
    </div>
  </div>
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
