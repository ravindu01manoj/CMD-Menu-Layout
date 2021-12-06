# You Can Add Your Own Command Menu For Sew Queen

***

## step 

1). Fork This Repo <br>
2). ADD YOUR OWN LAYOUT FILE To Menus Folder (do not use your name or any other copyright for layout)<br>
3). ADD YOUR REQUEST To export.js Like Exampels<br>
```js
let yourlayout  = require('./Menus/yourfilename')



// exsample for add your own layout

if(Details.CMD_LAYOUT == 'yourlayoutname') {
 DOWNLOADCMD = yourlayout.DOWNLOADCMD
 LOGOCMD = yourlayout.LOGOCMD
 PROFILECMD = yourlayout.PROFILECMD
 ADMINCMD = yourlayout.ADMINCMD
 AUDIOCMD = yourlayout.AUDIOCMD
 VIDEOCMD = yourlayout.VIDEOCMD
 IMAGECMD = yourlayout.IMAGECMD
 DEEPAICMD = yourlayout.DEEPAICMD
 }
```
<br><br>
4). Make Pull Request<br>
