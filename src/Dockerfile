FROM tmvdl/android:app

WORKDIR /app

COPY app .

RUN cordova platform add android

RUN cordova build android
