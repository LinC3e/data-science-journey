# Basic Definition
> The word "ethics" comes from the Greek word "ethikos" (and its root "ethos") meaning character or moral nature.

**Ethics** is about the shared values and moral principles that govern our behavior in society. Ethics is based not on laws but on 
widely accepted norms of what is "right vs. wrong". However, ethical considerations can influence corporate governance initiatives and government regulations 
that create more incentives for compliance.


- **Data Ethics** is a new branch of ethics that "studies and evaluates moral problems related to data, algorithms and corresponding practices". Here, "data" focuses 
on actions related to generation, recording, curation, processing, dissemination, sharing, and usage, "algorithms" focuses on AI, agents, machine learning, and robots, 
and "practices" focuses on topics like responsible innovation, programming, hacking, and ethics codes.
___
- **Applied Ethics** is the practical application of moral considerations. It's the process of actively investigating ethical issues in the context of real-world actions, 
products and processes, and taking corrective measures to make that these remain aligned with our defined ethical values.
___
- **Ethics Culture** is about operationalizing applied ethics to make sure that our ethical principles and practices are adopted in a consistent and scalable manner across the 
entire organization. Successful ethics cultures define organization-wide ethical principles, provide meaningful incentives for compliance, and reinforce ethics norms by encouraging
and amplifying desired behaviors at every level of the organization.
___

# Ethics Concepts
## *1.Ethics Principles*

Every data ethics strategy begins by defining ethical principles - the "shared values" that describe acceptable behaviors, and guide compliant actions, in our data & AI projects.
You can define these at an individual or team level. However, most large organizations outline these in an ethical AI mission statement or framework that is defined at corporate levels 
and enforced consistently across all teams.

*Example: Microsoft's Responsible AI mission statement reads: "We are committed to the advancement of AI-driven by ethical principles that put people first" - identifying 6 ethical principles in the framework below:*

![Responsible AI at Microsoft](https://docs.microsoft.com/en-gb/azure/cognitive-services/personalizer/media/ethics-and-responsible-use/ai-values-future-computed.png)

Let's briefly explore these principles. Transparency and accountability are foundational values that other principles built upon - so let's begin there:

- **Accountability** makes practitioners responsible for their data & AI operations, and compliance with these ethical principles.
- **Transparency** ensures that data and AI actions are understandable (interpretable) to users, explaining the what and why behind decisions.
- **Fairness** - focuses on ensuring AI treats all people fairly, addressing any systemic or implicit socio-technical biases in data and systems.
- **Reliability & Safety** - ensures that AI behaves consistently with defined values, minimizing potential harms or unintended consequences.
- **Privacy & Security** - is about understanding data lineage, and providing data privacy and related protections to users.
- **Inclusiveness** - is about designing AI solutions with intention, adapting them to meet a broad range of human needs & capabilities.
___
## *2.Ethics Challenges*
Once we have ethical principles defined, the next step is to evaluate our data and AI actions to see if they align with those shared values.
Think about your actions in two categories: data collection and algorithm design.

- With data collection, actions will likely involve personal data or personally identifiable information (PII) for identifiable living individuals.
This includes diverse items of non-personal data that collectively identify an individual. Ethical challenges can relate to data privacy, data ownership,
and related topics like informed consent and intellectual property rights for users.

- With algorithm design, actions will involve collecting & curating datasets, then using them to train & deploy data models that predict outcomes or automate
decisions in real-world contexts. Ethical challenges can arise from dataset bias, data quality issues, unfairness ,and misrepresentation in algorithms - including
some issues that are systemic in nature.

In both cases, ethics challenges highlight areas where our actions may encounter conflict with our shared values. To detect, mitigate, minimize, or eliminate, 
these concerns - we need to ask moral "yes/no" questions related to our actions, then take corrective actions as needed. Let's take a look at some ethical challenges
and the moral questions they raise:

### 2.1 *Data Ownership*
Data collection often involves personal data that can identify the data subjects. Data ownership is about control and user rights related to the creation, processing ,and dissemination of data.

The moral questions we need to ask are:
- Who owns the data? (user or organization)
- What rights do data subjects have? (ex: access, erasure, portability)
- What rights do organizations have? (ex: rectify malicious user reviews)

### 2.2 *Informed Consent*
Informed consent defines the act of users agreeing to an action (like data collection) with a full understanding of relevant facts including the purpose, potential risks, and alternatives.

Questions to explore here are:
- Did the user (data subject) give permission for data capture and usage?
- Did the user understand the purpose for which that data was captured?
- Did the user understand the potential risks from their participation?

### 2.3 *Intellectual Property*
Intellectual property refers to intangible creations resulting from the human initiative, that may have economic value to individuals or businesses.

Questions to explore here are:
- Did the collected data have economic value to a user or business?
- Does the user have intellectual property here?
- Does the organization have intellectual property here?
- If these rights exist, how are we protecting them?

### 2.4 *Data Privacy*
Data privacy or information privacy refers to the preservation of user privacy and protection of user identity with respect to personally identifiable information.

Questions to explore here are:
- Is users' (personal) data secured against hacks and leaks?
- Is users' data accessible only to authorized users and contexts?
- Is users' anonymity preserved when data is shared or disseminated?
- Can a user be de-identified from anonymized datasets?

### 2.5 *Right To Be Forgotten*
The Right To Be Forgotten or Right to Erasure provides additional personal data protection to users. Specifically, it gives users the right to request deletion or removal of personal data from Internet
searches and other locations, under specific circumstances - allowing them a fresh start online without past actions being held against them.

Questions to explore here are:
- Does the system allow data subjects to request erasure?
- Should the withdrawal of user consent trigger automated erasure?
- Was data collected without consent or by unlawful means?
- Are we compliant with government regulations for data privacy?

### 2.6 *Dataset Bias* 
Dataset or Collection Bias is about selecting a non-representative subset of data for algorithm development, creating potential unfairness in result outcomes for diverse groups. Types of bias include selection or
sampling bias, volunteer bias, and instrument bias.

Questions to explore here are:
- Did we recruit a representative set of data subjects?
- Did we test our collected or curated dataset for various biases?
- Can we mitigate or remove any discovered biases?

### 2.7 *Data Quality*
Data Quality looks at the validity of the curated dataset used to develop our algorithms, checking to see if features and records meet requirements for the level of accuracy and consistency needed for our AI purpose.

Questions to explore here are:
- Did we capture valid features for our use case?
- Was data captured consistently across diverse data sources?
- Is the dataset complete for diverse conditions or scenarios?
- Is information captured accurately in reflecting reality?

### 2.8 *Algorithm Fairness*
Algorithm Fairness checks to see if the algorithm design systematically discriminates against specific subgroups of data subjects leading to potential harms in allocation (where resources are denied or withheld from that group)
and quality of service (where AI is not as accurate for some subgroups as it is for others).

Questions to explore here are:
- Did we evaluate model accuracy for diverse subgroups and conditions?
- Did we scrutinize the system for potential harms (e.g., stereotyping)?
- Can we revise data or retrain models to mitigate identified harms?

### 2.9 *Misrepresentation*
Data Misrepresentation is about asking whether we are communicating insights from honestly reported data in a deceptive manner to support a desired narrative.

Questions to explore here are:
- Are we reporting incomplete or inaccurate data?
- Are we visualizing data in a manner that drives misleading conclusions?
- Are we using selective statistical techniques to manipulate outcomes?
- Are there alternative explanations that may offer a different conclusion?

### 2.10 *Free Choice*
The Illusion of Free Choice occurs when system "choice architectures" use decision-making algorithms to nudge people towards taking a preferred outcome while seeming to give them options and control. These dark patterns can cause 
social and economic harm to users. Because user decisions impact behavior profiles, these actions potentially drive future choices that can amplify or extend the impact of these harms.

Questions to explore here are:
- Did the user understand the implications of making that choice?
- Was the user aware of (alternative) choices and the pros & cons of each?
- Can the user reverse an automated or influenced choice later?