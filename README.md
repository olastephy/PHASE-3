
PERFORMING A PRACTICAL WEB APPLICATION ASSESMENT WITH ZAP

REQUIRED TOOLS

VMWARE MACHINE

KALI LINUX

ZAP

STEPS




![first shot](https://github.com/user-attachments/assets/47871252-ab6c-415d-98db-6b37edb6bbc1)
my kali login


Kali update
![SHOT 2](https://github.com/user-attachments/assets/4bdad937-0028-4468-90c2-4b597277361d)


![SHOT 3](https://github.com/user-attachments/assets/8a0d8496-1efe-470d-97c3-f3b1fba5908f)



![SHOT 3   4](https://github.com/user-attachments/assets/6ec8457a-58f8-4169-9bed-ebd8e8addcbb)

  Kali upgrade

![SHOT 5](https://github.com/user-attachments/assets/c8095383-baa3-410d-98dd-d5800bb6d3ec)
Zap Installtion


![SHOT 6](https://github.com/user-attachments/assets/41916daa-5363-4fe3-9d1f-32a4bc06c5cd)
Downloading of ADD-ONS for firefox browser extension


![SHOT 7](https://github.com/user-attachments/assets/a3a46608-ceb6-469c-917f-0eb650d82c47)
Configuration Of Foxyproxy


![SHOT 8](https://github.com/user-attachments/assets/4674ddbb-23cf-43b2-8f6a-2686d86dbecd)
Downloading Of the Certificate 


![SHOT 9](https://github.com/user-attachments/assets/28f8fe7b-d7fd-4243-8c7f-d034bc60c595)


![SHOT 10](https://github.com/user-attachments/assets/aadc630a-e5cb-4d1f-bf74-d7fdd259ea09)
Importation  of the Cerificate



![SHOT 11](https://github.com/user-attachments/assets/b474e0a7-ef2b-4287-a6c3-6a7f3bfc0c8c)

Powering Zap





![SHOT 12](https://github.com/user-attachments/assets/a6449c2e-3b9b-4956-a1cb-52eed1eeec46)

When you start ZAP, you’ll see a prompt asking, “Do you want to persist this ZAP session?” If you choose “No, I do not want to persist this session at this moment in time,” ZAP will not save the session to the HSQL database. This means that once you close ZAP, any request history, site information, and other session details will not be saved and will be lost. If you opt to persist the session, you can save and reload the session data later.



![SHOT 12   12](https://github.com/user-attachments/assets/37a9a20e-31cb-495f-95b1-b7b2af061aeb)

Before we begin using ZAP, let's take a look at the main interface and identify where some of the key features are located. The interface contains a lot of information because ZAP offers many functionalities.


![SHOT 13](https://github.com/user-attachments/assets/86bbe0f4-343f-4167-a484-3e9a7ce867b4)


Features:

    Menu Bar: Here, you can manage sessions, generate reports, access tools, get help, and more.
    Toolbar: Contains buttons that offer shortcuts to frequently used features.
    Tree Window: Shows a hierarchical view of the site you're testing and the script tree.
    Quickstart/Workspace Window: Provides an easy way to use ZAP, especially for beginners. It also displays request responses and editable scripts.
    Information Window, including:
        History Tab: Logs all HTTP requests and responses sent and received through ZAP.
        Search Tab: Allows you to search through requests and responses.
        Alerts Tab: Displays security alerts detected during scans.
        Output Tab: Provides detailed output from various scans and processes.
    Footer: Shows ZAP status information.
        Alerts Counter: Summarizes the alerts found, color-coded to indicate their severity.
        Main Proxy: Displays the main proxy configuration used by ZAP, set to "localhost:8080."
        Current Scans: Lists any ongoing scans, with icons showing their status or progress.

Update Addons

Before you start using ZAP, it's important to check for and update any addons to ensure you have the latest features and improvements. To check for updates, press CTRL + U or use the toolbar shortcut.




![SHOT 14](https://github.com/user-attachments/assets/b1b765c4-cceb-4eeb-af91-38fb74217347)

In the next window, input the URL of the web app you want to scan and choose the “Recurse” option. This instructs ZAP to explore all URLs or directories from the starting URL. When you’re prepared, click “Start Scan.”




![shot 15](https://github.com/user-attachments/assets/333857e4-d13e-41ec-a1db-b70bfbb3de29)


After the spidering process is complete, you will see all the discovered nodes for the web app. In the lower-right corner, it will show that 91 nodes were found, with "Nodes Added: 47," indicating the number of new items that the Spider has located and added to the Sites tree during the crawl.



![shot 16](https://github.com/user-attachments/assets/b1a776da-54e1-42cd-bae8-59cfa9ad8daa)
No vulnerability found



![shot 17](https://github.com/user-attachments/assets/0d12115a-d95b-416e-829b-4f6812941801)

After the scan is complete, any discovered nodes will be displayed in the site tree area with a red spider icon next to them. The AJAX spider examined 1,461 URLs, whereas the standard spider scanned 138 URLs.



![shot 18](https://github.com/user-attachments/assets/3415947f-3640-454c-9fbd-d33f1bacc0e1)
4 Ajax spider deteced


![shot 19](https://github.com/user-attachments/assets/99301f0d-ddc2-4ef9-8e46-b77efc483ff2)

 No Alert found



 ![shot 20](https://github.com/user-attachments/assets/2a8d5168-f505-4e4b-9a5b-c060208c5593)
11 Alerts found
0 Medium
5 Low
3 information

 





