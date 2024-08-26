# n8nWithGoogleCloud

## Create your Google Cloud account
- Create your Google Sheet account by connecting with your Google account. After you have created successfully, you will have $300 in credit for using. When you have used up or your trial session ends, it won't be autocharged.

## Create a Google Cloud project
- In the top menu, select the project dropdown in the top navigation and select New project or go directly to the New Project page.
![image](https://github.com/user-attachments/assets/ce4a0aaa-1e4b-45a7-a3c9-c94ffe5b06e8)

## Enable APIs
- Go to APIs & Services > Library like following these steps in the image below.
![image](https://github.com/user-attachments/assets/d0402b5a-2955-4f9d-8942-81dc87bd1a04)

- Here, I want to use Google Sheet API, so I will find it to have Client ID and Client Secret, and Enable it.
![image](https://github.com/user-attachments/assets/f9f3a077-c17b-462f-b63a-e7c93bb98bbf)
- I will add credentials for using in n8n.
![image](https://github.com/user-attachments/assets/fec2d703-b84a-4d2f-ac7d-2710ddf349df)
- Input following informaiton like App name, user support name,...
- In the authorized redirect URIs field, we must enter our host URI
![image](https://github.com/user-attachments/assets/90d8f4b2-3063-4e49-884c-cf0949349ef6)
- Finally, we will have Client ID and Client Secret, copy and paste them into localhost n8n
![image](https://github.com/user-attachments/assets/3ece037e-4640-48ee-939f-642c2940762e)







