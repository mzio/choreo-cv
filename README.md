# Choreo-CV
A pet project for learning (unsupervised) action localization.  

High level overview and prospective features:  
* Given a video input of humans doing actions (e.g. kpop dance choreography), detect:  
  * The humans (actors) with bounding box and labels  
  * A specific action label (predefined action description? Ideally want to know if given a set of specific dance moves, which move is it. So detecting when an action occurs and when it changes to something else)  
  * May also want to be able to do pose estimation, so can map the human movement to a simpler skeleton, which can be duplicated and put in another environment.  
  * Hosted on the web? Should ideally do this in an unsupervised or weaky supervised (few labels) setup, but when deployed live we may also want to consider generalibility of being able to deal with (potentially noisy) annotations.
