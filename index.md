---
title: Getting started with Cognigy.AI
permalink: /getting-started-with-cognigy-ai
---

# Getting started with Cognigy.AI

Cognigy.AI is a platform to create and customize  Virtual Agents (VA) that meet your customer experience (CX) needs. A VA is a bot that leverages AI to perform customer interactions. With Cognigy.AI, you can create [chat and voice VA's](https://support.cognigy.com/hc/en-us/articles/7138355918876-Universal-skills-for-Chat-and-Voice).

## Prerequisite <a name="prerequisite"></a>

You need to have created a Cognigy.AI account. If you do not have a Cognigy.AI account, [contact a Cognigy.AI consultant](https://www.cognigy.com/contact-us). <!-- What would be the correct process to get a Cognigy.AI account? For reference I'm using the contact us link, but I imagine the right way would be different. -->

## Log in to Cognigy.AI <a name="log-in-to-cofnigy-ai"></a>

To log in to Cognigy.AI, go to [https://train.cognigy.ai](https://trial.cognigy.ai/) and enter the following data that you used to create your Cognigy.AI account: <!-- I imagine this link is just for trials, so there's probably another URL to log in to the platform. Also, how do people log in for the first time? Do they get an invitation email? What are restriction due to access rights? These points might need to be clarified for the first log in. -->

1. **E-Mail**
2. **Password** 
3. Click **Sign in**.  
    You will be redirected to the Cognigy.AI index dashboard. <!-- I'm using index dashboard because that is the name you get at the browser tab, but the page doesn't seem identifiable -->

You can also set up single sign-on (SSO) login for your users. Learn how to set up SSO login in the [Single Sign On section](https://support.cognigy.com/hc/en-us/categories/360002716460-How-to-s-Tutorials) of our Help Center.

## Create a VA <a name="create-a-project"></a>

In the Congnigy.AI index dashboard, you can create and access your VA's.

To create a VA, follow these steps:

1. In the index dashboard, click **+ Create Project** on the top left.  <!-- Why is this button called create project if it triggers a processe to create a VA? Are there other objects to create inside a project or can you create different VA's inside one project -->  
    The configuration window opens.
2. In the **Basic Information** window, configure the following:
    - **Project Name**
    - **NLU language**: Primary language of your VA
    - **Color**: The color helps you identify your VA in the index dashboard.
    - (Optional) **Set Up Cognigy Live Agent**: To set up a [Congigy Live Agent](https://docs.cognigy.com/live-agent/tools/odata-endpoint/), click **Set Up Live Agent** and activate the **Create Cognigy Live Agent Inbox**. <!-- Are there any repercussions in setting it up from the get-go? Are there any prerequisites or any data needed for this? -->
3. Click **Next: Selection Solution Accelerator**.
4. In the **Solution Accelerator** window, select a flow and lexicon template and click **Next: Select Channels**. To create a VA without predefined resources, select **Blank**.
5. In the **Channels** window, select the channels in which you want to use your VA and **Next: Add Skills**.
6. (Optional) In the **Skills** window, select a lexicon that is helpful for your VA.
7. Click **Create**.

<!-- Why do all the buttons include "Next" and the name of the section that is repeated on the left side? Isn't this somewhat redundant? -->

You have created a VA! Now, you have the following options: <!-- Why do we give the user two options in the UI? Isn't this confusing? Is testing the VA directly after setting it up useful or is it better to keep configuring and improving it before really testing it? What is the benefit of people testing it directly after creating it? -->

- To check and test your VA's conversation Flow, click **Chat with your Agent**.
- To check your VA settings, click **Go to project**.

After you have created your VA, you can [design Flows and Messages](https://support.cognigy.com/hc/en-us/articles/360014524180-Design-a-Flow-and-add-a-Message) for your VA. <!-- What would be the best next step here? Setting up integrations, adding customized lexicons, maybe give various options depending on the use case? -->
