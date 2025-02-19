# 10-Codes

## What are 10-Codes?

10-Codes are used to differentiate and abbreviate dispatch situations.  
Ex: 10-10: Fight in Progress

### Modify 10-Codes

Under Admin &gt; Customization &gt; 10-Codes you can add, edit, or remove 10-codes for your community.

![Sonoran CAD - 10-Codes](../../.gitbook/assets/image%20%28113%29.png)

### My locality doesn't call them "10-Codes"

Sonoran CAD allows you to change the naming of "10-Codes" to anything else you'd like.  
Learn more about our [geographical customization](geographical-settings.md).

## Import 10-Codes from a Spreadsheet \(CSV\)

### 1. Copy the Google Sheet

Navigate to our official [10-code Google sheet](https://docs.google.com/spreadsheets/u/1/d/1QKKhrwBQQW2JMqeDplU_alo_CHPi0ML4KlYOEuPN4vs/copy) and make a copy. Using a copy of our official sheet ensures your 10-codes are formatted correctly.

![Sonoran CAD - Copy 10-Codes Spreadsheet](../../.gitbook/assets/image%20%28114%29.png)

### 2. Add Your 10-Codes

Now that you have copied this sheet into your Google Drive, you can add new rows and format your 10-codes.

{% hint style="warning" %}
**Do NOT add additional columns.**  
Every 10-code must be on a separate row to be properly imported into Sonoran CAD.
{% endhint %}

![Sonoran CAD - 10-Codes CSV](../../.gitbook/assets/image%20%28115%29.png)

### 3. Download the CSV

In Google Sheets, navigate to File &gt; Download &gt; Comma Separated Values \(.csv\) to download the file.

![Google Sheets - Download CSV](../../.gitbook/assets/image%20%28110%29.png)

### 4. Import the CSV File

In Sonoran CAD, navigate to Admin &gt; Customization &gt; 10-Codes

In the 10-codes section, select the "Import" button.  
Then, select "CSV" as the import type and select your downloaded CSV file.

![Sonoran CAD - Import Data](../../.gitbook/assets/image%20%28109%29.png)

![File Selector - Select CSV](../../.gitbook/assets/image%20%28112%29.png)

After selecting the CSV file, your 10-codes will be imported into the CAD and saved automatically.

## Import from JSON

You can also build and format your 10-Codes directly into JSON. These JSON formatted 10-Codes can then be pasted directly into the UI.

### 1. Format the JSON Structure

The JSON structure is an string array. Be sure to strictly follow the format.

```javascript
[
  "10-10: Fight In Progress",
  "10-11: Dog Case",
  "10-15: Civil Disturbance",
  "10-16: Domestic Problem",
  "10-17: Meet Complainant",
  "10-25: Report in Person (Meet)",
  "10-31: Crime in Progress",
  "10-32: Man with Gun",
  "10-33: Emergency",
  "10-34: Riot",
  "10-35: Major Crime Alert",
  "10-37: Suspicious Vehicle",
  "10-45: Animal Carcass",
  "10-46: Assist Motorist",
  "10-52: Ambulance Needed",
  "10-55: Intoxicated Driver",
  "10-56: Intoxicated Pedestrian",
  "10-57: Hit and Run",
  "10-59: Escort",
  "10-70: Fire Alarm",
  "10-73: Smoke Report",
  "10-80: Chase in Progress",
  "10-89: Bomb Threat",
  "10-90: Bank Alarm",
  "10-91: Pick Up Prisoner / Subject",
  "10-92: Improperly Parked Vehicle",
  "10-94: Street Racing",
  "10-96: Mental Subject",
  "10-98: Prison / Jail Break"
]
```

### 2. Import the JSON Structure

In Sonoran CAD, navigate to Admin &gt; Customization &gt; 10-Codes

In the penal codes section, select the "Import" button.  
Then, select "JSON" and paste the JSON string array of 10-codes.

![](../../.gitbook/assets/image%20%28109%29.png)

![Sonoran CAD - Paste JSON Content](../../.gitbook/assets/image%20%28121%29.png)

After pasting the JSON content, your 10-codes will be imported into the CAD and saved automatically.

