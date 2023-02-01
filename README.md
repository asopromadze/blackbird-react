# Blackbird React
This repo contains the FrontEnd React Source code for [Blackbird](https://github.com/p1ngul1n0/blackbird).

## Setup

#### Clone repository
```
git clone https://github.com/p1ngul1n0/blackbird-react
```

#### Install React-Scripts
Install `react-scripts@4.0.3` so Polyfills error doesn't happens with `react-pdf` as said in https://github.com/facebook/create-react-app/issues/11756
```
npm i react-scripts@4.0.3
```

#### Start the project
```
npm start
```

#### Test
To test the React JS FrontEnd along with Blackbird tool, follow the steps below:

1. Build code
```
npm run build
```

2. Copy "build" folder content to "templates" folder in blackbird tool

3. Start blackbird WebServer
```
python blackbird.py --web
```
