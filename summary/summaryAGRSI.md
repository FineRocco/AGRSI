## Terms and Definitions

- **Risk**: The effect of uncertainty on objectives
- **Level of risk:** magnitude of risk, which is the combination of consequences and likelihood
- **Consequence:** Also known as impact, is the outcome of the event affecting objectives
- **likelihood:** Is the chance/probability of happening
- **Event:** occurence or change of a particular set of circumstances
- **Risk Criteria:** is the terms of reference which the significance of a risk is evaluated
- **Risk management:** coordinated activities to control an organization with regard to risk
- **Risk management policy:** statement of overall intentions and direction of an organization related to risk management
- **Risk management framework:** set of components that provide the foundations and organizational
arrangements for designing, implementing, monitoring, reviewing and continually improving risk management throughout the organization
- **Risk management plan:** scheme within the risk management framework specifying the approach, the management components and resources to be applied to the management of risk
- **Risk owner:** person or entity with the accountability and authority to manage a risk
- **Risk management process:** systematic application of management policies, procedures and practices to the activities of communicating, consulting, establishing the context, and identifying, analyzing, evaluating, treating, monitoring and reviewing risk
- **Risk analysis:** process to comprehend the nature of risk and determine the level of risk
- **Risk evaluation:** process of comparing the results of risk analysis with the risk criteria to determine whether the risk and/or its magnitude is acceptable or tolerable
- **Risk treatment:** process to modify the risk

## Accountability for Risk management
All communities of interest should be involved in the management of risks:
- InfoSec members best understand the threats and attacks that introduce the risk (They usually take leadership to adress the risk)
- IT members must help to build the secure systems and ensure their safe operation
- Manangement and users play a part in the early detection and response process

**Top mamangement of the organization is resoponsible/accountable for the risk management program**

**StakeHolders:** Person or organization that can affect, be affected by, or perceive themselves to be affected by a decision or activity.

## Risk Management Process

![](/summary/figures/RMprocess.PNG)

### Establishing the Context

The context is the understanding of the **external and internal environments**, understanding the **RM process** (definded by the framework), understanding the **organizations's risk apetite statement**(will be used for appropriate risk treament):

- Identifying basic requirements of interested parties
- Applying risk assessment (knowing how to)
- Establishing and maintaining information security risk criteria (Qualitive, Quantitive or Hybrid approach)
- Risk acceptance criteria, consequence criteria, likelihood criteria, criteria for determing the level of risk

### Risk Identification (Risk Assessment)

The risk identification process begins with the identification and cataloguing of information assets.
An **information asset** is any asset that collects, stores, processes, or transmits information.

**Threat identification** - process of assessing potential exploitation of weaknesses in each information asset.

Manager must: 
1. identify the organization’s information assets
2. categorize them into useful groups (Hardware, Software, and Network Assets & People, Procedures, and Data Assets)
3. classify them (Assessing Values for Information Assets using weighting criteria questions)
4. and prioritize them by overall importance (Listing Assets in Order of Importance)

**Output:** a prioritized list of assets & a prioritized list of threats facing those assets which combined together create TVA worksheet.

### Risk Analysis (Risk Assessment)

Risk analysis in IS is a process that assigns a comparative risk rating or score to each information vulnerability/asset. (Assessing likelihood, Potential impact on asset value, Percentage of Risk Mitigated by Current Controls)

> Risk = likelihood of the occurrence of a vulnerability x the value of the asset - the percentage of risk mitigated by current controls + the uncertainty of current knowledge of the vulnerability. (Whitman Expression)

**Outputs:** Risk ranking worksheet

### Risk Evaluation (Risk Assessment)

Apply the risk acceptance criteria to determime whether or not the risks can be accepted. If cannot, they should be prioritized for treatment.

**Output:** a list of prioritized risks with scenarios that lead for those risks; whether a risk treatment is required; suggestions for risk management.

### Risk Treatment

Envolves choosing one of the basic control strategies:
- **Modification (Defense):** attempts to prevent the exploitation of the vulnerability (Ex: countering threats, removing vulnerabilities in assets, limiting access to assets, and adding protective safeguards)
- **Modification (Mitigation):** attempts to reduce the damage caused by a realized incident or disaster (Incident response (IR) plan, Disaster recovery (DR) plan, Business continuity (BC) plan, Crisis management (CM) plan)
- **Sharing (Transferal):** attempts to shift the risk to other assets, other processes, or other organizations (Purchasing insurance, Outsourcing to other organizations, Implementing service contracts with providers)
- **Retention (Acceptance):** the decision to do nothing to protect an information asset from risk and accept the outcome (implemented when the cost of protecting an asset does not justify the expense)
- **Avoidance (Termination):** - based on the organization’s need or choice not to protect an asset (must be a conscious business decision)

**Output:** Residual risk

![](/summary/figures/RiskTreatment.PNG)

### Risk Acceptance

The risk treatment plan and residual risk assessment is subjected to the acceptance decision (risk apetite) of the organization’s managers.

**Output:** a list of accepted risks with justification for those that do not meet the organization’s normal risk acceptance criteria.

## Managing Risk

**Residual risk** is the amount of risk that remains after the organization has implemented policy, education and training, and technical controls and safeguards. (ideal to be lower than the organization's risk apetite)
**Risk Apetite** also known as Risk Tolerance, is the quantity and nature of risk that organizations are willing to accept.

The key is for the organization to find balance in its decision-making processes and in its feasibility analyses. Rules of thumb for selecting a strategy:

- When a vulnerability exists in an important asset - implement security controls to reduce likelihood of a vulnerability being exploited
- When a vulnerability can be exploited - apply layered protections, architectural designs, and administrative controls to minimize risk
- When the attacker’s potential gain is greater than the costs of attack - apply protections to increase attacker’s cost
- When the potential loss is substantial - apply technical and nontechnical protections to limit the extent of attack

**Controls should be monitored and measured on an ongoing basis to determine effectiveness**























