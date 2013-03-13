*****BriceShatzer npp-Personalization*******
		- Adds syntax highlighting for SASS, SCSS, & jQuery
		- Adds code hinting and autocomplation for jQuery
		- Provides a darker and easier to view color theme 

		**jQuery Code Hinting And Autocompletion in Notepad++**
forked from jamesallardice - https://github.com/jamesallardice/notepadplus-jQuery.git 

**************************************************	
*****note: all instructions assume Windows 7******
********** and the system font 'Consolas' ********
************************************************** 

userDefineLang.xml
	- add to Notepad++ installation directory & user/AppData/Roaming/Notepad++ 
	- if a version already exists in either location simply copy the contents of userDefineLang.xml and paste it into the bottom of the existing userDefineLang.xml, and be sure to remove the extra </NotepadPlus><NotepadPlus> at the point where you pasted in the new content.
	-This adds SASS, SCSS, and jQuery syntax highlighting to Npp

jquery.xml
	-  Within the Notepad++ installation directory, add to /plugins/APIs

 
darkThemeBase.xml
	- Provides language specific sytanx highlighting for just the lanugages included with Npp
	- Within the Notepad++ installation directory, add to /themes

darkThemeExtend.xml
	- Provides language specific sytanx highlighting for all lanugages included with Npp and the additional user defined languages
	- Within the Notepad++ installation directory, add to /themes