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
  <a href="#how-to-guide">How-To Guide</a>
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
        <div class="faq-answer">You can save up to 50 results. From the Results tab, you can reorder results (press and drag), delete individual results (swipe left), share results (swipe right), or delete all saved results (from the menu button).</div>
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
        <div class="faq-answer">Yes! The more I learn, the more features I want to build into the app. But I also wanted to get it out there ASAP to start helping clinicians. If you have a suggestion of what would be helpful, please let me know at <a href="mailto:support@ebmcalculator.com">support@ebmcalculator.com</a>!</div>
      </div>
    </div>
  </div>

  <!-- How-To Guide Section Box -->
  <div class="faq-item">
    <div class="faq-question" id="how-to-guide" onclick="toggleAnswer(this)"><span>&#9654;</span> How-To Guide</div>
    <div class="faq-answer">
      <p>This section will include walkthroughs of how to use the calculator for different scenarios. Stay tuned!</p>
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
