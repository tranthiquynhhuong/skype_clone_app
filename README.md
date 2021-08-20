# skype_clone_app

Skype clone application with Flutter, inspired to [tutorials](https://www.youtube.com/playlist?list=PLTHrJfrjCyJDlOLSIT3bm2xCCuPanUNX4) of [The CS Guy](https://www.youtube.com/c/TheCSGuy). This mobile source was build in one week by me, so all the interactions are basic with functions: Login by Google account, Logout, Duo Video call, Chat (text, emotions, image), Search, Call logs history,...)

This project build with [Google Flutter](https://flutter.dev/), [Google cloud firestore](https://firebase.google.com/docs/firestore) realtime database, Firebase storage, [Agora](https://www.agora.io/en/) SDK video call realtime support for Flutter by [agora_rtc_engine](https://pub.dev/packages/agora_rtc_engine) package.

Architecture (using): Provider (ChangeNotifierProvider), Repository, Database local (HIVE, Sqlite),...

Testing only on Android device

`Give me 1` 🌟 `if you feel favorite it >.< Thank you bro!`

## Getting started
Clone or download this application and run in your device

## Pages
**1. Login screen**: You can login with Google account

![skype_clone_login](https://user-images.githubusercontent.com/33143698/130218205-3e23e749-3d2b-4056-be0a-3e7c78269ec1.png)

**2. Chat list screen**: You can track the status of the users you've chatted with here

![skype_clone_chat_list_non_contact](https://user-images.githubusercontent.com/33143698/130218230-1418822b-7484-4001-a967-33be788cd46f.png)
![skype_clone_chat_list](https://user-images.githubusercontent.com/33143698/130218260-f412f018-712c-4e5b-b084-9f7964e5a4e6.png)

**3. Chat screen**: Where you can comfortably chat, share photos, emotions and start video calls with other users

![skype_clone_chat_screen](https://user-images.githubusercontent.com/33143698/130218311-8fb3ee7b-a815-469c-b2e3-a3d5463b67dc.png)
![skype_clone_chat_screen_send_file_options](https://user-images.githubusercontent.com/33143698/130218325-9c560c5d-4aa2-4e0f-818e-ccfbf7ce0c61.png)
![skype_clone_chat_screen_emotion](https://user-images.githubusercontent.com/33143698/130218343-0987a821-c00d-4453-8ebe-f01e2e1d8012.png)

**4. Video call screen**: Where you can make online calls with 1 other user through integration by Agora 

![skype_clone_call_screen](https://user-images.githubusercontent.com/33143698/130219128-9a244680-aada-472c-9cc9-ada7c66d5960.png)
![skype_clone_photo_2021-08-20_17-00-37](https://user-images.githubusercontent.com/33143698/130219138-9fcd7912-9b24-4b40-93ef-8280e6944293.png)

**5.Search screen**: Where you can easily search real time other users in the system immediately

![skype_clone_search_result](https://user-images.githubusercontent.com/33143698/130218386-70f8b1ab-6a61-449e-83aa-2d0b71ee0c5e.png)

**6. Logs call screen**: Where to save your call history local by Hive/Sqlite database

![skype_clone_call_screen_non_contact](https://user-images.githubusercontent.com/33143698/130218492-e4afdb5c-cccf-4e2c-99d8-3b2aa1256a78.png)
![skype_clone_log_call_list](https://user-images.githubusercontent.com/33143698/130218439-d9bbfc41-c5f9-41c6-a834-7d3d24ff3c9a.png)
![skype_clone_log_call_delete](https://user-images.githubusercontent.com/33143698/130218468-3517c901-8956-44d0-8182-32ba5b2c2872.png)

**7. Info screen**: Where you can view your account information and log out (if desired)

![skype_clone_info_screen](https://user-images.githubusercontent.com/33143698/130220425-fdff7507-377f-44fc-bff9-3d27e79382f5.png)

