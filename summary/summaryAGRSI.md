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
- Risk acceptance criteria, consequence criteria, likelihood criteria, criteria for determening the level of risk **(Output)**

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

## Cost-Benefit Analysis (CBA)

**Cost Avoidance** is the money saved by using the defense strategy via the implementation of control.
**Benefit** is the value to the organization of using controls to prevent losses associated with a specific vulnerability (annualized loss expectancy (ALE))
The benefits of information security activities are directly related to cost savings, or cost avoidance.

**Asset valuation** is the process of assigning financial value or worth to each information asset.

**Single loss expectancy (SLE)** is the calculated value associated with the most likely loss from a single occurrence of a specific attack.
> SLE = asset value (AV) x exposure factor (EF)

**Annualized rate of occurrence (ARO)** indicates how often you expect a specific type of attack to occur

**Annualized loss expectancy (ALE)** a comparative estimate of the losses from successful attacks on an asset over one year.
> ALE = SLE x ARO

**Cost-benefit analysis (CBA)** is a form of feasibility study that compares the life-cycle cost of implementing a control mechanism against the estimated economic benefit that would accrue from the implementation of the control. Basically, it determines whether the benefit from a control alternative is worth the associated cost of the control.
> CBA = ALE(precontrol) - ALE(postcontrol) - ACS(annual cost of the safeguard)

**Alternatives to using CBA** are Benchamarking (seeking out and studying the practices used in other organizations that produce the results you desire), etc.

## Feasibility 

Measuring how ready an organization is for the introduction of controls is to determine the proposal’s:
- **Economic feasibility:** is the most common criterion and is used in CBA
- **Organizational feasibility:** examines how well the proposed InfoSec alternatives will contribute to the efficiency, effectiveness, and overall operation of an organization
- **Operational feasibility:** also known as behavioral feasibility, refers to user acceptance and support, management acceptance and support, and the system’s compatibility with the requirements of the organization’s stakeholders
- **Technical feasibility:** determining whether an organization already has or can acquire the technology necessary to implement and support them
- **Political feasibility:** considers what can and cannot occur based on the consensus and relationships among the communities of interest

## Net Present Value (NPV) & Return on Security Investement (ROSI)

NPV is the Present Value of all cash flows which means: 
> NPV = PV of future cash flows - PV of the cost of the investment

Present Value:
> PV = Cash flow / 1 + interest/discount rate

**Invest if NPV > 0**

> ROSI = (Monetary loss reduction - Cost of solution) / Cost of solution
> ROSI = (ALE - mALE - Cost of solution) / Cost of solution
> ROSI = (ALE * mitigation ratio - cost of solution) / Cost of solution

**Cons of ALE:**
- assumes losses are constant over time
- ignores other relevant characterisks of risk (Ex: dispersion)
- does not provide a rule for choosing the best investment
- does not compare the investement with the costs of cybersecurity improvments

#### Gleis Model

“the optimal amount to spend on information security never exceeds 37% of the expected loss resulting from a security breach"

## Costs

**Direct costs** can be clearly linked to specific breaches. (Ex: Personnel, hardware, software)
**Indirect costs** cannot be clearly linked to a particular breach, not with any reasonable degree of accuracy. (Ex: stock market value, overall cost of an IDS)

**Explicit costs** can be measured in an unambiguous manner. (Ex: encryption, firewalls, access controls, IDS, and other technically oriented IS activities)
**Implicit costs** are opportunity costs which cannot be measured without ambiguity (lost revenues – “reputation effect”)

## Business case for IS investements

1. Specify organizational cybersecurity objectives
2. Indentify alternatives for achieving cibersecurity objectives
3. Acquire data and examine each alternative identified
4. Conduct cost-benefit analysis and rank order the alternatives identified
5. Control (auditing)



























