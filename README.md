# Installation-du-firewall-pfSense
Installation du firewall pfSense

- D'abord création de la VM.

![pfsense0](https://github.com/JohanaJimenez1/Installation-du-firewall-pfSense/assets/137881601/baeb5500-a23c-49b6-8074-4125beceaca7)

Il faut mettre 2 type de réseau 
- Accès par pont (interface WAN) et réseau interne (LAN),
ensuite télecharger l'image ISO depuis le site internet pfsense.
- Démarrer la VM et commencer la configuration 

![pfsense0 1](https://github.com/JohanaJimenez1/Installation-du-firewall-pfSense/assets/137881601/58372d2e-cce9-4dcf-a649-ecb03427de22)

![pfsense0 2](https://github.com/JohanaJimenez1/Installation-du-firewall-pfSense/assets/137881601/7cfd4942-9767-4cde-b9fb-4b1a876103c9)

- Une fois fait l'installation de pfsense on fait la configuration des interfaces LAN et
WAN, indiquez la nouvelle adresse IP. Ensuite, pour le masque indiquez 24 et ok
une fois la configuration est pret vous pouvez aller sur la achine CLIENT2 et 
configurez une adresse IP fixe.

![pfsense2](https://github.com/JohanaJimenez1/Installation-du-firewall-pfSense/assets/137881601/41317d2a-2dbe-4169-8d37-58a5bd253cca)

![pfsense5](https://github.com/JohanaJimenez1/Installation-du-firewall-pfSense/assets/137881601/1990584d-28d9-45cc-bd69-b677610ae011)

- Ensuite ouvrir le navigateur machine CLIENT pour poursuivre la configuration.
écrire l'adresse IP dans la barre d'adresse. Par défaut.
S'authentifier avec l'utilisateur **admin** et le mot de passe **pfsense**.

![pfsense3](https://github.com/JohanaJimenez1/Installation-du-firewall-pfSense/assets/137881601/5f77f2a2-8c67-4c5c-8786-643a141275cd)

Pour créerune nouvelle regle clic sur **firewall** 
selectionnez rules puis clic en LAN puis **Add** bouton vert

![pfsense4](https://github.com/JohanaJimenez1/Installation-du-firewall-pfSense/assets/137881601/bc925cbc-54c3-49c5-a8b2-c80f6e057d7d)

![pfsense7](https://github.com/JohanaJimenez1/Installation-du-firewall-pfSense/assets/137881601/f94e1174-2a17-4e47-8f7c-2e2bf5a1b702)

![pfsense6](https://github.com/JohanaJimenez1/Installation-du-firewall-pfSense/assets/137881601/ebd1a56a-7429-458c-8b9a-9e136038b994)

![pfsense8](https://github.com/JohanaJimenez1/Installation-du-firewall-pfSense/assets/137881601/c654f5f1-a8d6-4fd9-8425-ad658f684c97)
