---
title: "Event 2"
date: 2026-07-11
weight: 1
chapter: false
pre: " <b> 4.2. </b> "
---

# Summary Report: Automated Security, SLA Monitoring & AWS Certification Roadmap

### Event Objectives

- Establish a strategic roadmap and preparation strategy for the AWS Certified Cloud Practitioner exam tailored for students and entry-level engineers.
- Introduce comprehensive cybersecurity automation solutions for web applications using the autonomous AI-powered AWS Security Agent.
- Outline the workflow for automated penetration testing, code review, and architectural design review within a DevSecOps environment.

### Speakers

- **Ngo Le Tan Huy** - AWS Cloud Specialist
- **Nguyen Huynh Son** - Infrastructure Support Engineer at Endava, Former Infrastructure Reliability Engineer at SPS, AWS Student Builder Group Leader at HUFLIT
- **Thinh Nguyen** - DevOps, DevSecOps, and Cloud Engineer at Styl Solutions, First Cloud AI Journey Member

### Key Highlights

#### AWS Cloud Practitioner Exam Preparation Strategy

**CLF-C02 exam structure**: The exam consists of 65 multiple-choice questions completed within 90 minutes, with an additional 30 minutes granted to non-native English speakers. The passing score is 700 out of 1000, and the certification remains valid for 3 years. The exam focuses on high-level concepts rather than requiring coding or complex system configurations.

**Four key knowledge domains**:
- Cloud Concepts: Core benefits of cloud computing, six pillars of the AWS Well-Architected Framework, and the AWS Cloud Adoption Framework.
- Security and Compliance: The Shared Responsibility Model, Identity and Access Management IAM, infrastructure security including Security Groups, NACLs, AWS Shield, and AWS WAF, as well as compliance services such as AWS Artifact.
- Cloud Technology and Services: AWS Global Infrastructure encompassing Regions, Availability Zones, Edge Locations, alongside service categories such as Compute with EC2 and Lambda, Storage and Databases with S3, EBS, RDS, and DynamoDB, and Networking with VPC and Route 53.
- Billing, Pricing, and Support: EC2 pricing models, cost management tools such as AWS Budgets and Cost Explorer, and AWS Support plans including Basic, Developer, Business, and Enterprise.

**Effective study methodology**: Apply the Keyword Mapping approach by linking theoretical concepts to practical use cases. Focus on analyzing why incorrect options are wrong during practice tests and utilize an AWS Free Tier account to visualize concepts.

**Exam and interview tips**: Use the process of elimination to remove illogical choices, avoid overcomplicating answers, pay attention to key terms like Not, Least cost, or Most scalable, and utilize the Flag for review feature for difficult questions.

#### Operational Risk Management and Service Level Agreements

**Real-world NOC and SOC operations**: Network Operation Center environments require continuous 24/7 monitoring across multiple displays, tracking proactive signals to respond to incidents promptly.

**Concept and role of SLAs**: A Service Level Agreement is a formal contract defining expected service standards between a provider and a customer. SLAs establish clear expectations, service accountability, risk management, and performance measurement. Violating SLAs may lead to financial compensation penalties for enterprises.

**Risk management loop**: Monitoring operates within risk management to detect risks early before impacting SLAs. The four-step process includes identifying risks, monitoring signals, responding through SNS or standard operating procedures, and improving systems.

#### Monitoring Pyramid and Real-Time Alerting Flow

**The Green Dashboard pitfall**: Infrastructure metrics displaying green status such as low CPU usage or healthy hosts do not guarantee a positive user experience. For example, database connection failures can cause login errors while health checks continue to pass.

**Monitoring Pyramid structure**: Monitoring should progress from lower infrastructure levels to higher customer-oriented levels:
- Infrastructure level: CPU, memory, disk, and network metrics.
- Application level: Latency, error rates, and request counts.
- Business level: Login success rates, order counts, and revenue.
- Customer Experience level: User ability to log in, search, and complete purchases.

**Automated alerting flow**: Push custom metrics into CloudWatch, trigger CloudWatch Alarms when thresholds are breached, publish notifications to SNS topics, and send alerts to Slack or Email channels for operational teams.

#### Cyber Attack Detection and Automated Security

**Traditional security bottlenecks**: Manual penetration testing is time-consuming, costly, and inconsistent depending on human assessors.

**AWS Security Agent architecture**: Powered by Amazon Bedrock using multi-agent systems, providing autonomous reasoning across the software development lifecycle and producing verifiable findings through active exploitation.

**Automated review capabilities**:
- Design Security Review: Analyzes Markdown documentation or Terraform code against managed compliance frameworks such as PCI DSS, NIST CSF, and AWS Well-Architected Framework.
- Code Security Review: Integrates into Pull Requests on GitHub or GitLab, inspecting code changes and suggesting automated pull request fixes while preventing credential leaks.
- Threat Modeling: Evaluates potential architecture threats and weaknesses based on system documentation.

#### Penetration Testing Workflow and Technical Limitations

**Autonomous Pentesting mechanism**: Executes multi-step exploit chains, authenticates as real users, and generates attack graphs with verifiable proof.

**Pricing model and Task-Hours**: Charged at 5 USD per Task-Hour based on agent execution time, offering a 2-month free trial with 400 Task-Hours per month. Parallel execution across tasks may consume 30 to 50 Task-Hours for complex applications, offering a cost-effective alternative to traditional human pentesting teams.

**Deployment workflow**: Verify target domain ownership via DNS TXT records, configure GitHub App integration, define out-of-scope URLs, and provide test credentials via AWS Secrets Manager.

**Technical limitations**: Agents cannot bypass strict authentication mechanisms such as Multi-Factor Authentication MFA, Biometrics, Mutual TLS mTLS, or One-Time Passwords OTP. They may also struggle with complex business logic flaws without sufficient context and can consume Task-Hours rapidly on complex applications.

### Key Takeaways

#### Cybersecurity and DevSecOps Automation Mindset
- **Behavioral Testing**: Shift from static code analysis tools like SAST or SonarQube to multi-agent AI systems that simulate realistic attack behaviors across both frontend and backend systems.
- **CI/CD Security Integration**: Apply automated Code Security Reviews on Pull Requests to prevent credential or API key leaks and remediate vulnerabilities early in development.
- **Understanding AI Agent Boundaries**: Recognize that AI Agents support security workflows effectively but cannot fully replace human expertise, particularly regarding mTLS, MFA, or custom business logic.

#### Infrastructure Operations and System Observability Mindset
- **Transition to User-Centric Monitoring**: Shift away from relying solely on green dashboards and establish measurement systems based on the customer journey, including login, checkout, and payment success rates.
- **Proactive Risk Management**: Build automated incident alerting workflows from custom metrics via CloudWatch Alarms and SNS to communication channels such as Slack or Email before user complaints arise.
- **Business-Oriented SLA Management**: Understand the direct relationship between system downtime, SLA breaches, and financial compensation within enterprise contexts.

#### Learning Methodology and AWS Certification
- **Keyword Mapping**: Associate theoretical concepts with practical use case keywords to improve recall and efficiency during exams.
- **Standardized Multiple-Choice Test Strategy**: Use elimination techniques for impractical options, manage time effectively, and maintain composure during examinations.

### Applying to Work
- **Trial AWS Security Agent Free Tier**: Utilize the two-month trial offering 400 Task-Hours per month to perform security reviews and penetration testing on personal projects or academic assignments.
- **Integrate PR Security Scanning**: Install the AWS Security Agent GitHub App on repositories to automatically inspect code changes and detect secret exposure on each Pull Request.
- **Implement User-Centric CloudWatch Metrics**: Export custom metrics tracking login and transaction success rates to AWS CloudWatch rather than measuring CPU or memory alone.
- **Configure Automated Alerting Flow**: Set up CloudWatch Alarms combined with Amazon SNS to deliver urgent alerts via Slack or Email when application error rates spike.
- **Register & Practice for CLF-C02**: Register an AWS Skill Builder account, complete hands-on labs using the AWS Free Tier, and apply keyword mapping to prepare for the AWS Certified Cloud Practitioner exam.

### Event Experience

Attending AWS Community Day provided a valuable practical experience, helping strengthen overall perspectives on automated cybersecurity, SLA monitoring practices, and a clear roadmap for AWS certifications.

#### Learning from Experienced Speakers
- Speaker Ngo Le Tan Huy provided a practical, concise, and structured strategy for certification preparation.
- Speaker Thinh Nguyen delivered an engaging demonstration of AWS Security Agent from a practical DevSecOps perspective.
- Speaker Nguyen Huynh Son shared real-world NOC and SOC operational insights and authentic SLA management experiences from corporate practice.

#### Practical Technical Experience
- Observed the console interface directly, including domain verification steps, integration setups, and detailed vulnerability reports generated by AWS Security Agent.
- Learned to analyze the Green Dashboard pitfall using the monitoring pyramid model and a realistic RDS database connection failure scenario.

#### Mindset Shift and Career Orientation
- Reframed cybersecurity awareness by recognizing the importance of automated penetration testing powered by AI in modern software development.
- Developed a deeper appreciation for the responsibility toward end-user experience in infrastructure operations.

#### Networking and discussions
- Engaged in an open atmosphere that facilitated direct discussion and learning with industry professionals and peers.

#### Lessons learned
- Infrastructure monitoring must align continuously with actual end-user experience.
- Adopting new automation technologies like AI Agents or automated pentesting requires understanding foundational technical constraints such as MFA, mTLS, or business logic flaws.

#### Event Gallery
![](/static/images/4-EventParticipated/Pic1-2026-07-11.jpg)
![](/static/images/4-EventParticipated/Pic2-2026-07-11.jpg)

> Overall, the event delivered valuable insights and practical knowledge, particularly regarding system security solutions and useful AI tools.