## Welcome to MuSync
I started this project because I switch from different music streaming services and the musics that I have liked/ created into a playlist are different across platforms. This project is meant to sync music into one location, then make sure every platform has the same songs. 

### youtube Data Api v3 (done)
instructions:

1.go to https://console.developers.google.com/apis/dashboard and get a src_client_secret.json for the account with the songs.

2.run /youtube/youtube-get-my-liked-videos.py This produces a csv file with your songs and song id from authed google account.

3.go to https://console.developers.google.com/apis/dashboard and get a tgt_client_secret.json for the account you want to add the songs to

4.run /youtube/youtube-add-to-liked-videos.py This will read the csv songs and add it to the desired youtueb account.

### Spotify (coming soon)

