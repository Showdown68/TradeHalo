<button id="toggleTheme">Toggle Theme</button>
<script>
  const button = document.getElementById("toggleTheme");
  button.addEventListener("click", () => {
    document.body.classList.toggle("dark");
    localStorage.setItem("theme", document.body.classList.contains("dark") ? "dark" : "light");
  });

  window.onload = () => {
    if (localStorage.getItem("theme") === "dark") {
      document.body.classList.add("dark");
    }
  };
</script>
<link rel="icon" href="static/branding/favicon.png" type="image/png">
<link rel="icon" href="static/branding/favicon.png" type="image/png">
<link rel="icon" href="static/branding/favicon.png" type="image/png">
[![View TradeHalo Site](https://img.shields.io/badge/site-TradeHalo-blue)](https://showdown68.github.io/TradeHalo/)
## 📊 Dashboard Previews

Here's a glimpse into TradeHalo's real-time dashboard capabilities:

![Hash Rate Monitor](static/branding/dashboard-hashrate.png)
*Consistent performance with AxeOS optimization.*

![Stale Share Alert](static/branding/dashboard-staleshares.png)
*Instant alerts for stale shares and system health.*

![Power Efficiency Chart](static/branding/dashboard-efficiency.png)
*Detailed metrics to maximize power-to-performance ratios.*
## 📊 Dashboard Preview

Explore the power behind TradeHalo’s real-time monitoring suite:

![Hash Rate Monitor](static/branding/Copilot_20250714_130018.png)
*Track your mining performance with live TH/s updates.*

![Stale Share Alert](static/branding/Copilot_20250714_131158.png)
*Instant alerts keep your rig running at max efficiency.*

![Power Efficiency Chart](static/branding/Copilot_20250714_131229.png)
*Visualize how every watt translates to trade power.*
<div style="display: flex; flex-wrap: wrap; gap: 20px;">
  <div style="flex: 1;">
    <img src="static/branding/Copilot_20250714_130018.png" alt="Hash Rate Monitor" />
    <p><em>Live TH/s performance monitoring</em></p>
  </div>
  <div style="flex: 1;">
    <img src="static/branding/Copilot_20250714_131158.png" alt="Stale Share Alert" />
    <p><em>Real-time alerting system</em></p>
  </div>
  <div style="flex: 1;">
    <img src="static/branding/Copilot_20250714_131229.png" alt="Efficiency Chart" />
    <p><em>Optimize every watt</em></p>
  </div>
</div>
## 🔌 Coming Soon: Plugin Modules

Explore the features rolling out soon to supercharge your dashboard:

| Module Name        | Description                                     | Status     |
|--------------------|-------------------------------------------------|------------|
| Pool Switcher      | Swap mining pools with a single click           | 🔄 In Dev   |
| Latency Watchdog   | Tracks server response time and flags delays    | 🧠 Planned  |
| Profit Estimator   | Converts mining output to fiat in real-time     | 💰 Beta     |
| Mobile Sync        | View stats from your phone (AxeOS Companion)    | 📱 In Dev   |
## 🔌 Plugin Modules (Coming Soon)

TradeHalo is built for extensibility. These modules will plug in seamlessly to expand your rig’s intelligence:

| ⚙️ Plugin         | 🔍 Functionality                                      | 🚧 Status   |
|------------------|--------------------------------------------------------|------------|
| Pool Switcher    | Swap mining pools instantly without downtime           | 🛠️ In Dev   |
| Latency Watchdog | Track pool ping, alert on slow response times          | 🧠 Planned  |
| Profit Estimator | Converts earnings to fiat or token in real time        | 💰 Beta     |
| Mobile Sync      | AxeOS dashboard on mobile via TradeHalo Companion App  | 📱 In Dev   |
| Plugin Loader    | Enables dynamic community-built plugin support         | 🔌 Concept  |
<button id="themeToggle">🌓 Toggle Theme</button>
<script>
  const toggle = document.getElementById("themeToggle");
  toggle.addEventListener("click", () => {
    document.body.classList.toggle("dark");
    localStorage.setItem("theme", document.body.classList.contains("dark") ? "dark" : "light");
  });

  window.onload = () => {
    if (localStorage.getItem("theme") === "dark") {
      document.body.classList.add("dark");
    }
  };
</script>
## 🔌 Plugin Modules (Coming Soon)

TradeHalo is built to adapt. These add-ons will expand your rig's insight and control:

| ⚙️ Plugin         | 🔍 Functionality                                      | 🚧 Status     |
|------------------|--------------------------------------------------------|--------------|
| Pool Switcher    | Swap mining pools instantly with zero downtime         | 🛠️ In Dev     |
| Latency Watchdog | Tracks pool ping and flags instability                 | 🧠 Planned    |
| Profit Estimator | Converts earnings to fiat or token
<script>
  const toggle = document.getElementById("themeToggle");
  toggle.addEventListener("click", () => {
    document.body.classList.toggle("dark");
    localStorage.setItem("theme", document.body.classList.contains("dark") ? "dark" : "light");
  });

  window.onload = () => {
    if (localStorage.getItem("theme") === "dark") {
      document.body.classList.add("dark");
    }
  };
</script>
<style>
  @keyframes pulse {
    0% { filter: drop-shadow(0 0 0px #58a6ff); }
    50% { filter: drop-shadow(0 0 4px #58a6ff); }
    100% { filter: drop-shadow(0 0 0px #58a6ff); }
  }
<button onclick="document.getElementById('dashboardPreviews').scrollIntoView({ behavior: 'smooth' })">📊 Dashboard ↓</button>

  link[rel="icon"] {
    animation: pulse 2s infinite ease-in-out;
  }
</style>
## 📊 Dashboard Previews
<div id="dashboardPreviews">
…your content…
</div>
button:hover {
  box-shadow: 0 0 8px rgba(88,166,255,0.6);
}
