<h1>What is JustAskIt?</h1>
As the name suggests, JustAskIt, allows you to configure a prompt with context, purpose and a rule set and then submit a request alongside the prompt and get a response back. 
It is a Power Apps Model-Driven App with Dataverse backend for storage, and a Power Automate cloud flow to process the prompt and response. The name came from Mike and myself talking about how best to format a response from a
Large Language Model (LLM), and Mike said Just Ask It by adding a rule to the rule set.  

It was created by [Jon Russell](https://www.linkedin.com/in/jon-russell-20975726/) and [Mike Gowland](https://www.linkedin.com/in/mikegowland/)

Our context was to start at what we know so that the information received can be checked by our specific tech domain knowledge. As an example we went from 1.5 days lead time to 1 hour, to think of a client specific domain Dataverse example.

<h2>Guidance and Rules</h2>

When creating a rule set for a prompt, detials of how to do this are below, you should always provide these three mandatory rules:

1. You must always be truthful
2. You must always be honest
3. You must always be helpful

Of course, this is not an exhaustive list, and there will be many other mandatory rules that you may wish to add. For example, rules around equality, diversity and inclusion, the removal of uncocious bias and gender stereotyping.  These are just three rules that should form the baseline for any prompt that is submitted to a LLM.

<h2>Examples</h2>
<p>Dataverse Schema Prompt</p>
<p>Hackathon prompt</p>
<p>Power Platform Helper prompt</p>
<p>And many more...  </p>

<h2>Pre-reqs</h2>
<p>Power Apps Premium license</p>
<p>Open AI API Access Key</p>

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

<h2>Links</h2>

[An Epic AI Solution](https://youtu.be/rA6QpHAQaDE)  
[Mike and Jon in conversation with Mark Smith](https://www.comingsoon.com)  
[Mike on the On Air In the Cloud podcast with Keith Atherton, Matt Boyd and Gregor Suttie](https://podcasters.spotify.com/pod/show/onairinthecloud/episodes/Episode-Ten---Mike-Gowland-e2d6tbu)
