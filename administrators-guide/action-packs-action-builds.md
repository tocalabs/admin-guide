
# Action Packs & Action Builds Explained (Administrator)




#### Action Packs

Action packs represent all the actions which have been added to your platform in various packs. This section simply allows you to view what packs have been synced to your platform from a Hub.
To see the action packs, click on the Action Packs icon in the Admin panel.

![Action Packs & Action Builds 1](https://docs.toca.io/hs-fs/hubfs/Action%20Packs%20%26%20Action%20Builds%201.png?width=602&name=Action%20Packs%20%26%20Action%20Builds%201.png) 


#### Action Builds

When new actions are added to the platform, either via the TDK or by importing a new Action pack from a Hub, we need a way to integrate and add them to our existing Bots. Action builds are the way to do this. An action build collects all the actions you have on your platform and creates a representation of the actions that a Bot can understand.
If a Bot does not have an Action Build associated with it then it cannot run any actions so action builds are imperative to your platform.
You should always run a new Action Build when either a new action pack has been pulled down to your platform or someone has published a new action from the TDK.
To see all action builds associated with your platform go to the Admin panel and click on the Action Builds icon.
 

![Action Packs & Action Builds 2](https://docs.toca.io/hs-fs/hubfs/Action%20Packs%20%26%20Action%20Builds%202.png?width=602&height=323&name=Action%20Packs%20%26%20Action%20Builds%202.png) 

Each action build gets a Build ID which is the ID the Bots use to find what actions they have.
From the Action Builds page you can see every action build, the status of the build, what changes there were and what date the build was run.
If you click on the Changes it will show you what actions were added compared to the previous run and what actions have been removed.

![Image](https://lh4.googleusercontent.com/WfXFhPcfPU_LjHEeL_H8BqreJ3qKWvWUV7-nAquk-TCHfhl-ti-R69KJioJc037s1X0GCacDixS-SPd1SkEfVcnp7vJTsENP4-XufkzT7G33n5F1p-AYFFUdMFGrLQFtLecFLatX) 

If an Action Build failed then you can check the logs to see why it failed.

![Image](https://docs.google.com/drawings/u/0/d/sbYxsmXUQuW7-p9PBjjgYOA/image?w=602&h=155&rev=7&ac=1&parent=1021Hys0a2A5pml4_OnXLucoUj01SY38hCWhwtsvqraM) 


#### Run an Action Build

To run a new action build go to the Action Builds section in the Admin panel.

![Action Packs & Action Builds 5](https://docs.toca.io/hs-fs/hubfs/Action%20Packs%20%26%20Action%20Builds%205.png?width=602&name=Action%20Packs%20%26%20Action%20Builds%205.png) 

Then click the build icon in the top right corner, this will collect all actions in the platform, old and new, and produce a new action build for the Bots on the platform to use.

![Action Packs & Action Builds 6](https://docs.toca.io/hs-fs/hubfs/Action%20Packs%20%26%20Action%20Builds%206.png?width=410&name=Action%20Packs%20%26%20Action%20Builds%206.png) 

When an action build starts you'll see that a new build has been added to the table with the status of Building.

![Image](https://lh5.googleusercontent.com/yMG5ymTsF3h9GdkwAuBmJ52lSk8UfceACQRVcpTbdiFTweOJQSRAvJIHqPsjDwj8mJA5t7HrGq7T1MZs75H0lxF_b86ZtAVWhY1O6DNpHB1tslc3VWngslfYLsrKk4NhODarp32v) 

An action build will usually take anywhere between 10 seconds to a couple of minutes so don't worry if it doesn't seem to progress for a while.
When the build is finished you'll get a notification informing you that the Action Build completed successfully.
An Action Build can fail for one of the following reasons:


- A new action has erroneous code inside it.


- A new action has dependencies that are missing from the platform such as an Action Helper.

 
