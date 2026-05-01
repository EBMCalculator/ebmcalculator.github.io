---
layout: default
title: Support
description: EBM Calculator help — FAQ, beta signup, and contact info. Step-by-step tutorials are now in-app (v1.6.0+).
---

<h2 class="page-title">Support</h2>

<div class="section-links-wrapper">
  <div class="section-links">
    <a href="#faq">FAQ</a>
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
    <p>EBM Calculator is optimized for iPhone and iPad on iOS/iPadOS 26, with support back to iOS/iPadOS 18.1. The app also runs on Apple Silicon Macs via iPad app compatibility.</p>
    <p>iCloud Sync requires being signed in to iCloud on each of your devices and is managed in your device's iCloud settings.</p>
  </div>
</details>

<details class="collapsible">
  <summary>How many results can I save?</summary>
  <div class="collapsible-body">
    <p>As of v1.6.0, you can save <strong>unlimited results</strong>. Saved results sync across all your devices via iCloud when iCloud Sync is enabled.</p>
    <p>From the Results tab:</p>
    <ul>
      <li><strong>Search</strong></li>
      <li><strong>Filter</strong> by type</li>
      <li><strong>Sort</strong></li>
      <li>Swipe right to <strong>share</strong></li>
      <li>Swipe left to <strong>edit</strong></li>
      <li>Swipe far-left to <strong>delete</strong></li>
      <li>Use "Select Results" in the menu for bulk actions</li>
      <li>Toggle Full/Condensed view from the filter menu</li>
    </ul>
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
    <p>Yes! The more I learn, the more features I want to build.</p>
    <p>If you have suggestions for new features or improvements, please email me at <a href="mailto:support@ebmcalculator.com">support@ebmcalculator.com</a>.</p>
    <p>If you're interested in testing new features before they're released, see below.</p>
  </div>
</details>

<details class="collapsible" id="beta">
  <summary>How do I sign up for beta releases?</summary>
  <div class="collapsible-body">
    <p>If you're interested in testing new features before they're released, I'd love your help! Just send an email to <a href="mailto:beta@ebmcalculator.com">beta@ebmcalculator.com</a> and I'll add you to the list &mdash; or, if you prefer, fill out the form below.</p>

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
          Your email will only be used for beta program updates &mdash; no spam, ever.
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

<section class="policy-section">
  <p><strong>The How-To Guide has moved into the app.</strong></p>
  <p>Starting with EBM Calculator v1.6.0, step-by-step guided tutorials live directly inside the app &mdash; open them from the menu in any calculator view, or from Settings.</p>
  <p>If you don't see them, please update to the latest version on the App Store.</p>
  <p style="text-align: center; margin-top: 18px;">
    <a href="https://apps.apple.com/us/app/ebm-calculator/id6737999201"
       target="_blank" rel="noopener noreferrer"
       aria-label="Update EBM Calculator on the App Store">
      <img src="/assets/images/Download_on_the_App_Store_Badge_US-UK_RGB_blk_092917.svg"
           alt="Download on the App Store" style="height: 50px;">
    </a>
  </p>
</section>

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
