---
sidebar_position: 2
---

# Configuration

On this page, you will learn how to create skills and Evocoins fields to enable their distribution in the courses' activities.

### Activity custom fields

Before you get started using the Game on the platform, you first need to set up skills and Evocoins.

To configure it, go to: `Site administration > General > Evoke > Evoke Game - Activity custom fields`.

![Game custom module fields](/img/local_evokegame/game1.png)

Custom module fields are extra fields displayed for all activities. It will be visible when you add or edit a course activity.

As you can see in the image above, it is possible to group the fields by categories.

**Short name convention:** you need to follow a name convention on every Game custom module field. You can see this convention in the image above, but we will highlight it in every skill and Evocoin explanation.

### Skills fields

It is possible to deliver skill points after some user's action.

**1. Submission skill points**:

**Short name convention:** **submission_**yourskillname`

This is available only for Portfolios and Evokations.

The user receives the configured skill points after submitting evidence on the portfolio.

**2. Likes skill points**:

**Short name convention:** ***like***_yourskillname

This is available only for Portfolios and Evokations.

The user receives the configured skill points after a mentor likes the user's evidence on the portfolio.

**2. Grading skill points**:

**Short name convention:** ***grading***_yourskillname

This is available only for Portfolios and Evokations.

The user receives the configured skill points after a mentor evaluate the user's evidence on the portfolio.

**NOTE:** When the activity uses rubric to grade students, and the rubric has only 4 values, 1, 2, 3 and 4. The skill points will be multiplyed following the rules below:

1. multiply skill points by 0.5
2. multiply skill points by 0.75
3. multiply skill points by 1
4. multiply skill points by 1.5

### Evocoins

**Short name convention:** ***evocoins*** . For Evocoins, you only need to use **evocoins** as short name.

Evocoins are delivered when the user completes an activity, in other words, when the activity is marked as complete. You need to configure activity completion rules if you want to deliver Evocoins.

As Evocoins works with activity completion, you can deliver Evocoins for any activity marked as complete. Page, H5P, Portfolio, Quiz, or any other Moodle activity can deliver Evocoins after being marked as complete.

