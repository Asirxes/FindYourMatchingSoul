# FindYourMatchingSoul

A dating application built from scratch using .NET and Angular. Entity Framework is widely used in the application, third party components are added. The styling of the application is created using bootstrap. The cloudinary service is used for the functionality of the photos, they are downloaded thanks to the API. Docker is used for developing the app.

To use the project, you need to create a fake account. You will be logged in automatically. Then you can view users in the Matches tab. There you can like the user, see their profile or send them a message. This tab contains filters.

Liked users appear in the list tab.

In the news tab you can view correspondence with other users.

Thanks to the panel in the upper right corner by clicking edit profile you can edit your profile, upload photos, set a photo to the main photo, or delete photos (unless it's the only one).

To take full advantage of the application and see its functionality, I recommend setting up 2 accounts and initiating all possible interactions between them (messages, likes, browsing the profile, filters).

Some options are only available if you are an admin. In my exact appliaction lisa have admin permissions. You can login as admin using 'admin' as username and 'Pa$$w0rd' as password, admin tab will be then available with every option. Other users can't use this.

SignalR is implemented to run a live chat and to notify users when another user logs in to the application. To observe the action, you need to create 2 accounts and initiate interactions between them.
