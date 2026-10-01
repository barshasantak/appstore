---
layout: default
title: Mac Apps Portfolio
description: Thoughtfully crafted utilities and tools for macOS.
---

<style>
  .app-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 1.5rem;
    margin: 2rem 0;
  }
  .app-card {
    background: #ffffff;
    border: 1px solid #e1e4e8;
    border-radius: 12px;
    padding: 1.5rem;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    box-shadow: 0 4px 6px rgba(0,0,0,0.04);
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }
  .app-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 8px 16px rgba(0,0,0,0.08);
  }
  .app-header {
    display: flex;
    align-items: center;
    gap: 1rem;
    margin-bottom: 0.75rem;
  }
  .app-icon {
    width: 56px;
    height: 56px;
    border-radius: 12px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    flex-shrink: 0;
  }
  .app-title {
    margin: 0;
    font-size: 1.25rem;
    font-weight: 600;
  }
  .app-desc {
    color: #586069;
    font-size: 0.95rem;
    line-height: 1.4;
    margin-bottom: 1.5rem;
  }
  .app-actions {
    display: flex;
    gap: 0.75rem;
    align-items: center;
  }
  .btn {
    display: inline-block;
    padding: 0.45rem 0.85rem;
    font-size: 0.85rem;
    font-weight: 500;
    text-decoration: none;
    border-radius: 6px;
    text-align: center;
  }
  .btn-primary {
    background-color: #0366d6;
    color: #ffffff !important;
  }
  .btn-primary:hover {
    background-color: #0255b3;
  }
  .btn-secondary {
    background-color: #f6f8fa;
    color: #24292e !important;
    border: 1px solid #e1e4e8;
  }
  .btn-secondary:hover {
    background-color: #e1e4e8;
  }
</style>

## Crafted for macOS

Focused, lightweight, and native tools built to enhance your everyday workflow.

<div class="app-grid">

  <!-- App 1 -->
  <div class="app-card">
    <div>
      <div class="app-header">
        <img class="app-icon" src="assets/icons/app1.png" alt="App 1 Icon" />
        <h3 class="app-title">App One</h3>
      </div>
      <p class="app-desc">Brief, impactful one-line elevator pitch highlighting the primary benefit of the app.</p>
    </div>
    <div class="app-actions">
      <a href="https://USERNAME.github.io/app-one-repo/" target="_blank" rel="noopener" class="btn btn-secondary">Learn More</a>
      <a href="https://apps.apple.com/app/idYOUR_APP_ID_1" target="_blank" rel="noopener" class="btn btn-primary">App Store ↗</a>
    </div>
  </div>

  <!-- App 2 -->
  <div class="app-card">
    <div>
      <div class="app-header">
        <img class="app-icon" src="assets/icons/app2.png" alt="App 2 Icon" />
        <h3 class="app-title">App Two</h3>
      </div>
      <p class="app-desc">Brief, impactful one-line elevator pitch highlighting the primary benefit of the app.</p>
    </div>
    <div class="app-actions">
      <a href="https://USERNAME.github.io/app-two-repo/" target="_blank" rel="noopener" class="btn btn-secondary">Learn More</a>
      <a href="https://apps.apple.com/app/idYOUR_APP_ID_2" target="_blank" rel="noopener" class="btn btn-primary">App Store ↗</a>
    </div>
  </div>

  <!-- App 3 -->
  <div class="app-card">
    <div>
      <div class="app-header">
        <img class="app-icon" src="assets/icons/app3.png" alt="App 3 Icon" />
        <h3 class="app-title">App Three</h3>
      </div>
      <p class="app-desc">Brief, impactful one-line elevator pitch highlighting the primary benefit of the app.</p>
    </div>
    <div class="app-actions">
      <a href="https://USERNAME.github.io/app-three-repo/" target="_blank" rel="noopener" class="btn btn-secondary">Learn More</a>
      <a href="https://apps.apple.com/app/idYOUR_APP_ID_3" target="_blank" rel="noopener" class="btn btn-primary">App Store ↗</a>
    </div>
  </div>

  <!-- App 4 -->
  <div class="app-card">
    <div>
      <div class="app-header">
        <img class="app-icon" src="assets/icons/app4.png" alt="App 4 Icon" />
        <h3 class="app-title">App Four</h3>
      </div>
      <p class="app-desc">Brief, impactful one-line elevator pitch highlighting the primary benefit of the app.</p>
    </div>
    <div class="app-actions">
      <a href="https://USERNAME.github.io/app-four-repo/" target="_blank" rel="noopener" class="btn btn-secondary">Learn More</a>
      <a href="https://apps.apple.com/app/idYOUR_APP_ID_4" target="_blank" rel="noopener" class="btn btn-primary">App Store ↗</a>
    </div>
  </div>

  <!-- App 5 -->
  <div class="app-card">
    <div>
      <div class="app-header">
        <img class="app-icon" src="assets/icons/app5.png" alt="App 5 Icon" />
        <h3 class="app-title">App Five</h3>
      </div>
      <p class="app-desc">Brief, impactful one-line elevator pitch highlighting the primary benefit of the app.</p>
    </div>
    <div class="app-actions">
      <a href="https://USERNAME.github.io/app-five-repo/" target="_blank" rel="noopener" class="btn btn-secondary">Learn More</a>
      <a href="https://apps.apple.com/app/idYOUR_APP_ID_5" target="_blank" rel="noopener" class="btn btn-primary">App Store ↗</a>
    </div>
  </div>

  <!-- App 6 -->
  <div class="app-card">
    <div>
      <div class="app-header">
        <img class="app-icon" src="assets/icons/app6.png" alt="App 6 Icon" />
        <h3 class="app-title">App Six</h3>
      </div>
      <p class="app-desc">Brief, impactful one-line elevator pitch highlighting the primary benefit of the app.</p>
    </div>
    <div class="app-actions">
      <a href="https://USERNAME.github.io/app-six-repo/" target="_blank" rel="noopener" class="btn btn-secondary">Learn More</a>
      <a href="https://apps.apple.com/app/idYOUR_APP_ID_6" target="_blank" rel="noopener" class="btn btn-primary">App Store ↗</a>
    </div>
  </div>

</div>

---

### Need Support or Have Feedback?
Contact us at [support@yourdomain.com](mailto:support@yourdomain.com) or view our [Privacy Policy](https://USERNAME.github.io/privacy-repo/).
