# Manage users
## Description
In this walkthrough task we will create a new user for our environment and next we assign user to Resource Group with defined role.
## Prerequisites
You require need an Azure subscription to perform these steps. If you don't have one you can create one by following the steps outlined on the Create your Azure free account today webpage https://azure.microsoft.com/en-us/free/.
## Steps
1. Sign into the Azure portal at https://portal.azure.com
Click on Menu button on left top corner of the Azure portal and select **Azure Active Directory** from the list.
If there is no **Azure Active Directory** option, click on **All Services**, next fill <abbr>**Azure Active Directory**</abbr> in Search field and click on **Azure Active Directory** link.
2. Go to section **Manage / Users** and click on New user link on top of page.
3. Choose **Create user** option and fill the form

| Label | Value |
| ------------ | ------------ |
| Username: | For example, <abbr>**your-first-name**</abbr>
| Name: | For example, <abbr>**Your-Name and Surname**</abbr>
| Password: | Choose <abbr>**Auto-generate password**</abbr> and check option <abbr>**Show Password**</abbr>

> _**Note! Remember to copy username (with domain) and initial password.**_

**Congratulations! You have created a new user in your tenant (Azure Active Directory).**

1. Click on Menu button on left top corner of the Azure portal and select **Subscriptions** from the list.
If there is no **Subscriptions** position, click on **All Services**, next fill <abbr>**Subscriptions**</abbr> in Search field and click on **Subscriptions** link.
2. Choose your Subscription, and when new page opened choose **Access control (IAM)** option.
3. Click **Add** link on top of the page, choose **Add co-administrator**, and select your newly created user from the list. You dan use search form. Next click **Add** button from below.
You can check if user is subscription co-administrator – using Check access form.

