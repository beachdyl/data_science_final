# About the Data

This data was scraped by me from the internet forum in question.
By default, it comes with six columns.

Name | Description | Notes
-----|-------------|------
AuthorID | The UUID of the account that posted the message | This is not useful to us unless two users have the same exact username, which I'm pretty sure is impossible.
Author | The full username of the account that posted the message | This includes the "tag" which I mostly ignore. One name was changed because it contained profanity and I noticed it.
Date | The timestamp of the message | This is to the nearest minute. All seconds values are 00.
Content | The message itself | This is (or at least should be) the number that was counted
Reactions | Embedded reactions to the message | I removed this attribute in pre-processing because it was always empty
Attachaments | Attachments to teh message | I removed this attribute in pre-processing becasue it was always empty

All this data is publicly available, but you do have to be a member of the server to get it. I say it is public because anybody can become a member without verification or oversight. You just join.