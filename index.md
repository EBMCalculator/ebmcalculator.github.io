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

<!-- Hero Download Section -->
<div class="hero-download">
  <p style="margin-bottom: 1em;">Available now on the App Store</p>
  <a href="https://apps.apple.com/us/app/ebm-calculator/id6737999201" target="_blank" rel="noopener noreferrer">
    <img class="hero-sticky-img" src="/assets/images/Download_on_the_App_Store_Badge_US-UK_RGB_blk_092917.svg" alt="Download on the App Store">
  </a>
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
        <li>Used for studies that examine the effect of a therapy or exposure</li>
        <li>
          Calculate key effect estimates for <strong>dichotomous outcomes</strong>:
          <ul>
            <li><strong>Absolute Risk Reduction (ARR)</strong></li>
            <li><strong>Number Needed to Treat (NNT)</strong></li>
            <li><strong>Risk Ratio (RR)</strong></li>
            <li><strong>Relative Risk Reduction (RRR)</strong></li>
            <li><strong>Odds Ratio (OR)</strong></li>
          </ul>
        </li>
        <li>Includes <strong>95% Confidence Intervals</strong> for every metric</li>
      </ul>
    </div>
  </div>
  
  <!-- Diagnostic Test Calculator -->
  <div class="faq-item">
    <div class="faq-question">Diagnostic Test Calculator</div>
    <div class="faq-answer">
      <ul>
        <li>Used for studies that evaluate the accuracy of a diagnostic test</li>
        <li>
          Calculate core statistics:
          <ul>
            <li><strong>Sensitivity & Specificity</strong></li>
            <li><strong>Likelihood Ratios (LR+, LR-)</strong></li>
            <li><strong>Positive & Negative Predictive Values (PPV, NPV)</strong></li>
          </ul>
        </li>
        <li>Includes <strong>95% Confidence Intervals</strong> for all measures</li>
      </ul>
    </div>
  </div>
  
  <!-- Post-Test Probability Calculator -->
  <div class="faq-item">
    <div class="faq-question">Post-Test Probability Calculator</div>
    <div class="faq-answer">
      <ul>
        <li>Used to estimate the likelihood of disease after a test result</li>
        <li>Input Sensitivity & Specificity or Likelihood Ratios</li>
        <li>Visualize probability changes with an <strong>interactive Fagan Nomogram</strong></li>
      </ul>
    </div>
  </div>
  
  <!-- Save, Search & Share -->
  <div class="faq-item">
    <div class="faq-question">Save, Search &amp; Share</div>
    <div class="faq-answer">
      <ul>
        <li><strong>Save</strong> up to 50 results for future reference</li>
        <li><strong>Search</strong> results to quickly find what matters</li>        
        <li><strong>Share, print, or export</strong> directly from the app</li>
      </ul>
    </div>
  </div>
  
  <!-- Library -->
  <div class="faq-item">
    <div class="faq-question">Library</div>
    <div class="faq-answer">
      <ul>
        <li>Explore lessons in <strong>Evidence-Based Medicine (EBM)</strong></li>
        <li>Reinforce core concepts in biostatistics and study design</li>
      </ul>
    </div>
  </div>
</div>
