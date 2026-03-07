# PART1_Eniac A/B Testing Case Study

## Overview
This project explores how to increase conversions for Eniac’s iPhone 13 sales through A/B testing. The main focus is on improving the click-through rate (CTR) of the homepage “SHOP NOW” button, which is currently a bottleneck in the purchase funnel.

## Purchase Funnel
1. Visit Eniac’s website  
2. Click “SHOP NOW” button on iPhone 13 banner  
3. Select iPhone model  
4. Add to shopping basket  
5. Check-out  
6. Add delivery details  
7. Add payment details  
8. Confirm purchase  

> Current stats: 50,000 weekly visits → 30 confirmed iPhone sales (0.06% overall conversion)

## A/B Test Design
We tested four versions of the homepage button:

| Version | Description |
|---------|-------------|
| A       | Original button |
| B       | Red button |
| C       | Text changed to "SEE DEALS" |
| D       | Red + "SEE DEALS" |

### Key Considerations:
- Number of versions to test  
- Metrics for evaluation (CTR, conversion rate)  
- Random user assignment  
- Statistical significance  
- Test duration  

## Methodology
- Focus on top-of-funnel performance: clicks on “SHOP NOW”  
- Conversion rate = conversions ÷ previous step completions  
- Use statistical analysis to validate results  

## References
- [Optimizely – What is A/B Testing?](https://www.optimizely.com/optimization-glossary/ab-testing/)  
- [ABTasty – How to A/B Test Your Landing Page](https://www.abtasty.com/ab-testing-landing-page/)  
- *Trustworthy Online Controlled Experiments* – Google/LinkedIn/Microsoft  
- Basic Inferential Statistics concepts

## Outcome
Provides a data-driven approach to evaluate website design changes and increase sales via improved CTR and conversion rates.

PART 2_ENIAC_A/B Testing_click through rate analysis
Eniac Homepage A/B Testing – Click-Through Rate Analysis

## Overview
This project focuses on improving the click-through rate (CTR) of Eniac’s homepage “SHOP NOW” button for the iPhone 13. Despite high website traffic, only a small fraction of visitors click the button, creating a bottleneck in the purchase funnel.  

Using A/B testing, we evaluated four variations of the button to determine which design leads to the highest user engagement and conversions.

## Variants Tested
| Version | Description |
|---------|-------------|
| A       | White “SHOP NOW” (control) |
| B       | Red “SHOP NOW” |
| C       | White “SEE DEALS” |
| D       | Red “SEE DEALS” |

## Key Metrics
- **Click-through rate (CTR):** clicks ÷ total page visits (primary metric for test).  
- **Drop-off rate:** % of users who did not complete the conversion process after clicking.  
- **Homepage-return rate:** % of users returning to the homepage after clicking the button.  

## Hypotheses
- **Null (H₀):** All button versions have the same CTR.  
- **Alternative (H₁):** At least one version has a different CTR.  
- **Significance Level:** α = 0.05  
- **Minimum Detectable Effect:** 20% increase in CTR  

## Analysis
- **Chi-square test** was used to evaluate if differences in CTR were statistically significant.  
- **Post-hoc tests with Bonferroni adjustment** were used for pairwise comparisons to control Type I error.  
- Red buttons (B, D) performed worse, while white buttons (A, C) had higher CTRs.  
- **Winner:** Version C – White “SEE DEALS”  

## Outcome
Version C was selected as the best-performing variant, leading to improved CTR while maintaining favorable user behavior metrics. The project demonstrates the impact of **UX design and A/B testing** on driving website engagement and conversions.

## References
- [Optimizely – What is A/B Testing?](https://www.optimizely.com/optimization-glossary/ab-testing/)  
- [ABTasty – How to A/B Test Your Landing Page](https://www.abtasty.com/ab-testing-landing-page/)  
- *Trustworthy Online Controlled Experiments* – Google/LinkedIn/Microsoft  
- *Passion Driven Statistics* – Alan T. Arnholt  
