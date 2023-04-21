# webxr-pwa-factory
Progressive Web Apps example

## Task 1. Start App and audit PWA with Chrome Lighthouse utility

- In terminal call
 ```
npx http-server -p 8080
```
- Open http://localhost:8080 in Chrome browser
- Launch Lighthouse utility from Developer tools
Expected audit results
  ![](info/lighthouse_audit_result.png)

## Task 2. Deploy to your `github.io` web page
1. Create new repository
![](info/git_new_repo_1.png)
2. Insert repository name and click `Save` button
![](info/git_new_repo_2.png)
3. Copy link to your repository
![](info/git_new_repo_3.png)

4. Open terminal. Then add access token to the copied repository link and set as your origin repository
```aidl
git remote set-url origin https://<ACCESS_TOKEN>@github.com/it-zmina/pwa-factory.git
```
## Task 3. Generate APK file and install to your VR headset

1. Navigate [https://www.pwabuilder.com/](https://www.pwabuilder.com/) and insert link to your PWA web page
   ![](info/pwabuilder_intro.png)

2. Select packaging for stores
   ![](info/pwabuilder_select_1.png)

3. Select Meta Quest Store
   ![](info/pwabuilder_select_2.png)

4. Generate and download APK package
   ![](info/pwabuilder_packaging.png)
   
## Install APK file to your VR headset

1. Enable debug via USB port
   ![](info/com.oculus.shellenv-20230415-020943.jpg)
2. Connect VR headset to your PC.
3. Open SideQuest app on your PC and install APK archive.
  ![](info/sidequest.png)

4. Select applications from unknown sources
 ![](info/com.oculus.shellenv-20230415-023154.jpg)

5. Launch installed application
 ![](info/com.oculus.shellenv-20230415-023206.jpg)
