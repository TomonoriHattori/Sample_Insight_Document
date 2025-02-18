# OpenAI's pricing structure
When using OpenAI's features (ChatGPT/dall-e, etc.) with ailia DX Insight, please be aware of the pricing structure and rate limits. Rate limits are implemented by OpenAI from a service stability perspective, and the number of requests is restricted based on the user's Tier (usage level). Please note that if you plan to use one account with multiple people, it may take about a week or more (sometimes up to three weeks) to prepare for removing rate limits.

## About ChatGPT tokens
Each OpenAI model determines the amount of pay-as-you-go billing based on token units. The usage fee is the sum of the unit price according to the number of tokens input and the unit price according to the number of tokens output.

A token, in the case of English, is equivalent to one word being one token, and in the case of Japanese, one character is usually equivalent to 1-2 tokens. Also, in the case of Japanese, terms like "desu" and "masu" may equal one token for two characters. "The number of tokens varies depending on the version of ChatGPT."<br>
Additionally, punctuation marks or question marks are each counted as one token.<br>


```
e.g.） What is the captal of Japan? &rarr; 7 Tokens
e.g.） What is the capital of the United States? &rarr; 9 Tokens
```

By using a tool called "[Tokenizer](https://platform.openai.com/tokenizer)" provided by OpenAI, you can check how the input tokens are being counted.<br>
![API_key_17](img/API_key_17.png)<br>

Please check [here](https://openai.com/api/pricing/) for the usage fees for each model, as they vary.
<br>

## Rate limit
OpenAI has implemented rate limits from a perspective of service stability. Rate limits are measured in five ways: RPM (requests per minute), RPD (requests per day), TPM (tokens per minute), TPD (tokens per day), and IPM (images per minute).<br>
Rate limits can hit any option depending on what happens first. For example, if you send only 100 tokens per request to the ChatCompletions endpoint 20 times, you will reach the limit (if the RPM is 20) without sending 150,000 tokens in those 20 requests (if the TPM limit is 150,000).<br>
Also, rate limits vary by the user's Tier and the model being used.<br>

For more information on rate limits, please check [OpenAI's HP](https://platform.openai.com/docs/guides/rate-limits/usage-tiers?context=tier-one).



## Tier *1
Tier is divided into five stages from Tier 1 to Tier 5 based on the payment amount and the number of days elapsed since the first payment. (There is also a free tier limited to user registration only)

<div class="scroll_area" style="width:100%;max-width:800px;overflow-x:scroll;">
    <table style="width:800px;">
      <thead>
      <tr>
      <th>Tier</th>
      <th>Qualification</th>
      <th>Usage Limits</th>
      </tr>
      </thead>
      <tbody>
      <tr>
      <td>Free</td>
      <td></td>
      <td>$100/month</td>
      </tr>
      <tr>
      <td>Tier1</td>
      <td>$5 paid</td>
      <td>$100/month</td>
      </tr>
      <tr>
      <td>Tier2</td>
      <td>$50 paid and 7+ days since first successful payment</td>
      <td>$500/month</td>
      </tr>
      <tr>
      <td>Tier3</td>
      <td>$100 paid and 7+ days since first successful payment</td>
      <td>$1,000/month</td>
      </tr>
      <tr>
      <td>Tier4</td>
      <td>$250 paid and 14+ days since first successful payment</td>
      <td>$5,000/month</td>
      </tr>
      <tr>
      <td>Tier5</td>
      <td>$1,000 paid and 30+ days since first successful payment</td>
      <td>$50,000/month</td>
      </tr>
      </tbody>
    </table>
</div>

*1 Please note that the conditions for the Tier may vary, so please also refer to [OpenAI's official HP](https://platform.openai.com/docs/guides/rate-limits/usage-tiers?context=tier-one).


## Requesting to increase rate limits
Once you reach Tier2 or higher, you can request an increase in rate limits.

1. Select "Request an exception" at the bottom of the "Limits" section in your profile.
![RateLimit_01](img/RateLimit_01.png)
2. The "Request a limit increase" window will appear, enter the necessary information about the limit you want to increase, and select "Submit".
![RateLimit_02](img/RateLimit_02.png)
 * `Limit type`<br>Select one from limits per minute (RPM) / tokens per minute (TPM) / images per minute (IPM) / monthly usage limits.
 * `Model`（*）<br>Select the model you want to increase limits for.<br>(If your main use is as a chat, it will likely be 'gpt-4' / if it's for image generation, it will likely be 'dal-e')<br>
 * `Request rate limit`<br>Enter the figure you wish to request for the rate limit.
 * `Reason`Enter a brief explanation of how increasing rate limits will help and what inconveniences occur with current rate limits.

 （*） If 'Monthly usage limit' is selected for Limit type, no model selection is necessary.



## Setting a spending limit
OpenAI's models are pay-as-you-go, and usage limits can be set to manage usage fees.

1. Click on the account icon at the top right of OpenAI's home screen and select "Your profile".<br>
![API_key_12](img/API_key_12.png)<br>
1. A screen called Settings will appear, select "Billing" from the left menu, and then select "Usage limits".<br>
![API_key_16](img/API_key_16.png)<br> 




#### [Back to Home](README.md)