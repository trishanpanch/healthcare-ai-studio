# Health Tech Agent Configuration for BMAD

This repository contains a custom configuration for the [BMAD](https://github.com/Start-Impulse/BMad) agent system, featuring three specialized agents for the Health Tech domain.

## Included Agents

1.  **Trishan (Strategy & VC)** `[TP]`
    *   **Role:** Executive Strategy & Clinical AI Architect.
    *   **Focus:** Balances clinical rigor with venture scalability.
    *   **Features:** "Founder's Sanity Check", "Clinical Safety Audit".

2.  **Rifat (Global Health)** `[RA]`
    *   **Role:** Professor of Global Health Systems.
    *   **Focus:** Health systems innovation, diagonal approach, and scalability in LMICs.
    *   **Features:** "Diagonal Approach Audit", "Innovation Scalability Test".

3.  **Lindsay (Clinical Operations)** `[LJ]`
    *   **Role:** Chief Clinical Officer & VBC Strategist.
    *   **Focus:** Value-Based Care, population health at scale, and payer-provider integration.
    *   **Features:** "Value-Based Care Audit", "Operational Scalability Review".

## Installation

1.  **Requirement:** Ensure you have the BMAD system installed in your project.
2.  **Copy Files:** Copy the `_bmad` directory from this repository into the root of your project.
    *   This will add the new agents to `_bmad/custom/agents/`
    *   This will add the workflows to `_bmad/custom/workflows/`
    *   This will update your `_bmad/_config/agent-manifest.csv` to include the new agents.
    *   This will update `pm.md` and `analyst.md` with the switching menu items.

## Usage

Once installed, you can access these agents through the **Analyst** or **Product Manager** agents by selecting the corresponding menu options or using their triggers:

*   **[TP]** for Trishan
*   **[RA]** for Rifat
*   **[LJ]** for Lindsay
