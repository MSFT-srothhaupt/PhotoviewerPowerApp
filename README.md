# PhotoviewerPowerApp
This repo is for a PowerApp that integrates into Teams and displays Photos.

You can browse Photos, that are stored in a DocLib on Sharepoint through this App.
When you have selected the Photo-Folder you want to view, you can start a slide-show with different kinds of transitions.

This App was built with Power Apps Studio.

## Requirements

1. PowerApps Licence 
2. Sharepoint Document Library
3.Folders with Photos
4. Copy (ZIP-Download of this Repository)

## Deployment Guide
1. Download the Code [here](https://github.com/MSFT-srothhaupt/PhotoviewerPowerApp/blob/main/Fotos%20(Events%20%26%20Vacay)%203.msapp) if you have not done it so far.
2. Extract all files from the **ZIP-Folder**.
3. Find the **.msapp** file.
4. Open [Power Apps Studio](https://make.preview.powerapps.com) and sign in with your credentials.
4.1 Click on **Blank app**.
![Landing page of PowerApps Studio](https://github.com/MSFT-srothhaupt/PhotoviewerPowerApp/blob/main/Deployment_Photos/Screenshot%20(9).png)
4.2 Under Blank canvas app, click on **Create**.
![Landing page of PowerApps Studio](https://github.com/MSFT-srothhaupt/PhotoviewerPowerApp/blob/main/Deployment_Photos/Screenshot%20(10).png)
4.3 Enter an application Name (e.g.: MyPhotoApp), check if **Tablet** is selected and continue with a click on **Create**.
![Landing page of PowerApps Studio](https://github.com/MSFT-srothhaupt/PhotoviewerPowerApp/blob/main/Deployment_Photos/Screenshot%20(11).png)
4.4 You will get to the Home Page of PowerApps Studio. In the upper left corner click on **File**.
![Landing page of PowerApps Studio](https://github.com/MSFT-srothhaupt/PhotoviewerPowerApp/blob/main/Deployment_Photos/Screenshot%20(12).png)
4.5 On the right, click on **Open** and then on **Browse**. Select the .msapp file you downloaded earlier.
![Landing page of PowerApps Studio](https://github.com/MSFT-srothhaupt/PhotoviewerPowerApp/blob/main/Deployment_Photos/Screenshot%20(13).png)
4.6 Now you have to fix the connection to the Sharepoint Site, that hostes your pictures.
![Landing page of PowerApps Studio](https://github.com/MSFT-srothhaupt/PhotoviewerPowerApp/blob/main/Deployment_Photos/Screenshot%20(14).png)
![Landing page of PowerApps Studio](https://github.com/MSFT-srothhaupt/PhotoviewerPowerApp/blob/main/Deployment_Photos/Screenshot%20(15).png)
5. Replace the Sharepoint Connector with your own Sharepoint Site.
6. Replace the "Documents" path with the Path to your own document library name.
7. Safe the App
8. Add to MS Teams
9. Have fun
10. How to add new Photos to your Photo viewer.

