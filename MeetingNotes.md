##_Reed_ Meeting Notes

Our first meeting to discuss the app was great and involved a lot of good ideas. We laid down the foundation for what the reading list app, now called _Reed_, should comprise. The following is a synopsis of the notes that were taken through the first and second meetings.
#Primary Ideas
* The main idea of the app is to have a centralized location to save articles to a reading list and easily share them with other people.
* You should be able to easily save articles from the web to your list, whether it's through the built in share extension or through copy and paste.
* Within the app there should be the tools needed to manage your list.
* Other users will be able to see your list, and you will be able to see their lists. This also includes being able to follow users.
* A discover feature will allow you to hot articles and articles that a large amount of people have favorited.

#Implementation
* Users themselves should see the 20 oldest articles they added to their list. This will encourage, (read: force), them to read articles they are saving rather then using it as another bookmarks repository.
* Other users that look at your profile will see your 20 most recently added articles.
* After reading a user can mark an article **read**. This will remove it from the _To Read_ list and place it in the archive.
* A user can also mark an article as a **favorite**. This will mark it as **read** as well.
* New articles added by the user get added to the bottom of the user's reading list.
* List management will be handled through swipe gestures on the articles themselves.
* Within the app the articles will be opened in a web view.
* **Discover** tab will show articles that have been favorited the most in the past 24 hours or past week.
* Logins will be handled through **Twitter**. This will allow for us to pull in profile information and profile pictures to attach personalities to users.
* Most of the back-end will be handled through **Parse**
* Push notifications could be used to remind users to read articles as they age within the reading list.

#Platform/Tool Choice
* Built in Xcode 6.x for the time being.
* Swift 1.x for the time being.
* Features that are in iOS 8.x or lower.
* iOS 9 / Xcode 7 / Swift 2.0 will be used in the future.

***Contribution Information***

* At some point the information for the collaboration process should be added to the readme. A couple of points that we should keep in mind:
	* Trello is being used as a task tracker. https://trello.com/b/AQmzXnw9/read
	* Cards should be assigned to yourself as a member, then moved to the _Doing_ list while working on it.
	* If someone has assigned themselves to a card that you would like to work on, please contact them before beginning work so that conflicts are limited.
	* Please use GitHub for all contributions.
		* Fork the repository.
		* Make your changes and commit with a description.
		* Push changes to your fork.
		* Initiate a pull request.
	* If there are issues with the code base feel free to open an issue on the base GitHub repo.

***Future meetings/hangouts/program sessions will probably be recorded and uploaded somewhere to document our process.***