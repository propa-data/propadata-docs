
# What is Propa Data Management App

The **Propa Data Management App** is a platform built on **DHIS2**, designed to help organizations collect, manage, and analyze data related to fish traders.  
It provides tools for **data entry, validation, visualization, and reporting**, supporting both **individual trader-level records** and **aggregate data** at higher administrative levels.

## Propa Data Management App

### Login Page

Access the platform here  [Propa Data Platform](https://fishtrader.exhaustivesoln.com/propa-data/dhis-web-login/)   and insert the login credentials i.e **username** and **DHIS2** as provided.

![Web Login Landing Page](images/web-login.png)

### Dashboards

Once logged in, you will see **custom dashboards** that summarize key indicators, trader activities, and survey results.  
These dashboards provide quick insights for monitoring and decision making.

![Dashboards](images/image41.png)

### Applications

Propa Data integrates several DHIS2 apps to handle different tasks.  
You can access these apps from the **App Menu** (grid icon at the top right corner).

Examples include:  
- **Data Entry App**: For entering aggregate data.  
- **Capture App**: For registering traders and recording events.  
- **Event Reports & Data Visualizer**: For analyzing and visualizing data.  
- **Dashboard App**: For quick access to key performance metrics.  
- **PropaData Notifications App**: For creating and dispersing notifications.  

![App Highlights](images/image42.png)

## Maintenance App

The **Maintenance App** is where administrators configure the core building blocks of the Propa Data Management System.  
Here you can define **data elements, attributes, indicators and option sets** that power data entry, analysis and reporting.

![maintenance app](images/image49.png)

### 1. Data Elements
Data elements are the **basic units of information** collected in the system (e.g., *Trader Age*, *Training Completed*, *Business Type*).  
They are the raw data fields used in forms, programs, and indicators.  

- **Example:** *Traders with registered businesses*.  

![maintenance app](images/image50.png)

### 2. Option Sets
Option sets define **predefined lists of choices** for data entry fields.  
This ensures standardization and avoids inconsistent answers.  

- **Example:** Gender (Male, Female), Business Type (Retail, Wholesale, Fish Processor).  


### 3. Indicators
Indicators are **custom calculations** created from data elements, attributes, or other indicators.  
They turn raw data into **meaningful measures** for monitoring and reporting.  

#### Creating an Indicator
1. Open the **Maintenance App** → *Indicators*.  
2. Click **+ Add New** and provide:  
   - **Name** → e.g., *Digital Skills Completion Rate*  
   - **Short Name** → used in charts/tables  
   - **Description** → purpose of the indicator  
3. Build the **Formula**:  
   - **Numerator** → Traders who completed training  
   - **Denominator** → Total enrolled traders  
4. (Optional) Add it to an **Indicator Group** for easy categorization.  
5. Save and test it in the **Data Visualizer** app.  

## Data Entry App

The **Data Entry app** in Propa Data is used to capture **aggregate information**.  
Aggregate data refers to information collected at a **group level** (i.e, ward, sub-county, county) rather than for a single individual.  

Typical aggregate entries in Propa Data include:

- Number of **traders registered** in a given period.  
- Number of **surveys completed** by in a certain ward.  
- Counts of **activities** (trainings, market visits, outreach events).  

![Data entry app](images/image43.png)

### How the Data Entry App is Organized

Propa Data uses a **hierarchical organisational structure**, so all data must be linked to the correct level:

1. **County**  
2. **Sub-County**  
3. **Ward**

> 🔑 **Important:** All aggregate data (registrations, surveys, activities) must be entered under your **assigned ward**. This ensures that reporting and dashboards reflect the correct geographic location.


### Key Features of the Data Entry App

- **Organisation Unit Selection**  
  Choose your ward (or higher level if authorised) before entering data.  

- **Dataset Selection**  
  Different datasets represent different forms, e.g., *Trader Onboarding*, *Survey Completion* or *Activities Report*.  

- **Period Selection**  
  Enter data for a specific reporting period (weekly, monthly or quarterly, depending on the dataset).  

- **Forms**  
  Data entry forms may include numbers, yes/no fields or options. Required fields are highlighted.  

- **Validation**  
  Before saving, the system checks your entries (i.e., missing or invalid values).  

- **Save & Complete**  
  - Use **Save** if you’re still working on the form.  
  - Use **Complete** when all data is filled in correctly. Completed forms lock the period for that dataset.  

## Capture App

The **Capture app** in Propa Data is used to register **events** — activities or records that happen at a specific **time** and **place**.  
Unlike routine aggregate data (collected at regular intervals), events are logged as they occur, and each event can carry detailed information.  

### How it Works in Propa Data

- Events are tied to a **program**.  
- In this case, Propa Data uses the **Fish Trader Program**.  
- Traders are treated as **tracked entities**, meaning:  
  - You can **search existing traders** using attributes such as **phone number, names or trader ID**.  
  - You can also **register new traders** into the program if they don’t already exist.  
- Each event is linked to a **date** and **organisation unit** (e.g., your assigned ward).  

![Capture app](images/image44.png)

### Typical Uses of the Capture App

- **Registering new traders** into the Fish Trader Program.  
- **Onboarding assessments** (e.g., digital skills survey).  
- **Recording trader activities** such as training sessions, market attendance, or extension visits.  
- **Longitudinal follow-up** of traders across multiple events (e.g., training → survey → progress checks).  


## Data Visualizer

The **Data Visualizer App** is a powerful tool for program officers to analyze and present data collected in Propa Data.  
It allows you to create **charts, tables, and pivot views** that help monitor program performance and compare results across different groups or locations.  


### How to Build a Chart

Follow these steps to create your own visualizations:

#### 1. Select Your Data
- Choose the **data element** or **indicator** you want to visualize (e.g., *Digital Skills Assessment Completed*).  
- You can select one or multiple indicators depending on the type of chart.  

![Data Selection](images/image45.png)


#### 2. Select the Time Period
- Choose either a **Relative Period** (e.g., *Last month*, *This quarter*, *This year*)  
- Or a **Fixed Period** (e.g., *January 2025*, *Q1 2025*).  

![Period Selection](images/image46.png)

#### 3. Select Organisation Units
- Navigate through the hierarchy (**County → Sub-County → Ward**).  
- Select the area(s) you want to analyze.  

![Org Unit Selection](images/image47.png)


#### 4. Choose the Chart Type
- Decide how you want to present your data:  
  - **Bar chart** (good for comparisons)  
  - **Line chart** (good for trends over time)  
  - **Pie chart** (good for proportions)  
  - **Tables / Pivot tables** (for detailed breakdowns)  


### Example Output
Here is a **pie chart** showing **male vs. female traders** who have completed the **Digital Skills Assessment**.  

![Pie Chart Example](images/image48.png)

You can also **download or share** your charts directly from the visualizer.  

