# FE All Stars: Genie🧞 Can Autocomplete✍️ You🙊!
[![Databricks](https://img.shields.io/badge/Databricks-Solution_Accelerator-FF3621?style=for-the-badge&logo=databricks)](https://databricks.com)
[![Unity Catalog](https://img.shields.io/badge/Unity_Catalog-Enabled-00A1C9?style=for-the-badge)](https://docs.databricks.com/en/data-governance/unity-catalog/index.html)
[![Serverless](https://img.shields.io/badge/Serverless-Compute-00C851?style=for-the-badge)](https://docs.databricks.com/en/compute/serverless.html)

# TL;DR:
Users often don’t know what questions to ask in Genie rooms and sometimes asking vague questions, which lead to lower-quality responses and higher curator effort. Genie Autocomplete provides real-time, context-aware suggestions, guiding users to ask better questions, improving response quality, and reducing curator workload.

Genie Autocomplete makes question-asking easier and smarter by suggesting the most relevant questions as users type.

- **🧠Context-aware suggestions** – Drawn from room metadata and historical business questions asked by previous users.

- **⚡Real-time guidance** – Autocomplete surfaces options instantly as users type partial input.

- **🪞Clarity for vague queries** – Helps users reframe imprecise questions into clearer, more precise ones.

- **🤖Less curator effort** – Automatically generates useful suggestions, reducing the need for curators to manually create and maintain starter questions.

With Genie Autocomplete, users explore rooms more effectively, get higher-quality answers, and curators save time.


# Assets:
1. Backend part including ETL & Synthesis & VS index modules tested on Dogfood Workspace. Please reference the three notebooks under the root folder.
2. Genie Frontend UI and API part sit inside the Genie Eng codebase so we couldn't put here. Internal link of PR: https://github.com/databricks-eng/universe/pull/1292467
3. If you couldn't access the previous PR link, for reference about how to connect backend and frontend parts to enable Genie user's keyboard input's real-time semantic search autocompletion with debounce, I have included a full demo showcasing how to connect a Databricks App using the Dash framework to the 1. backend part to realize the goal. Repo: https://github.com/BlitzBricksterYY-db/cvs_POC_original_code

# Wiki:
1. internal link:
   - Hackathon link: https://databricks.atlassian.net/wiki/spaces/UN/pages/5351080471/Genie+Can+Autocomplete+You
   - FE-All-Stars link: https://databricks.atlassian.net/browse/FEIP-1572
3. Youtube demo video: https://www.youtube.com/watch?v=ipHh_NbOkS4


>------------------------------
---------------------------------you can skip below SolAcc template for now--------------------------------------
## Installation Guidelines

1. Clone the project you'd like to run into your Databricks Workspace

<img width="1726" height="677" alt="Screenshot 2025-07-23 at 11 05 25 AM" src="https://github.com/user-attachments/assets/55b1729f-ad07-420e-a271-843266abfb71" />

2. Open the Asset Bundle Editor in the Databricks UI

<img width="1120" height="665" alt="Screenshot 2025-07-23 at 11 06 12 AM" src="https://github.com/user-attachments/assets/d1f91256-eb8f-4456-8d88-c0a37b1bd4c5" />

3. Click on "Deploy"

<img width="1523" height="902" alt="Screenshot 2025-07-23 at 11 09 37 AM" src="https://github.com/user-attachments/assets/9564cbdd-c5c5-4210-bf27-2b19e6efc85b" />

4. Navigate to the Deployments tab in the Asset Bundle UI (🚀 icon) and click "Run" on the job available. This will run the notebooks from this project sequentially.

<img width="1527" height="880" alt="Screenshot 2025-07-23 at 11 10 13 AM" src="https://github.com/user-attachments/assets/0f612882-7123-449b-8349-1835bc59523c" />

## Contributing

1. **git clone** this project locally
2. Utilize the Databricks CLI to test your changes against a Databricks workspace of your choice
3. Contribute to repositories with pull requests (PRs), ensuring that you always have a second-party review from a capable teammate


## 📄 Third-Party Package Licenses - FILL IN WITH YOUR PROJECT'S OPEN SOURCE PACKAGES + LICENSING

&copy; 2025 Databricks, Inc. All rights reserved. The source in this project is provided subject to the Databricks License [https://databricks.com/db-license-source]. All included or referenced third party libraries are subject to the licenses set forth below.

| Package | License | Copyright |
|---------|---------|-----------|
| | | |
