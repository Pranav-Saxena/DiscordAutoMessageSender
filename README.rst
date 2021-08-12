**************************
DiscordAutoMessageSender
***************************
A Python Program to send messages in an automated manner on discord

Here is the code to do the task

..code:: py
  #---Note-- 
  #You'll need to leave your desktop/laptop idle after running this program , otherwise this won't work

  import pyautogui as pg
  import time
  n = int(input("How many times you want to send message?"))
  word= input("Enter word which you want to send")
  print("You Have 10s to go and open the channel/DM on discord where you want to spam. Make sure the discord app is opened in full screen mode")
  time.sleep(10)
  for i in range(n):
      pg.moveTo(899,953)
      pg.click()
      pg.typewrite(word)
      pg.press("enter")
      time.sleep((2))
