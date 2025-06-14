# PoseTraining ReadMe

# Released by P&K Industries for use by the general public
# Software is supplied 'as-is', but feedback and suggestions are welcome and encouraged
# For questions, comments, concerns or kudos, email Rayna at pkindtoys@gmail.com
# If you'd like to remix the files, by all means. But please include credit, and adhere to the license.
# Pose data was gleamed from pictures on the internet. While the pictures themselves aren't included in the program, if I find them again, credit will be added here.

=== Description ===
This is a slave pose training program that I wrote for private use, but thought was fun enough to share with the wider world. It's not perfect, but work will continue for as long as it's fun. The program is set up so that the user will input the number of poses they wish the program to cycle through (google 'Slave Poses' if you need a reference). As each pose is cycled through, the user will have a short grace period to adopt the pose specified in the window. The program will evaluate the user's pose, and if the user is posed within the (adjustable) tolerance of the reference pose, a timer will start. If the user leaves the pose, the timer restarts and points are deducted. Once the randomly set time to hold the pose has elapsed, the next pose is selected and the user is expected to adopt the new pose. Once the program has cycled through the number of poses specified by the user, the program will assign a score and end.

=== To Install ===
-This requires python to be installed. 
-This requires the mediapipe, cv2, and playsound packages.
-Download the files and run the *.bat file to prompt the python code to run.

=== Change Log ===
14-June-25
Initial commit

=== Current Plans ===
1. Make the GUI pretty
2. Give the poses more accessible names for displaying in the GUI
3. Make a self contained installation thing that doesn't require so much back end work
4. Refine and publish a program for establishing new pose files
5. Add sound effects and voice lines for encouragement/admonishment :)
6. Find out how to integrate with something like XToys or Buttplug.io for buzzy-zappy fun >:)

=== Lofty Dreams ===
Ideally, I'd like this to end up something like 'Cornertime' (Google it, it's amazing) where users can be sent a task to complete and the results get reported back to the one that initiated the task. I think it would be fun to also integrate with an app like Chaster, but that's a far flung goal and requires knowledge I don't currently have. Also, if you've read this far, use code 'MoreLikeBreedMe' on [pandktoys.spicerack.com](https://spicerack.market/p-and-kindustries/) for 5% off. And yes. That discount code exists specifically so I could make that pun.
