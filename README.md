<img align="left" width="150" src="images/rocketchat.png">
Rocket.Chat is installed automatically as an application based on prebuilt Docker containers on Jelastic PaaS which supports Java, PHP, Node.js, Ruby, Python, Docker and Kubernetes, available as public, private on-premise, virtual private, hybrid and multi-cloud.  
  
&nbsp;  
&nbsp;  
## Rocket.Chat Deployment to the Cloud

Get your Jelastic account at any of available [hosting provider](https://jelastic.cloud/).

Click the **DEPLOY TO JELASTIC** button, specify your email address within the widget and press **Install**.

[![Deploy to Jelastic](https://jelastic.com/getithosted/button.png)](https://jelastic.com/install-application/?manifest=https://raw.githubusercontent.com/jelastic-jps/rocket-chat/master/manifest.jps)

> **Note:** If you are already registered at Jelastic, you can deploy this application by [importing](https://docs.jelastic.com/environment-import) the  [package manifest raw link](https://raw.githubusercontent.com/jelastic-jps/rocket-chat/master/manifest.jps) or find Rocket.Chat application in the [Marketplace](https://docs.jelastic.com/marketplace) within the [dashboard](https://docs.jelastic.com/dashboard-guide).  

  
## Installation Process

In the opened confirmation window at Jelastic dashboard, if required change:  

* __Environment__ name  

* __Display Name__  

* destination __[Region](https://docs.jelastic.com/environment-regions)__ if several are available  

and click on __Install__.

<p align="left"> 
<img src="images/install.png" width="500">
</p>

Once the deployment is finished, you’ll see an appropriate success pop-up.

<p align="left"> 
<img src="images/success.png" width="350">
</p>

 The application is ready to use just press **Open in Browser** button and proceed to admin account setup and to configuration and customization.

For production mode, the installation will require a custom domain and traffic encryption with valid SSL certificate wich can be installed with [Let's Encrypt SSL Add-On](https://jelastic.com/blog/free-ssl-certificates-with-lets-encrypt/). Learn more how to [install Rocket.Chat in Jelastic](https://jelastic.com/blog/install-rocketchat-server/).

The installation process itself looks simple.

<p align="left"> 
<img src="images/rocketchat.gif" width="1920">
</p>
