# Lesson: Digital & Serious Games

### First and Last Name: Orestis Ntagiannis
### University Registration Number: dpsd18084
### GitHub Personal Profile: https://github.com/Orestis18084
### Digital & Serious Games Personal Repository: https://orestis18084.github.io/Role-Playing-Game/

# Introduction

test

# Summary


# 1st Deliverable

Προσθήκη χαρακτήρα και κώδικα για κινήσεις.
Απο [εδώ](https://craftpix.net/freebies/free-knight-character-sprites-pixel-art/)

![Protect](https://user-images.githubusercontent.com/116592885/201412815-0b4370a9-46f1-45c5-9406-f04aa2621d04.png)
 
Η κάμερα ακολουθεί τον χαρακτήρα.
Δημιουργία περιβάλλοντος αφού κατέβασα ένα pack με assets.
Απο [εδώ](https://angrysnail.itch.io/pixel-art-graveyard-tileset)

![image](https://user-images.githubusercontent.com/116592885/201414807-4c3116cb-c960-4c35-ac82-16ade2b3ae88.png)

Διαχωρισμός layers για περαιτέρω διακόσμηση και interaction με το περιβάλλον(κρύβεται πίσω από αντικείμενα ή περνά απο μπροστά τους)

![image](https://user-images.githubusercontent.com/116592885/201414855-5b2f915d-4bf4-421c-bc62-1701cd53b8ed.png)
![image](https://user-images.githubusercontent.com/116592885/201414912-644e4885-2292-47fd-9003-bc7b6ed30ef2.png)


# 2nd Deliverable

Το παιχνίδι άλλαξε διότι δημιουργήθηκε ένα πρόβλημα με ένα απο τα GameObjects στα prefabs.

Ξεκίνησα νέο project με διαφορετικά assets ταιριαστά για top-down.

Παρακάτω βλέπουμε τον χαρακτήρα και τους αντιπάλους αντίστοιχα.


![Ancient Skeleton Animation Showreel](https://user-images.githubusercontent.com/116592885/208311618-fcff51b0-354c-4018-8459-8c431544684e.gif)

![Skeleton Idle](https://user-images.githubusercontent.com/116592885/208311684-d6d008d4-03c6-436f-94d8-c9b40306cfb6.gif)![Skeleton Walk](https://user-images.githubusercontent.com/116592885/208312335-c7eefa33-815d-40bb-801e-29a777dd3031.gif)![Skeleton React](https://user-images.githubusercontent.com/116592885/208312339-d4120a7f-5ab9-4d42-8500-a68054e01fac.gif)![Skeleton Attack](https://user-images.githubusercontent.com/116592885/208312305-9f4f78e9-f7dd-4ec7-aeec-d411e1e858be.gif)![Skeleton Hit](https://user-images.githubusercontent.com/116592885/208312309-64a103c2-4265-4163-a166-6f3b943af82c.gif)![Skeleton Dead](https://user-images.githubusercontent.com/116592885/208312310-9e9715ae-9163-4cc3-9e8c-548edb83b374.gif)




 -World Interactions - Blocking Movement.
 
 Αφού δημιούργησα το περιβάλλον τοποθέτησα ενα πλαίσιο ώστε να μην μπόρει να υπερβεί τα όρια η κάμερα και βγεί εκτός.
 
 ![image](https://user-images.githubusercontent.com/116592885/208311512-cfff7549-f735-4552-86f5-f49fbfb85340.png)
 ![image](https://user-images.githubusercontent.com/116592885/208311550-c922e6fa-4af1-4378-876b-c2634da69371.png)
 
 Έπειτα πρόσθεσα colliders του περιβάλλοντος για τους χαρακτήρες.

![image](https://user-images.githubusercontent.com/116592885/208311530-6514d8c3-cf7b-434e-8046-608cf03b4018.png)



 -World Interactions - Damage Zones and Enemies. 
 
 Τοποθέτησα (RigidBody/Collider)2D και όταν ο χαρακτήρας έρχεται σε επαφή με τους αντίπαλους σκελετούς δέχεται damage παρόλο που δεν υπαρχουν τα animations ακόμα.
 
 ![image](https://user-images.githubusercontent.com/116592885/208311577-c70cac61-365f-4dc1-845f-f8e0e42a36bc.png)
 
 ![image](https://user-images.githubusercontent.com/116592885/208311591-fc31e021-033f-48fe-afe1-7a1725611778.png)
 
![image](https://user-images.githubusercontent.com/116592885/208311596-d932cf25-1aa2-4f1f-98bd-a7d2f85c9142.png)




 -Sprite Animation
 
 Υπάρχει ένα glitch στην κίνηση του χαρακτήρα, το οποίο ευθύνεται στο flip animation/MovementTree.
 
 Melee/Damage/Death animations θα ξαναπροσθεθούν μόλις κατασταλάξω σε Assets.
 
 Μέχρι τώρα οι σκελετοί παραμένουν ακίνητοι στο σημείο που δέχθηκαν το τελειωτικό χτύπημα.
  
 

 -World Interactions - Projectile .
C = Projectile.

 -Camera - Cinemachine.

Όσον αφορά την κάμερα πρόσθεσα ενα πλέγμα στο περιβάλλον για να ορίσω τα όρια της.
(CameraConfiner)

Τέλος έβαλα PixelPerfect(Script) ελπίζοντας σε μια πιο καθαρή εικόνα inGame.



# 3rd Deliverable 


# Conclusions


# Sources
