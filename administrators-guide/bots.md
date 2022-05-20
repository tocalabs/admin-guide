
# Bots (Administrator)




#### Bots

You can manage all the Bots for a platform from a single place in the Admin panel. From here you can manage which user each Bot is assigned to, what actions the Bot has access to, the capabilities of each Bot and you can also turn the Bot on and off.
To navigate to the Bot section of the Admin panel, first go to the Admin Panel and then click on the Bots icon.

![Bots 1](https://docs.toca.io/hs-fs/hubfs/Bots%201.png?width=602&name=Bots%201.png) 

If you wish to add a new Bot to your platform you must contact [support@Toca.io](mailto:support@tocabot.io). 


#### Bot services

A Bot is made up from 5 different services and these are as follows:


- Bot


- Screen


- Orchestrator


- Office


- OCR


- Drivers


- Python

A bot will run with only the Bot and Screen service installed but for the full experience you can install all the other services.
To install a service, click on the Bot you wish to install the service on and click on the Services tab.

![Bots 2](https://docs.toca.io/hs-fs/hubfs/Bots%202.png?width=602&name=Bots%202.png) 

On the Services tab you will see all the services which are available to install alongside the services which are already installed.

![Image](https://lh6.googleusercontent.com/VxxwxOgYVYe8DJ9j3IE3dkNFqbP5pJwWrWD3EOsKZa0l_Y4EypFlJmW58dYFSuDUNRt2SjraQezyifxrprRnerk5TYzacCUQm4ZqhwpD_5zGe92egjRMchttERpvKhu9Mgx0qfSY) 

If a service is not installed then the State will be "*Not Installed*".


![Bots 4](https://docs.toca.io/hs-fs/hubfs/Bots%204.png?width=602&name=Bots%204.png) 

To  install it you can tick the box and then press Install Service at the bottom of the table.
Click INSTALL SERVICES.

![Image](https://docs.google.com/drawings/u/0/d/ssEDeCLcLAN7B0PfdYsCnCg/image?w=602&h=59&rev=7&ac=1&parent=1021Hys0a2A5pml4_OnXLucoUj01SY38hCWhwtsvqraM) 

 
The Bot will start to download the new service. You can check on the progress of the download by checking the State column.

![Bots 5](https://docs.toca.io/hs-fs/hubfs/Bots%205.png?width=602&name=Bots%205.png) 

When a service finishes installing, it will show you the configuration that the Bot is set up with, usually leaving all configuration to its default settings is fine.

![Image](https://lh6.googleusercontent.com/FFC_sdHnRh9L_bZy7wWAbzuI6AFyYwhv-2AKOtf11gtBDJ9mdC0OIJPGAJW1jj4BkzMdlBHQWfb4bAvRc_8T2INzERyfhrDJiGELK3t4wf5QcDHlLIzZyCl7dIY7Bc3t8MwhpRI2) 

Click APPLY CONFIG when you are happy with the configuration and the service will start running automatically.

#### Change service configuration

If you ever need to change the configuration on a Bot service, maybe to turn an experimental feature on or off, then you can also change the config from the Bot section in the Admin panel.
Navigate to the Bot you wish to update and click on the Services tab. 

![Bots 8](https://docs.toca.io/hs-fs/hubfs/Bots%208.png?width=602&name=Bots%208.png) 

Find the service you wish to change the configuration of and press the config option of the service.

![Bots 9](https://docs.toca.io/hs-fs/hubfs/Bots%209.png?width=602&name=Bots%209.png) 

Change whatever configuration is required and then click Apply Config. This will stop the Bot service and leave it in the *Configured* state.


![Image](https://lh3.googleusercontent.com/xS87Ds85LNPA5FjlFwxVDZM5iha0PKn8Ka-xM07o5Igi4sPF15M02rncZJWezcIhVn3--vxbR20fLHK2bPRJg22ybRTqRKNzNwS0FyFYr4HmWnuuFJBEiEgjOhlH8C-RHPiky8Jy) 

To start the service after it is configured, press the play button to the left of the service.

![Bots 11](https://docs.toca.io/hs-fs/hubfs/Bots%2011.png?width=414&name=Bots%2011.png) 

This will then start the service up using the new configuration.

![Image](https://lh3.googleusercontent.com/OuS_R43QLrN42vx1oIFpOaP146PgiomYeDQ391ui7rPbT4vSKbN59etk4QXzPAkaaRynTc_Nz--w2j_51NRBoBm6wFUdgepm3GWOz6Cz3nduI7G24t6dfHfGx-RBym1tWyPG4Owr) 


#### Start and stop services

Sometimes it is necessary to stop a service and restart it or simply stop it if the Bot is no longer needed. To do this, each Bot service comes with a Play/Stop button allowing you to simply and quickly bring up and tear down services when necessary.
Identify the Bot you wish to turn on/off and then find the service on the Bot you wish to turn on/off.
To turn a service off, press the Stop icon which appears to the left of every Bot service.

![Bots 13](https://docs.toca.io/hs-fs/hubfs/Bots%2013.png?width=563&name=Bots%2013.png) 

To turn a service back on, press the Play icon.

![Bots 14](https://docs.toca.io/hs-fs/hubfs/Bots%2014.png?width=283&name=Bots%2014.png) 


#### Assign action builds

A Bot has access to actions via something called an Action Build. An action build is simply a collection of the latest actions built into a format which a Bot can understand. If a Bot does not have an Action Build then it cannot run any actions and if a Bot has a very old Action Build then it won't have the latest actions. It is a good idea to keep Bots up to date with the latest Action Builds available on the platform.
To assign an Action Build to a Bot select the Bot you want and click on the BOT tab.

![Bots 15](https://docs.toca.io/hs-fs/hubfs/Bots%2015.png?width=602&name=Bots%2015.png) 

The second property under the Bot tab is the property for Action Builds, labelled Build ID.

![Image](https://lh3.googleusercontent.com/K901fPHZr-Skqs18aqCgNSEYuiAN5PF6noCrJU_DneM3wR-_1OysQ9LtSZ19IrzqkcmK_lHYI8f3QE1CVMYENWWfqmpWrzSrzY-meoCqv7tqax5rN-uTOkN0mGolpYfUs2onGXF6) 

As we can see, the build shown in the screenshot is 23 days out of date. To update it just click the refresh button.

![Bots 18](https://docs.toca.io/hs-fs/hubfs/Bots%2018.png?width=242&name=Bots%2018.png) 

Once you click this you'll get a notification saying the action build is updating.

![Image](https://lh6.googleusercontent.com/2N2N6b19D6n2xi80Fvpsui6SAjqC13QcK7MxvdXqx7FeErPZ-FDaxoCyOH8-EIOLxOZe2e6cN21hCbdddMNwk68KwheQrSlX6t3DZnpoFeNuFWu7FDzBcXrCSVTCz2y_L2E91eRP) 

Once it has finished updating you'll see that it says *Up to date* next to the Build ID and the refresh button is greyed out as we are running the latest actions on the Bot.


![Image](https://lh5.googleusercontent.com/NuUDLJjt1nHtfO7MopvG1Nu0D8QHhhSmQd6JdVN-_4EmqLjwQVYdx2ZDtmPT_ReAvTp88xKlDdkN6v3ve10p5tuv9E5u7WPccSottgEgO64eLAb8Tm0klifKPnTOu752gUaUaf7r) 


#### Assign to a user

When a user is created on the platform, they do not have any Bots assigned to them as it is the responsibility of the Administrator to assign the relevant Bots to each user.
To do so, navigate to the Bot you are intending to assign to a user and click on the Bot tab.

![Bots 21](https://docs.toca.io/hs-fs/hubfs/Bots%2021.png?width=602&name=Bots%2021.png) 

The penultimate property on the BOT tab is the one to assign a user to the Bot.

![Bots 22](https://docs.toca.io/hs-fs/hubfs/Bots%2022.png?width=602&name=Bots%2022.png) 

To change the user or add an assigned user, click the dropdown and this will show all users you can assign the Bot to on the platform.

![Image](https://lh3.googleusercontent.com/giVK4zlbDXwLGgO07oVxxYeE8INNNrzdIM5c95i0LfHCQRZQJu1dt_d9VyBKUBDR03wwZIhX3cQMPODBcrC6jjRv7MGtHnhUWKtLzqk1hjNtsjGPKWugpC0OFnOyx5-aJ8T6xjVh) 

Select the relevant user and then press Save Changes.

![Bots 24](https://docs.toca.io/hs-fs/hubfs/Bots%2024.png?width=602&name=Bots%2024.png) 

The user will now see this Bot and use it to run activities when they are logged into the platform.
 
