#Test Art Scan

## call different image tpye

![TestArtScanUse](.\Images\_TestArtScanUse.bmp)

![TestArtScanUse](.\Images\_TestArtScanUse.gif)

![TestArtScanUse](Images\_TestArtScanUse.jpeg)

![TestArtScanUse](.\Images\_TestArtScanUse.jpg)

![TestArtScanUse](.\Images\_TestArtScanUse.png)

## Different Address
![](.\Images\_TestArtScanUse_NoName.jpeg)

![12](.\Images\_TestArtScanUse_NOName.bmp)

with title
![TestArtScanUse](.\Images\_TestArtScanUse_WithTitle.jpg "title")

image0
![TestArtScanUse][Image0]

image0 uppercase
![TestArtScanUse][IMAGE0]


no title
![TestArtScanUse][Image0EX0]

Wrong Path
![TestArtScanUse][Image0EX1]

uppercase of the extension
![TestArtScanUse][Image0EX2]

thw extension of .abcpng
![TestArtScanUse][Image0EX3]


No Space after : 
![TestArtScanUse][Image4]

Multi Space after :
![TestArtScanUse][sd]

No Value in the ID
![TestArtScanUse][]

a Space value in the ID
![TestArtScanUse][ ]

two space value in the ID
![TestArtScanUse][  ]

## In the Content
There should be a image ![TestArtScanUse](.\Images\_TestArtScanUse_IntheContent.png)

## Nested

Name|Image
----|-----
AAAA|![TestArtScanUse](.\Images\_TestArtScanUse_NestedINTable.jpg)
BBBB|![TestArtScanUse][Image1]

1. ![TestArtScanUse](.\Images\_TestArtScanUse_NestedInList.jpg)
2. ![TestArtScanUse][Image2]

> ![TestArtScanUse](.\Images\_TestArtScanUse_NestedInblock.png)
> ![TestArtScanUse][Image3]

muity nested 
> Name|Image
> ----|----
> AAAA|![TestArtScanUse](.\Images\_TestArtScanUse_MutiNested.jpg) 

> 1. ![TestArtScanUse](.\Images\_TestArtScanUse_MutiNested.jpg) 
> 2. ![TestArtScanUse][Image3]
> 



List the refernce of image, should no be shown
[Image0]: .\Images\_TestArtScanUse_RAddress.png "Title"
[Image0EX2]: .\Images\_TestArtScanUse_RAddress1.PNG "Title"
[Image0EX3]: .\Images\_TestArtScanUse_RAddress.abcpng "Title"


[Image0EX0]: .\Images\_TestArtScanUse_RA_NoTitle.gif
[Image0EX1]: \_TestArtScanUse_RA_NoTitle.gif "Title"
[Image1]: .\Images\_TestArtScanUse_NestedINTable_RA.jpg "Title"
[Image2]: .\Images\_TestArtScanUse_NestedInList_RA.jpg "Title"
[Image3]: .\Images\_TestArtScanUse_NestedInblock_RA.png "Title"

[Image4]:.\Images\_TestArtScanNOTUse.bmp "Title"
[sd]:    .\Images\_TestArtScanNOTUse.gif "Title"

[]:.\Images\_TestArtScanNOTUse.gif "Title"
[ ]:.\Images\_TestArtScanNOTUse.gif "Title"
[  ]:.\Images\_TestArtScanNOTUse.gif "Title"

[IMAGE0]: .\Images\Desert.jpg "Title"