# K-RMA DoS

Développé dans nos atteliers, le K-RMA DoS est très simple à utiliser !

Voici donc un petit tutoriel très détaillé pour les moins doués en informatique d'entre vous : 

## 1. Le télécharger

Pour commencer appuyez sur "CODE"

![image](https://user-images.githubusercontent.com/108224457/193016172-1464f671-9fe7-41f5-a44e-5c47856e5269.png)

Puis sur "DOWNLOAD ZIP"

![image](https://user-images.githubusercontent.com/108224457/193016332-76a952be-621b-4bef-9470-4fcccf0368dc.png)

Extrayez l'archive zip puis ouvrez la

## 2. L'installer

Pour commencer installez python si vous ne l'avez pas déjà (https://python.org).

Ensuite ouvrez vôtre cmd

![image](https://user-images.githubusercontent.com/108224457/193017134-c62db3cd-4719-407d-ac9f-227f2bb28a6f.png)

Puis tapez : 

```pip install pip-upgrader```

```pip-upgrade```

![image](https://user-images.githubusercontent.com/108224457/193017318-9fa0913e-2b81-4a67-b096-6fd743d1a1fe.png)

![image](https://user-images.githubusercontent.com/108224457/193017410-16c50a63-3ddf-4249-b266-57f6d91b19e3.png)

Si jamais au ```pip-upgrade``` il vous marque ceci : 

![image](https://user-images.githubusercontent.com/108224457/193017493-5f744a46-6437-4939-bd63-ec6fc03ee601.png)

Ou toute autre erreur passez cette étape

On peut maintenant l'utiliser !

## 3. L'utiliser

Fermez le cmd et allez dans le dossier de K-RMA DoS

![image](https://user-images.githubusercontent.com/108224457/193017744-bd88f21a-cbb1-4b2d-bce6-eb878ef65699.png)

Puis appuyez ici : 

![image](https://user-images.githubusercontent.com/108224457/193017888-c800f1da-9da2-4769-809f-0add59bd00f4.png)

Et écrivez cmd puis appuyez sur Entrée

![image](https://user-images.githubusercontent.com/108224457/193018024-ff55c8a5-2b01-49f0-957c-7d1528868167.png)

Vous y écrivez : 

```python "K-RMA DoS.py" -s L'ADRESSE IP CIBLE -p LE PORT À ATTAQUER```

Ceci lancera une attaque DoS sur l'ip en question !

ASTUCE : pour attaquer un site, copier son url, enlevez le https:// afin de ne garder que le nom de domaine ! Celui-ci est l'ip publique du site et peut être utilisée comme ip cible de l'attaque, exemple : 

```https://google.com > google.com```

Ce qui donnera : 

```python "K-RMA DoS.py" -s google.com -p 80 -t 140```

Plus d'option : 
        -s : The server IP / IP Cible
        -p : The port (default 80) / Le port (80 par défault)
        -t : The turbo (default 135) / Le turbo (135 par défault)

# ATTENTION, JE NE SUIS PAS RESPONSABLE DE VOS ACTES ! CE SCRIPT EST À BUT EDUCATIF ! IL NE DOIT EN AUCUN CAS SERVIR À DES FINS MALVEILLANTES !
