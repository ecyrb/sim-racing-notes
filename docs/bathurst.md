# Thoughts on Spotting and Cameras for iRacing's Bathurst 12HR

tl;dr: I created a camera group [1] for spotting for the iRacing's *Bathurst 12HR*. You can download it [here](bathurst_advspot_v2.cam). Directions for use are below. The name of the camera group is **AdvSpot** (short for "advance spotter").

[1] A *camera group* is any arbitrary set of camera shots in iRacing. E.g. *TV1* is a camera group: when you watch TV1, the camera shot will change to different individual cameras in the TV1 group.

I applied the following philosophy to create this group:

1. You should **clearly** 5 seconds ahead of the *spotted car* at all times.
2. You should see the *spotted car* at all times.
3. Static shots of the track are preferred.
4. Your view should be such that your left is the driver's left.

I was not able to always apply these rules, but I did apply them in the above priority.

Another assumption I made is that the driver has some other spotter (e.g. CrewChief) to notify them about immediate threats ("car left").

### 1. You should **clearly** see 5 seconds ahead of the *spotted car* at all times.

I hope this one is obvious. If not, please see exhibit A: The case of the BMW coming down the mountain: ![](img/motivating_example.png)

This means that you "jump" to the next shot *at least* 5 seconds before the spotted car would leave the frame. Combined with #2, this means that you need more shots than you would, if you could follow a car to the end of the in-frame track segment.

### 2. You should see the *spotted car* at all times.

Because it's boring to spectate a race and not watch the car you're cheering for. Also, you can perform traditional spotting ("car left") in a pinch, or give guidance on rejoiring the track.

### 3. Static shots of the track are preferred.

Static cameras don't move, so you're less likely to become confused about which direction your facing, or having your view become obscured.

Unfortunately, trees, walls, bridges, and long straightaways make this difficult to do in practice. I cheated, and used a few chase cams on straightaways.

### 4. Your view should be such that your left is the driver's left.

So that if you do have to make a spotting call, you don't have to take the split-second to figure out which side a car is on.

### Directions

Put the downloaded .cam file in your `Documents\iRacing\cameras\tracks\bathurst` directory. When in the sim, bring up the camera controls (Ctrl + F12), and on the `group` tab, `load track`. `AdvSpot` should now show up in your list of cameras in the replay controls:

![](img/available_cams.png)
