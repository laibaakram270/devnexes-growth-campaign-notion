# Week 4: Analytics + CAC/LTV Forecast
**Project**: 30-Day Growth Marketing Campaign - Notion for Teams
**Goal**: Forecast CAC, LTV, ROI and define tracking with GA4
**Tools Used**: Google Sheets, Excel, GA4
**Date**: August 24, 2026
**Campaign Budget**: $500 for 30 days

---

## 1. Key Metrics & Assumptions
| Metric | Assumption | Source |
| --- | --- | --- |
| LinkedIn Clicks | 300 | $300 / $1 CPC |
| Google Clicks | 200 | $200 / $1 CPC |
| Total Clicks | 500 |  |
| Landing Page CVR | 20% |  |
| Trial Signups | 100 | 500 x 20% |
| Trial to Paid CVR | 15% |  |
| New Customers | 15 | 100 x 15% |
| Avg Revenue per Customer/mo | $15 | Notion Team Plan |
| Avg Customer Lifespan | 12 months |  |

## 2. CAC / LTV / ROI Model
**CAC = Total Ad Spend / New Customers**  
CAC = $500 / 15 = **$33.33**

**LTV = Avg Revenue x Lifespan**  
LTV = $15 x 12 = **$180**

**ROI = (LTV - CAC) / CAC**  
ROI = ($180 - $33.33) / $33.33 = **4.4x** or **440%**

**Payback Period**: $33.33 / $15 = 2.2 months

## 3. GA4 Tracking Plan
| Event | Trigger | Purpose |
| --- | --- | --- |
| `ad_click` | UTM click from LinkedIn/Google | Track ad source |
| `signup_start` | User clicks "Start Trial" | Funnel drop-off |
| `trial_complete` | Email confirmed | Lead captured |
| `paid_conversion` | Payment done | Revenue tracking |

UTM Structure: `utm_source=linkedin&utm_medium=paid&utm_campaign=agency_q3`

## 4. Conclusion
With $500 spend, we forecast 15 new customers, $180 LTV, and 4.4x ROI.  
Next steps: A/B test ad copies, retarget blog readers, reduce CAC to <$25.
