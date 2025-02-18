# ailia DX Insight 1.0 to 1.1 Update Guide

In ailia DX Insight 1.1, the application’s electronic certificate has been updated. In Microsoft’s installer, msix, when the electronic certificate is updated, it is recognized as a different application. <br> 
(Reference: [https://github.com/microsoft/msix-packaging/issues/365](https://github.com/microsoft/msix-packaging/issues/365))<br>
Therefore, when updating from ailia DX Insight 1.0 to 1.1, please follow the steps below to uninstall the old version before installing the new one.

## For Windows
Select ailia_dx_insight from the Start menu, right-click to uninstall. <br>
(If not found in the Start menu, please check under "All Apps") <br>
<img src="img/UpdateGuide_01.jpg" alt="UpdateGuide_01"><br>
Double-click on ailia_dx_insight.msix to proceed with the installation. <br>
<img src="img/UpdateGuide_02.png" alt="UpdateGuide_02.png"><br>
User data is saved in <code>c:/Users/[UserName]/Documents(*)/ailia DX Insight</code>, so it will be retained. 
(*) It may also be displayed as "My Documents."

## For Mac
Open ailia_dx_insight.dmg and drop ailia_dx_insight.app into the Applications folder to overwrite.

## Config File Update
If you are using a config file in ailia DX Insight 1.0, it will be necessary to update the config file. On the first launch of ailia DX Insight 1.1, the following dialog will be displayed, so please set the path to the config file. <br>
<img src="img/ConfigFile_02.png" alt="ConfigFile_02.png"><br>
If there are changes to the file after registering the config file, a dialog confirming whether to reload will be displayed. Selecting "Yes" will reload the config file and apply the changes. <br>
<img src="img/ConfigFile_03.png" alt="ConfigFile_03.png"><br>
Additionally, you can manually register the config file from the settings screen → config file. <br>
You can also unregister the config file from the same screen. <br>
<img src="img/ConfigFile_01.png" alt="ConfigFile_01.png"><br>
  
  #### [Next&emsp;＞](MainOperation.md) 