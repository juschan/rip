# RIP
Realistic Insurance Portfolio

### Description
Realistic Insurance Portfolio (RIP) is a set of data files from a simulated an insurance portfolio simulator (IPS). The csv format data files include data for policyholders, policies, claims, channels and products. These data files have primary and foreign id keys to identify the relationship between the various 'entities'.

IPS can be found [here](https://github.com/juschan/ips).
Use hash ending 95a5e92.


### Simulated Scenario
Apex is a young insurance company that started selling various insurance products from 1st January 2007. The products sold include Term Life, Whole of Life, Accelerated Critical Illness and Hospitalization policies. It sells via 3 channels:
* banks (ie. 2 banks each with 3 bank branches)
* Independent Financial Advisors (IFA)
* Agents

Policyholders can voluntarily choose to join Apex's Fab wellness programme, which rewards Fab participants with 'tokens' if they reach daily fitness goals (ie. 10,000 steps). These tokens can be redeem with Apex's various retail partners. 

### Data
The data consists of data from policies sold from 1st January 2007 till 31st December 2017, consisting of 1.2 million policyholder and their corresponding records as such:
* policyholders.csv - policyholder data including gender, smoking status, underwriting status etc.
* policies.csv - each policyholder can purchase several policies over time.
* claims.csv - claims are linked to policies.
* channels.csv - Each policy is sold via one particular channel
* products.csv - Each policy is linked to a particular product. 