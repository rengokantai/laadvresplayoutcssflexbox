#laadvresplayoutcssflexbox
##2. Flexbox-Powered Menus
###Using Flexbox to control single-level menu layout
6:13
```
.single-nav li{
		flex: 1 0 auto;
	}
}
```
 What this means is if there's available space, the box for the individual item will grow to fill the space. However, if the space is smaller than the default space for the item, then this box will not shrink but instead wrap down.