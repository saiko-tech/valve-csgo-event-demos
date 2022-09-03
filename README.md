# valve-csgo-event-demos

All Replay/Demo Files from Valve Sponsored CS:GO Events (Majors)


## Google Drive

https://drive.google.com/drive/folders/1WPs7WRjJKHDYOlIX1H81xFozCtVIgkQ4


## Google Cloud Storage

    gs://valve-csgo-event-demos

:information_source: The bucket has `Requester Pays` enabled, see https://cloud.google.com/storage/docs/using-requester-pays

e.g. to download all demos:

    gsutil -u <YOUR_GOOGLE_CLOUD_PROJECT_ID> -m cp -r gs://valve-csgo-event-demos .
