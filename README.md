# Ex-4Scenario-Based-Report-Development-Utilizing-Diverse-Prompting-TechniquesDiverse Prompting Techniques

## Scenario

A retail store plans to introduce an AI-powered customer support
chatbot. It should assist customers with product enquiries, basic
troubleshooting, order tracking, returns, exchanges, and general
questions. It must communicate politely, ask for clarification when
needed, avoid inventing information, and refer complex issues to a human
support representative.

## Aim

To design and develop an AI-powered chatbot for a retail environment by
applying diverse prompt engineering techniques. The experiment aims to
create prompts that help the chatbot handle customer enquiries, provide
relevant support, organise information, and improve customer experience.

## Algorithm

1.  Identify the retail customer service scenario and common customer
    enquiries.
2.  Define the chatbot's role, responsibilities, tone, and limitations.
3.  Prepare sample queries about products, troubleshooting, order
    tracking, returns, and general enquiries.
4.  Create prompts using role-based, straightforward (zero-shot),
    few-shot, contextual (preceding-question), tabular-format, and
    step-by-step prompting techniques.
5.  Submit each prompt to an AI model and collect its responses.
6.  Review the responses for relevance, clarity, politeness, and
    accuracy.
7.  Check that the chatbot does not invent order details, delivery
    dates, product specifications, or store policies.
8.  Identify queries that need clarification or escalation to a human
    representative.
9.  Analyse the generated responses and prepare the report.
10. Record the output and result.

## Prompt

### 1. Role-Based Prompting

**Prompt:** \> Act as a professional retail customer support chatbot.
Assist customers with product enquiries, basic troubleshooting, order
tracking, returns, and general questions. Communicate in a polite,
friendly, and simple manner. Ask follow-up questions when information is
missing. Do not invent order details or store policies. If an issue
requires human assistance, explain how the customer can contact the
support team.

**Purpose:** Defines the chatbot's role, responsibilities, tone, and
limitations.

### 2. Straightforward (Zero-Shot) Prompting

**Prompt:** \> A customer says, "My new wireless headphones are not
connecting to my phone." Provide three safe and simple troubleshooting
suggestions in a polite tone.

**Purpose:** Gives the AI a direct instruction without providing
examples.

### 3. Few-Shot Prompting

**Prompt:** \> Respond to customer enquiries using the examples below.
Follow the same polite and helpful style. \> \> **Example 1**\
\> Customer: "How can I track my order?"\
\> Chatbot: "Open the shopping app, select 'My Orders', and choose the
order you want to track. Use the authorised support channel if you need
further help." \> \> **Example 2**\
\> Customer: "Can I return a product?"\
\> Chatbot: "I can help you understand the return process. Please check
the store's return policy or provide the product and purchase details so
the correct policy can be confirmed." \> \> **Now respond to this
query:**\
\> Customer: "I received a damaged product. What should I do?"

**Purpose:** Provides examples so the AI can follow the expected
response pattern.

### 4. Contextual / Preceding-Question Prompting

**Prompt:** \> What information is usually required to identify an
online order? A customer wants to know the status of a recently placed
order. Explain how the chatbot should guide the customer while
protecting their personal information.

**Purpose:** Establishes context before the main instruction.

### 5. Tabular Format Prompting

**Prompt:** \> Prepare a table for a retail customer support chatbot
showing common customer issues, information required, the chatbot's
suggested response, and when the issue should be escalated to a human
representative.

**Purpose:** Organises customer support information in a structured
table.

### 6. Step-by-Step Task Prompting

**Prompt:** \> A customer reports that their order has not arrived.
Organise the chatbot's response into these steps: (1) acknowledge the
customer's concern; (2) ask for the order ID through the authorised
channel; (3) explain how to check the order status; (4) state that an
accurate delivery update requires access to verified order information;
and (5) explain when to contact a human support representative. Use
simple and polite language. Do not invent a delivery date.

**Purpose:** Divides the response into clear stages for consistent
customer support.

## Output

The following sample outputs illustrate the expected behaviour of the
retail chatbot.

### Output 1: Product Troubleshooting

**Customer:** My new wireless headphones are not connecting to my phone.

**Chatbot:** "I'm sorry you're facing this issue. Please try these
simple steps: 1. Check whether Bluetooth is enabled on your phone. 2.
Make sure your headphones have sufficient battery. 3. Refer to the
headphone manual for the correct pairing procedure.

If the issue continues, please contact the product support team for
further assistance."

### Output 2: Damaged Product

**Customer:** I received a damaged product. What should I do?

**Chatbot:** "I'm sorry your product arrived damaged. Please keep the
packaging and purchase details available. Check the store's
damaged-product or return policy, and contact customer support with your
order ID and a description of the issue. The support team can confirm
the available replacement or refund options."

### Output 3: Order Tracking

**Customer:** How can I track my order?

**Chatbot:** "You can usually track your order by following these
steps: 1. Open the retailer's website or mobile application. 2. Go to
the 'My Orders' section. 3. Select your order to view its latest status.

An exact delivery update can only be provided when the chatbot has
access to verified order information."

### Output 4: Customer Support Table

---

Customer Issue Information Chatbot's Escalation
Required Suggested Required
Response

---

Product not Product name and Provide safe If the issue
working issue basic continues
troubleshooting  
 steps

Order tracking Order ID through Guide the If the status is
an authorised customer to the unavailable or
channel order status page incorrect

Damaged product Order details and Explain how to For replacement
issue description contact support or refund
and check the approval
policy

Return request Product and Explain where to If eligibility is
purchase details find the return unclear
policy

Payment issue Transaction Suggest checking If payment is
reference through payment and order debited but the
an authorised status order is not
channel confirmed

---

### Output 5: Handling an Unclear Query

**Customer:** I need help with my order.

**Chatbot:** "Of course. I can help you. Could you please tell me what
you need assistance with---for example, tracking your order, cancelling
it, or reporting a product issue? Please do not share passwords, OTPs,
or full payment details."

## Analysis

---

Evaluation Criteria Observation

---

Relevance Responses address the customer's
stated issue

Clarity Instructions use simple and
understandable language

Tone The chatbot communicates politely
and professionally

Structure Lists and tables make information
easier to follow

Accuracy The chatbot avoids claiming access
to unverified order information

Privacy The chatbot avoids requesting
passwords, OTPs, or full payment
details

Escalation Issues requiring account access,
policy decisions, or human
judgement are referred to customer
support

---

Different prompting techniques serve different purposes. Role-based
prompting establishes the chatbot's behaviour; zero-shot prompting
handles direct questions; few-shot prompting demonstrates the expected
response style; contextual prompting adds background; tabular prompting
organises information; and step-by-step prompting structures a support
workflow.

## Result

Thus, an AI-powered retail customer support chatbot was designed using
diverse prompt engineering techniques. Sample customer enquiries were
processed and analysed successfully. The experiment demonstrates how
well-structured prompts can help a chatbot provide clear, polite,
organised, and responsible customer support while identifying situations
that require human assistance.
