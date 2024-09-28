  ----> onCreate()
 |         |
 |     onStart()
 |         |
 |     onResume() <--------------------
 |         |                            |
 |     Running (User is interacting)    |
 |         |                            |
 |     onPause() ---------------------> |
 |         |                            |
 |     onStop()                         |
 |         |                            |
 |     onRestart() <------------------- |
 |         |
  ----> onDestroy()
  
Key Transitions:
onCreate() → Initializes the activity.
onStart() → The activity becomes visible.
onResume() → The activity comes to the foreground and the user can interact.
onPause() → The activity loses focus but is still partially visible.
onStop() → The activity is completely hidden.
onDestroy() → The activity is being destroyed and resources should be cleaned up.
