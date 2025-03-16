graph TD;
    A[Data Science Problem Statements] -->|Prescriptive Analytics| B[Smart Public Transport Route Optimization];
    A -->|Predictive Analytics| C[Early Identification of Financial Fraud in Small Businesses];
    A -->|Diagnostic Analytics| D[Root Cause Analysis for Supply Chain Disruptions in FMCG];
    
    B -->|Problem Statement| B1[Urban public transport faces inefficiencies due to static routes and schedules that don't adapt to changing commuter behavior. Develop an AI-driven system that dynamically adjusts bus/train routes based on real-time passenger demand, traffic conditions, and external events.];
    B -->|Expected Outcomes| B2[Integrate live GPS, traffic, and commuter data to optimize routes in real time.];
    B -->|Expected Outcomes| B3[Use reinforcement learning to recommend route diversions to reduce congestion.];
    B -->|Expected Outcomes| B4[Develop a simulation model that suggests changes in bus/train frequency based on historical and live demand trends.];
    B -->|Expected Outcomes| B5[Provide actionable recommendations to transit authorities to improve efficiency and reduce operational costs.];
    
    C -->|Problem Statement| C1[Small businesses often suffer from financial fraud that remains undetected for months. Predict potential fraudulent activities based on transaction data, expense patterns, and business anomalies before major financial damage occurs.];
    C -->|Expected Outcomes| C2[Use historical financial transactions to identify irregular spending behaviors.];
    C -->|Expected Outcomes| C3[Build a predictive model that flags businesses with a high risk of fraud.];
    C -->|Expected Outcomes| C4[Integrate external market factors (such as sudden tax filings, supply chain issues) into the model.];
    C -->|Expected Outcomes| C5[Provide an automated fraud alert system for small business owners.];
    
    D -->|Problem Statement| D1[FMCG companies face frequent supply chain disruptions due to unforeseen demand fluctuations, supplier delays, logistics bottlenecks, and regional economic factors. Traditional methods focus on post-incident reporting rather than real-time root cause identification. Build an AI-driven diagnostic analytics system that dynamically identifies patterns leading to disruptions and pinpoints the root cause to help supply chain managers take proactive action.];
    D -->|Expected Outcomes| D2[Analyze historical disruptions to detect recurring patterns in supply chain failures.];
    D -->|Expected Outcomes| D3[Develop a multi-variable anomaly detection model that flags potential supply chain risks.];
    D -->|Expected Outcomes| D4[Implement causal inference techniques to determine the true drivers of disruptions (e.g., weather impact, supplier performance, transport failures).];
    D -->|Expected Outcomes| D5[Create a real-time interactive dashboard that alerts managers to emerging risks and recommends countermeasures before failures occur.];
    D -->|Expected Outcomes| D6[Provide a self-learning system that refines its predictions based on newly incoming data.];
