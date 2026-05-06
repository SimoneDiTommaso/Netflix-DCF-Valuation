# Netflix-DCF-Valuation
Equity valuation of Netflix Inc. using a five-year DCF model with R&amp;D capitalization

### Executive Summary
This project presents a rigorous intrinsic valuation of **Netflix Inc.** using a five-year Discounted Cash Flow (DCF) framework based on fiscal data from 2017–2021.

**Key Financial Outputs:**
*   **WACC:** 9.06%
*   **Cost of Equity ($K_e$):** 9.80%
*   **Adjusted Operating Income:** $7,094,118 (thousands)
*   **Invested Capital:** $24,514,516 (thousands)

### Technical Highlights
*   **R&D Capitalization:** Converted R&D expenses into a capital asset using a 5-year straight-line amortization, adjusting the book value of equity and operating income to reflect true economic reality.
*   **Bottom-up Beta:** Utilized an unlevered industry beta for the Entertainment sector (0.91), re-levered based on Netflix's specific D/E ratio (13.71%).
*   **Cost of Debt:** Estimated a pre-tax cost of debt of 4.96% using interest coverage ratios and corporate default spreads.

### Risk Modeling Integration
This valuation serves as the fundamental basis for my Master's Thesis research on tail-risk forecasting. I utilize the Expected Shortfall ($ES$) metric to assess potential downside:
$$ES_{t}(\alpha)=\left(1+\frac{1}{\alpha(\Omega_{t}(q_{t}(\alpha))-1)}\right)q_{t}(\alpha)$$


<img width="474" height="203" alt="02_RnD_Capitalization" src="https://github.com/user-attachments/assets/4401697b-e8d9-4302-9021-c1a3e13b4b10" />
<img width="1449" height="123" alt="01_WACC_Assumptions" src="https://github.com/user-attachments/assets/81ec770f-bc91-4ee8-a3c4-46bda4fd046b" />
<img width="926" height="25" alt="03_Growth_and_ROIC" src="https://github.com/user-attachments/assets/8762690b-a32a-4fb4-9f1b-b612799d5926" />
