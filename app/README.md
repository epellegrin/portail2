#Portail Mobvino
##chapitres du portail
###header
MOBVINO 
	{Une Phrase Choc}:  "découvrez de nouveaéux vins selon vos gouts blabbla"
	{un texte plus long}: "Partagez vos "commentaires/degustations puis ensuites blabla" 
Le vin en toute Mobilité 

{Bouton Signup}
###page de contenu 1
{3 /4 photos de l'appli avec dec commentaires des fonctions clefs}
{photo 1} : 
{photo 2}: partagez sur mobvino et sur vos réseaux sociaux préférés
{photo 3}: decouvrez le vin 
{photo 4 }: suivez vos amis
{photo 5}: trouvez de nouveaux lieux 
###page de contenu 2
{focus sur un fonctionnalité clef}
1 prends en photo ce vin  
next...

###page de contenu 3
{ focus sur une autre fonctionalité}
Note le / partage le 


###page de contenu social
	{lien vers le compte twitter
	instagram	comme ce qui est fait sur leadoff.fr}

###Contact
suivez nous sur twitter @mobvino
sur facebook  : https://www.facebook.com/mobvino
=> rester en contact
=> 
###The Crew/ l'équipe/ Behind the project
Emmanuel Pellegrin - Fondateur
Thomas Hear - Designer fou
Julien Rénier - Heavy codeur
Mr X - 
Toi Peut-être ?=>si tu est developpeur, commercial, fou de vins et que tu veux participer à une aventure humaine
###Les partenaires
LEAD OFF:  
INNOVOSUD

###Footer

{Message d'attente et d'invitation à  s'enregistrer}:
Nous sommes tout prêt à  vous offrir le meilleur des services.
Nous mettons tout en oeuvre pour peaufiner notre version première version Beta. Si vou ne voulez pas la rater, vous pouvez vous enregistrer
dès ajourd'hui
devenir un beta testeur de l'application : {bouton Notification}

#installation du serveur
##parametrage du serveur ssh
des erreurs peuvent apparaitre dans la log :  
Could not load host key: /etc/ssh/ssh_host_ecdsa_key" when connecting

`dpkg-reconfigure openssh-server`

##installation du serveur web
`sudo apt-get install apache2 php5`


##installation de github
 apt-get install git

##mise en place du mailer
sudo apt-get install ssmtp
Then edit /etc/ssmtp/ssmtp.conf file, comment out existing mailhub line and add the following lines (this example is for gmail smtp server):

mailhub=smtp.gmail.com:587
UseSTARTTLS=YES
AuthUser=<YOUR-EMAIL>@gmail.com
AuthPass=<YOUR-PASSWORD>
(Provide your gmail username & password. Of course you can use any other SMTP server).

Now make sure that your php.ini has correct sendmail_path. It should read as:

sendmail_path = /usr/sbin/sendmail -t
Reload apache and your php should be able to send outgoing emails now.

#redirection vers app store et google play