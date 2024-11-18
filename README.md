# Creating an AWS Static Website

# Create a S3 bucket
The name of the buckey has to be globally unique.
Provide all the necessary details.
![ss2](https://github.com/user-attachments/assets/aedbe35f-efbd-4b2b-9a85-07b9ca55ee7d)
There has to be couple of changes that has to be made in order to move ahead with the project.
Go to Properties tab and scroll all the down and enable 'Static Website Hosting' and also provide the 'Index Document'.
![ss3](https://github.com/user-attachments/assets/fcebdbf1-d96c-4f93-a869-9ad2591eab4f)

At the end of the webpage, you can find a link to access the website and by default all public access will be denied by the bucket. To enable this feature go back to the bucket which you have created and under 'Permissions' tab, disable 'Block all public access' and Save changes.
Now we need to edit the bucket policy which can allow contents of the bucket to be publicly available. I have attached the Policy code, update the bucket name. And Save changes.
![ss5](https://github.com/user-attachments/assets/e87d1157-3314-40e0-bd69-7ccb3d5a247c)

And Save changes.
I have created a simple HTML page, which links to my Medium blog.
Go to 'Objects' tab and choose the files which has to be uploaded. 
![ss6](https://github.com/user-attachments/assets/9e293522-6131-44af-89e4-7a2336837934)

Refresh the link and now you can view the contents of your static website.
![ss7](https://github.com/user-attachments/assets/d6cba11e-de2e-456b-8f8e-f50e9beb5b9b)

The link contains the URL to my Medium([url](https://shreyassrinivasa297.medium.com/) blog page.
