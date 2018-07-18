# react-gradle-example
How to wrap an react.js app build with gradle

## Create app
set 'appName' in build.gradle then execute

`./gradlew createApp`

1. Move package.json and package-lock.json into project dir (one level higher)
2. delete dir appName/node_modules

## Build app
set 'appName' in build.gradle then execute

`./gradlew build`

1. The distribution is created in appName/build
2. A war file is created in build/libs

## Run app
set 'appName' in build.gradle then execute

`./gradlew start`

Open your browser on http://localhost:3000/