# Infinite Interaction Template
# Documentation

Setup
In project settings > Collision : create a new Object type and name it (“Use” for example)
Update the variable “Usable Objects Types”


Create a new usable actor
From the parent base, create a child
Minimal setup in child:
Add a (or multiple) collision shape Scene Component (box, sphere, …) and set the “Collision Presets” to “Custom” and “Object Type” to the name of the Object Type you created earlier in the project settings. Place it how you like
Add the “Use” event

Customization
You can add or edit the already existing variables in the “modular” category (fomr the Use childs you can access them from the “Class defaults” panel or directly in the “Details” panel if you want to edit per-instance (inside level)

Extra
Add the “Locked” event
Add the “SCBP_Use” Scene Component and place it how you like
