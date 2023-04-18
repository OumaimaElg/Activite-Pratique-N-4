# Activite-Pratique-N-4

## objectifs de l'atelier:
Récupérer le code source de l'application non sécurisé qui permet de gérer les patients (résultat de l'activité pratique N°3). 
Sécuriser cette application en intégrant un système d'authentification basé sur Spring security avec les trois stratégies : 
-InMemoryAuthentication

-JdbcAuthentication 

-UserDetailsService

## Les dependances utilisées dans cet atelier sont:
 -Lombok : Un outil de bibliothèque Java qui génère du code pour minimiser le code ‘boilerplate’. La bibliothèque remplace le code ‘boilerplate’ par des annotations faciles à utiliser (Exemples : @NoArgsConstructor, @Getter, @Setter…). 
 
 -Spring Web : pour créer des applications Web, y compris RESTful, à l'aide de Spring MVC. Utilise Apache Tomcat comme conteneur intégré par défaut.
 
 -Spring DATA JPA : Pour conserver les données dans ‘SQL stores‘ avec Java Persistance API à l’aide de Spring Data et Hibernate. C'est un module qui facilite le ORM basé sur JPA. Il est utilisé avec les bases de données relationnelles.
 
  -H2 Database : Une base de données intégrée, open source et en mémoire. C'est un système de gestion de base de données relationnelle écrit en Java. C'est une application client/serveur et elle est généralement utilisée dans les tests unitaires.
  
  
  
   # Compte Rendu et Capture d'ecrant de l'atelier
  
  * page d'authentification:
  
  ![image](https://user-images.githubusercontent.com/72994860/232752580-f31b71ed-ec09-495a-b7d1-eae64028eb12.png)
  
  * L'interface si le compte est un compte USER :
  
  ![image](https://user-images.githubusercontent.com/72994860/232757166-f9d895c2-6cbe-4522-b512-517360f87dba.png)

  * User peut chercher un patient et naviguer la pagination :
  
  ![image](https://user-images.githubusercontent.com/72994860/232757377-0d4bd081-de85-46f4-ab1c-d569dd10223c.png)
  
  * un user n'est pas authoriser a supp un patient:
  
  ![image](https://user-images.githubusercontent.com/72994860/232758232-2cdbffa5-a707-4cd0-8ae2-1be8a480432f.png)
 
  * user Logout:
   
   ![image](https://user-images.githubusercontent.com/72994860/232758776-73286e79-ea5e-4fd3-a7a6-fd532dfe4726.png)
  
  * Un Admin peut chercher, ajouter, modifier ou supprimer un patient :
  
  ![image](https://user-images.githubusercontent.com/72994860/232760652-93f182e0-3ac6-42bc-a2cd-a6d5d863a913.png)



