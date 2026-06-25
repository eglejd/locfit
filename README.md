# LocFit 🌍
[www.locfit.egle.works](http://locfit.egle.works/)

**Scored Website Localization QA**

LocFit reviews localized website pages and tells content teams what to fix first. It acts as a first-pass triage tool with a human in the loop, catching genuine market-breaking errors (like mistranslations, broken tone, and wrong locale formatting) without punishing "good enough" content for not being perfect.

## How It Works
1. **Input:** Upload saved HTML or paste page code directly. 
2. **Analysis:** The engine checks for things that actually break a market launch (mistranslations, terminology, grammar, cultural fit).
3. **Transparent Scoring:** Runs on MQM 2.0 (the localization industry's standard). An AI model annotates each error and assigns an MQM dimension and severity. The app computes the score in-browser using MQM's exact penalty weights. 
4. **Actionable Reports:** Each page generates a scorecard splitting findings into **"Must Fix"** (critical failures) and **"Could Polish"** (minor improvements).
5. **Human-in-the-Loop:** Dismiss false alarms or approve fixes to write back to your TMS (future iteration).

## Built With
* **AI Engine:** Anthropic's Claude
* **Scoring Framework:** MQM 2.0 (themqm.org)

## Possible Future Roadmap
* **Seamless Site Sync:** Automated multi-page feeding of entire domains into the site-health view.
* **TMS Write-Back:** A functional approval step where human sign-offs automatically write fixes back to a Translation Management System (TMS).

*Built for the GenAI Localization Hackathon.*
