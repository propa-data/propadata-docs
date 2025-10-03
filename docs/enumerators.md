# Enumerator App Guide
_The Enumerator App is a mobile application for implementing partners to support participants who may not self-register. It facilitates structured data collection, onboarding, and performance monitoring at the field level._

The Enumerator App (DHIS2 Data Capture) is used by field officers to onboard participants into the system, capture assessments, and sync data with the central Propa Data server. 
 
This guide explains how enumerators can **Log in**, **Register Participants** and  Submit  participants survey data.

The Enumerators App includes the following key modules:

* **Participant Registration & Onboarding**: Implementing partners register and onboard participants onsite.

- **Activity Data Collection**: Field staff capture real-time participant activity data including business profiles, market interactions, and product details.

- **Performance Tracking**: Enables entry and monitoring of program targets, output metrics, and performance indicators.

- **Secure access**: Secure and role-based authorized access

- Also ensures **data consistency** and supports **offline syncing**

> NOTE:
>
> For Enumerators they are required to:

- **Sync data** at the beginning and end of each day in a place with a stable internet connection.  
- **Always Search** participants first before adding/registering new participants to avoid duplicates.  
- **Complete all forms** before submitting.  
- **Keep your device charged** while in the field.  
- **Report any issue immediately** if you experience  **system errors** during onboarding or syncing 

## Download & Install the Data Capture App

You will first download the app from **Google Play Store** the **DHIS2 Data Capture App**.  
Click the download button to install if not installed yet, [Download](https://play.google.com/store/search?q=dhis2%20capture&c=apps).

## Login
- Open the Data Capture App.  
- Enter your **Username** & **Password** then paste the **Server URL** as below:
- **Server URL**:
```bash
 https://fishtrader.exhaustivesoln.com/propa-data
```
- Then tap the **Login** button to access the system.

![dHIS2 CAPTURE APP LOGIN PAGE  FOR ENUMERATORS](images/image15.png)


- Upon successful login, you'll access the Home Dashboard featuring all available programs and surveys.

![Landing Home Page](images/image61.png)

## Participant Management

### Searching for a Participant

- Select the relevant **program or survey** as directed.  
   - In this demo, we will use the **PropaData Integrated Questionnaire** program

- Enter a search attribute such as:  

   - **Phone Number**  
   - **First or Last Name**  
   - **Participant ID**  

- Then click the **Search** button at the bottom of the page to view search results.

![Search attributes](images/image81.png)


#### Existing Participant

If the participant exists in the selected program, their **full profile details** will be displayed.  
For example, the screenshot below shows an existing self-registered user:

![Existing participant](images/image18.png)

#### Non-Existing Participant

- If the participant is **not found** within the selected program, expand the search to cover the **entire platform** by clicking on the **Search outside this program** button.  

![Search outside program](images/image82.png)

- If the partcicipant still is not yet registered in other programs, tap the **+ New Trader** button to register/onboard  them.  

![Register new participant](images/image83.png)


### Onboarding A New participant

#### Select Organisation Unit
Each participant must be linked to their ward.  

- Search by **Ward**.  
- Select the correct location.  
- Tap **Done** to confirm.  

![org unit search by ward](images/image84.png)

#### Adding Participant Attributes
After selecting the participants Organisation unit you will be directed to the participants registration form which you'll add now the participant details.

- Fill in all **mandatory fields** (marked with an asterisk *).  
- A **Participant ID** will be generated automatically.  

![participant attributes](images/image85.png)

After completing to fill the form click on the save icon which is on the bottom right of the page with a blue background to save the participant details.

![participant attributes](images/image86.png)

#### Preview Traders Form

![preview participant attributes](images/image87.png)

####  Addind A Note
One can add simple notes from the notes section.

![adding a note](images/image88.png)

## Survey Enrollment
After onboarding a participant, the available surveys which they can participate in will be listed. Select the appropriate survey to begin.  

- In this demo, we’ll use the **PropaData Integrated Questionnaire** survey as an example.

- Click on the **Enter Activity**  to open the enrollment form.

![survey enrollment](images/image89.png)

### Completing a Survey Form
- Start by selecting the **Enrollment Date** and **Assessment Date**.  
- Then proceed to enter the required survey fields according to your data collection protocol.  

![survey enrollment](images/image90.png)

#### Saving Survey Details
- Once the form is filled in, click the blue **Save** icon at the bottom right of the page.  

![survey enrollment](images/image91.png)

You’ll then have the option to:  
   - **Complete** – Save and mark the survey as finished.  
   - **Not Now** – Save the survey as a draft for review or completion later.  

![survey enrollment](images/image92.png)


#### Adding Notes to Surveys
- During data collection, you can attach notes for additional clarity.  

- To add a note, click on the **Notes** button to open the notes page.  

![adding notes](images/image32.png)

- Tap **+** button to add your note.
- Type your note and save.  
- Review any previously saved notes linked to the same survey.  

![adding notes](images/image33.png)


## Settings

- From the home page, click on the navigation bar **(menu icon)** to navigate to the navbar section.

![Navbar](images/image62.png)

>  🔑 **Important:** **Do not** tamper or tap on the settings, apart from the one's highlighted below and how to go about them.

### Set PIN Code
From the Side Navbar section click on the Set Pin with a **(Padlock icon)** where you'll be prompted to set a **4-digit PIN** of your liking but **Secure** for faster login access.

>  📝 **NOTE:** After setting the pin you'll be logged out of that section and you'll be prompted to insert the **New Pin** which you have set to have access to the system again.


![Set Pin](images/image63.png)

### Sync Data

- Go to: **Settings** then click on the **Sync data**   which is on the first row of the different settings.
- Enable: **Sync Data Now** if you have a strong stable internet connection but when under internet connection the sync happens automatically after every one hour.
- After the sync the **Last sync on** will update to the current time you have done the sync

![Sync Data Settings](images/image64.png)

### Sync Configuration

- Still on the **Settings**  click on the **Sync Configuration**   which is on the second row of the settings.
- Enable: **Sync Configuration Now** if you have a strong stable internet connection but when under internet connection the settings auto update automatically after one day.

![Sync Configuration Settings](images/image65.png)

### Reserved Values
Reserved values allow enumerators to register participants and collect data **offline**, by using pre-downloaded unique identifiers.

- Go to: **Settings → Reserved Values**  

![Reserved Values](images/image66.png)

- Click on the **Manage Reserved Values** .  

- From there you will be directed to another page indicating how many reserved values you have left, in this case it will be **100** then click on **REFILL** to have the reserved the values.

![Refill Reserved Values](images/image67.png)

### Manual Sync
For the **Sync Data** you can also do it from the Homepage section by clicking on the **Sync Icon** (top-right corner)

![Sync Data Icon](images/image70.png)  

- You should always **Manually Sync** before starting field work and after finishing the day under a stable internet connection.

- This will update participant records and submit any unsynced data.  

#### Successful sync
- After a successful sync a green notification will be displayed with sync successfull.

![Sync Data](images/image68.png)  

#### Sync Error
- Incase the sync fails the app will highlight the specific issue why the the sync has failed. But incase it still fails after making changes contact the administrators for more assistance.

![Sync error](images/image71.png)

<!-- - You can also highlight 
![Search params](images/image69.png) -->

