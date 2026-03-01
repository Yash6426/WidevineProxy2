Install Tools

N\_m3u8DL-RE – DASH downloader

WidevineProxy2 – Chrome extension for key extraction





.wvd file



Load into WidevineProxy2





Capture MPD URL + Key

Copied MPD URL from Chrome DevTools (Network tab → filter .mpd)

Copied decryption key from WidevineProxy2 popup (format KID:KEY)





N\_m3u8DL-RE "MPD\_URL" ^

  -H "User-Agent: Mozilla/5.0 ..." ^

  -H "Referer: https://www.nextias.com/..." ^

  --key "KID:KEY" ^

  --use-shaka-packager ^

  --mp4-real-time-decryption ^

  --auto-select ^

  --thread-count 16 ^

  -M format=mkv ^

  --save-name "Lecture\_Name"











N\_m3u8DL-RE "https://chtest1snf.nextias.com/file\_library/videos/dash\_drm/41424/dash/video\_1758013198948.mpd?Expires=1771438184\&Signature=..." ^

  -H "User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/144.0.0.0 Safari/537.36" ^

  -H "Origin: https://www.nextias.com" ^

  -H "Referer: https://www.nextias.com/lms/aws?entity=..." ^

  --key "082c13a5d4f7b1481655d6c33a8e97c0:f60ba5da2ad120c733d9f84322755113" ^

  --use-shaka-packager ^

  --select-video "res=1920x1080:for=best" ^

  --select-audio "for=best" ^

  --thread-count 16 ^

  -M format=mkv ^

  --save-name "Disaster\_Management\_Lecture1\_1080p"



N\_m3u8DL-RE "https://chtest1snf.nextias.com/file\_library/videos/dash\_drm/41424/dash/video\_1758013198948.mpd?Expires=1771438184\&Signature=Nq4rcQu1Q8ZcdKiI5z~0YGF~OknsD3YqQHE7u3hWjp~Ri3i5X5qcv0iqZ57n8fcYRvMv1V3g3KOK5A4B-LWHPC9e0cMOjcjIQqSFdq6FjFkIKTgvQlxFuKQhz2PbWqIKBC27WR-nEPpJ0pAgrc2mxURlRD1bLvYWqa~S4lJ2mmGu2oWBlW1vrg-2fuzK02X8UGwVHfta2RBMK6pwG8A3lhu5UIdVUAEfl3XkFiKpJnxRiRxe~0QAadx~6VmeciCc7yTRdgAkIgj1wWhdcm799fDmdcTcQdJeqX0Ch4XkvJWI9qadgjQ-vVEw7BeNLf0MrnuVQw452qqizyajS1ivGw\_\_\&Key-Pair-Id=APKA6K4UQLEJVDX7C67F" ^

  -H "User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/144.0.0.0 Safari/537.36" ^

  -H "Origin: https://www.nextias.com" ^

  -H "Referer: https://www.nextias.com/lms/aws?entity=JTdCJTIyY291cnNlSWQlMjIlM0ElMjI1MzUlMjIlMkMlMjJuYW1lJTIyJTNBJTIyNDE0MjRfMF84Mzc3NTY4NzA4OTU5Nzg0JTIyJTJDJTIydGlsZUlkJTIyJTNBJTIyMTIxOCUyMiUyQyUyMlR5cGUlMjIlM0ElMjJ2aWRlbyUyMiUyQyUyMlVzZXJJZCUyMiUzQSUyMjk3NzkyJTIyJTJDJTIyVmlkZW9JZCUyMiUzQTQxNDI0JTJDJTIyc3ViamVjdElkJTIyJTNBJTIyNDElMjIlMkMlMjJzdWJqZWN0TmFtZSUyMiUzQSUyMkRpc2FzdGVyX01hbmFnZW1lbnQlMjIlMkMlMjJ2aWRlb1RpdGxlJTIyJTNBJTIyTGVjdHVyZV8wMSU1QjE2LjA5LjIwMjUlNUQlMjIlN0Q=" ^

  --key "082c13a5d4f7b1481655d6c33a8e97c0:f60ba5da2ad120c733d9f84322755113" ^

  --use-shaka-packager ^

  --mp4-real-time-decryption ^

  --auto-select ^

  --thread-count 16 ^

  -M format=mkv ^

  --save-name "Disaster\_Management\_Lecture1"





referurl - https://www.nextias.com/lms/aws?entity=JTdCJTIyY291cnNlSWQlMjIlM0ElMjI1MzUlMjIlMkMlMjJuYW1lJTIyJTNBJTIyNDE0MjRfMF84Mzc3NTY4NzA4OTU5Nzg0JTIyJTJDJTIydGlsZUlkJTIyJTNBJTIyMTIxOCUyMiUyQyUyMlR5cGUlMjIlM0ElMjJ2aWRlbyUyMiUyQyUyMlVzZXJJZCUyMiUzQSUyMjk3NzkyJTIyJTJDJTIyVmlkZW9JZCUyMiUzQTQxNDI0JTJDJTIyc3ViamVjdElkJTIyJTNBJTIyNDElMjIlMkMlMjJzdWJqZWN0TmFtZSUyMiUzQSUyMkRpc2FzdGVyX01hbmFnZW1lbnQlMjIlMkMlMjJ2aWRlb1RpdGxlJTIyJTNBJTIyTGVjdHVyZV8wMSU1QjE2LjA5LjIwMjUlNUQlMjIlN0Q=





N\_m3u8DL-RE --help







|<br />PSSH Data|AAAAW3Bzc2gAAAAA7e+LqXnWSs6jyCfc1R0h7QAAADsIARIQCCwTpdT3sUgWVdbDOo6XwBoKZG92ZXJ1bm5lciIZNDE0MjRfdmlkZW9fMTc1ODAxMzE5ODk0OA==|
|-|-|
|Fresh MPD URL|https://chtest1snf.nextias.com/file\_library/videos/dash\_drm/41424/dash/video\_1758013198948.mpd?Expires=1771438184\&...|
|Decryption Key|082c13a5d4f7b1481655d6c33a8e97c0:f60ba5da2ad120c733d9f84322755113|
|All Required Headers|User-Agent, Referer, Origin, etc|





WidevineProxy2\_v0.9.0

v Last week

Disaster\_Management\_Lecture1.mkv

shaka-packager.exe

WidevineProxy2\_v0.9.0.xpi

ffmpeg.exe

ffplay.exe

ffprobe.exe

v A long time ago

N\_m3u8DL-RE.exe



https://github.com/nilaoda/N\_m3u8DL-RE/releases   v-- x64
https://github.com/DevLARLEY/WidevineProxy2

wvd file


https://emarsden.github.io/pssh-box-wasm/convert/


https://forum.videohelp.com/

