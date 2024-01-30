# vrops-google-chat-payload-template
Payload template for sending alerts from vRrealize Operation/Aria Operations to Google Chat

# How to use
1. Create Outbound template by navigating to Configure > Alerts > Outbound Settings
2. In the Outbound Settings page set your Google Chat webhook URL and set the type to Webhook
3. Navigate to Configure > Alerts > Payload Templates and import the file in this repo - Google-Chat-Payload-Template.json
4. Navigate to Configure > Alerts > Notifications and create new notification setting by configuring the Outbound Settings and Payload Template from steps 1-3
5. That's it, Aria Operations is now able to send Google Chat Notifications

# Useful links
You can customize the template using this tool - https://addons.gsuite.google.com/uikit/builder
JSON validator - https://jsoneditoronline.org/#left=local.tubusi
Google Chat API docs - https://developers.google.com/chat/api/reference/rest/v1/cards

