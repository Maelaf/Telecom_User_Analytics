# Telecom_User_Analytics

An advertising company is running an online ad for a client with the intention of increasing brand awareness. The advertiser company earns money by charging the client based on user engagements with the ad it designed and serves via different platforms. To increase its market competitiveness, the advertising company provides a further service that quantifies the increase in brand awareness as a result of the ads it shows to online users. The main objective of this project is to test if the ads that the advertising company runs resulted in a significant lift in brand awareness. 
Data
The BIO data for this project is a “Yes” and “No” response of online users to the following question

Q: Do you know the brand Lux?
		O  Yes
		O  No

This is a test run and the main objective is to validate the hypothesis algorithm you built. SmartAd ran this campaign from 3-10 July 2020. The users that were presented with the questionnaire above were chosen according to the following rule:

* Control: users who have been shown a dummy ad
* Exposed: users who have been shown a creative (ad) that was designed by SmartAd for the client. 

<h1>Fields</h1>
* auction_id: the unique id of the online user who has been presented the BIO. In standard terminologies this is called an impression id. The user may see the BIO questionnaire but choose not to respond. In that case both the yes and no columns are zero.
● experiment: which group the user belongs to - control or exposed.
● date: the date in YYYY-MM-DD format
● hour: the hour of the day in HH format.
● device_make: the name of the type of device the user has e.g. Samsung
● platform_os: the id of the OS the user has. 
● browser: the name of the browser the user uses to see the BIO questionnaire.
● yes: 1 if the user chooses the “Yes” radio button for the BIO questionnaire.
● no: 1 if the user chooses the “No” radio button for the BIO questionnaire

