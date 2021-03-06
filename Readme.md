#Game Librarian

A Windows Metro XAML interface for my freeware game collection. Very early stages and very little functionality, but lots of ugly hard-coding, inefficient loops and template hacking. Peruse at own risk.

##How to use

*Step 1:* Have a game collection with a folder structure that looks something like this:

```
Games
|----SomeCategoryWithSubCategories
     |----SomeSubcategory
	      |----Game1
		  |----Game2
		  |----...
		  |----GameN
|----SomeOtherCategoryWithoutSubcategories
     |----Game1
	 |----Game2
	 |----...
	 |----GameN
```

*Step 2:* Launch the app and provided it with the main folder.

##Upcoming features

* In-app configuration of subcategories (currently hardcoded to match my collection)
* In-app configuration of folders to ignore (currently anything beginning with "zzz")
* Listing and launching of game documentation and executables (if at all possible)
* Random coloured boxes or something for category and game grid squares
* Search
* Statistics page that tells you how many games you have in each category
* Logging of new game additions
* Editable game and category descriptions so you can make notes