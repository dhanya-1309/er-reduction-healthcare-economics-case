# Reducing Unnecessary ER Visits: Healthcare Economics Case Study

A financial comparison of three options for reducing emergency room (ER) visits at Good Health Physicians, built in Excel, with a recommendation to management.

**Course:** BAN5650, Clark University (MBA, Business Analytics)
**Tools:** Excel (multi-sheet model with linked formulas), PowerPoint
**Files:** the Excel model and the PDF presentation are in this repo

## The problem
Good Health Physicians' members visit the ER at a rate of 525 visits per 1,000 members. Each ER visit costs $1,200. The goal is to bring the rate down to **450 visits per 1,000** within three years, at the lowest cost. Membership grows from 5,000 to 5,500 to 6,000 over the three years.

## The three options

| | Option 1: Additional practitioner | Option 2: Urgent care center | Option 3: Triage nurse line |
|---|---|---|---|
| Cost | $90,000 salary, rising 3% a year | $115,000 operating cost, rising 5% a year | $10,000 setup (Year 1), $5,000 marketing and $20,000 overhead per year |
| ER reduction | 10% in Year 1, 5% more in Year 2 | 15%, but only reaches 40% of members | 10% in Year 1, 5% more in Year 2 |
| Cost of replacement care | 50% of avoided visits become $75 office visits | Avoided visits become $150 urgent care visits | 30% go to urgent care ($150), 40% to primary care ($75), 30% need no other visit |

## How the model works
- **Core Sheet:** every assumption in one place (membership, baseline rate, visit costs, option inputs).
- **Option 1, 2 and 3 sheets:** each calculates baseline ER visits, avoided visits, gross savings, operating cost, replacement-care cost, net savings, and the Year 3 ER rate.
- **Summary Sheet:** compares the three options side by side and checks whether each one meets the 450-visit target.
- All sheets are linked by formulas, so changing an assumption on the Core Sheet updates every result.

## Results (3-year totals)

| | Option 1 | Option 2 | Option 3 |
|---|---|---|---|
| Gross savings | $1,401,750 | $623,700 | $1,401,750 |
| Total cost | $321,986 | $440,500 | $172,609 |
| **Net savings** | **$1,079,764** | **$183,200** | **$1,229,141** |
| Year 3 ER rate (per 1,000) | 446.3 | 493.5 | 446.3 |
| Meets 450 target? | Yes | No | Yes |

## Recommendation
**Option 3, the triage nurse line.** It meets the 450-visit target, has the lowest total cost of the three options, and has the highest net savings. Option 2 does not reach the target, because only 40% of members can reach the urgent care center. Option 1 also meets the target, but it costs almost twice as much as Option 3, mainly because of the practitioner's salary.

## Assumptions and limitations
- The ER reductions in Years 1 and 2 are applied to the baseline ER visits. The reduction in Year 3 is assumed to be 0%, meaning the program's effect holds but does not grow.
- Savings depend on a fixed $1,200 ER cost and fixed replacement-care costs. Real costs would vary.
- The model does not include the cost of members who ignore triage advice, or the quality-of-care impact of each option.
- Results are sensitive to the ER reduction percentages, which are assumptions from the case and not measured outcomes.

## What I did
I built the Excel model (linked Core, Option and Summary sheets), compared the three options against the 450-visit target, and
