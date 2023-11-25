# RoutinizerApp# RoutinizerApp
### :one: Introduction
Routinizer App is an Android app created with Java in Android Studio. This app simplifies daily life by offering timers, to-do lists, and reminders. Powered by Firebase for real-time data storage, Routinizer helps users organize tasks, build habits, and optimize their routines. Stay productive and reach your goals effortlessly with Routinizer.
###2️⃣:Hardware Specification<br>
✔ Processor - Intel Pentium IV.
✔ Processor Speed – 1.40 GHz.
✔ RAM – 2 GB or above.
✔ Monitor resolution - A color monitor with a minimum resolution of 1000*700
Software Specification<br>
✔ Operating System: Windows / LINUX / any operating system that supports a browser.
✔ Language used: JAVA
✔ Database: Firebase

### :three: Architecture Diagram

  <img src="https://github.com/shivannirai/RoutinizerApp/blob/master/achitecturediagram.png" width=700>
 </p>

### :four: Pseudocode of LZW algorithm
Main page with Navigation Bar : 
````
 Mainpagewithnavbar
protected void onCreate(Bundle savedInstanceState) {
 super.onCreate(savedInstanceState);
 setContentView(R.layout.activity_main_page_with_nav_bar);
 bnv = findViewById(R.id.bottomNavBar);
 fragmentManager = getSupportFragmentManager();
 showFragment(new ForyouFragment());
 bnv.setOnItemSelectedListener(item -> {
 if(item.getItemId()==R.id.forYou) {
 showFragment(new ForyouFragment());
 return true;
 } else if (item.getItemId()==R.id.task) {
 showFragment(new MainPageFragment());
 return true;
 } else if (item.getItemId()==R.id.timerMenu) {
 showFragment(new TimerFragment());
 return true;
 } else if (item.getItemId()==R.id.logoutMenu) {
 finish();
 return true;
 }
 return false;
 });
 }
 private void showFragment(Fragment fragment) {
 fragmentManager.beginTransaction()
 .replace(R.id.fragmentContainerView, fragment)
 .commit();
 }
}
 ````


 


### :five: Conclusion
In conclusion, "Routinizer App" is a mobile application developed using Android Studio and Java.
The Routinizer app is a valuable tool for individuals looking to manage their time effectively,
improve productivity, and stay accountable to their routines. With features like timers, task
organization, and reminders, the app helps users streamline their daily activities and accomplish their
goals efficiently. Thank you!


````

### :five: Conclusion
This project demonstrates LZW Algorithm and its two parts - the encoding algorithm, which converts strings to integer codes, and the decoding algorithm, which does the opposite. Thank you!