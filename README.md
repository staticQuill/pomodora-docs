# Pomodora, a timer and wellbeing app for Jira

## What is Pomodora

Pomodora is an app for Atlassian's Jira that enhances the wellbeing of your team with a friendly Pomodoro timer interface, as well as work time leaderboards!

Pomodora was made for Atlassian's Codegeist 2022.

Pomodora has two forms:
- On the Jira Issue Panel, it's a timer that tells you when it's time to work and when it's time to take a break.
- On the dashboards section of Jira, you can add the Pomodora Dash gadget to any of your existing dashboards to see information about your current Pomodoros, adjust your settings, and view your team's collective progress.

## What is the Pomodoro Technique?

The Pomodoro technique is a method for establishing a work time and break time routine that was developed by Francesco Cirillo in the 1980s.

You can find more information on the Pomodoro Technique on [Wikipedia](https://en.wikipedia.org/wiki/Pomodoro_Technique).

## Installing Pomodora?

Pomodora must currently be installed via an install link from the developer, Jennifer Black.
Once Pomodora is available on the Atlassian marketplace, you'll be able to install it from there.

## Using Pomodora

### Setting up

- To use Pomodora, you'll need the Pomodora Dash dashboard gadget. You can add it to an existing dashboard in Jira, or create a new dashboard
and add it as a gadget.

- Once you have the dashboard gadget added, click on the "set your pomodora settings" button to adjust how long you want your timers to be.
  - Adjust the sliders left and right to decrease and increase the time for each pomodoro stage.
  - Be sure to click submit under the slider you've adjusted after each adjustment to save your choice and refresh the estimations at the top of the window
  - Click "Save your settings" to save your changes to the timers.

> If you only click Submit, and do not click "Save your settings", your timer lengths will not be changed

> If you ever want to return to the default timer lengths, click "restore defaults"

### Timing your work and breaks

- Navigate to the Jira issue you wish to work on. 
- Ensure that the issue is assigned to you so that the time is logged under your name.
- Open the Pomodora panel by clicking the Pomodora Icon (a litle orange dog), which should be under the issue title
- Press "Start work "timer" or "Start break timer", depending on which stage is next for you.
- You should hear a notification sound as your timer starts
- Your timer will run down. When it reaches 0 seconds, you will hear another notification sound as long as you have not navigated away from the page
- At this point, you can start your next timer

> If you navigate away from the timer page, your notifications will not sound until you press your next "Start work/break timer" button.

> You can mute notifications in general through the Pomodora Dash dashboard gadget

### Checking your team's statistics and leaderboard

- navigate to the dashboard where you've added Pomodora Dash.
- At the top of the dasboard, your team's cumulative working time will be displayed
  - This cumulative total only reflects the past two weeks.
  - A feature to adjust this timeframe may be added
- Click on the "View your team's leaderboard!" button to see how much time your teammates have logged
  - The table will be sorted in descending order of total time worked per teammate.
  - An ability to sort by other fields may be added in the future

## What's next for Pomodora?

Pomodora is in active development. New features will be added as they are developed. Potential new features include:

- More insights and leaderboards from the Pomodora Dash
- Improved graphics for the timer and timing animations
- Support for adjusting how far back Dora collects logged time (currently set to two weeks)
- More leaderboard sort functionality

Bug reports are always welcomed. Please raise an issue on the public Pomodora Docs github repository if you encounter a bug. [You can find the issue board here.](https://github.com/staticQuill/pomodora-docs/issues)
