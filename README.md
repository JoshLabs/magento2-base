# magento2-base
Magento 2.2.4 base from [official site](https://magento.com/tech-resources/download)... Full Release with Sample Data


## Installing WAMP Server
**Step 1:** Click **[here](http://www.wampserver.com/en/download-wampserver-64bits/)** to download your preferred edition of WAMP Server

**Step 2:** Install WAMP (usually in C:\)

## Clone this repository in `wamp/www` folder
```
git clone git@github.com:JoshLabs/magento2-base.git
cd magento2-base
```

## Magento Installation
**Step 1:** In your browser, navigate to **`localhost/magento2-base`**

**Step 2:** In the first pop-up, click on **Agree and Setup Magento** and choose **Start Readiness Check** to have your WAMP environment checked. Assume the checking process goes smoothly as expected, click on **Next** button to move on.

**Step 3:** To setup your database:

Open a new tab and navigate to **__`http://localhost/phpmyadmin/`__** using credentials `root with no password` and click **New**
Name the database `Magento` and click **Create**
Get back to the other tab when you get the below message and click **Next**

> Database `Magento` has been created.


**Step 4:** In **Web Configuration**, make your preferred changes and click **Next**

** ***Note:** __In the **Magento Admin Address** box, you can put just **Admin** in order to have better security and easily remember.__

**Step 5:** In **Customize Your Store**, you can make changes such as Time Zone, Currency, Language and other Advanced Configurations. Click **Next** when you are done.

**Step 6:** In **Create Admin Account**, fill out your Username, Email, and set your Password. We do recommend you to go with a strong password (including Numbers, Symbols, Capital Letters, and Lower-Case Letters). When you are done, click **Next** to keep moving.

**Step 7:** Click on **Install Now** button to install Magento when you feel all of your configuration is ready. A message with your basic filled out information will appear when the installation is successful.

**Final Step:** To access your Admin Panel, click **Launch Magento Admin.**
