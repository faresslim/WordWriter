from pynput.keyboard import Key, Controller
import keyboard
import time
import random

def KBP ():
    time.sleep(5)
    while(True):
        keyboard = Controller()
        
        stop_program()
        time.sleep(2)
        keyboard.type("Hej detta är en typer bot skapad av Fares Slimani, detta är 100 procent legit. Han har gjort hela denna koden från scratch tack o hej Mr.balancestio")
        stop_program()
        keyboard.press(Key.enter)
        
def stop_program():
    if keyboard.is_pressed('p'):
        exit()
KBP ()
