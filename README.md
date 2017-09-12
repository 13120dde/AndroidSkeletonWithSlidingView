# AndroidSkeletonWithSlidingView
Simple Android app with a sliding menu. Only the logic for creating a slidingmenu is implemented.
Create new Fragments wchich will be shown in MainActivity's main_content-layout.

To populate the menu with new menu-items, simply instantiate new ItemSlideMenu-objects in 
addItemsToSlidingList(List<ItemSlideMenu> listSliding) in Controller class. 

To show Fragment on clicking on the ItemSllideMenu-object in the menu, implement code in 
replaceFragment(int position, boolean backstack) method in Controller class.
