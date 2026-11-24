# Annotation Guidelines (version 1)

## Task
Each item is a short message that a customer sent to an online shop. Give each message exactly one label.

All messages in this project are synthetic examples written for practice. They are not real customer data.

## Labels

### Complaint
The customer says something went wrong or they are unhappy with the product or service.
- Example: "My parcel arrived two weeks late and the box was crushed."
- Example: "The app keeps logging me out and nobody has replied to my emails."

### Question
The customer asks for information and does not report a problem.
- Example: "Do you deliver to Port Harcourt?"
- Example: "What time does your support team open?"

### Praise
The customer says something positive about the product or service.
- Example: "The shoes fit perfectly and arrived early. Thank you!"
- Example: "Your support agent was kind and solved my issue in minutes."

### Other
The message is none of the above, or it is too unclear to label.
- Example: "Hello"
- Example: "Please send me the invoice for order 4471."

## Rules for hard cases
1. **One label only.** Choose the label that matches what the customer mainly wants or feels.
2. **Complaint and question in one message.** If the customer reports a problem and also asks a question about it, label it Complaint.
3. **Praise and complaint in one message.** Label the part that comes last, because it usually shows how the customer feels in the end.
4. **Sarcasm.** Label what the customer really means. "Great, another late delivery" is a Complaint.
5. **Requests for action** (refund, invoice, change of address) with no complaint or praise are Other.
6. **Not sure.** Choose Other and write a short note saying why. Do not guess.

## What the second labeller receives
Only this file and the list of messages. They do not see my labels.