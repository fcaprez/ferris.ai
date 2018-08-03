# Use Case – BCBS248 and Intraday Liquidity Management

#### Customer: Large global wealth management institution
<br>

Intraday Liquidity Management creates the analytics driven infrastructure to report the banks intraday liquidity to 
the regulators (BCBS 248) as well as finding optimization opportunities of the banks liquidity and cash reserves.
<br><br>

> ## PROBLEM STATEMENT

"External regulatory pressure and internal processes based on our pre-subsidiarized structure have created a burning 
platform". Various drivers for Regulatory Compliance as well as Risk Control result in internal challenges:
* **Intraday Liquidity Transparency:** no complete, correct and timely view of IL usage and the underlying business drivers
* **Intraday Liquidity Risk Framework:** risk appetite and buffer setting are not based on actual understanding of the IL risk but rather follow regulator's minimum expectations
* **Real-time Intraday Liquidity Management:** there are only very limited manual means at hand to actively influence payment timing
<br>

> ## THE ILM SANDBOX

Sourcing payments and cash flow data from the banks various payments and interchange systems to obtain a global view 
of cash flow patterns and through data science applications determine optimization opportunities of the banks cash 
flow reserves:
* **Understand payments and cash flow patterns** throughout the year, by division, entity or payment types
* Apply data science methods to **determine optimization opportunities** on intraday payments and cash flow streams
* Provide **optimization scripts** to the operational ILM organization with **proposed measures** how **the banks cash 
flow reserves can be optimized**
<br>

## Project Approach & Onboarding
Small number of preparatory meetings to determine the scope, expected outcome, tools and data context:

Tools                   | Configuration                 
---------------------   | ---------------------
Major working tools:    | Jupyter, Pandas, Hive
Required environment:   | 11x VM with 4CPU, 96GB RAM, 1TB Disk Space

**Special requirements:** It is notable that for special security requirements data and end users had to be segregated 
into two physically separate network environments. For that purpose, one part of the Hadoop cluster was used to manage 
System Administration, Container Management and Data Sourcing and the other part was used to setup the analytical and
data science environment.
<br>

## Benefits
Project scope definition, staffing and ramp up in relatively short time span:
* Leverage existing Big Data platform in the red zone, able to load productive data
* Build Proof of Concept that can migrate later onto strategic solution
* Leverage early insights and results for optimizing cash flows
<br>
