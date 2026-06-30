# sales-intelligence-dashboard
Sales Intelligence Dashboard

A single-page sales analytics dashboard built with plain HTML, CSS, and JavaScript. It pulls a sales team's most important numbers into one dark-themed interface — revenue, quota attainment, pipeline health, rep performance, and win/loss trends — so the story behind the data is readable at a glance rather than buried in a spreadsheet.

Overview
I built this to see how far a clean, dependency-light front end could go in presenting real sales reporting. The goal was a dashboard that feels like a finished internal tool — fast, organized, and pleasant to navigate — without reaching for a heavy stack to get there. It currently runs on representative sample data, so the structure and behavior are fully in place and ready to be wired to a live data source.

Features
Collapsible sidebar navigation across nine dedicated views: Dashboard, Pipeline, Forecasting, Accounts, Rep Performance, Win / Loss, Territory View, Integrations, and Preferences.
KPI summary cards for headline metrics including gross revenue, quota attainment, pipeline velocity, and average deal size, each shown against its prior period or target.
Interactive charts rendered with Chart.js for visualizing trends over time.
Sortable data tables breaking down performance by sales rep and by region (closed revenue, win rate, active pipeline, average cycle, and status).
Responsive dark UI with a consistent design system driven by CSS custom properties, so colors, spacing, and typography stay uniform throughout.

Tech Stack
HTML5 for structure
CSS3 (custom properties, Flexbox) for layout and theming
Vanilla JavaScript for navigation and interactivity
Chart.js 4.4.1 for data visualization, loaded via CDN

Project Status
he dashboard currently runs on built-in sample data to demonstrate the full layout and interactions. The natural next step is connecting it to a live API or database so the metrics update in real time.
Roadmap
Connect to a live data source (REST API or database)
Add date-range and filter controls
Persist user preferences between sessions
Export reports to PDF or CSV
