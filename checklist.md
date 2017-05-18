Installation de openfire sous ubuntu 14.04

telecharger le fichier .deb sur le site officiel
ensuite ds la console faire 
  sudo dpkg -i openfirefile.deb
  
  apres installation le dossier de openfire est creer sous le groupe et l'utilisateur 'openfire' ds /usr/share/openfire
   et ds le dossier /etc/openfire se trouve qlq fichier de configuration
    ds ce dossier on retrouve openfire.xml. ce fichier file comporte la configuratioin qui a été fait en interface web(localhost:9090). Pour reinitialiser la config il suffit de changer true par false ds la balise setup et d'enregistrer et de proceder à une nvelle config en interface web. Eglmt un fichier openfire est crée ds le dossier /etc/init.d , grace à ce fichier openfire est lancé automatiquement à chaque demarrage de la machine dc il te suffit d'acceder à localhost:9090 pour faire tes trucs.
    A notez que lors de la config en interface web dc domain est le nom qui sera utilisé ds le JID des utilsateurs. Tu peux choisir tout ce que tu veux pas forcement localhost com example.org.
    Apres configuration tu va ds l'onglet serveur puis da l'onglet parametres du serveurpuis clique sur HTTP Binding à gauche et tu verras l'URL du BOSCH (ex: http://example.org:7070/http-bind/).
    Pr le muc le service ar defaut est conference.example.org où example.org sera remplace par tn domain
    
    
    
    
    encadrer les trois quarts d'un bloc HTML code:
    
     #holder {
        border: 1px solid #000;
        height: 200px;
        width: 200px;
        position:relative;
        margin:10px;
} 
#mask {
        position: absolute;
        top:20px;
        left:20%;
        width:100%;
        height: 80%;
        background-color:#dddde2;
}
html{
  background:#eee;
}
