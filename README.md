# Jobathon Analytics Vidhya August 2022 
#### (Problem statement and solution)
![jobathan](https://user-images.githubusercontent.com/97030219/184666669-0fd56ab7-ee40-41f4-a18c-53b3d1039ae4.JPG)

### Problem statement
Most organizations today rely on email campaigns for effective communication with users. Email communication is one of the popular ways to pitch products to users and build trustworthy relationships with them.


Email campaigns contain different types of CTA (Call To Action). The ultimate goal of email campaigns is to maximize the Click Through Rate (CTR).


CTR is a measure of success for email campaigns. The higher the click rate, the better your email marketing campaign is. CTR is calculated by the no. of users who clicked on at least one of the CTA divided by the total no. of users the email was delivered to.


CTR =   No. of users who clicked on at least one of the CTA / No. of emails delivered


CTR depends on multiple factors like design, content, personalization, etc. 


* How do you design the email content effectively?
* What should your subject line look like?
* What should be the length of the email?
* Do you need images in your email template?.


### Objective
Task is to build a machine learning-based approach to predict the CTR of an email campaign.


#### About the Dataset
You are provided with the information of past email campaigns containing the email attributes like subject and body length, no. of CTA, date and time of an email, type of the audience, whether its a personalized email or not, etc and the target variable indicating the CTR of the email campaign.

#### Data Definition
Variable||Description

campaign_id ||Unique identifier of a campaign

sender ||Sender of an e-mail

subject_len ||No. of characters in a subject

body_len ||No. of characters in an email body

mean_paragraph_len ||Average no. of characters in paragraph of an email

day_of_week ||Day on which email is sent

is_weekend ||Boolean flag indicating if an email is sent on weekend or not

times_of_day  ||Times of day when email is sent: Morning, Noon, Evening

category ||Category of the product an email is related to

product  ||Type of the product an email is related to

no_of_CTA ||No. of Call To Actions in an email

mean_CTA_len  ||Average no. of characters in a CTA 

is_image ||Boolean flag indicating if an email contains an image or not

is_personalised ||Boolean flag indicating if an email is personalized to the user or not

is_quote ||Boolean flag indicating if an email contains a quote or not

is_timer ||Boolean flag indicating if an email contains a timer or not

is_emoticons ||Boolean flag indicating if an email contains emoticons or not

is_discount ||Boolean flag indicating if an email contains a discount or not

is_price ||Boolean flag indicating if an email contains price or not

is_urgency ||Boolean flag indicating if an email contains urgency or not

target_audience ||Cluster label of the target audience

click_rate (Target Variable) ||Click rate of an email campaign

Model Used : XGbooster and Adaboosting models
