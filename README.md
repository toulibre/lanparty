# Lanparty

Pour déployer une lan party

Sur ubuntu / debian :

    sudo apt install \
      wesnoth teeworlds teeworlds-server \
      hedgewars 0ad supertuxkart \
      minetest gcompris fretsonfire \
      openarena openarena-server armagetronad \
      kobodeluxe

Texte du dépliant pour les visiteurs dans [jeux.md](jeux.md)

Pour le générer en odt :

    pandoc jeux.md -o jeux.odt
