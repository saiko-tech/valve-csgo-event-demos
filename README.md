# valve-csgo-event-demos

All Replay/Demo Files from Valve Sponsored CS:GO Events (Majors)


## Google Drive

https://drive.google.com/drive/folders/1WPs7WRjJKHDYOlIX1H81xFozCtVIgkQ4


## Google Cloud Storage

    gs://valve-csgo-event-demos

:information_source: The bucket has `Requester Pays` enabled, see https://cloud.google.com/storage/docs/using-requester-pays (note that this is purely to cover network traffic - the money goes to Google, not to us)

e.g. to download all demos:

    gsutil -u <YOUR_GOOGLE_CLOUD_PROJECT_ID> -m cp -r gs://valve-csgo-event-demos .

## Disclaimer

This repository and the data set is not affiliated with or endorsed by Valve Corporation or any of the event tournament organisers.

Use this data at your own risk.
