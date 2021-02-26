# Thoughts on Spotting and Cameras for iRacing's Bathurst 12HR

tl;dr: I created a camera group [1] for spotting for iRacing's *Bathurst 12HR*. You can download it [here](bathurst_advspot_v2.cam). Directions for use are below. The name of the camera group is **AdvSpot** (short for "advance spotter").

[1] A *camera group* is any arbitrary set of camera shots in iRacing. E.g. *TV1* is a camera group: when you watch TV1, the camera shot will change to different individual cameras in the TV1 group.

I applied the following philosophy to create this group:

1. You should **clearly** see 5 seconds ahead of the *spotted car* at all times.
2. You should see the *spotted car* at all times.
3. Static shots of the track are preferred.
4. Your view should be such that your left is the driver's left.

I was not able to always apply these rules, but I did apply them in the above priority.

Another assumption I made is that the driver has some other spotter (e.g. CrewChief) to notify them about immediate threats ("car left").

#### 1. You should **clearly** see 5 seconds ahead of the *spotted car* at all times.

I hope this one is obvious. If not, please see exhibit A: The case of the BMW coming down the mountain: ![](img/motivating_example.png)

Being able to see *5 seconds ahead* means that we have to leave the shot *at least* 5 seconds before the spotted car. Combined with #2 and #3, this has the effect of needing more camera shots. AdvSpot is made up of 24 different cameras (shots), so for a 2:06 lap, you average 5.25 seconds on each camera.

#### 2. You should see the *spotted car* at all times.

It's boring to spectate a race and not watch the car you're cheering for. Always having your car in frame also means that you can perform traditional spotting in a pinch ("car left"), or give guidance on track rejoins, etc.

#### 3. Static shots of the track are preferred.

Static cameras don't move, so you're less likely to become confused about which direction you're facing. And you can set the camera up so that your view isn't obscured. See also exhibit B: The chopper view of the BMW coming down the mountain: ![](img/chopper_view.png)

Unfortunately, trees, walls, bridges, and long straightaways make achieving this goal difficult; I cheated and used a few chase cams on straightaways.

#### 4. Your view should be such that your left is the driver's left.

So that if you do have to make a spotting call, you don't have to take the split-second to figure out which side a car is on. This means that cameras are placed to look *behind* the driver, in the direction of travel. Due to obscured sight-lines at Mount Panorama, this isn't always possible, so there are a few backwards-looking shots.

### Directions

Put the downloaded .cam file in your `Documents\iRacing\cameras\tracks\bathurst` directory. When in the sim, bring up the camera controls (Ctrl + F12), and on the `group` tab, `load track`. `AdvSpot` should now show up in your list of cameras in the replay controls:

![](img/available_cams.png)

**Note these buttons on the group editor control:** ![](img/group_editor.png)

The circled buttons can be used to move the camera group up or down in the list of cameras. **A camera's position is its number.** Also note that you cannot change the position (or number) of the first 9 cameras. A camera's number is used in the shortcut controls:

`*[car number]*[camera number]<enter>`: Focus specified camera on specified car.\
`*[car number]<enter>`: Focus current camera on specified car.\
`**[camera number]`: Switch to specified camera, keeping focus on current car.

I bump `AdvSpot` up to position 10 (`**10`), and also move the chase cams up to positions 11-13, so I can quickly flip to them.

I'm also using [Joel Race Timing](http://joel-real-timing.com/).
