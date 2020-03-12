# Get alerts when something is not right

If something happens in your environment or for one of your customers that you need to take action on, it is better that the system sends you an alert.

Azure Application Insights makes it easy to define such alerts.

Here is an example to get you started:
 1. Open the Azure portal and locate your AppInsights account
 2. Click "Alerts" in the navigation pane on the left
 3. Use one of the KQL samples in the condition for a custom log search 
 4. Create a new action group, add an action to send an email to you
Now you will get an email whenever your app or your customers make HTTP calls that fail.
