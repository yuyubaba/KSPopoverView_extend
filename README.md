KSPopoverView_extend
====================

2012-5-17


extend to finish Dropdown
 
oday0311@hotmail.com
==========================

*** KSPopoverView ***

KSPopoverView is an iOS view controller that a user can flick & select the menu.

** Usage **
1. Include a "KSPopoverViewController.h" header
2. Apply KSPopoverViewControllerDelegate protocol
3. Init like as [[KSPopoverViewController alloc] initType:KSPopoverTypeTextLabel withImage:image point:location]
4. Add buttons by [vc addButtonWithTitle:button]
5. Write popoverViewController:selectedButton:AtIndex: delegate method and the event

** Author **
KatokichiSoft
http://cielo.rojo.jp

** License **
The new BSD license
