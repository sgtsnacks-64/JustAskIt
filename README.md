<h1>What is JustAskIt?</h1>
As the name suggests, JustAskIt, allows you to configure a prompt with context, purpose and a rule set and then submit a request alongside the prompt and get a response back. 
It is a Power Apps Model-Driven App with Dataverse backend for storage, and a Power Automate cloud flow to process the prompt and response.  

It was created by [Jon Russell](https://www.linkedin.com/in/jon-russell-20975726/) and [Mike Gowland](https://www.linkedin.com/in/mikegowland/)

Our context was to start at what we know so that the information received can be checked by our specific tech domain knowledge. As an example we went from 1.5 days lead time to 1 hour, to think of a client specific domain Dataverse example.

<h2>Examples</h2>
Dataverse Schema Prompt
Hackathon prompt
Power Platform Helper prompt

And many more...

<h2>Pre-reqs</h2>
*Power Apps Premium license
*Open AI API Access Key

<h2>Components of JustAskIt</h2>

*Dataverse ERD:

![image](https://github.com/sgtsnacks-64/JustAskIt/assets/60231096/94afdd45-267d-498d-bd96-e8e5d2ba1823)

*Power Automate cloud flow

<h2>Steps for user</h2>

1. Click on Prompts to create your prompt:

![image](https://github.com/sgtsnacks-64/JustAskIt/assets/60231096/4912d313-c6ae-4e67-9c70-33808fa00e0c)

2. Complete the details for your prompt:

![image](https://github.com/sgtsnacks-64/JustAskIt/assets/60231096/87867f19-3d52-4532-b88f-34cc2a0115d6)

3. Save the Prompt
4. Create Rules:

![image](https://github.com/sgtsnacks-64/JustAskIt/assets/60231096/fdd3365d-013b-4d7c-85b5-f4c1c1a2e4d9)

5. Make the rule mandatory if required.
6. Click on Prompt Rules
7. Associate the rules you create with the Prompt you created in step 1
8. Go to Requests
9. Add your request and choose the prompt you just created
10. Submit prompt
11. Prompt and Response cloud flow will execute and a response will be provided back to the Request in the Response subgrid.
