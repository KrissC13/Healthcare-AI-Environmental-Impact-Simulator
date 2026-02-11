README — Healthcare AI Environmental Impact Simulator

Overview

The Healthcare AI Environmental Impact Simulator is an interactive web-based tool designed to estimate and visualize the environmental footprint of healthcare artificial intelligence deployments.

The simulator models energy consumption, carbon emissions, and water usage based on configurable AI system parameters and maps outputs to governance and sustainability frameworks including:
	•	NIST AI Risk Management Framework (AI RMF)
	•	AHIMA Information Governance Principles
	•	ESG and Greenhouse Gas Protocol reporting domains

This tool is designed for healthcare executives, AI governance leaders, informatics professionals, and sustainability teams evaluating AI adoption decisions.

⸻

Purpose

Healthcare organizations are rapidly adopting AI across imaging, documentation, and generative workflows. However, environmental impact is rarely quantified during procurement or governance review.

This simulator helps decision-makers:

Estimate environmental impact before deployment
Compare architecture and scale scenarios
Support governance and ESG reporting
Translate technical AI metrics into executive decision signals

⸻
 Key Features

Environmental Impact Modeling
	•	Energy consumption (kWh)
	•	Carbon emissions (kg CO₂)
	•	Water consumption (Liters)

Interactive Visual Dashboard
	•	KPI summary cards
	•	Benchmark comparison bar charts
	•	Architecture ecological profile radar charts
	•	Real-world translation metrics (trees, miles, device charges)

 Scenario Configuration Controls

Users can adjust:
	•	AI architecture profile
	•	Model parameter count
	•	Monthly usage volume (duty cycle)
	•	Data center efficiency (PUE)

Auto-Configuration Wizard

Guided setup using:
	•	AI function type (Imaging, Documentation, Generative)
	•	Deployment scale (Department vs Enterprise)
	•	Model type (Task-specific vs Foundation)

 Governance Alignment Indicators

Outputs mapped to:
	•	NIST AI RMF risk tiering
	•	AHIMA governance review signals
	•	ESG materiality risk flags

⸻

Technical Stack

Frontend
	•	HTML5
	•	Tailwind CSS
	•	Chart.js
	•	Font Awesome
	•	Google Fonts (Inter)

Simulation Logic

Client-side JavaScript modeling:

Environmental constants include:
	•	Energy intensity per parameter
	•	Grid carbon intensity
	•	Water intensity per kWh

⸻

Core Simulation Inputs

Variable	Description
Parameter Count	Model size in millions of parameters
Duty Cycle	Monthly inference volume
PUE	Data center efficiency factor


⸻

 Core Outputs

Metric	Unit
Energy	kWh
Carbon	kg CO₂
Water	Liters

Derived impact translations:
	•	Equivalent miles driven
	•	Equivalent phone charges
	•	Tree offset requirements

⸻

 Healthcare Use Cases

AI Procurement Evaluation

Compare vendor architectures before contract approval.

Governance & Risk Committees

Provide environmental risk context alongside clinical and financial metrics.

ESG Reporting Support

Translate AI infrastructure impact into sustainability reporting metrics.

Strategic Infrastructure Planning

Support cloud region, hardware, and scaling decisions.

⸻

 Intended Audience
	•	Healthcare CIO / CTO
	•	AI Governance Committees
	•	Sustainability & ESG Officers
	•	Health Informatics Leaders
	•	Digital Health Strategy Teams

⸻

 How to Run

Option 1 — Local
	1.	Download repository
	2.	Open index.html in browser

Option 2 — Static Hosting

Deploy via:
	•	GitHub Pages
	•	Netlify
	•	Azure Static Web Apps
	•	AWS S3 Static Hosting

⸻

 Limitations
	•	Uses average grid carbon assumptions
	•	Does not model real-time cloud regional variability
	•	Does not yet include hardware lifecycle emissions
	•	Intended for scenario comparison, not regulatory reporting

⸻

Roadmap

Planned future enhancements:
	•	Cloud region carbon intensity integration
	•	Hardware class modeling (GPU vs CPU vs TPU)
	•	Cost + environmental dual optimization modeling
	•	API export for Tableau / BI pipelines
	•	Scenario batch comparison mode

⸻

 Framework Alignment

Framework	Alignment Area
NIST AI RMF	Risk visibility and mitigation planning
AHIMA IG	Responsible data and AI lifecycle stewardship
ESG / GHG Protocol	Scope 2 / Scope 3 digital infrastructure impact


⸻

 Author

Kristen Coote
Master of Health Informatics & Health Information Management
Healthcare AI Governance and Sustainable AI Strategy

⸻

 License

(Choose one when you publish)

Recommended:
	•	MIT License → if you want max reuse
	•	Apache 2.0 → if you want patent protection
