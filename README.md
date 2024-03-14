# WindowsVM_Lightsail
## Swift Windows VM Server 2022 Deployment with Lightsail

Description: Easily launch your Windows Server 2022 instance within seconds using Lightsail, the ultimate solution for rapid deployment. 
Select Windows Server 2022 effortlessly, and with one-click RDP access, start utilizing your server instantly. Whether it’s for hosting applications or managing data, Lightsail simplifies the process. 
Experience the convenience of installing Windows-based software seamlessly and accessing your instance with unparalleled ease. Make your Windows Server 2022 journey hassle-free with Lightsail.

Step 1: Create an Amazon account or log in and search for Lightsail

Step 2: Create a Windows Server 2022 instance or the one that best fits your organization in Amazon Lightsail.
a. Choose the Create Instance button on the Instances tab
![image](https://github.com/JohnnyLouisTech/WindowsVM_Lightsail/assets/29494723/dd913334-08d8-45a8-aa9e-2ffb62c1ef53)

Step 3: Let’s Configure the instance to your need
a. Choose Change Region and Availability Zone to create your instance in another location
![image](https://github.com/JohnnyLouisTech/WindowsVM_Lightsail/assets/29494723/a28b6102-77c3-40fb-a3b7-2f4f9348bf8c)

b. Choose the Microsoft Windows platform option, and choose OS only to view the operating system-only instance images available in Lightsail. Select the Windows Server 2019 image.
![image](https://github.com/JohnnyLouisTech/WindowsVM_Lightsail/assets/29494723/00631e96-6945-433c-b955-1644f242472f)

c. (Optional) Choose Add launch script to add your own PowerShell script — you can leave it blank and one will be created for you.
![image](https://github.com/JohnnyLouisTech/WindowsVM_Lightsail/assets/29494723/bc443104-4d38-4430-ae52-77b2b3b070df)

d. Pick an instance plan. You can try the $8 USD Lightsail plan free for three months (up to 750 hours). You actually have 3 months for free with this plan.
![image](https://github.com/JohnnyLouisTech/WindowsVM_Lightsail/assets/29494723/d9507a1a-6191-411e-987f-1a61622e8714)

e. Please enter a name for your instance.
![image](https://github.com/JohnnyLouisTech/WindowsVM_Lightsail/assets/29494723/88b0581c-a31e-4727-b1e5-aed5a8cd25f7)

. (Optional) Choose one of the following options to add tags to your instance:

(Optional) Add key-only tags — Enter your new tag into the tag key text box, and press Enter. Choose Save when you’re done entering your tags to add them, or choose Cancel to not add them.
(Optional) Create a key-value tag — Enter a key into the Key text box, and a value into the Value text box. Choose Save when you’re done entering your tags, or choose Cancel to not add them.
Key-value tags can only be added one at a time before saving. To add more than one key-value tag, repeat the previous steps.

g. Choose to Create instance here.
![image](https://github.com/JohnnyLouisTech/WindowsVM_Lightsail/assets/29494723/af23737d-86ee-4d4e-97f5-c8d49a3cd6fc)

Step 4: Connect to your instance using the browser-based RDP client in Lightsail. Click on “Connect” to start the connection.
a. On the Instances tab of the Lightsail home page, choose the RDP icon, or the ellipsis (⋮) icon next to the Windows Server 2019 instance you just created and choose Connect.
![image](https://github.com/JohnnyLouisTech/WindowsVM_Lightsail/assets/29494723/3d33bd5f-2d10-4476-b97f-5833d7bc4175)

b. The browser-based RDP client window appears. You can use and manage your instance without configuring a third-party RDP client.
![image](https://github.com/JohnnyLouisTech/WindowsVM_Lightsail/assets/29494723/cc505f36-9836-4d7f-b841-9f7e33ec8d65)

Step 5: Get an administrator password for your Windows Server 2022 instance.
a. Choose the name of the Windows Server 2019 instance on the Instances tab of the Lightsail homepage.
![image](https://github.com/JohnnyLouisTech/WindowsVM_Lightsail/assets/29494723/4255381b-fd96-4c79-ad6b-9401b584612e)

b. Select the Connect tab, scroll down to the Default login credentials section of the page, and choose Retrieve default password.
![image](https://github.com/JohnnyLouisTech/WindowsVM_Lightsail/assets/29494723/a45b01ab-06db-4eb6-b960-781efc293a45)

Default Password shown below
![image](https://github.com/JohnnyLouisTech/WindowsVM_Lightsail/assets/29494723/9d1bfc2e-81ad-46f8-93b1-b703774db5b3)

Important: If you changed the administrator password after signing in to your Windows Server 2022 instance, then the administrator password displayed in the Lightsail console is no longer valid.

Step 6: You now have full access to the Windows Server 2022 instance.
![image](https://github.com/JohnnyLouisTech/WindowsVM_Lightsail/assets/29494723/8f12ad72-9797-4f4b-a3cf-f2bb15a70645)

Step 7: Clean up
a. On the Instances tab of the Lightsail home page, choose the ellipsis (⋮) icon next to the Windows Server instance you just created and choose Delete.
![image](https://github.com/JohnnyLouisTech/WindowsVM_Lightsail/assets/29494723/aeda6410-4266-4bf9-bdbe-aa3d066f8f3a)

b. Choose Yes, to confirm deletion of your running instance from the prompt.
![image](https://github.com/JohnnyLouisTech/WindowsVM_Lightsail/assets/29494723/0afe471d-3700-4a54-8fc0-a8ddfaf78af1)


































