# Human Control Deadlocks on the GGE on LAWS
  
This project seeks to map the debate over the **deadlocks** on the operationalization of **human control** over Autonomous Weapon Systems (AWS) on the GGE on LAWS in 2024. It is part of a wider project conducted by the [InterAgency Institute](https://interagency.institute) that seeks to inform delegations in both Geneva and New York with more granularity in threshold concepts of the policy debate over AWS, focusing on International Security and Ethics. This project is financed by Stop Killer Robots. In this github page we make available a detailed explanation of our methodology to support our findings on the human control debate, and also the [database used](https://github.com/campaniluis/human_control_2024/blob/main/human_control_gge2024_db.csv) as a csv (comma separated value) file. We hope our work will lead to a more granular understanding of the discussions on the GGE and beyond. For any questions you may reach me at luis.campani@interagency.institute
  
  
## Methodology
From a database generated for our previous project containing all the discussions on the GGE on LAWS, we created a subcorpus based on a key-word list that would incorporate identified terms referring to human control. Retroactively, we can identify four clusters for the keywords: the ones using the word “control” explicitly; those referring to a specific human in control; those related to the concept of nominal human input, an idea proposed in CCW/GGE.1/2023/WP.2/Rev.1 by the State of Palestine [2]; and other similar terms identified in the database.
  
### Operationalization of Human Control Terminology
  
| Cluster | Key-words |
|---------|----------|
| **Specific terms using "control"** | "human control", "appropriate control" |
| **Specific human in control** | "human command and control", "direct supervision and control", "human command", "human responsible chain of command", "human intention", "human user", "human operator" |
| **Nominal Human Input** | "nominal human input", "nominal input", "human input" |
| **Other terms** | "human supervision", "human agency", "human involvement", "human interaction", "human intervention", "human validation", "human oversight", "meaningful human decision making", "intervention by the human user", "human responsibility", "human judgment" |
  
  
  
Our objective is to understand where are the caveats and oppositions to the operationalization of the different aspects of human control. For this end, we used the framework for the different aspects of human control proposed by Boulain et al (2020)[1].
  
We proceeded to identify the statements which belonged to each variable of the operationalization. With the sub-corpus assembled, we trimmed the statements to remove all sentences that didn’t talk about human control. Then, based on the framework … we’ve created a set of keywords to find statements that addressed the topic for each aspect of the operationalization. The key-words were also selected based on the explanations given by Boulain at al (2020) [1] of what each aspect of the operationalization refers to. 
  
### Boulain at al (2020) Human Control Operationalization + Key-Words
  
| Dimension | Aspect | Key-words |
|-----------|--------|-----------|
| **Who has human control?** | Operator | "operator" |
|  | Commander | "commander" |
|  | Command and Control | "command and control" |
| **Control over what?** | Critical Functions | "critical functions", "target", "engage" |
|  | Consequences of AWS | "consequence", "attack" |
|  | AWS as a Whole | "control over laws", "control of the system", "control over the system", "control of lethal", "control over weapon", "control over the weapon" |
| **When is control exerted?** | Study or Pre-Research and Development | "requirement" |
|  | Research and Development | "research", "develop" |
|  | Acquisition | "test", "evaluate", "validation", "verification", "legal review" |
|  | Deployment | "deployment", "plan", "operating procedure", "rules of engagement", "target profile", "train" |
|  | Use | "activate", "use" |
|  | Post-use | "effects", "assessment" |
|  | Life Cycle | "life cycle" |
| **How is control exerted?** | Parameters of use | "parameters" |
|  | Environment | "environment" |
|  | Human-Machine Interaction   | "human-machine", "human machine", "machine interaction" |
  

  
Then, we proceeded to categorization, by creating a classification of the position expressed through the statement ranging from “Support” to “Opposition”, and two supplementary categories to handle when the key-words matched a statement that didn’t address human control, or when it was unclear what the position was from the statement. 
  
### Classification for Statements on Operationalization of Human Control
  
| Result | Meaning |
|--------|---------|
| **[04] Support** | Expressed support to operationalizing this aspect of human control. |
| **[03] Direct use** | The operationalization of this aspect of human control is a necessary condition for what the delegation suggested. |
| **[02] Willing to Negotiate** | Expressed a caveat in the operationalization of the variable, but proposed a solution to overcome that caveat, while still operationalizing the variable. |
| **[01] Caveat** | Expressed a caveat in the operationalization of the variable, without proposing a solution to overcome that caveat, while still operationalizing the variable. |
| **[00] Oppose** | Expressed opposition to the operationalization of the variable. |
| **[98] Unclear** | Not possible to infer from statement, or more context was required to make an assessment. |
| **[99] Other Subject** | The statement did not operationalize human control for that dimension. |

  
  
The categorization was based on a two-step process, where it was first accessed if the key-words were related to the subject, if they were not, the 99 value was assigned to them. If they were related to the subject, we asked “What is the position on the operationalization of this variable?” and proceeded to the categorization using the other labels. To avoid pre existing bias regarding the position of each Delegation, the metadata (delegation, session, time, and date) were hidden during this process.
  
  
## Bibliographic References
[1] Boulain, V., Davison, N., Goussac, N., & Peldán Carlsson, M. (2020). Limits on autonomy in weapon systems: Identifying practical elements of human control. Stockholm International Peace Research Institute & International Committee of the Red Cross. Available at: https://www.sipri.org/publications/2020/policy-reports/limits-autonomy-weapon-systems-identifying-practical-elements-human-control
  
[2] State of Palestine. (2023, March 3). Working Paper. CCW/GGE.1/2023/WP.2/Rev.1. United Nations Office for Disarmament Affairs. Available at: https://meetings.unoda.org/meeting/67246/documents

