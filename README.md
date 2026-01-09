description: |
  This dataset provides firm-year measures of artificial intelligence (AI)
  engagement derived from textual analysis of U.S. firms’ annual 10-K filings.
  The AI intensity measure captures the extent to which firms discuss AI-related
  technologies, infrastructure, and applications in regulatory disclosures.
sources:
  - name: SEC EDGAR
    web: https://www.sec.gov/edgar.shtml
resources:
  - name: ai_intensity_firm_year
    path: data/ai_intensity_firm_year.csv.zip
    format: zip
---

## Overview
This dataset contains firm-level measures of AI engagement constructed from
textual disclosures in Form 10-K filings. The AI intensity metric is designed
to be comparable across firms, industries, and time, and captures firms’
strategic exposure to artificial intelligence as an operational and
risk-transforming technology.

## Sample
- Coverage: U.S. publicly listed firms
- Identifier: Central Index Key (CIK)
- Period: 2010–2024
- Frequency: Firm-year

## Data Description
The dataset includes firm-year observations with a unique CIK-year pair.
Key variables include measures of overall AI engagement and subcomponents
reflecting different dimensions of AI-related disclosures.

The data are provided as a compressed CSV file due to file size constraints.

## Intended Use
This dataset is intended for academic research on artificial intelligence,
corporate strategy, firm value, and risk. It is suitable for replication,
extension, and related empirical analyses in finance, accounting, and
economics.

## Citation Requirement
**If you use this dataset, you must cite the following paper:**

Dong, F., Doukas, J., and Zhang, R.  
"Artificial Intelligence Engagement, Firm Value, and Risk Transformation", 
Working paper.

Failure to cite the above paper when using this dataset is not permitted.

## Contact
For questions or clarification regarding the data construction, please
contact the authors.
