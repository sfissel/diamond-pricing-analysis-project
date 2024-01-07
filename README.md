# Diamond Pricing Analysis Project
### Stephanie Fissel, Jack Gallagher, Lindley Slipetz, and Will Tenpas
#### July 2, 2023

## Data
### Dataset:
Contains information on over 1,000 diamonds, including carat, clarity, color, cut, and price.

### Variables:
* `carat:` Numerical variable measuring a diamond's weight.
* `clarity:` Categorical variable assessing small imperfections within a diamond.
* `color:` Categorical variable indicating the colorlessness of a diamond.
* `cut:` Categorical variable measuring how well-proportioned a diamond's dimensions are.
* `price:` Diamond price in USD.

## Summary of Findings
When purchasing diamonds, consumers often consider various factors such as cut, clarity, color, and carat. Our team analyzed a dataset containing information on 1,000 diamonds from Blue Nile, an online diamond seller, to assess the validity of claims made by Blue Nile regarding diamond pricing.

### Claims and Results
<b>1. Cut Importance:</b> Blue Nile claims that cut is a crucial factor in determining diamond prices. Our analysis suggests a slight increase in price with improved cut, but cut is not as influential as claimed.

<b>2. Clarity Impact:</b> Blue Nile suggests that better clarity leads to higher prices. Our findings indicate no clear association between clarity and price, except for flawless clarity, which lacks sufficient data for a robust analysis.

<b>3. Color Influence:</b> Blue Nile asserts that colorlessness increases diamond prices. While more colorless diamonds show a slight price increase, it is not strong enough to support Blue Nile's claim.

<b>4. Carat vs. Price:</b> Blue Nile claims a positive relationship between carat and price, and our analysis supports this claim. A 1% increase in carat corresponds to a 3.9% increase in price.

<b>5. Cut vs. Clarity Impact:</b> Blue Nile contends that cut affects price more than clarity. Our analysis confirms this, showing a stronger association between cut and price compared to clarity.

<b>6. Color and Cut Relationship:</b> Blue Nile suggests a relationship between the cut of the diamond and its color. Our analysis does not support this claim, indicating no noticeable difference in cut quality with changes in color.

<b>7. Cut and Clarity Correlation:</b> Blue Nile claims a positive relationship between cut and clarity. Our analysis contradicts this claim, showing inconsistent relationships between cut and clarity levels.

<b>8. Clarity Rarity:</b> Blue Nile claims that clearer diamonds are rarer. Our analysis, using price as a proxy for rarity, suggests no significant difference in rarity across clarity levels.

<b>9. "Buying Shy":</b> Blue Nile suggests savings by buying diamonds just below round carat numbers. Our analysis supports this claim, indicating significantly lower prices for diamonds just below certain carat thresholds.

## Claims Validation
We summarized and validated nine claims made by Blue Nile regarding diamond pricing. Our detailed analysis and visualizations provide insights into the relationships between various diamond characteristics and their impact on prices.

## Regression of Price Against Carat & Conclusions
We fit a simple linear regression for price against carat to test Blue Nile's claim of a positive relationship between carat and price. Our analysis supports this claim, with a significant positive relationship between carat and price. We addressed assumption violations through variable transformations, ensuring the reliability of our findings.

For further details, refer to the comprehensive analysis provided in the R Markdown Script file.

## Conclusion
Blue Nile's claim that price is positively related to carat is supported by our analysis.

##
<em> For a detailed analysis and visualizations, please refer to the R Markdown code script and report in this repository.</em>

