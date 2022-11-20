# NickPersonalPageFrontend

## This is a persional website frontend project

> The original react project is clone from matrial ui template:
> [Berry Free - React Material Admin Dashboard
> ](https://mui.com/store/items/berry-react-material-admin-free/)

## Try on local

1. clone this project
2. `npm install`
3. `npm run start`
4. Access to `localhost:3000`

## My Deploy

You can try on: [My Host](http://nickwang.online:8089/)

## How to deploy

1. Jenkins CI will run `npm run build`, and push the static file to personal nexus registry.

2. And anthor CD job will pull the static to SpringBoot static folder and build via `mvn clean package`
