Report Generation Plan

  Date: YYYY-MM=DD

  Workflow Steps:

  1. Fetch Top 10 DeFi Projects
    - Query AIXBT for top 10 DeFi projects sorted by momentum score
  2. Create Project Infrastructure
    - Create a subfolder for each project (e.g., ./Aave/, ./Uniswap/)
  3. For Each Project, Generate Report:
  <ProjectName>-YYYY-MM-DD.md

  3. Report Structure:
    - Header - Project name, date, momentum score
    - Fundamental Analysis - From AIXBT (tokenomics, team, use case, TVL, etc.)
    - Technical Analysis - From AIXBT (price action, indicators, support/resistance)
    - Latest News - From Perplexity (today's news and developments)
  4. Update README.md
    - Add table/list with all reports and direct links for GitHub Pages compatibility

  Expected Output:

  DefiReports/
  ├── README.md (updated with links)
  ├── Project1/
  │   └── Project1-YYYY-MM-DD.md
  ├── Project2/
  │   └── Project2-YYYY-MM-DD.md
  └── ... (10 project folders)
