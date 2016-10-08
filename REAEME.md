#laadvresplayoutcssflexbox
##2. Flexbox-Powered Menus
###3 Using Flexbox to control single-level menu layout
6:13
```
.single-nav li{
		flex: 1 0 auto;
	}
}
```
 What this means is if there's available space, the box for the individual item will grow to fill the space. However, if the space is smaller than the default space for the item, then this box will not shrink but instead wrap down.


###4 Using Flexbox to control advanced menus
03:14
```
flex:0 0 1.5em;
```
So this basically means regardless of what is happening to the Flexbox, the item that's contained within the icon class will always be 1.5 ems wide


04:45
```
flex: 1 0 auto;
```
So the property is set to grow whenever possible so that it grows in width if the menu's really wide. But if the space available for the menu item is less than 12 ems, then the menu item's gonna wrap down instead of just shrink.
###3. Responsive Card Layouts
####5 Solving the common "anchor doesn't fill the card" problem
02:30
Flexbox, within each of the flex items, is making sure that the anchor tag is flooding the entire available space.