# Conditional Access Policy Documentation - exempting users from multi-factor authentication(MFA). 

## 1. Navigate to the Microsoft teams admin panel - link to admin panel below.

https://admin.microsoft.com

## 2. Login to the admin panel with an ADMIN account.

Note - if you do NOT have admin permissions you will not be granted access.

## 3. Locate ≡ near the top left of the screen and select Show All.

<img width="465" alt="image" src="https://user-images.githubusercontent.com/44510115/191438854-91fe9bb3-6b4f-42d6-8a82-a1960f851d9a.png">

## 4. Select Azure Active Directory - located under the __Admin centers__ section.

<img width="274" alt="image" src="https://user-images.githubusercontent.com/44510115/191440450-deb55830-ee91-4d00-8066-35d10aeb7c9a.png">

## 5. Select Enterprise Applications - located under the Favorites Section.

<img width="277" alt="image" src="https://user-images.githubusercontent.com/44510115/191873655-f110ab9a-5917-4e23-97e9-cbc8da741e03.png">

## 6. Select Conditional Access - located under the security section.

<img width="267" alt="image" src="https://user-images.githubusercontent.com/44510115/191873778-cc38da18-5ea5-4beb-94e0-36fa00e1b418.png">

## 7. Create a new policy. 

<img width="668" alt="image" src="https://user-images.githubusercontent.com/44510115/191874065-1c801fe7-751c-454c-bcc7-3e3a5419df87.png">

## 8. Name the policy. 
For our use case we're going to be adding MFA for all users and add exemptions for certain users. Note, you are able to exempt *ANY* user, including admins, from policies. 

<img width="302" alt="image" src="https://user-images.githubusercontent.com/44510115/191874617-dcb63410-8221-4ab5-8883-10653c639d2b.png">

## 9. Under assignments select the Users and groups radio button. 
This will provide you with a list of groups and users on the right hand side of the page. Select the user(s) and or group(s) that you would like to exemept from MFA. 

## 10. Under Cloud apps or actions select all cloud apps. 
This will exempt the user group, selected in step 9, from MFA. 

<img width="330" alt="image" src="https://user-images.githubusercontent.com/44510115/191876153-59907802-48a1-4f16-89c5-cab6f7eff355.png">

## 11. Select access control and select the grant access radio button. Next, check the require MFA box. 
This will impose MFA on user groups selected in step 9. Make sure you press the select button at the bottom of the page after checking the MFA box. 

<img width="301" alt="image" src="https://user-images.githubusercontent.com/44510115/191888115-e8650b47-e1d3-4170-b451-d9272ff2e5f2.png">

## 12. Toggle the Enable Policy button to on. 

<img width="272" alt="image" src="https://user-images.githubusercontent.com/44510115/191888249-66acee30-b20d-49f3-9f04-00de31de24e5.png">

## 13. Create. 

<img width="267" alt="image" src="https://user-images.githubusercontent.com/44510115/191888324-52fe85e1-c5a6-4ed0-9cdd-071874a9512e.png">

## 14. You have created a MFA policy for selected user groups. 
Users in your selected group will now be required to use MFA to login. 
