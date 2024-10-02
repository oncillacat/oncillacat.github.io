## Loop structure: if else loop
new month new loop structure,Hooray. 。。。sort of? 
Anyway, today we are talking about **if else** loop. And yes...it is kind of different from *if loop* we discussed in the pervious post.

## if else loop 
this photo in class shows how for if else works

<img width="435" alt="Screenshot 2024-10-01 at 10 25 48 PM" src="https://github.com/user-attachments/assets/7fa3b3ca-e4cd-4808-aef0-69b71ffb482b">

the main difference of it from if loop is that it **can** and **must** put in 2 statement.

If we are translating if else loop to written language. It should be like *when we found [condition X] then do [statement Y]. If [condition X] is 
not met,then we perform [statement Z]*

Note statement here is the code we wrote in the loop. For example, print("Hello").

An example if loop looks like this:
```r
x <- -5
if(x >=0)
{print("Non-negative number")}
else
{print("Negative number")} 
```
Please note the location of () and {}* matter!!! Make sure [condition X] is in the () and [statement Y/Z] is in the {}. AKA
```r
if([condition X]){
[statement Y]}
else{
[statement Z]
}
```
In pervious example:

[condition X] = x >=0

[statement Y] = print("Non-negative number")

[statement Z]= print("Negative number")

Let us use scratch block to repeat this If loop again

<img width="527" alt="Screenshot 2024-10-01 at 10 35 57 PM" src="https://github.com/user-attachments/assets/eb541a96-077c-46b7-9f18-801737f2416f">

the operation result is as follow:
![ScreenRecording2024-10-01at10 36 40PM-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/c7fde985-ee40-42ae-880e-264945f003ad)


PS:what if you want to use if else but does not want to write 2 statements? 。。。I saw my follow classmates set 
statement 2 to NA,but I haven't try it myself. 
