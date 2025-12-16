---
editor_options: 
  markdown: 
    wrap: 72
---

@readme

# Data visualization competition

## The UK Co-Benefit Atlas

The [UK Co-Benefit Atlas](https://ukcobenefitsatlas.net), developed by
the [Edinburgh Climate Change Institute](https://edinburghcentre.org) is
an interactive visual interface for communicating the co-benefits of
reaching net zero across the UK.

Climate actions are designed to lower greenhouse gas (GHG) emissions but
the gains for society reach further. The actions we need to undertake to
reduce fossil fuel emissions often have significant and positive impacts
on health, economy and society, as well as the environment. The team at
ECCI have been modelling these wider benefits (‘co-benefits’) to make
the positive case for climate action.

These values are estimates of these wider socio-economic impacts from
the UK reaching net zero by 2050. The data are monetised figures,
representing the value to individuals and society across 11 co-benefit
types from following the actions set out by the [UK Climate Change
Committee](https://www.theccc.org.uk/publication/the-seventh-carbon-budget/).
They represent improved quality of life, reduced air pollution, better
health outcomes and safer, more comfortable homes. They have been
modelled at the local level to include local context, for example
rurality, wealth and demographics.

*Note.* Information extracted from [The Data
Lab](https://thedatalab.com/data-visualisation-competition-2025/).

## Data questions

**Research Question 1:** How much does each Scottish local authority
benefit from net zero?

-   Which authorities benefit the most from reaching net zero? Are there
    meaningful differences between groups of local authorities (e.g.,
    urban vs. rural)?

-   ***TO DO: plot the benefits per person for each local authority as a
    map***

**Research Question 2:** When does each local authority benefit from net
zero?

-   Which authorities benefit at what time on the path to net zero?
    Which authorities have an early pay-out, late pay-out, constant
    pay-out? Are there meaningful differences between groups of local
    authorities (e.g., urban vs. rural)?

-   Do authorities need to invest up front, or do they get a pay out?

-   In what year does the local authority receive 25%, 50%, and 75% of
    the pay out per person?

**Research Question 3:** What should local authorities do with the
money?

-   How much does reaching net zero cost?

### Data specifications

Only use data from Scotland (remove all English and Welsh local areas).

Present all results as money per person to make the findings more
tangible.

Different levels of data:

-   **Geographical:** Scotland (g = 1), local authorities (g = 32),
    small areas (g = 139,520)

-   **Time:** across years (t = 1), each year (t = x)

-   **Factors:** across factors (f = 1), each factor (f = 11)

-   **People:** across the population, for each person

## Exploratory Data Analysis

**Co-benefits outweigh associated costs:** Across all Scottish local
authorities, the sum of anticipated costs for reaching net zero is
approximately XXX until 2050. In contrast, the sum of estimated benefits
for reaching net zero is approximately XXX until 2050. Per person, the
costs are XXX whereas the benefits are XXX.

**Co-benefit ranking does not vary much (or at all) across Scottish
local authorities:** Scottish local authorities receive most benefits
from the same factors (i.e., physical acitivity, noise, air quality).
Similarly, Scottish authorities face most costs from the same factors
(i.e., hassle cost, congestion, road safety).

**Total co-benefits per person from 2025 up until 2050:**

| Mean     | Median   | SD      | Min      | Max      |
|----------|----------|---------|----------|----------|
| £2419.09 | £2343.76 | £365.21 | £1695.50 | £3195.00 |

**Research questions: What? \> So what? \> Now what?**

What? -what are the top 5 (top 3) co-benefits for different areas in
Scotland? -split into urban vs rural -what are the top 5 (top 3)
co-benefits that will introduce the most cost in Scotland?

So what? -what types of benefits do we get in which areas? are there
areas with more benefits than others? -every area in Scotland benefits
from net zero, though to a different extent and through different
pathways

Now what? -can we make this more equal? can we supercharge from one area
to another? -how can we supercharge some of them? \> can we do some sort
of intervention to increase them? -can we map system-level interventions
to co-benefits?

############################################################################### 

Boundaries: -Scotland only \> use `lookups.xlsx` to filter Scottish area
codes -Add label/ classifier for urban, rural, and in-between? -get this
from Dominik's dataset

Notes: -some co-benefits are negative and some are positive? \> some
factors represent benefits whereas others describe costs

Comments: -top 5 (and top 3) co-benefits are the same across Scottish
local authorities

### Data Used

I used the full, detailed dataset containing x variables and x rows.
