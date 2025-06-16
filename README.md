# AzColorizerPreview

> There was a time when we had to manage so many on-prem Windows Servers over RDP that the only way to distinglish between them was to use different themes on them, for example: red = production, blue = integration and green = development.
  
With the cloud we can easily have the similar problems but within our web browsers: Have you even been lost between the different browser windows or the many Azure subscriptions?

I hope this project will help you out in that matter! 

AzColorizer is here to give you the ability to change the color of the top navigational bar giving you a bit of help on the job.

With the most recent update `v2.0.0` you can set dedicated colors for up to 4 different Azure subscriptions:


https://github.com/sassdawe/AzColorizerPreview/assets/10754765/9adcae5a-d120-4315-9332-ef7ab9b5e16f


You can get the Extension from the [Microsoft Edge Marketplace](https://bit.ly/AzColorizer) for Microsoft Edge.

You can get the Extension from the [Google Chrome Marketplace](https://bit.ly/AzColorizerChrome) for Google Chrome.

> The Firefox version is still in the making.

## Precedence of color settings  

Colors have a precedence order in which they get applied, for example when a color is set for a subscription that will be used, but when there is no match for the subscription the resource color will beused. 

The precedence order is the following:

1. Subscription color
2. Resource color
3. Main color

## Settings colors for subscriptions

On the extension's popup page the **Subscription settings** tab can be used to set colors for the subscriptions using their ID:

![image](https://github.com/sassdawe/AzColorizerPreview/assets/10754765/553b8380-59f3-4289-b26b-895e5da8e1a6)

## Important to know / Privacy Policy

- AzColorizer currently does not support syncronizing settings between browers instances of the users, all settings are stored locally in the browser.
- AzColorizer _while in preview_ does not transit any information back to the developers or any other parties, if/when that changes it will be communicated here.    

![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fsassdawe%2FAzColorizerPreview&countColor=%23263759)
