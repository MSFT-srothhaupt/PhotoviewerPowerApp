# PhotoviewerPowerApp
This repo is for a PowerApp that integrates into Teams and displays Photos.

You can browse Photos, that are stored in a DocLib on Sharepoint through this App.
When you have selected the Photo-Folder you want to view, you can start a slide-show with different kinds of transitions.

This App was built with Power Apps Studio.

## Requirements

1. PowerApps Licence 
2. Sharepoint Document Library
3. Folders with Photos
4. Copy (ZIP-Download of this Repository)

## Deployment Guide
1. Download the Code [here](https://github.com/MSFT-srothhaupt/PhotoviewerPowerApp/blob/main/Fotos%20(Events%20%26%20Vacay)%203.msapp) if you have not done it so far.
2. Extract all files from the **ZIP-Folder**.
3. Find the **.msapp** file. Save it so you can easily find it later. (Download-folder is also fine)
4. Open [Power Apps Studio](https://make.preview.powerapps.com) and sign in with your credentials.
4.1 Click on **Blank app**.
![Landing page of PowerApps Studio](https://github.com/MSFT-srothhaupt/PhotoviewerPowerApp/blob/main/Deployment_Photos/Screenshot%20(9).png)
4.2 Under Blank canvas app, click on **Create**.
![Landing page of PowerApps Studio](https://github.com/MSFT-srothhaupt/PhotoviewerPowerApp/blob/main/Deployment_Photos/Screenshot%20(10).png)
4.3 Enter an application Name (e.g.: MyPhotoApp), check if **Tablet** is selected and continue with a click on **Create**.
![Landing page of PowerApps Studio](https://github.com/MSFT-srothhaupt/PhotoviewerPowerApp/blob/main/Deployment_Photos/Screenshot%20(11).png)
4.4 You will get to the Home Page of PowerApps Studio. In the upper left corner click on **File**.
![Landing page of PowerApps Studio](https://github.com/MSFT-srothhaupt/PhotoviewerPowerApp/blob/main/Deployment_Photos/Screenshot%20(12).png)
4.5 On the right, click on **Open** and then on **Browse**. Select the .msapp file you downloaded earlier. If PowerApps asks you to **save** you can click **NO** for now.
![Landing page of PowerApps Studio](https://github.com/MSFT-srothhaupt/PhotoviewerPowerApp/blob/main/Deployment_Photos/Screenshot%20(13).png)
![Landing page of PowerApps Studio](https://github.com/MSFT-srothhaupt/PhotoviewerPowerApp/blob/main/Deployment_Photos/Screenshot%20(14).png)
4.6 Now you have to click **Fix connection** to connect the Sharepoint Site, that hostes your pictures. Just click on **Allow** (we have to change to your connection in a second).
![Landing page of PowerApps Studio](https://github.com/MSFT-srothhaupt/PhotoviewerPowerApp/blob/main/Deployment_Photos/Screenshot%20(15).png)
5. Replace the Sharepoint Connector with your own Sharepoint Site. Click on the data connector symbol. Click on the three dots next to the **Sharepoint** Data Connector. 
![Landing page of PowerApps Studio](https://github.com/MSFT-srothhaupt/PhotoviewerPowerApp/blob/main/Deployment_Photos/Screenshot%20(18).png)
5.1 Click on the **Remove** button.
![Landing page of PowerApps Studio](https://github.com/MSFT-srothhaupt/PhotoviewerPowerApp/blob/main/Deployment_Photos/Screenshot%20(19).png)
5.2 Click on **Add** and search for **Sharepoint**. Select **Sharepoint**.
![Landing page of PowerApps Studio](https://github.com/MSFT-srothhaupt/PhotoviewerPowerApp/blob/main/Deployment_Photos/Screenshot%20(20).png)
5.3 Choose the **Sharepoint Site** you want to connect to.
![Landing page of PowerApps Studio](https://github.com/MSFT-srothhaupt/PhotoviewerPowerApp/blob/main/Deployment_Photos/Screenshot%20(21).png)
5.4 Choose the list (document library) your photos are stored in. Click **Connect**
![Landing page of PowerApps Studio](https://github.com/MSFT-srothhaupt/PhotoviewerPowerApp/blob/main/Deployment_Photos/Screenshot%20(22).png)
![Landing page of PowerApps Studio](https://github.com/MSFT-srothhaupt/PhotoviewerPowerApp/blob/main/Deployment_Photos/Screenshot%20(23).png)
5.5 as the last step: Go to **the Tree view** and select the Gallery1. Make sure **Items** is selected in the function field. Instead of **Documents** you have to fill in the **Name** of your document library.
![Landing page of PowerApps Studio](https://github.com/MSFT-srothhaupt/PhotoviewerPowerApp/blob/main/Deployment_Photos/Screenshot%20(24).png)
6. Save the App.
7. Add to MS Teams COMING SOON
8. Have fun
9. How to add new Photos to your Photo viewer. COMING SOON

