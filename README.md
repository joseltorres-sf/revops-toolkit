RevOps Toolkit & Portfolio

A suite of automated web-based tools designed to streamline Deal Desk operations, SaaS pricing calculations, and contract management workflows. Developed by Jose Torres.

🚀 Overview

This repository contains a collection of single-file applications built to solve specific friction points in the B2B SaaS sales cycle. These tools bridge the gap between complex contract logic and operational efficiency.

The Suite

1. 📅 Contract Timeline Visualizer

Problem: It's difficult to visualize how multiple customer agreements (MSAs, Order Forms, Amendments) overlap.
Solution: An interactive Gantt-chart style visualizer that maps:

Underlying Agreements vs. New Mapped Agreements.

Deal types: Consolidations, Divestitures, Early Renewals, and True-ups.

Visual cues for contract overlap and gaps.

2. 💰 Commission Splitter

Problem: Calculating sales commissions on complex deals with multiple reps and "Supersede & Replace" scenarios is error-prone.
Solution: A calculator that:

Splits ACV percentages among multiple stakeholders while validating the 100% total.

Incremental ACV Mode: Automatically carves out "Renewal Baselines" to ensure commissions are paid only on Net New revenue.

3. 🧮 Proration & Co-Term Calculator

Problem: Calculating "stub periods" for add-ons to align with a master agreement end date usually involves manual spreadsheet math.
Solution: A robust calculator that:

Generates accurate stub fees based on day-count logic.

Produces a full Year-over-Year Fee Schedule.

Applies annual Uplift/CPI caps automatically to future renewal years.

Toggles between ACV (Annual Value) and TCV (Total Contract Value) inputs.

4. ⏳ Day Counter

Problem: Quick date math for contract terms often requires context switching.
Solution: A simplified utility to calculate the exact duration (Days, Months, Years) between two dates, including business day logic.

🛠️ Tech Stack

Core: Vanilla HTML5 & JavaScript (ES6+)

Styling: Tailwind CSS (via CDN)

Icons: Lucide Icons

Architecture: Single-file components for portability and ease of deployment. No build step required.

📦 How to Run

Clone the repository:

git clone [https://github.com/your-username/revops-toolkit.git](https://github.com/your-username/revops-toolkit.git)


Navigate to the directory.

Open portfolio_home.html in any modern web browser to launch the Launchpad.

From the Launchpad, you can open any of the individual tools.

👤 Author

Jose Torres
Product Manager / RevOps Manager

📍 Bay Area / Sacramento

📧 joseluistorres@outlook.com

🔗 LinkedIn

© 2026 Jose Torres. All rights reserved.
