<div align="center">

## Make Your Own Internet Explorer


</div>

### Description

to make your own internet web browser to use for personal uses. make a internet web browser to dislay latest news from your website. this uses the Microsoft Internet Explorer.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[D1M3N510N](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/d1m3n510n.md)
**Level**          |Beginner
**User Rating**    |2.5 (20 globes from 8 users)
**Compatibility**  |VB 6\.0
**Category**       |[Internet/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-html__1-34.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/d1m3n510n-make-your-own-internet-explorer__1-51375/archive/master.zip)





### Source Code

```
start a new .EXE file. go to Project>Components>Microsoft Internet Controls then click apply then close. you should see a new icon in the general window. it looks like a globe. click that and draw a big square on your form. you should make it fit right down to the bottom and right to the sides. not too far as users may not be able to see the information as it may go off screen. add a new text box and 1 new command button. double click on the command button and the code window will open. in the middle of the:
Private Sub Command1_Click()
and
End Sub
put WebBrowser1.Navigate Text1.Text so the code would look like this:
Private Sub Command1_Click()
WebBrowser1.Navigate Text1.Text
End Sub
what this code does is tells the web browser control to navigate to the url in the text box. you can add other commands other than Navigate.
Here are some of them:
WebBrowser1.Refresh
WebBrowser1.goBack
WebBrowser1.goForward
WebBrowser1.Stop
WebBrowser1.goHome
i think you can figure out what they all do. experiment with them.
NOTE: the user must have Microsoft Internet Explorer to run. hope you like my tutorial. rate it plz!
```

