# MAD Practical 3 - Event-Handler
Continuing from last week, you will be adding interactivity to your app. <br/>
Follow the instructions below to complete your app.

1. Modify the onClickListener of left button to show a Toast message. The toast message will show `Followed` if the user click on the `Follow` button, and vice versa.

![Toast Message](/images/p2_toast.png)

2. Create a new Empty Activity with the following configuration,
    * Activity Name: ListActivity
    * Generate a Layout File: Checked
    * Layout Name: activity_list
    * Launcher Activity: Checked
    * Source Language: Java

3. In the `activity_list` layout file, create an `ImageView`, position it in the middle of the screen.

![ImageView in middle of Activity](/images/p2_img.png)

4. Create an `onClickListener` for the image created in previous step. Upon clicking the image, an `AlertDialog` will appear as shown in the figure below.

![AlertDialog](/images/p2_alert.png)

5.	Upon clicking the `View` button, a random integer will be generated. The `MainActivity` (created in previous practical) will be launched, and the random integer is sent over.

6.	Modify the `MainActivity` to display the random integer together with the name. 

![Updated Profile page](/images/p2_final.png)

To submit your practical, remember to commit the changes and push to remote repository.
