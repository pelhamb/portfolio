## LAB 1
  
Lab 1 mostly consisted of setting up our robot's first mechanisms and 
creating protocols for turning and reading distances. Our initial assembly went smoothly, with most of the connections between mechanical components being tight and secure. The servos were slightly more problematic. We noticed immediately that, even with the battery outputting the proper voltage, one wheel was slightly out of sync with the other, causing our robot to veer to the left across any non-minute distance. We ended up correcting for this inconsistency by changing the respective wheel powers, but this ordeal was made even more difficult as we realized the battery power affected the performance of the robot in very significant ways, and somehow our batteries had drained especially fast despite us unplugging the connections before we left the robot each week. With low servo battery voltage, our turns were misaligned, so we had to be sure that we had the proper voltage across each battery before finalizing our code for the first maze demo.  
  
The US sensor integration went relatively smoothly in comparison to the host of problems with the servos and battery. After plugging them all in as specified in the example code, we found them working properly and giving reliable measurements when the frequency of measurement was in a good place. If we made it read too often, it would be overly sensitive to small changes in the distances it was reading. If it read too infrequently, we risked hitting a wall while the read was in its waiting period. We found a happy medium where the robot appeared to sense the walls well and not have issues with overcorrecting. 
  
The final maze demo was more challenging. We made states for each part of the operation, a strategy which appeared to work well, but fine tuning the turn values and hoping the robot's error wouldn't compound too much throughout the maze was tougher. One thing that helped us a lot in fixing our calculations was ensuring that the servo battery voltage was at a proper level, as described above. This made our turns consistent and reliable. After doing this, we only had to fine-tune the values of the turn time and the code we had written worked almost perfectly. We used a trial-and-error approach to get the proper delay times for each respective turn, and for the final straightaway where the robot's change in action is not triggered by a wall.
  
## MEDIA
  
This is a capture of the serial monitor for the distance sensors during the first maze test.  
  
<img src="positionLog.png" height="700" width="700">
  
This is the [video of our robot completing the first maze test](https://www.youtube.com/watch?v=lyOWazyi4gk&ab_channel=pberg).  
  
<video width="500" height="700" src="IMG_6084.mp4" type="video/mp4" autoplay preload="auto" loop>
</video>
  
This is a picture of our robot.  
  
<img src="IMG_6099.png" height="800" width="700">