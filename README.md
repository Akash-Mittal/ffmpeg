# ffmpeg
Compress High Size PICS in FFMPEG and Split Big Video to 2-3 Minutes Bytes

### Below Commands will Create 5 Minutes Videos from Big videos

'''
ffmpeg -y -i 1.mpg -ss 00:00:00 -t 00:05:00 -async 1 akash-marriage-jagran-1.mp4
ffmpeg -y -i 1.mpg -ss 00:05:00 -t 00:05:00 -async 1 akash-marriage-jagran-2.mp4
ffmpeg -y -i 1.mpg -ss 00:10:00 -t 00:05:00 -async 1 akash-marriage-jagran-3.mp4
ffmpeg -y -i 1.mpg -ss 00:15:00 -t 00:05:00 -async 1 akash-marriage-jagran-4.mp4
ffmpeg -y -i 1.mpg -ss 00:20:00 -t 00:05:00 -async 1 akash-marriage-jagran-5.mp4
ffmpeg -y -i 1.mpg -ss 00:25:00 -t 00:05:00 -async 1 akash-marriage-jagran-6.mp4
ffmpeg -y -i 1.mpg -ss 00:30:00 -t 00:05:00 -async 1 akash-marriage-jagran-7.mp4
ffmpeg -y -i 1.mpg -ss 00:35:00 -t 00:05:00 -async 1 akash-marriage-jagran-8.mp4
ffmpeg -y -i 1.mpg -ss 00:40:00 -t 00:05:00 -async 1 akash-marriage-jagran-9.mp4
ffmpeg -y -i 1.mpg -ss 00:45:00 -t 00:05:00 -async 1 akash-marriage-jagran-10.mp4
ffmpeg -y -i 1.mpg -ss 00:50:00 -t 00:05:00 -async 1 akash-marriage-jagran-11.mp4
ffmpeg -y -i 1.mpg -ss 00:55:00 -t 00:05:00 -async 1 akash-marriage-jagran-12.mp4
ffmpeg -y -i 1.mpg -ss 00:60:00 -t 00:05:00 -async 1 akash-marriage-jagran-13.mp4
'''