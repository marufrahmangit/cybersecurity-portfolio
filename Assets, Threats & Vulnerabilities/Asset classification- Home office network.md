# Classification of assets in a home office network

[Project reference](https://www.coursera.org/learn/assets-threats-and-vulnerabilities) 

# Scenario
One of the most valuable assets in the world today is information. Most information is accessed over a network. There tend to be a variety of devices connected to a network and each is a potential entry point to other assets.

An inventory of network devices can be a useful asset management tool. An inventory can highlight sensitive assets that require extra protection.

![image](https://github.com/user-attachments/assets/58df5db3-4416-451f-b794-2b1ea3366ee1)

You’re operating a small business from your home and must create an inventory of your network devices. This will help you determine which ones contain sensitive information that require extra protection.

To do this, you will start by identifying three devices that have access to your home network. This might include devices such as:

- Desktop or laptop computers
- Smartphones
- Smart home devices
- Game consoles
- Storage devices or servers
- Video streaming devices

Then, you’ll list important characteristics of each device such as its owner, location, and type. Finally, you will assign each device a level of sensitivity based on how important it is to protect.

# Asset Classification

| Categories      | Access designation            |
|-----------------|-------------------------------|
| Restricted      | Need-to-know                   |
| Confidential    | Limited to specific users      |
| Internal-only   | Users on-premises              |
| Public          | Anyone                         |

Here is the table converted to Markdown format:


| Asset            | Network access | Owner                       | Location          | Notes                                                                 | Sensitivity    |
|--------------------------|---------------------------|-----------------------------|-------------------|-----------------------------------------------------------------------|----------------|
| Network router   | Continuous     | Internet service provider (ISP) | On-premises       | Has a 2.4 GHz and 5 GHz connection. All devices on the home network connect to the 5 GHz frequency. | Confidential   |
| Desktop          | Occasional     | Homeowner                   | On-premises       | Contains private information, like photos.                            | Restricted     |
| Guest smartphone | Occasional     | Friend                      | On and Off-premises | Connects to my home network.                                          | Internal-only  |
| Smart home devices | Occasional     | Homeowner                      | On and Off-premises | Connects to my home network.                                          | Internal-only  |
| Storage devices or servers | Continuous     | Cloud Provider                      | On-premises | Connects to my home network.                                          | Internal-only  |
| Video streaming devices | Occasional     | Homeowner                      | On-premises | Connects to my home network.                                          | Confidential  |
