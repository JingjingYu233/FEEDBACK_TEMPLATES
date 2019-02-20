# Team Feedback on lab02.md for ____TEAM NAME GOES HERE____

## Rubric for y/n/? items

Mentors will use a y/n/? rubric to provided feedback on some items.  Here is the interpretation

| item | interpretation |
|------|-----------------|
| y | definitely yes: any reasonable person would agree that the submitted work meets the criteria |
| n | definitely no: no reasonable person would see even a partial credit worthy attempt at meeting the criteria |
| ? | somewhere in-between. In this case, mentor should make notes, and TA should pay particularly attention to the item when grading |


## Team Graded items


| Item                                                       | Response | 
|------------------------------------------------------------|----------|
|  Each team member contributed to a Hello World app (y/n/?) |          |
|  There is a user story in the in progess column  (y/n/?)   |          |
|  There is at least one issue under each user story         |          |
|  Each team member is a assigned to at least one issue      |          |


Mentor: If n or ?, explain.  Note which team members didn't contribute to a Hello World app.

# TA Team Grading


| Item                                                       | Grade    | 
|------------------------------------------------------------|----------|
|  Each team member contributed to a Hello World app (y/n/?) |    /30   |
|  There is a user story in the in progess column  (y/n/?)   |    /20   |
|  There is at least one issue under each user story         |    /20   |
|  Each team member is a assigned to at least one issue      |    /30   |


# Hello World app in a branch, and a pull request is performed

<div class="grade" markdown="1">

**Graded**: (lab02-I) (20 pts) You earn these points if/when you:
* Have a branch and a pull request for your hello world app (the one that you did as an individual or as part of a pair) by the due date of this assignment (i.e. {{page.due |  date: "%a, %b %d at %l:%M%p"}})

</div>



# Hello World app in a branch, and a pull request is performed

<div class="grade" markdown="1">

**Graded**: (lab02-I) (20 pts) You earn these points if/when you, by the due date of this assignment (i.e. {{page.due |  date: "%a, %b %d at %l:%M%p"}}):

* are assigned to an issue that has been moved from To-Do to In-Progress to Done on the Kanban board, tracking the progress of your issue from start to finish.

Note that each time an issue is moved or assigned, the date/time is tracked; so for full credit, this should be done "in real time" as you work on the issue, not "after the fact".   We'll assess this to encourage you to get in the habit of doing it in real time as you work; doing it that way has benefit to the team.   When you do it in real time, the Kanban board reflects the state of the project, and gives the team a way to visualize the status of what's going on.

But doing it "after the fact" is better than not doing it at all; if nothing else, it helps you learn the mechanics to that you can know better how to do it next time.  So if you forget to do it as you work, go back and do it, going through the motions.  This will earn you partial credit, which is better than getting a zero for this part.

</div>

# Hello World app Deployed or Demoed

As explained below, each 

<div class="grade" markdown="1">

**Graded**: (lab02-I) (20 pts) You earn these points if/when by the due date for this lab,  (i.e. {{page.due |  date: "%a, %b %d at %l:%M%p"}}) you have, as explained below, either:

* deployed your app live on the public web (if it is a webapp) through Heroku, or another provider, or
* demoed your app to your mentor during open lab hours, or another mentor if that doesn't work for your schedule.

</div>

## *Each* webapp "Hello, World" branch/pull-request should be deployed

If your app is being deployed as a webapp: you should have have DEPLOYED it so that it runs on a service such as Heroku, 
Google App Engine, Amazon Web Services, etc. at a stable URL.    The easist platform on which to do this
for Java Spring Boot, and Python Flask is Heroku.   If you don't know how, ask on the slack channel (well in advance, not at the last minute), 
and mentors and other students can point you to the resources to get started with this.

Put the URL of your running app in the README in your branch.

## *Each* non-webapp "Hello, World" branch/pull-request should be demoed

If you are NOT doing a webapp, you must set up a time with your mentor, or your TA, to demo your app to them.  You are strongly encouraged to do 
this BEFORE the lab next Thursday.   The mentors and TAs hold 
[open lab hours]({{'/info/open_lab_hours/' | relative_url }}) during which you can schedule this demo.    The last opportunity to do this demo
is during lab on the due date for this assignment, but it may not be possible to fit all of those in, and in that case, regrettably, you may lose the opportunity to do so (and earn the points.)  Please coordinate with your team to
get as many of these demos done *before* lab on the due date of this assignment.

If working in a pair, *each* member of the pair should demo the app, to show that they understand how to run it.

NOTE: If you cannot schedule with your own mentor, you may coordinate on slack between your mentor and another mentor/TA holding open lab hours that better fit your schedule.  Please use the slack to coordinate this.  

# Launching the project

**As a team**, in addition to completing your Hello World apps (as described in more detail below), you should also 
   * settle on a first user story or set of user stories for your minimum viable product.  
   * have created issues to support that story or stories
   * have populated the Kanban board with those
   * have dragged the user stories and issues your team is are working on (immediately after your hello world issues) into the
      In-Progress column of the Kanban board.
   * Have assigned at least one issue to each team member (as an individual or as part of a pair or group), and have dragged those issues into the in-progress column.

<div class="grade" markdown="1">


**Graded (lab02-T)**: (lab02-T) is your Team grade for {{page.num}}.  As part of this grade:

* (20 pts) There should be at least one user story in the In-Progress column for your team.  If there is more than one, it is because the user stories for the first one are insufficient to keep the team making progress, and it was necessary to bring over a second one to have enough issues to work on.
* (20 pts) There should be at least one issue under each user story that supports implementing that user story.
* (30 pts) Each user on the team should be assigned to at least one issue in the in-progress column.   
   For teams of 6, this part of your grade is 5 points per team member.  For teams of 5, it is 6 points per team member.  

This component of your team grade is designed to encourage each team member to reach out to all the other members of the team, and be aware of the progress they are making towards the goal of having every team member be making a contribution to the project.  The most important learning goal of the course is to learn to work as a team, supporting one another.

</div>  

# About assigning issue to team members

It is possible to assign multiple users to an issue.

You may work on issues either:
* as an individual
* as a pair
* as a "mob" (like pair programming, but with more than one person)

However, if you are working as a pair or a mob, you should *really* be
working as a pair or a mob.  That is, you should plan times to get
together, ideally in person, but at least via screen sharing, and work
together on the code.

What we don't encourage is for Alice and Bob to be assigned to the
issue, and then Alice and Bob take turns "solo programming" on the
issue.  That's a way of working but not the one we are encouraging you
to try.

# About limiting work in progress

Throughout the rest of the course, up until we wrap things up with the final project delivery, you are encouraged to:
* ensure that each team member, at all times, is assigned to at least one in-progress issue
* limit the number of in-progress issues.  

Being assigned to more than one in-progress issue is occasionally unavoidable, but typically not ideal.    An example of a case where you may be tempted to do it is when you are blocked on an issue (e.g. waiting for someone else to finish something you need).  In that case, you might decide to start another issue so that you are assigned to two in-progress issues at a tine.  

But the experience of most teams is that it's best to try not to do this too often.  

Context switching among issues has a cost, and having lots of work in progress can slow a team down further and complicate the delivery of working software that adds value for the user.
Coming soon...

