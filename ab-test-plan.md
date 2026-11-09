# A/B Test Plan: CurlCraft Lab

## 1. The Page and Element
* **Page:** The Home page (`index.html`) at `https://fatima4206.github.io/curly-hair-care/`
* **Element Changed:** The main hero section headline text.
  * **Version A (Current):** "Mastering Type 3 Curl Care"
  * **Version B (Variant):** "Science-Backed Product Guides for Type 3 Curls"

## 2. Hypothesis
Changing the hero headline from "Mastering Type 3 Curl Care" to "Science-Backed Product Guides for Type 3 Curls" will increase the percentage of AI visitors answering "yes" to whether they would trust and explore the guide, because it explicitly highlights the scientific credibility upfront.

## 3. AI Model, Persona, and Prompt
* **Model:** Gemini 
* **Persona & Instructions (Given in every trial in a fresh conversation with no memory of earlier trials):** 
  > "You have Type 3B curly hair and are looking for reliable, non-heavy product recommendations. Read this home page and decide whether you would trust this site and click through to a product guide. Answer yes or no, then give one sentence of reasoning."
* **Assignment Method:** A random number generator will be used to assign each individual trial to Version A or Version B before running it, and the assignment will be recorded.

## 4. Primary Outcome
* A recorded binary response ("yes" or "no") measuring whether the AI visitor would trust the site and click through to a guide.

## 5. Sample Size and Timeline
* **Sample Size:** At least 50 trials for Version A and 50 trials for Version B (100+ total trials).
* **Expected Completion Date:** November 15, 2026.

## 6. Evaluation and Support
* **Comparison:** Compare the proportion of "yes" responses between Version A and Version B. 
* **Support Criteria:** If Version B yields a statistically significantly higher proportion of "yes" responses compared to Version A, the hypothesis is supported.
