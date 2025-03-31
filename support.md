<!-- Top anchor added so ^Top links go to the very top of the page -->
<a id="top"></a>
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

  .section-links {
    text-align: center;
    margin-top: 20px;
  }
  .section-links a {
    margin-right: 15px;
    text-decoration: none;
  }
  
  /* Section header style with ^Top link on the right */
  .section-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-bottom: 1px solid #ccc;
    padding-bottom: 5px;
    margin-top: 40px;
  }
  .section-header h3 {
    margin: 0;
  }
  
  .faq-item {
    margin-bottom: 20px;
  }
  .faq-question {
    font-weight: bold;
    cursor: pointer;
  }
  .faq-answer {
    display: none;
    margin-top: 10px;
  }
</style>

<div class="tab-bar">
  <a href="/">Home</a>
  <a href="/about">About</a>
  <a href="/support">Support</a>
  <a href="/privacy-policy">Privacy</a>
</div>

<!-- Support header with centered links immediately below -->
<h2>Support</h2>
<div class="section-links">
  <a href="#faq">FAQ</a>
  <a href="#how-to-guide">How-To Guide</a>
  <a href="#versions">Versions</a>
</div>

<div style="max-width: 600px; margin: 20px auto;" markdown="1">
  If you have any issues, questions, or feedback, please email me at 
  <a href="mailto:support@ebmcalculator.com">support@ebmcalculator.com</a>.

  For privacy-related information, please view the 
  <a href="/privacy-policy">Privacy Policy</a>.
</div>

---

<!-- FAQ Section -->
<div class="section-header">
  <h3><a id="faq"></a> Frequently Asked Questions</h3>
  <a href="#top">^Top</a>
</div>

<div style="max-width: 600px; margin: 20px auto;" markdown="1">
  <div class="faq-item">
    <div class="faq-question" onclick="toggleAnswer(this)"><span>&#9654;</span> What devices are compatible?</div>
    <div class="faq-answer">EBM Calculator is available on iOS devices running iOS 18.1 or later. It is optimized for iPhones, but will also run on iPads and Apple Silicon Macs.</div>
  </div>

  <div class="faq-item">
    <div class="faq-question" onclick="toggleAnswer(this)"><span>&#9654;</span> How many results can I save?</div>
    <div class="faq-answer">You can save up to 50 results. From the Results tab, you can reorder results (press and drag), delete individual results (swipe left), share results (swipe right), or delete all saved results (from the menu button).</div>
  </div>

  <div class="faq-item">
    <div class="faq-question" onclick="toggleAnswer(this)"><span>&#9654;</span> Why do the calculators have different input options?</div>
    <div class="faq-answer">Different input methods are available to fit various ways authors report their results. Choose the one that makes the most sense for the study you are appraising. For example, if you are assessing the performance of a Diagnostic Test and the authors report only the Predictive Values (and not sensitivity or specificity), choose PPV/NPV for your input fields.</div>
  </div>

  <div class="faq-item">
    <div class="faq-question" onclick="toggleAnswer(this)"><span>&#9654;</span> Why did you create this app?</div>
    <div class="faq-answer">I was frustrated by constantly having to switch between various websites to find online calculators for interpreting study results. I built the EBM Calculator app to streamline this process and to simplify evidence appraisal. My first version was coded in Python on my local devices. I decided to make it an official iOS app to share it easily with colleagues who were also evaluating the medical literature!</div>
  </div>

  <div class="faq-item">
    <div class="faq-question" onclick="toggleAnswer(this)"><span>&#9654;</span> Are you planning to add more features?</div>
    <div class="faq-answer">Yes! The more I learn, the more features I want to build into the app. But I also wanted to get it out there ASAP to start helping clinicians. If you have a suggestion of what would be helpful, please let me know at <a href="mailto:support@ebmcalculator.com">support@ebmcalculator.com</a>!</div>
  </div>
</div>

<script>
function toggleAnswer(element) {
  const answer = element.nextElementSibling;
  const arrow = element.querySelector('span');
  if (answer.style.display === 'block') {
    answer.style.display = 'none';
    arrow.innerHTML = '&#9654;'; // Right caret
  } else {
    answer.style.display = 'block';
    arrow.innerHTML = '&#9660;'; // Down caret
  }
}
</script>

---

<!-- How-To Guide Section -->
<div class="section-header">
  <h3><a id="how-to-guide"></a> How-To Guide (Coming Soon)</h3>
  <a href="#top">^Top</a>
</div>

<p style="max-width: 600px; margin: 20px auto;">
  This section will include walkthroughs of how to use the calculator for different scenarios. Stay tuned!
</p>

---

<!-- Versions Section -->
<div class="section-header">
  <h3><a id="versions"></a> Versions (Coming Soon)</h3>
  <a href="#top">^Top</a>
</div>

<p style="max-width: 600px; margin: 20px auto;">
  A list of past versions and updates will be available here, along with release notes and new features.
</p>

---

<div style="text-align: center; margin-top: 40px;">
  &copy; 2024 David A. Stewart, MD
</div>
