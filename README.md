# instagram-bot-selenium
Let’s create an Instagram bot to show you the power of Selenium!

For now, our bot should be capable of the following actions:

- Sign in.
- Follow a user
- Unfollow a user
- Get a user’s followers

# The architecture of the script

To keep our code organized and reusable in other projects, we will put our code in a class named InstagramBot. Every action the bot will be capable of taking will be a method.

class InstagramBot():
   def __init__
   def signIn
   def followWithUsername
   def unfollowWithUsername
   def getUserFollowers
   def closeBrowser
   def __exit__
