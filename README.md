# Cinemates20_BackEnd
In questa Repository viene descritto il codice relativo alle funzioni AWS Lambda, utilizzando il framework NodeJS, relativo al progetto CineMates20.<br><br>
Il client Android e la relativa documentazione cui questa repository fa riferimento è presente al seguente <a href="https://github.com/lucaLP98/CineMates20_Mobile">LINK</a>

<h1>SCHEMA ARCHITETTURA SERVER</h1>
Il sistema utilizza un'architettura del tipo Servless, sfruttando le potenzialità offerte dai servizi AWS: API Gateway, Lambda, RDS.<br><br>

Il sistema fa uso anche del servizio Cloudinary per l'hosting dei file multimediali, The Movie Database per le informazioni riguardanti i film e AWS Cognito per fornire autenticazione agli utenti.<br><br>

Di seguito uno schema architettura del server:<br>
![image](https://drive.google.com/uc?export=view&id=15MNPxO6eXV8AxhA9D4oOXEauQpy1RQ_H)
