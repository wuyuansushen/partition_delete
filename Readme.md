# Can not Remove partition in Windows

## 1.Can not delete partition

<img src="blankDelete.PNG" width="551" height="403" />

## 2.Open `Diskpart` in `CMD`

<img src="diskPart.PNG" />

## 3.Select your *disk* and *partition*

 <img src="select.PNG" />
 
 ## 4.Change `ID` of this partition

<img src="setID.PNG" />
 
```
set ID=ebd0a0a2-b9e5-4433-87c0-68b6b72699c7
```


ID Refer:[Example in Microsoft DOCS](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/set-id)

## 5.Delete partition successfully

<img src="delete.PNG" />