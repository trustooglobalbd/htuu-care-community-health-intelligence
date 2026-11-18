# System Architecture

## 1. Community Access Layer

### Htuu Care
Telegram-based health information and navigation.

Responsibilities:
- Health information access
- Topic selection and questions
- Referral/navigation information
- Myanmar, English and Thai support
- Safe escalation to human support

### 7887
Human health-information and counselling layer.

Responsibilities:
- Human support
- Health-information clarification
- Escalation and referral
- Feedback on information needs

## 2. Intelligence Layer

The intelligence pipeline should:
1. Receive permitted, minimized interaction metadata.
2. Classify health-information topics.
3. Aggregate topic counts.
4. Calculate trends over time.
5. Flag unusual increases for human review.
6. Generate concise public-health summaries.

## 3. Response Layer

Reviewed signals can support:
- Health awareness content
- Community outreach
- Referral/service coordination
- Public-health planning

## Safety boundary

The system must not:
- diagnose users;
- prescribe treatment;
- identify individuals from aggregated data;
- make autonomous public-health decisions;
- expose private conversations in dashboards.

AI output is advisory and requires authorized human review.
