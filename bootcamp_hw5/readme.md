# Weather Alert Project

## Step 1: Use code in `weather_alert.ipynb`
- Define the functions
- Create schema
- Load raw data
- Get forecast with external API
- Use Gemini to generate alert
- Save result to BigQuery table

## Step 2: Create Scheduler
- Create bucket
- Create hourly scheduler
- Check `scheduler_hourly.png` for details

## Step 3: Report in Looker
1. Generate a new column called `geopoint` using latitude and longitude
2. Insert Google Map
3. Use `geopoint` as location
4. Use airport name as tooltip
5. Generate a single-column table with only `generated_text` (shown as text)  

**Note:** Enable Google Chart cross-filtering. When a user clicks on a map point, the corresponding generated text in the table will update.

I can not share the report link with student account, so report screen short is attached.
