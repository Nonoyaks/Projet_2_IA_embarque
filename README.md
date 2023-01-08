# Projet_2_IA_embarque

Plutôt que de modifier la fréquence de clignotement en fonction du mot détecté ce que je trouvais peu lisible, j'ai choisi de faire un code couleur en fonction du mot détecté.

L'ordre des mots est le suivant :

- "FPGA" : GREEN
- "microcontroleur" : BLUE
- noise : RED
- "resistance" : RED + GREEN
- "transistor" : RED + BLUE


Le fichier .ino à utiliser est le fichier nano_ble33_sense_microphone_continuous_modified.ino
et non pas nano_ble33_sense_microphone_continuous.ino qui est le fichier généré par Edge Impulse et qui ne répond pas encore à toutes les demandes.
