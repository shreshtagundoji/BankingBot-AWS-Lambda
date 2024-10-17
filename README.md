## BankingBot-AWS-Lambda
 BankerBot, an AI-driven chatbot to assist customers with banking tasks such as checking account balances and transferring funds between accounts.

#### Tools & Technologies: Amazon Lex, AWS Lambda, Python, AWS CloudFormation

#### Key functionalities included:
- Defined intents (WelcomeIntent, CheckBalance, TransferFunds) and slot types for seamless user interactions.
- Created custom slots for account types (Checking, Savings, Credit) and integrated validation prompts for date of birth to enhance security.
- Implemented the CheckBalance intent to retrieve account balances based on user input with context carryover, minimizing repeated prompts.
- Designed a TransferFunds intent with multiple slots (sourceAccountType, targetAccountType, transferAmount) to allow users to transfer funds between accounts.
- Integrated the chatbot with AWS Lambda for backend processing, enabling dynamic responses such as balance retrieval and fund transfers.
- Automated the deployment of chatbot infrastructure using AWS CloudFormation.
- Employed confirmation prompts and context carryover for improved user experience, reducing redundant information requests across multiple intents.
