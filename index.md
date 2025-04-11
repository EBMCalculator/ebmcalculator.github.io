---
layout: default
title: Home
---

<!-- Force feature boxes to be always expanded -->
<style>
  .static-feature .faq-answer { 
    display: block !important;
  }
  .static-feature .faq-question { 
    cursor: default;
  }
</style>

<style>
  .index-sticky {
    top: 50px !important; /* Reduce the top offset on the home page so the button sits only 5px below the tab bar */
    margin-top: 0 !important; /* Remove the negative margin so the button isn't pushed upward */
  }
</style>


<!-- TestFlight Button -->
<div class="section-links-wrapper index-sticky" style="padding-top: 5px;">
  <div class="section-links">
    <a href="https://testflight.apple.com/join/9FZgaZyd" style="background-color: #073472; color: white; padding: 12px 24px; font-size: 16px; border-radius: 8px; text-decoration: none;">
      Join the EBM Calculator Beta on Apple's TestFlight
    </a>
  </div>
</div>

<!-- Goal Statement -->
<div style="max-width: 600px; margin: 20px auto;" markdown="1">
  The goal of **EBM Calculator** is to help with your appraisal of the medical literature!
</div>

<!-- Individual Feature Boxes (Always Expanded) -->
<div class="static-feature" style="max-width: 600px; margin: 20px auto;">
  <!-- Effect Calculator -->
  <div class="faq-item">
    <div class="faq-question">Effect Calculator</div>
    <div class="faq-answer">
      <ul>
        <li>Used for studies that examine the effect of a therapy or exposure.</li>
        <li>
          Calculate key effect estimates for <strong>dichotomous outcomes</strong>, including:
          <ul>
            <li><strong>Absolute Risk Reduction (ARR)</strong></li>
            <li><strong>Number Needed to Treat (NNT)</strong></li>
            <li><strong>Risk Ratio (RR)</strong></li>
            <li><strong>Relative Risk Reduction (RRR)</strong></li>
            <li><strong>Odds Ratio (OR)</strong></li>
          </ul>
        </li>
        <li>Each measure is accompanied by a <strong>95% Confidence Interval</strong> to assess the precision of the effect.</li>
      </ul>
    </div>
  </div>
  
  <!-- Diagnostic Test Calculator -->
  <div class="faq-item">
    <div class="faq-question">Diagnostic Test Calculator</div>
    <div class="faq-answer">
      <ul>
        <li>
          Evaluate the utility of diagnostic tests using metrics like:
          <ul>
            <li><strong>Sensitivity</strong></li>
            <li><strong>Specificity</strong></li>
            <li><strong>Likelihood Ratios (LR+ and LR-)</strong></li>
            <li><strong>Positive Predictive Value (PPV)</strong></li>
            <li><strong>Negative Predictive Value (NPV)</strong></li>
          </ul>
        </li>
        <li>Each measure includes a <strong>95% Confidence Interval</strong> to ensure accurate evaluation.</li>
      </ul>
    </div>
  </div>
  
  <!-- Post-Test Probability Calculator -->
  <div class="faq-item">
    <div class="faq-question">Post-Test Probability Calculator</div>
    <div class="faq-answer">
      <ul>
        <li>Estimate the likelihood of a condition or disease based on the result of a diagnostic test.</li>
        <li>Calculate <strong>Post-Test Probability</strong> using Sensitivity, Specificity, or Likelihood Ratios.</li>
        <li>Use an <strong>Interactive Fagan Nomogram</strong> to see how Post-Test Probability changes.</li>
      </ul>
    </div>
  </div>
  
  <!-- Save & Share -->
  <div class="faq-item">
    <div class="faq-question">Save &amp; Share</div>
    <div class="faq-answer">
      <ul>
        <li>Up to 50 results can be <strong>saved</strong> within the app for future reference.</li>
        <li>Easily <strong>share, export, or print</strong> results directly from the app.</li>
      </ul>
    </div>
  </div>
  
  <!-- Library -->
  <div class="faq-item">
    <div class="faq-question">Library</div>
    <div class="faq-answer">
      <ul>
        <li>Access lessons in <strong>Evidence-Based Medicine (EBM)</strong>.</li>
        <li>Reinforce concepts in biostatistics and study design.</li>
      </ul>
    </div>
  </div>
</div>
