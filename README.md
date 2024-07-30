# AppleScript-Dock
Ce bout de code est une commande bien connue dans l'univers macOS pour personnaliser l'apparence du Dock. Bien que largement documentée et utilisée, elle mérite d'être soulignée pour sa simplicité et son efficacité à améliorer l'ergonomie de l'interface utilisateur sur macOS.
En utilisant la commande defaults write, il modifie les préférences système en ajoutant un espace vide entre les applications présentes dans le Dock. La syntaxe -array-add permet d'ajouter un nouvel élément à la liste des applications persistantes du Dock. 
Le segment {tile-data={}; tile-type="spacer-tile";} spécifie que l'élément ajouté est un "spacer-tile" (espaceur).

Enfin, la commande killall Dock redémarre le Dock pour appliquer immédiatement les modifications. Cette commande est particulièrement appréciée par les utilisateurs cherchant à organiser visuellement leurs applications dans le Dock de manière plus structurée.
