# Power BI Project 2 --- Sales & Purchase Performance Analysis

**A decision-support portfolio case study using synthetic retail sales
and purchasing data.**

> **Portfolio status:** Prepared for review. This project has not been
> approved for public publication. All figures below are demonstration
> results, not actual company performance.

## Executive overview

This Power BI project connects sales, purchasing, category performance,
profitability analysis, and intervention planning in one
decision-support model. It demonstrates how operational and procurement
data can support management decisions through transparent KPIs,
reconciliations, and scenario-based analysis.

The dataset is synthetic and covers **January 2018 through October
2019**. The purpose is to demonstrate analytical methodology rather than
report the performance of a real business.

## Business questions

-   How do sales, cost of goods sold, gross profit, and purchasing
    values compare?
-   Which categories contribute most to sales and profitability?
-   Which categories have negative gross margins and require management
    attention?
-   What is the simulated impact of margin-improvement interventions?
-   How can category master-data coverage and model consistency be
    validated?

## Validated reference KPIs

  Metric                                      Value
  ----------------------------- -------------------
  Net Sales                       1,087,604,416 HUF
  Cost of Goods Sold (COGS)         988,885,175 HUF
  Gross Profit                       98,719,241 HUF
  Net Purchase                    1,286,211,333 HUF
  Sales Quantity                      117,311 units
  Gross Profit Reconciliation                 0 HUF

These values are reference totals for the supplied synthetic workbook
and the validated Power BI model.

## Analytical components

### Sales and purchasing performance

The model combines synthetic sales and purchase facts with shared
analytical dimensions. It supports comparison of commercial performance,
purchase activity, and gross profit.

### Category performance and validation

Category-level analysis identifies margin distribution, including
loss-making categories. Validation queries check category-code coverage,
missing keys, duplicate codes, and sales/purchase alignment.

### Margin simulation and intervention strategy

Scenario controls and improvement assumptions illustrate the potential
financial effect of category-level actions. The simulations are
illustrative, not forecasts or evidence of realized savings.

### Action planning

The sample action plan demonstrates pricing optimization and supplier
negotiation workflows. Action owners, statuses, priorities, and expected
improvement values are synthetic examples.

### Data quality and reconciliation

The project includes checks for category relationship keys,
source/master coverage, and financial consistency. The reference
gross-profit reconciliation equals zero.

## Data and model scope

-   **1,000 synthetic sales records**
-   **1,300 synthetic purchase records**
-   **40 synthetic categories**
-   **18 synthetic suppliers**
-   **22 monthly periods** (January 2018--October 2019)
-   Power Query transformation, fact/dimension modeling, DAX measures,
    validation, and scenario analysis

## Report preview

Screenshots will be added after a separate review for publication
safety.

```{=html}
<!-- Add reviewed images under screenshots/ and reference them here. -->
```
## Repository contents

``` text
power-bi-project-2-sales-purchase-analysis/
├── README.md
├── Project_2_PORTFOLIO.pbix
├── Project_2_Synthetic_Data.xlsx
├── README_Project_2.txt
└── screenshots/
```

The screenshot directory is planned and may be empty during preparation.

## Open and refresh locally

1.  Install **Microsoft Power BI Desktop**.
2.  Download the PBIX, synthetic Excel workbook, and installation
    instructions.
3.  Open `Project_2_PORTFOLIO.pbix`.
4.  Go to **Home → Transform data → Edit parameters**.
5.  Set `pSourceFilePath` to the full local path of
    `Project_2_Synthetic_Data.xlsx`.
6.  Confirm the change and select **Apply changes** if prompted.
7.  Allow the model to load; use **Home → Refresh** if necessary.
8.  Compare the six reference KPIs above with the **Model Validation**
    report.

The PBIX may initially refer to the example location
`C:\PortfolioData\Project_2_Synthetic_Data.xlsx`. Users should replace
it with their own file path. See `README_Project_2.txt` for the
Hungarian installation guide.

## Interpretation and limitations

-   **Synthetic data:** No presented result represents actual company
    performance.
-   **Scenario assumptions:** Margin improvements and interventions are
    illustrative inputs, not measured outcomes.
-   **Historical scope:** The dataset covers a fixed 22-month
    demonstration period.
-   **Portability:** A local Excel path must be configured before
    refreshing on another computer.
-   **Power BI Desktop required:** GitHub does not render the PBIX as an
    interactive report.

## Publication and privacy

The repository is being prepared for a **private review workflow**.
Public distribution of the PBIX, workbook, and screenshots requires a
separate final approval, including consideration of any metadata that
cannot be fully inspected with the available tools.

## Portfolio context

**Data Compass / Data-Driven Strategy** --- applying operational,
procurement, and commercial experience to practical business
intelligence and management decision support.
