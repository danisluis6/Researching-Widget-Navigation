# WELCOME YOU RESEARCHING ANDROID TUTORIAL [![Build Status](https://travis-ci.org/nomensa/jquery.hide-show.svg)](https://travis-ci.org/nomensa/jquery.hide-show.svg?branch=master)

> Nickname: "Lorence"
> Hopies: Socer and Chess
> Major: Programmer
> Address: VietNam

- [Navigation Drawer](#navigation-drawer)
  - [Version1](#version1)
  - [RelationShip](#relationship)

  => Popup: Definition Menu And Initialize Event on Any Widget to call Popup and show
  => Toolbar: Definition Toolbar and Using include to set position toolbar in main layout.

## Step By Step 
    - Implement : "android.support.v4.widget.DrawerLayout"
    - Design layout activity_layout.xml 
       + Position Of Navigation Drawer
       + List of selection menu in android
    - Coding xml 
    - Notice that: We’ve used a ToolBar in place of an ActionBar here. ToolBar has been introduced since Android 5.0 as a     generalisation of ActionBar. It gives us more control and flexibility to modify and its easier to interleave with other views in the hierarchy.
    - We need to use the Theme Theme.AppCompat.NoActionBar in the styles.xml when using Toolbars.
    ==> Using commnad: <style name="AppTheme" parent="Theme.AppCompat.Light.NoActionBar">
    Finish Step 1

    Create A Menu For Navigation Drawer (Step 2)
    - Create a list_view_item_row.xml like listview[Custom ListView Advance]

    The navigation drawer items are put in a string array in the strings.xml file as shown below.

    - Customize String.xml 
    
    Step 3: Definition Object for Navigation Drawer.
    The DataModel.java class is used to define the objects for the drawer list items.
    
    Step 4: The drawer items are stored in the form of a ListView. Hence we need to use an Adapter Class to provide that data to the activity class.
    => You should create DrawerItemCustomAdapter.java (Think setAdapter or setModel to understand it)

    Finally, We coding MainActivity.java and Connect Fragment In Android Studio.
    

## Version1
<p align="center">
  <img src="https://github.com/danisluis6/Researching-Widget-Navigation/blob/version1/Navigation/1.png">
</p>

<p align="center">
  <img src="https://github.com/danisluis6/Researching-Widget-Navigation/blob/version1/Navigation/2.png">
</p>


