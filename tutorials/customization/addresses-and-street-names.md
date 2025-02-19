---
description: >-
  Sonoran CAD allows you to upload custom street names to auto-populate in the
  dispatch call editor.
---

# Addresses and Street Names

{% hint style="warning" %}
Community customization requires the **plus** version of Sonoran CAD or higher.  
For more information, see our [pricing](../../pricing/faq/) or view how to check your community [limits](../getting-started/view-your-limits.md).
{% endhint %}

## Import Street Names from a Spreadsheet \(CSV\)

### 1. Copy the Google Sheet

Navigate to our official [street name Google sheet](https://docs.google.com/spreadsheets/u/1/d/1wMEiv1EcDI4VnTjCLbechJHzUEQoMQTK_ujWU3BfKIk/copy) and make a copy. Using a copy of our official sheet ensures your street names are formatted correctly.

![Sonoran CAD - Copy Street Name Spreadsheet](../../.gitbook/assets/image%20%28118%29.png)

### 2. Add Your Street Names

Now that you have copied this sheet into your Google Drive, you can add new rows and format your street names and addresses.

{% hint style="warning" %}
**Do NOT add additional columns.**  
Every street name must be on a separate row to be properly imported into Sonoran CAD.
{% endhint %}

![Sonoran CAD - Street Names CSV](../../.gitbook/assets/image%20%28116%29.png)

### 3. Download the CSV

In Google Sheets, navigate to File &gt; Download &gt; Comma Separated Values \(.csv\) to download the file.

![Google Sheets - Download CSV](../../.gitbook/assets/image%20%28119%29.png)

### 4. Import the CSV File

In Sonoran CAD, navigate to Admin &gt; Customization &gt; Customization &gt; Addresses

In the addresses section, select the "Import" button.  
Then, select "CSV" as the import type and select your downloaded CSV file.

![Sonoran CAD - Import Data](../../.gitbook/assets/image%20%28109%29.png)

![File Selector - Select CSV](../../.gitbook/assets/image%20%28117%29.png)

After selecting the CSV file, your street names and addresses will be imported into the CAD and saved automatically.

### 5. View the Call Editor

In the dispatch call editor, the `address` section is now a dropdown. This dropdown will auto-filter and suggest your street names and addresses as you type.

![](../../.gitbook/assets/addresses.gif)

### 6. Utilize in Custom Records

Custom records can also have a field with the type set to `address`. This field will auto-filter the same list of street addresses from your gamemode.

![Custom Records - Address Field](../../.gitbook/assets/90433cf83d1d487c05d18ea392289815.gif)

