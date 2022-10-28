# ffmpeg-android-maker 3.3.9 or others
original author[https://github.com/Javernaut/ffmpeg-android-maker/wiki]

1.git clone 
2.install docker
3.docker
4.1 cd tools/docker 
4.2 docker build -t ffbuild:v1 .
5.docker run --rm -v {pwd}/ffmpeg-android-maker-sh:/mnt/ffmpeg-android-maker ffbuild:v1
6.look ffmpeg-android-maker-sh\output
