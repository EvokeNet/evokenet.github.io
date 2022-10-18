---
sidebar_position: 4
---

# Evoke badges

Badges are a good way of celebrating achievement and showing progress. Badges may be awarded based on a variety of chosen criteria and may be displayed on a user's profile.

By default, Moodle comes with some criteria to deliver badges, but it is a poor toolset, that limits our creativity and Evoke's innovative purpose.

Evoke project has its own toolset of badge criteria, with possibilities to combine these criteria, and if necessary, a simple way to develop new criteria.

### Course badges

Creating new badges on your course is simple, you need to navigate through the secondary menu and click on More, and then in Evoke badges settings.

![Evoke badges settings](/img/local_evokegame/game5.png)

On this page, it is possible to manage all course badges, configure their criteria, and deliver badges to those who deserve the badge.

![Evoke badges settings](/img/local_evokegame/game6.png)

### Create badge

To create a new badge, you just need to click on the button Create badge.

A modal is displayed with a simple form.

![Evoke badges settings](/img/local_evokegame/game7.png)

#### Badge type

There are two types of badges, badges, and achievements. The initial idea is that Badges are big accomplishment, and achievements are usual and more easy to achieve.

When a user receives a badge/achievement a different modal is displayed for each one.

#### Highlight this badge?

Highlighted badges, are badges displayed in the top navbar. Scoreboard page only displays highlighted badges too.

#### Name

The name of the badge.

#### Description

The description of the badge.

#### Image

The image of the badge.

### Badges criterias

Once created, you need to configure criteria to deliver badge. All students who accomplish the criteria will receive the badge.

Currently, Evoke project have these criteria available:

- Course access;
- Evocoins;
- Skill points;
- Skill points aggregation.

#### Course access

Users will accomplish the criteria when they access the course for the amount of configured days.

#### Evocoins

Users will accomplish the criteria when they obtain the amount of configured Evocoins.

#### Skill points

When the teacher configures skill points on the course activities, then it is possible to deliver badges based on acquired skill points.

Eg: If you select skill **Tech** and set the value to **25**, all users who get **25** points or more of the skill **Tech** will receive the badge.

#### Skill points aggregation

The last criteria is the possibility to select more then one skill to deliver badge.

For this criteria, users accomplish the criteria when they obtain the sum of points of the selected skills.

Eg: If you select skills **Tech and Innovation** and set the value to **40**, all users who sum **40**  points of skills **Tech and Innovation** will receive the badge.

- User with 20 points of Tech and 20 points of Innovation receives badge.
- User with 40 points of Tech and 0 points of Innovation receives badge.
- User with 20 points of Tech and 19 points of Innovation, will not receive the badge.

#### Configuring badge criterias

It is very easy to add badge criteria, you just need to choose your criteria and configure what is the reference value to achieve that.

The most exciting Evoke feature is that is possible to combine the criterias, what is not possible with Moodle by default.

![Evoke badges settings](/img/local_evokegame/game8.png)

As you can see in the image above, to receive this badge users need to accomplish three criteria:

- **skillpoints:** get 35 points of skill vision;
- **courseaccess:** access the course for 20 days;
- **evocoins:** get 150 Evocoins.

### Deliver badges

Evoke badges works with Moodle events, this mean that when an event happen, Evoke analyse whether the user deserves the badge and then deliver it or not. Events are everything, activity completion, skill points and evocoins aquirement, course login. This is why badges are delivered instantly when the user finishes or do something.

Sometime it is necessary to deliver badges after the course started, with activities already completed by students and all of other actions.

This button deliver the badge for everybody who deserves it, who already accomplished the criteria.