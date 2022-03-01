# Mercero Deal Desk - Post Install Configuration

Thanks for installing Mercero Deal Desk (MD2). Before using the app, Salesforce must be configured either manually or by using a post install script packaged and distributed with the app.

## CPQ Integration

MD2 is independent of Salesforce CPQ, but it does come with useful features derived from CPQ. In order to unlock Salesforce CPQ integrated functionality, the following custom setting will have to be set:

Setup -> Platform Tools: Custom Code -> Custom Settings -> Mercero Deal Desk: CPQ Integration  -> Manage -> New

Check "Use CPQ"

<img alt="Custom CPQ Setting" src="images/Custom-Settings-Salesforce.png" width="768px"/>


## Post Install Page

After installation of the MD2 package, recommended post install configurations can be applied using pre packaged scripts that are accessible to the System Administrator:

Setup -> Platform Tools: Custom Code -> Visualforce Pages -> Post Install

<img alt="Custom CPQ Setting" src="images/PostInstall.png" width="768px"/>


## Deal Desk Queue and Case Assignment Rule

MD2 uses the standard Salesforce Case object. MD2 specific cases are assigned to users via a queue and case assignment rule that must be setup once after installation.
