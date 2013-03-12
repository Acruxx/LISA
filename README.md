JARVIS
======

Repository of a JARVIS system to control my house
![Image](docs/images/jarvis-architecture.png?raw=true)

Installation :
apt-get install julius julius-voxforge

You will need these python libraries :
easy_install pyjulius
easy_install python-rivescript

Launch with:
julius -module -input adinnet -48 -realtime -v voxforge/sample.dict  -dfa voxforge/sample.dfa -h /usr/share/julius-voxforge/acoustic/hmmdefs -hlist /usr/share/julius-voxforge/acoustic/tiedlist

USEFULL RESSOURCE TO CHECK FOR FRENCH LANGUAGE : http://www-lium.univ-lemans.fr/fr/content/ressources