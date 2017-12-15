# 网易云音乐API
## 1、search
> * url: http://music.163.com/api/search/get/
> * method: post
> * parameter: s:search limit:number sub:false type:1

## 2、song information
url: http://music.163.com/api/song/detail/?id=song_id&ids=[song_id]
method: get
parameter: id:song_id ids:[song_id]

## 3、singer album
url: http://music.163.com/api/artist/albums/?id=singer_id&offset=0&total=true&limit=number
method: get
parameter: id:singer_id offset:0 total:true limit:number

## 4、album information
url: http://music.163.com/api/album/album_id?ext=true&id=album_id&offset=0&total=true&limit=
method: get
parameter: id:album_id ext:true offset:0 total:true limit:number

## 5、playlist
url: http://music.163.com/api/playlist/detail
method: get
parameter: id:playlist_id
my_playlist_id:565510145
飙升榜: 19723756
新歌榜: 3779629
原创榜: 2884035
热歌榜: 3778678
Billboard: 60198
iTunes: 11641012
HongKong: 10169002



## 6、lyric
url: http://music.163.com/api/song/lyric
method: get
parameter: id:song_id lv:-1 kv:-1 tv:-1

## 7、mv
url: http://music.163.com/api/mv/detail?id=mv_id&type=mp4
method: get
parameter: id:mv_id type:mp4

## 8、toplist
url: http://music.163.com/#/discover/toplist?id=toplist_id
method: get
parameter: id:toplist_id

## 9、comment
url: http://music.163.com/weapi/v1/resource/comments/R_SO_4_song_id
method: post
parameter: csrf_token:? params:? encSecKey:?

## 10、play
url:http://music.163.com/outchain/player?type=2&id=${song.id}&auto=1&height=32

