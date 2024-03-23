PUBLIC REPOSITORY owned by Andrea Taloni - GPT-Wars-Creating-and-Detecting-Fake-Data-Sets-with-Generative-Artificial-Intelligence
------
README
------

1 - LINKS TO CUSTOM GPTs

These are links to access the Custom GPTs used in the manuscript "GPT Wars: Creating and Detecting Fake Data Sets with Generative Artificial Intelligence", submitted to The Lancet Digital Health.

To use the Custom GPTs an active subscription to ChatGPT is required.


GPT Data Analyst - developed by OpenAI: https://chat.openai.com/g/g-HMNcP6w7d-data-analyst

Fake Data Creator (1) - developed by Andrea Taloni: https://chat.openai.com/g/g-xKObjb0Am-fake-data-creator-1

Fake Data Creator (2) - developed by Andrea Taloni: https://chat.openai.com/g/g-Ubbfd3Jzx-fake-data-creator-2

Fake Data Creator (3) - developed by Andrea Taloni: https://chat.openai.com/g/g-xHiPRvzJ1-fake-data-creator-3

Fake Data Detector - developed by Andrea Taloni: https://chat.openai.com/g/g-8FaFnkSlB-fake-data-detector

-----------------------------------------------

2 - SAMPLE CONVERSATIONS

Before testing our Custom GPTs, we highly recommend to check the sample conversations down below.
The sample conversations were recorded after manuscript submission to aid reviewers and editors in using and evaluating the Custom GPTs.

2.1 - The sample conversations were screenshotted and merged in single PDF files:

Fake Data Creator (1) - Sample Conversation.pdf

Fake Data Creator (2) - Sample Conversation.pdf

Fake Data Creator (3) - Sample Conversation.pdf

Fake Data Detector - Sample Conversation for Unrefined Fake Data Set 1a.pdf

They can be downloaded from the public repository.


2.2 - These are the "Refined" Fake Data Sets produced in these sample conversations with Fake Data Creator:

Refined Fake Data Set - Sample Conversation with Fake Data Creator (1).xlsx

Refined Fake Data Set - Sample Conversation with Fake Data Creator (2).xlsx

Refined Fake Data Set - Sample Conversation with Fake Data Creator (3).xlsx

They can be downloaded from the public repository as Excel files. These data sets were not included inside the Manuscript.


2.3 - This is the data set submitted to Fake Data Detector for the purpose of forensic analysis (it was renamed to "Data Set 1a" prior to the analysis to prevent bias):

"Unrefined Fake Data Set 1a.xlsx"

It can be downloaded from the public repository. The data set is identical to the "Refined Fake Data Set 1a" featured inside the Supplementary Material of this submission.

-----------------------------------------------

3 - IMPORTANT NOTES ABOUT USING THE CUSTOM GPTs

The Custom GPTs Fake Data Creator (1,2,3) and Fake Data Detector have been developed with specific instructions and additional knowledge, to optimize the execution of all the required statistical tasks. However, as mentioned in the manuscript, analysis errors and hallucinations may still occur. In these cases, there are two main options:
- to edit your original prompt with more accurate instructions
- to directly ask ChatGPT to fix what was done wrong
- to press the "regenerate" button below the answer of ChatGPT

As you can notice in the sample conversations for Fake Data Creator, the first steps of data set fabrication are very smooth; however, fixing very specific statistical flaws may be challenging.
In other words, Custom GPTs perform very well in creating the main infrastructure of the data set, meeting criteria for significancy levels and linear correlations.
Surprisingly, Custom GPTs seem quite inefficient when it comes to performing small targeted changes to data, such as adjusting few specific numbers.
For the purpose of this research, we employed ChatGPT to fabricate the entire data sets, without performing any manual editing, which is certainly suboptimal.
Performing minor fixes, such as adjusting last digits and distribution shapes took longer than necessary; few minor manual changes could have improved the data sets without requiring generative AI.
As discusses in the manuscript, the most dangerous attempts at fabricating data may involve a mixed approach, using both generative AI and manual input.

-----------------------------------------------

4 - PERFORMANCE ISSUES

Although we cannot prove this, we noticed that ChatGPT performance varies considerably according to the time of the day (most likely due to traffic on OpenAI servers).
In addition, we had the impression that being ALT-tabbed or browsing the internet while waiting for the answers of ChatGPT led to worse performance (possibly due to internet connection issues).
Custom GPTs may rarely "forget" some details inside their Instructions. In these uncommon cases a simple reminder is sufficient to fix the issue.
ChatGPT performance may also change with every update released by OpenAI.

-----------------------------------------------

5 - CHATGPT SUBSCRIPTIONS

To use the Custom GPTs an active subscription to ChatGPT is required:
- ChatGPT Plus subscription provides 40 messages in 3 hours (20 usd per month)
- ChatGPT Team subsciption provides 100 messages in 3 hours (25 usd per month)
- ChatGPT Enterprise subscription provides unlimited messages (can only be bought by business users or companies contacting OpenAI directly)

Forty messages every 3 hours may be unpractical to interact with our custom GPTs efficiently.
In fact, when the message cap is reached, it is not possible to send new messages to ChatGPT, and the Python environment resets after about 20 minutes of inactivity, preventing further editing of the data set later on. Therefore, when the user is about to reach the cap of 40 messages, it is recommended to download the work in progress data set and reupload it later on to the custom GPT.

While not mandatory, ChatGPT Team is the most efficient option to use our Custom GPTs.
ChatGPT Team increases the number of messages per hour, delays the Python environment reset and offers team-specific features for collaboration. It does not provide better performance.


