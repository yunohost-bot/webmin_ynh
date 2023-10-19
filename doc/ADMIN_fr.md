* Cette application dispose d'un accès **root** qui peut modifier les éléments essentiels du système, **casser YunoHost**. Utilisez-le avec précaution et lisez la [document](https://doxfer.webmin.com/Webmin/Main_Page) avant de modifier les valeurs.
* Seul l'**utilisateur** disposant de l'autorisation au moment de l'installation peut **accéder** à l'interface de connexion Webmin.
* Pour vous connecter à webmin, utilisez root et le mot de passe root
* Webmin se mettra **à jour** lorsque les mises à jour du système seront exécutées. Pas besoin donc d'**exécuter le script de mise à niveau** une fois installé.

### Corriger le nom d'utilisateur et le mot de passe

Si vous ne parvenez pas à vous connecter, vous pouvez corriger le mot de passe de l'utilisateur avec la commande suivante :
```
/usr/share/webmin/changepass.pl /etc/webmin root >nouveau mot de passe>
```