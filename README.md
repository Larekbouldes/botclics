import pyautogui
import time

# Obtenez les coordonnées des emplacements où vous voulez que le bot clique
pos1 = (100, 200)
pos2 = (300, 400)
pos3 = (500, 600)

# Effectuez trois clics sur les coordonnées spécifiées avec une pause de 1 seconde entre chaque clic
pyautogui.click(pos1[0], pos1[1])
time.sleep(1)
pyautogui.click(pos2[0], pos2[1])
time.sleep(1)
pyautogui.click(pos3[0], pos3[1])
