# CHAPTER_8
Creating an App’s Navigation

Creating an app’s navigation in Flutter involves designing a way for users to move between different screens or pages within the app. Flutter provides multiple tools and patterns for navigation, enabling developers to build simple or complex navigation flows efficientl.  I've learned that navigation is a major component in a mobile application. Good
navigation creates a great user experience (UX) by making it easy to access information. For
example, imagine making a journal entry, and when trying to select a tag, it’s not available, so
you need to create a new one. When the user taps each
BottomNavigationBarItem, the appropriate page is displayed. To enhance the look of a bottom
navigation bar, you used the BottomAppBar widget and enabled the optional notch. The notch is the
result of embedding a FloatingActionButton to a BottomAppBar by setting the BottomAppBar
shape to a CircularNotchedRectangle() class and setting the Scaffold floatingActionButtonLocation property to FloatingActionButtonLocation.endDocked.
The TabBar widget displays a horizontal row of tabs. The tabs property takes a List of widgets,
and tabs are added by using the Tab widget. The TabBarView widget is used in conjunction with the
TabBar widget to display the page of the selected tab. Users can swipe left or right to change content
or tap each Tab. The TabController class handled the syncing of the TabBar and selected TabBarView. The TabController requires the use of with SingleTickerProviderStateMixin in the class.


![6907d237-dc28-4ee3-8055-f9fb26b33d3a](https://github.com/user-attachments/assets/a6109925-f75b-4720-a926-0832139c2a7f)
