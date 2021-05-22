
import pyautogui
import webbrowser as wb
import time
wb.open("web.whatsapp.com")
time.sleep(20)
for i in range(10):
	pyautogui.press("h")
	pyautogui.press("enter")
