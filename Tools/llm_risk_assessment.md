# LLM Risk Assessment Sheets

## Hallucinations
**Definition**: The model may produce false or misleading information that sounds plausible.

**Risk Indicators**:
- Model generates facts without sources
- Outputs vary widely with slight prompt changes
- Responses sound confident but lack citations

**Assessment Questions**:
- Does the project rely on factual accuracy?
- Are outputs used in public or high-stakes settings?
- Are users likely to trust the model’s responses without verification?

**Impact Rating**: ☐ Low ☐ Medium ☐ High

**Mitigation Strategies**:
- Require source citations
- Include disclaimers
- Use retrieval-augmented generation (RAG)

**Follow-Up Areas**:
- Review prompt design
- Test outputs against trusted sources
- Consult domain experts

---

## Bias and Fairness
**Definition**: The model may reflect stereotypes, prejudices, or unfair assumptions found in training data.

**Risk Indicators**:
- Responses include gendered or racial assumptions
- Unequal treatment of professions or roles
- Stereotypical language or framing

**Assessment Questions**:
- Is the model used in sensitive domains like hiring or healthcare?
- Are outputs reviewed for fairness and inclusivity?
- Is bias testing part of the development process?

**Impact Rating**: ☐ Low ☐ Medium ☐ High

**Mitigation Strategies**:
- Use inclusive prompt design
- Conduct bias audits
- Incorporate diverse training data

**Follow-Up Areas**:
- Review output samples for bias
- Consult DEI experts
- Test with diverse user groups

---

## Privacy Violations
**Definition**: The model may inadvertently reveal personal, sensitive, or confidential information.

**Risk Indicators**:
- Model outputs include real names or financial details
- Echoes private conversations or documents
- Mishandles user-provided data

**Assessment Questions**:
- Is sensitive data used in prompts or training?
- Are outputs reviewed for privacy compliance?
- Is data anonymization enforced?

**Impact Rating**: ☐ Low ☐ Medium ☐ High

**Mitigation Strategies**:
- Avoid sharing sensitive data in prompts
- Use placeholder data
- Implement privacy filters

**Follow-Up Areas**:
- Review data handling policies
- Conduct privacy impact assessments
- Consult legal and compliance teams

---

## Security Vulnerabilities
**Definition**: The model may be manipulated or misused through prompt injection or other attacks.

**Risk Indicators**:
- Model follows harmful or unethical instructions
- Leaks internal system prompts
- Generates malicious code or phishing content

**Assessment Questions**:
- Is the model exposed to public inputs?
- Are prompts sanitized and validated?
- Is adversarial testing performed?

**Impact Rating**: ☐ Low ☐ Medium ☐ High

**Mitigation Strategies**:
- Use input sanitization
- Implement role-based access controls
- Test for prompt injection

**Follow-Up Areas**:
- Review system architecture
- Conduct security audits
- Consult cybersecurity experts

---

## Environmental Impact
**Definition**: Training and running large models consumes significant energy and resources.

**Risk Indicators**:
- High GPU usage
- Long training times
- Large-scale deployment infrastructure

**Assessment Questions**:
- Is the model size justified by its use case?
- Are energy-efficient options considered?
- Is the carbon footprint tracked?

**Impact Rating**: ☐ Low ☐ Medium ☐ High

**Mitigation Strategies**:
- Use smaller models when possible
- Optimize training and inference
- Use renewable energy sources

**Follow-Up Areas**:
- Review infrastructure choices
- Consult sustainability experts
- Track energy consumption

---

## Economic Disruption
**Definition**: LLMs may automate tasks and displace jobs, affecting industries and workers.

**Risk Indicators**:
- Tasks previously done by humans are automated
- Job roles are redefined or eliminated
- Skill gaps emerge in the workforce

**Assessment Questions**:
- Is the model replacing human roles?
- Are workers being supported with training?
- Is the impact on employment considered?

**Impact Rating**: ☐ Low ☐ Medium ☐ High

**Mitigation Strategies**:
- Use AI to assist, not replace
- Provide upskilling opportunities
- Engage stakeholders in deployment decisions

**Follow-Up Areas**:
- Review workforce impact
- Consult labor experts
- Monitor job market trends

---

## Misinformation and Disinformation
**Definition**: The model may generate or amplify false or misleading content.

**Risk Indicators**:
- Outputs include outdated or debunked claims
- Model generates persuasive but false narratives
- Responses lack source verification

**Assessment Questions**:
- Is the model used in public communication?
- Are outputs fact-checked?
- Is source attribution enforced?

**Impact Rating**: ☐ Low ☐ Medium ☐ High

**Mitigation Strategies**:
- Use verified sources
- Include disclaimers
- Limit use in sensitive domains

**Follow-Up Areas**:
- Review content moderation policies
- Consult media literacy experts
- Test outputs for accuracy

---

## Overreliance and De-skilling
**Definition**: Excessive dependence on LLMs may reduce human expertise and critical thinking.

**Risk Indicators**:
- Users rely on model without verification
- Skills degrade over time
- Outputs are accepted without review

**Assessment Questions**:
- Are users trained to use the model critically?
- Is human oversight part of the workflow?
- Are tasks being delegated too fully to the model?

**Impact Rating**: ☐ Low ☐ Medium ☐ High

**Mitigation Strategies**:
- Encourage active engagement
- Use models as assistants, not replacements
- Provide training on critical use

**Follow-Up Areas**:
- Review user behavior
- Consult training experts
- Monitor skill retention

---

## Alignment and Control
**Definition**: The model may behave in ways that don’t match human values or safety expectations.

**Risk Indicators**:
- Model follows unethical or harmful instructions
- Outputs conflict with organizational values
- Behavior is unpredictable in edge cases

**Assessment Questions**:
- Are safety constraints enforced?
- Is the model tested for ethical alignment?
- Are outputs reviewed for value consistency?

**Impact Rating**: ☐ Low ☐ Medium ☐ High

**Mitigation Strategies**:
- Use reinforcement learning from human feedback
- Define clear ethical boundaries
- Conduct alignment testing

**Follow-Up Areas**:
- Review ethical guidelines
- Consult alignment researchers
- Test edge-case scenarios

---

## Opacity and Interpretability
**Definition**: It’s difficult to understand or explain how the model makes decisions.

**Risk Indicators**:
- Model outputs lack reasoning
- Decisions are hard to trace
- Users can’t explain model behavior

**Assessment Questions**:
- Is interpretability important for this use case?
- Are decisions auditable?
- Can the model explain its reasoning?

**Impact Rating**: ☐ Low ☐ Medium ☐ High

**Mitigation Strategies**:
- Use explainable AI techniques
- Provide reasoning steps in outputs
- Limit use in regulated domains

**Follow-Up Areas**:
- Review decision-making workflows
- Consult interpretability experts
- Test model transparency

---

