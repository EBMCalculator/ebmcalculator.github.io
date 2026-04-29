---
layout: default
title: Support
description: EBM Calculator help — FAQ, step-by-step how-to guide for the Effect, Diagnostic Test, and Post-Test Probability calculators, beta signup, and contact info.
---

<h2 class="page-title">Support</h2>

<div class="section-links-wrapper">
  <div class="section-links">
    <a href="#faq">FAQ</a>
    <a href="#how-to-guide">How-To</a>
    <a href="#contact">Contact</a>
  </div>
</div>

<h3 id="faq" class="section-heading">Frequently Asked Questions</h3>

<details class="collapsible">
  <summary>How do I download the app?</summary>
  <div class="collapsible-body">
    <p>EBM Calculator is available now on the App Store.</p>
    <p style="text-align: center;">
      <a href="https://apps.apple.com/us/app/ebm-calculator/id6737999201"
         target="_blank" rel="noopener noreferrer">
        <img src="/assets/images/Download_on_the_App_Store_Badge_US-UK_RGB_blk_092917.svg"
             alt="Download on the App Store" style="height: 50px;">
      </a>
    </p>
  </div>
</details>

<details class="collapsible">
  <summary>What devices are compatible?</summary>
  <div class="collapsible-body">
    <p>EBM Calculator is available on iOS devices running iOS 18.1 or later. It is optimized for iOS 26 on iPhones, but will also run on iPads and Apple Silicon Macs.</p>
  </div>
</details>

<details class="collapsible">
  <summary>How many results can I save?</summary>
  <div class="collapsible-body">
    <p>You can save up to 100 results. From the Results tab, you can also:</p>
    <ul>
      <li>Search through saved results using keywords or citation info</li>
      <li>Share results by swiping right</li>
      <li>Edit individual results by swiping left</li>
      <li>Reorder results by pressing and dragging</li>
      <li>Delete individual results by swiping far left</li>
      <li>Delete all saved results from the menu button</li>
    </ul>
  </div>
</details>

<details class="collapsible">
  <summary>Why do the calculators have different input options?</summary>
  <div class="collapsible-body">
    <p>Each calculator offers different input options to match how authors commonly report their results. Choose the one that best fits your study.</p>
    <p>For example, if the study only provides PPV and NPV (and not sensitivity or specificity), select PPV/NPV as your input method.</p>
  </div>
</details>

<details class="collapsible">
  <summary>What formulas are used for calculating confidence intervals?</summary>
  <div class="collapsible-body">
    <p><a href="/assets/pdf/Formulas.pdf" target="_blank" rel="noopener noreferrer">Click here to review the formulas</a> used for calculating all metrics and confidence intervals in the app.</p>
  </div>
</details>

<details class="collapsible">
  <summary>Why did you create this app?</summary>
  <div class="collapsible-body">
    <p>I got tired of jumping between different online calculators just to interpret study results, so I built the EBM Calculator to streamline the process and make evidence appraisal simpler for all of us.</p>
    <p>The app has come a long way since I first started developing it, but the goal remains the same: to provide a purposefully simple tool that helps you assess the strength of an association (for therapies or exposures), evaluate diagnostic test performance, and calculate post-test probability.</p>
  </div>
</details>

<details class="collapsible">
  <summary>Are you planning to add more features?</summary>
  <div class="collapsible-body">
    <p>Yes! The more I learn, the more features I want to build. But I also wanted to release the app quickly to start helping clinicians.</p>
    <p>If you have suggestions for new features or improvements, please email me at <a href="mailto:support@ebmcalculator.com">support@ebmcalculator.com</a>.</p>
    <p>If you're interested in testing new features before they're released, see below!</p>
  </div>
</details>

<details class="collapsible" id="beta">
  <summary>How do I sign up for beta releases?</summary>
  <div class="collapsible-body">
    <p>If you're interested in testing new features before they're released, I'd love your help! You can sign up below to be included in future beta versions of EBM Calculator — or, if you prefer, just send an email to <a href="mailto:beta@ebmcalculator.com">beta@ebmcalculator.com</a> and I'll add you to the list.</p>

    <div id="form-wrapper">
      <form action="https://api.web3forms.com/submit" method="POST" id="beta-signup-form" onsubmit="handleBetaSubmit(event)">
        <input type="hidden" name="access_key" value="64dff39e-917c-4a85-a79e-1bdc5fc5342a">
        <input type="hidden" name="subject" value="New Beta Signup from ebmcalculator.com">
        <input type="hidden" name="from_name" value="EBM Calculator Website">
        <h4 style="text-align: center; margin-top: 0;">Join the Beta Program</h4>
        <p style="text-align: center;">Be the first to try out new features in EBM Calculator.</p>
        <label for="email" style="display: block; margin-bottom: 6px; font-weight: 500;">Email address<span style="color: #c00;">*</span></label>
        <input type="email" name="email" id="email" required placeholder="your@email.com" style="padding: 10px; margin-bottom: 16px; border: 1px solid var(--border); border-radius: var(--radius-sm); background: var(--bg); color: var(--text); font-size: 16px;">
        <label for="name" style="display: block; margin-bottom: 6px; font-weight: 500;">Name (optional)</label>
        <input type="text" name="name" id="name" placeholder="Jane Smith" style="padding: 10px; margin-bottom: 20px; border: 1px solid var(--border); border-radius: var(--radius-sm); background: var(--bg); color: var(--text); font-size: 16px;">
        <input type="text" name="botcheck" style="display: none;">
        <button type="submit" style="background-color: var(--accent); color: var(--accent-fg); padding: 12px 24px; border: none; border-radius: var(--radius-md); font-size: 16px; font-weight: 600; cursor: pointer;">
          Sign Up
        </button>
        <p style="text-align: center; font-size: 0.85em; color: var(--text-muted); margin-top: 1em;">
          Your email will only be used for beta program updates — no spam, ever.
        </p>
      </form>
      <div id="thank-you" style="display: none; text-align: center;">
        <h4>Thank you!</h4>
        <p>Your email was received. You'll be contacted with the next beta release.</p>
      </div>
    </div>
  </div>
</details>

<h3 id="how-to-guide" class="section-heading">How-To Guide</h3>

<details class="collapsible">
  <summary>Effect Calculator</summary>
  <div class="collapsible-body">
    <p>First, select how you would like to input the study data. You can choose either "Event Rates" or "Counts" (the number of participants in each arm of the study).</p>
    <p style="text-align: center;">Event Rates:</p>
    <a href="/assets/images/screenshots/Effect - Screenshot 2a.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/Effect - Screenshot 2a.png" alt="Effect Calculator: Event Rates input">
    </a>
    <p style="text-align: center;">or Counts:</p>
    <a href="/assets/images/screenshots/Effect - Screenshot 2b.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/Effect - Screenshot 2b.png" alt="Effect Calculator: Counts input">
    </a>
    <p>If you are reviewing a <strong>Case-Control</strong> study, enable the <strong>Case-Control Study</strong> toggle. This changes the input fields to match the way data are collected in these studies — starting with groups of cases (with the outcome) and controls (without the outcome), then entering exposure information for each group.</p>
    <p style="text-align: center;">Exposure Rates for Case-Control Study:</p>
    <a href="/assets/images/screenshots/Effect - Screenshot 2d.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/Effect - Screenshot 2d.png" alt="Effect Calculator: Case-Control Exposure Rates">
    </a>
    <p style="text-align: center;">or Counts for Case-Control Study:</p>
    <a href="/assets/images/screenshots/Effect - Screenshot 2e.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/Effect - Screenshot 2e.png" alt="Effect Calculator: Case-Control Counts">
    </a>
    <p>Based on how the authors of this randomized controlled trial<sup><a href="#ref1" style="text-decoration: none;">[1]</a></sup> presented their results in the table below, you could choose either "Event Rates" or "Counts" to input the data.</p>
    <p style="text-align: center;">(click to enlarge)</p>
    <a href="/assets/images/screenshots/Effect - Example Study.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot app-screenshot--wide" src="/assets/images/screenshots/Effect - Example Study.png" alt="Example study table">
    </a>
    <p style="text-align: center;">Here, I chose to enter the event rates (EER 90.0%, CER 63.3%):</p>
    <a href="/assets/images/screenshots/Effect - Screenshot 3a.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/Effect - Screenshot 3a.png" alt="Effect Calculator: filled-in event rates">
    </a>
    <p>Press the "Calculate" button to see the relevant effect estimates and their confidence intervals.</p>
    <p>The manuscript's table above provides the odds ratio (OR), but absolute risk measures offer a clearer understanding of the treatment effect's magnitude. In this example, EBM Calculator displays the absolute risk increase (ARI) and number needed to treat (NNT) to cause one additional outcome, along with relative risk metrics and their confidence intervals.</p>
    <a href="/assets/images/screenshots/Effect - Screenshot 4.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/Effect - Screenshot 4.png" alt="Effect Calculator: results">
    </a>
    <p id="ref1" class="ref">
      <a href="https://pubmed.ncbi.nlm.nih.gov/29913001/" target="_blank" rel="noopener noreferrer">
        <sup>[1]</sup> Basu B, Sander A, Roy B, Preussler S, Barua S, Mahapatra TKS, Schaefer F. Efficacy of Rituximab vs Tacrolimus in Pediatric Corticosteroid-Dependent Nephrotic Syndrome: A Randomized Clinical Trial. JAMA Pediatr. 2018 Aug 1;172(8):757-764. doi: 10.1001/jamapediatrics.2018.1323. Erratum in: JAMA Pediatr. 2018 Dec 1;172(12):1205. doi: 10.1001/jamapediatrics.2018.3632. PMID: 29913001; PMCID: PMC6142920.
      </a>
    </p>
    <p style="text-align: right;"><a href="#top" class="back-to-top">⬆ Back to top</a></p>
  </div>
</details>

<details class="collapsible">
  <summary>Diagnostic Test Calculator</summary>
  <div class="collapsible-body">
    <p>First, select how you would like to input the study data. You can choose from "Sens/Spec" (sensitivity and specificity), "PPV/NPV" (positive and negative predictive values), or "Counts" (the number of participants in each arm of the study).</p>
    <p style="text-align: center;">Sens/Spec:</p>
    <a href="/assets/images/screenshots/Diagnostic Test - Screenshot 2a.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/Diagnostic Test - Screenshot 2a.png" alt="Diagnostic Test: Sens/Spec input">
    </a>
    <p style="text-align: center;">PPV/NPV:</p>
    <a href="/assets/images/screenshots/Diagnostic Test - Screenshot 2b.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/Diagnostic Test - Screenshot 2b.png" alt="Diagnostic Test: PPV/NPV input">
    </a>
    <p style="text-align: center;">or Counts:</p>
    <a href="/assets/images/screenshots/Diagnostic Test - Screenshot 2c.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/Diagnostic Test - Screenshot 2c.png" alt="Diagnostic Test: Counts input">
    </a>
    <p>Based on how the authors of this study<sup><a href="#ref2" style="text-decoration: none;">[2]</a></sup> presented their results in the table below, it would be easiest to use the "Sens/Spec" input method.</p>
    <p style="text-align: center;">(click to enlarge)</p>
    <a href="/assets/images/screenshots/Diagnostic Test - Example Study.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot app-screenshot--wide" src="/assets/images/screenshots/Diagnostic Test - Example Study.png" alt="Example diagnostic study table">
    </a>
    <p>Enter the sensitivity (94.1%), specificity (79.2%), prevalence (20.6%), and total sample size (248).</p>
    <a href="/assets/images/screenshots/Diagnostic Test - Screenshot 3.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/Diagnostic Test - Screenshot 3.png" alt="Diagnostic Test: filled-in inputs">
    </a>
    <p>Press the "Calculate" button to see the relevant diagnostic test metrics and their confidence intervals.</p>
    <p>The manuscript's table above provides sensitivity and specificity. Some authors also report positive and negative predictive values (PPV and NPV). However, because predictive values depend on disease prevalence, they may not apply to your patients if the study population's prevalence differs from your own.</p>
    <p>For this reason, we prefer using positive and negative likelihood ratios (LRs) to better understand post-test probability. In this example, EBM Calculator displays LR(+) and LR(–) with confidence intervals, along with an option to calculate post-test probability using a different prevalence.</p>
    <a href="/assets/images/screenshots/Diagnostic Test - Screenshot 4.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/Diagnostic Test - Screenshot 4.png" alt="Diagnostic Test: results">
    </a>
    <p>Press the menu button at the top right to see more options.</p>
    <a href="/assets/images/screenshots/Diagnostic Test - Screenshot 5a.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/Diagnostic Test - Screenshot 5a.png" alt="Diagnostic Test: menu">
    </a>
    <p>You can see the results as an interactive Fagan Nomogram through the menu button or by pressing the nomogram button. Select either the LR(+) or LR(-) value.</p>
    <a href="/assets/images/screenshots/Diagnostic Test - Screenshot 5c.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/Diagnostic Test - Screenshot 5c.png" alt="Diagnostic Test: nomogram option">
    </a>
    <p>Use the sliders to explore how a change in Pre-Test Probability influences the Post-Test Probability.</p>
    <a href="/assets/images/screenshots/Diagnostic Test - Screenshot 6.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/Diagnostic Test - Screenshot 6.png" alt="Diagnostic Test: interactive nomogram">
    </a>
    <p id="ref2" class="ref">
      <a href="https://pubmed.ncbi.nlm.nih.gov/24145848/" target="_blank" rel="noopener noreferrer">
        <sup>[2]</sup> Traube C, Silver G, Kearney J, Patel A, Atkinson TM, Yoon MJ, Halpert S, Augenstein J, Sickles LE, Li C, Greenwald B. Cornell Assessment of Pediatric Delirium: a valid, rapid, observational tool for screening delirium in the PICU. Crit Care Med. 2014 Mar;42(3):656-63. doi: 10.1097/CCM.0b013e3182a66b76. PMID: 24145848; PMCID: PMC5527829.
      </a>
    </p>
    <p style="text-align: right;"><a href="#top" class="back-to-top">⬆ Back to top</a></p>
  </div>
</details>

<details class="collapsible">
  <summary>Post-Test Probability Calculator</summary>
  <div class="collapsible-body">
    <p>First, select how you would like to input the study data. You can choose from either "Sensitivity &amp; Specificity" or "Likelihood Ratios".</p>
    <p style="text-align: center;">Sensitivity &amp; Specificity:</p>
    <a href="/assets/images/screenshots/PostTest Prob - Screenshot 2a.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/PostTest Prob - Screenshot 2a.png" alt="Post-Test Prob: Sens/Spec input">
    </a>
    <p style="text-align: center;">or Likelihood Ratios:</p>
    <a href="/assets/images/screenshots/PostTest Prob - Screenshot 2b.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/PostTest Prob - Screenshot 2b.png" alt="Post-Test Prob: LR input">
    </a>
    <p>Based on how the authors of this study<sup><a href="#ref3" style="text-decoration: none;">[2]</a></sup> presented their results in the table below, it would be easiest to use the "Sensitivity &amp; Specificity" input method.</p>
    <p style="text-align: center;">(click to enlarge)</p>
    <a href="/assets/images/screenshots/PostTest Prob - Example Study.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot app-screenshot--wide" src="/assets/images/screenshots/PostTest Prob - Example Study.png" alt="Example post-test probability study table">
    </a>
    <p>Enter the sensitivity (94.1%) and specificity (79.2%) of the diagnostic test. Next, choose your pre-test probability (often the prevalence of disease or condition in your patient population).</p>
    <p style="text-align: center;">In this example, I chose a pre-test probability of 35%:</p>
    <a href="/assets/images/screenshots/PostTest Prob - Screenshot 3a.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/PostTest Prob - Screenshot 3a.png" alt="Post-Test Prob: filled-in inputs">
    </a>
    <p>Press the "Calculate" button to see the post-test probabilities for a positive or negative test result.</p>
    <a href="/assets/images/screenshots/PostTest Prob - Screenshot 4.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/PostTest Prob - Screenshot 4.png" alt="Post-Test Prob: results">
    </a>
    <p>You can also access an interactive Fagan Nomogram through the menu button at the top right…</p>
    <a href="/assets/images/screenshots/PostTest Prob - Screenshot 5a.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/PostTest Prob - Screenshot 5a.png" alt="Post-Test Prob: menu">
    </a>
    <p>…or by pressing the nomogram button and selecting either the LR(+) or LR(-) value.</p>
    <a href="/assets/images/screenshots/PostTest Prob - Screenshot 5b.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/PostTest Prob - Screenshot 5b.png" alt="Post-Test Prob: choose LR">
    </a>
    <p>Use the sliders to explore how changes in Pre-Test Probability and Likelihood Ratio influence the Post-Test Probability.</p>
    <a href="/assets/images/screenshots/PostTest Prob - Screenshot 6.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/PostTest Prob - Screenshot 6.png" alt="Post-Test Prob: interactive nomogram">
    </a>
    <p id="ref3" class="ref">
      <a href="https://pubmed.ncbi.nlm.nih.gov/24145848/" target="_blank" rel="noopener noreferrer">
        <sup>[2]</sup> Traube C, Silver G, Kearney J, Patel A, Atkinson TM, Yoon MJ, Halpert S, Augenstein J, Sickles LE, Li C, Greenwald B. Cornell Assessment of Pediatric Delirium: a valid, rapid, observational tool for screening delirium in the PICU. Crit Care Med. 2014 Mar;42(3):656-63. doi: 10.1097/CCM.0b013e3182a66b76. PMID: 24145848; PMCID: PMC5527829.
      </a>
    </p>
    <p style="text-align: right;"><a href="#top" class="back-to-top">⬆ Back to top</a></p>
  </div>
</details>

<details class="collapsible">
  <summary>Adding Citations</summary>
  <div class="collapsible-body">
    <p>Every calculator has the option to add a citation at the bottom by pressing "Add".</p>
    <a href="/assets/images/screenshots/Citation - Screenshot 1a.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/Citation - Screenshot 1a.png" alt="Citation: Add button">
    </a>
    <p>Enter a PMID to fetch the citation from PubMed, or enter it manually.</p>
    <p style="text-align: center;">PubMed:</p>
    <a href="/assets/images/screenshots/Citation - Screenshot 2a.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/Citation - Screenshot 2a.png" alt="Citation: PMID entry">
    </a>
    <a href="/assets/images/screenshots/Citation - Screenshot 3a.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/Citation - Screenshot 3a.png" alt="Citation: PubMed result">
    </a>
    <p style="text-align: center;">or Manual Entry:</p>
    <a href="/assets/images/screenshots/Citation - Screenshot 2b.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/Citation - Screenshot 2b.png" alt="Citation: manual entry form">
    </a>
    <a href="/assets/images/screenshots/Citation - Screenshot 3b.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/Citation - Screenshot 3b.png" alt="Citation: manual entry filled">
    </a>
    <p>After saving the citation, you can edit or remove it from within the calculator.</p>
    <a href="/assets/images/screenshots/Citation - Screenshot 4.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/Citation - Screenshot 4.png" alt="Citation: edit/remove">
    </a>
    <p>A condensed citation will display below the results.</p>
    <a href="/assets/images/screenshots/Citation - Screenshot 5a.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/Citation - Screenshot 5a.png" alt="Citation: condensed display under results">
    </a>
    <p>Tap any citation to view the full details, open it in PubMed, or copy the citation to your clipboard.</p>
    <a href="/assets/images/screenshots/Citation - Screenshot 5b.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/Citation - Screenshot 5b.png" alt="Citation: detail view">
    </a>
    <p style="text-align: right;"><a href="#top" class="back-to-top">⬆ Back to top</a></p>
  </div>
</details>

<details class="collapsible">
  <summary>Viewing Results</summary>
  <div class="collapsible-body">
    <p>Click on the Results tab to view up to 100 of your saved results. You can press and drag to rearrange, or click a result to view it individually.</p>
    <a href="/assets/images/screenshots/Results - Screenshot 2.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/Results - Screenshot 2.png" alt="Results: list view">
    </a>
    <p>Swipe right on a result to email, message, print, or export.</p>
    <a href="/assets/images/screenshots/Results - Screenshot 3a.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/Results - Screenshot 3a.png" alt="Results: swipe-right actions">
    </a>
    <p>Swipe left to edit the original inputs or to delete the result.</p>
    <a href="/assets/images/screenshots/Results - Screenshot 3b.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/Results - Screenshot 3b.png" alt="Results: swipe-left actions">
    </a>
    <p>Press the menu button to see more options.</p>
    <a href="/assets/images/screenshots/Results - Screenshot 4.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/Results - Screenshot 4.png" alt="Results: menu">
    </a>
    <p>Use the Search function to filter results by keyword.</p>
    <a href="/assets/images/screenshots/Results - Screenshot 5.png" target="_blank" rel="noopener noreferrer">
      <img class="app-screenshot" src="/assets/images/screenshots/Results - Screenshot 5.png" alt="Results: search">
    </a>
    <p style="text-align: right;"><a href="#top" class="back-to-top">⬆ Back to top</a></p>
  </div>
</details>

<h3 id="contact" class="section-heading">Contact</h3>

<section class="policy-section">
  <p>Please email <a href="mailto:support@ebmcalculator.com">support@ebmcalculator.com</a> with any questions, comments, or suggestions.</p>
</section>

<script>
  // Beta signup form: handle submit, show thank-you state.
  function handleBetaSubmit(event) {
    event.preventDefault();
    const form = event.target;
    const formData = new FormData(form);
    fetch(form.action, {
      method: form.method,
      body: formData,
      headers: { Accept: "application/json" }
    }).then(response => {
      if (response.ok) {
        form.style.display = "none";
        document.getElementById("thank-you").style.display = "block";
      } else {
        alert("There was a problem submitting your request. Please try again.");
      }
    }).catch(() => {
      alert("Something went wrong. Please try again.");
    });
  }

  // Auto-open the <details> matching the URL hash on initial load
  // (and any ancestor <details>), so links from the app to #beta etc. land open.
  function openDetailsForHash() {
    const id = window.location.hash.slice(1);
    if (!id) return;
    let el = document.getElementById(id);
    while (el) {
      if (el.tagName === "DETAILS") el.open = true;
      el = el.parentElement;
    }
  }
  window.addEventListener("DOMContentLoaded", openDetailsForHash);
  window.addEventListener("hashchange", openDetailsForHash);
</script>
