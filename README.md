# Very Simple Zoom Spam Pinger!

Code:

    import pyautogui
    import time
    
    print("You Must First Ping The Person Then Copy Paste The Text Here !")
    print("Example: '@PndaBoi!'")
    print()
    print("This Program Is Meant For Zoom, Not Tried Other Platforms !")
    print()
    msg1 = input("Enter the message -> ")
    msg2 = input("Enter the Second message -> ")
    n = input("How many times ? -> ")
    delay = int(input("How much delay do you want bettween messages ? -> "))
    print()
    print("T minus!")
    
    count = 5
    while(count != 0):
    	print(count)
    	time.sleep(1)
    	count -= 1
    print()
    print("It's Troll TIme!!!")

    for i in range(0,int(n)):
    	pyautogui.typewrite(msg1 + '\n')
    	pyautogui.typewrite('\n')
    	pyautogui.typewrite(msg2 + '\n')
    	pyautogui.typewrite('\n')
    	time.sleep(delay)

I found this code and made it better :)

# You need `pyautogui` for this!

To install:

    pip install pyautogui

### Made by @PndaBoi, Hope it helps! :)

Not Sorry for the bad repo name :D
