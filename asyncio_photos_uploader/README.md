# Google Photos Uploader

## How it works

Choose a folder with photos and then the script uploads all photos cocurrently to a new album.

## Usage

Install the requirements:
``` sh
$ pip install requirements.txt
```

Get your credentials on [google console](https://developers.google.com/photos/library/guides/get-started) and name it `client_id.json`.

Use this command to start your upload:
```sh
$ python uploader.py $folder_name $album_name
```

**OBS**: The current authorization method is depecrated by google.
