# QA_Xpath
Level 01 of 26:
Select the plates
//plate

Level 02 of 26:
Select the bento boxes
//bento

Level 03 of 26:
Select the apple on a plate
//plate/apple

Level 04 of 26:
Select all elements
//*

Level 05 of 26:
Select all apples on any other element
//*/apple

Level 06 of 26:
Select the fancy plate
//*[@id="fancy"]

Level 07 of 26:
Select the apple on the plate
//plate/apple

Level 08 of 26:
Select the pickle on the fancy plate
//*[@id="fancy"]/pickle

Level 09 of 26:
Select the small apples
//*[contains(@Class,"small")]

Level 10 of 26:
Select the small oranges
//orange[contains(@Class,"small")]

Level 11 of 26:
Select the small oranges in the bentos
//bento/orange[contains(@Class,"small")]

Level 12 of 26:
Select all the plates and bentos
//plate|//bento

Level 13 of 26:
Select everything on a plate
//plate/*

Level 14 of 26:
Share
Select every apple that's next to a plate
//plate/following-sibling::apple

Level 15 of 26:
Select every pickle prior to the plate
//plate/preceding-sibling::pickle

Level 16 of 26:
Select the third pickle
(//pickle)[3]

Level 17 of 26:
Select the apple directly on a plate
//plate/apple

Level 18 of 26:
Select the small apple and the big orange
//plate/*[last()]

Level 19 of 26:
Select the last apple on each plate
//plate/apple[last()]

Level 20 of 26:
Select the second last apple on each plate
//plate/apple[last()-1]

Level 21 of 26:
Select the items for someone
//*[@for]

Level 22 of 26:
Select the plates for someone
//plate[@for]

Level 23 of 26:
Select Vitaly's meal
//*[@for="Vitaly"]

Level 24 of 26:
Select Hanna's meal on the fancy plate
//plate[@id="fancy" and @for="Hanna"]/apple

Level 25 of 26:
Select the items for names that start with 'Sa'
//*[starts-with(@for,"Sa")]

Level 26 of 26:
Select the items for names that end with 'ato'
//*[substring(@for,string-length(@for)-string-length('ato')+1)='ato']
