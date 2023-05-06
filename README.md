# ZOHO CRM WIDGET STARTER TEMPLATE

## Requirements ! MUST HAVE !!

1. First, make sure you have all requirements to create simple zoho crm widget, please refer to this article https://help.zwidgets.com/help/v1.1/index.html.

```
npm install -g zoho-extension-toolkit
```

2. Then, clone the repository

```
git clone https://github.com/vjbautista8/zoho-crm-widget-starter-template-ReactJS.git
```

2. To install dependencies in `crm_app` folder, change the directory of cmd to `/crm_app`, then run the following command;

```
npm install
```

3. To install dependencies in `react_app` folder, change the directory of cmd to `/react_app`, then run the following command;

```
npm install
```

## How to run locally

1. In your cmd, make sure your command path is `/react_app`, then run the following command

```
npm run zoho-crm
```

In your Zoho Creator Widget External Link

```
https://127.0.0.1:5000/app/index.html
```

2. Edit the code like normal React JS application.

## How to build and deploy to Zoho CRM

1. Build your application. Make sure your directory in cmd is `/react_app` folder, then run the following command

```
npm run build
```

2. Go to `/crm_app/dist` folder, you will find `crm_app.zip`.
