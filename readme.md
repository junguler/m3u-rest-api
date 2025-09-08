## Simple Rest Api
simple rest api for m3u/m3u8 playlists, made with chatgpt

### how to use
create a copy/fork of this repo, place your m3u/m3u8 playlists in the `playlists` folder, go to the settings page of your repo, in the `pages` section set `Build and deployment` source to `Github Actions` and it will make your api

which each update to this repo this api will be rebuilt, meaning changing the playlists will be shown in the api automatically

### address to your api
your api's main page will be at ``https://your_github_name.github.io/your_repo_name/api/index.json``

the sub pages are all listed there, just replace `index.json` at the end of the link with the name of your playlist like 'rock.json' so the final link will be ``https://your_github_name.github.io/your_repo_name/api/playlists/rock.json``

### example player using this api
here is a simple player that is made using this rest api and chatgpt, see it in action here [repo](https://github.com/junguler/m3u-player-web) and [webpage](https://junguler.github.io/m3u-player-web/)