---
title: Visual Studio Code
tab: vscode
---
### Overview

GitLive focuses on improving developer visibility with what we’re dubbing enhanced presence, to help developers work more effectively as a team.

<table>
<thead>
<tr>
   <th>Presence</th>
   <th>Questions Answered</th>
  </tr>
</thead>
 <tbody>
  <tr>
   <td>Traditional</td>
   <td>
    Who is online?<br />
    Who is online but not currently active (away)?
   </td>
  </tr>
  <tr>
   <td>Enhanced<br />
    (with GitLive)
   </td>
   <td>
    Who is online or away?<br />
    Which repositories are they working on?<br />
    What branch are they currently on?<br />
    What files have they changed in their working copy?
   </td>
  </tr>
 </tbody>
</table>

### Who's Online?

The GitLive window in your IDE lists the teammates of a given organization. Being online is denoted by a little green dot.

![See who else is online](/uploads/visibility-online-vscode.png "Online Visibility"){:class="screenshot"}

### Which repositories are they working on?

GitLive displays all of your teammates’ working copies for the repositories that you share write access to. If your teammate is not active in a working copy, the last known state of the file will be visible, including uncommitted changes.

In the screenshot below **Ismael Juma** shares access with you to the repository called **spark**. He is currently working on the **spark** repository as denoted by the green dot next to the repository name.

![See which repos your teammates are on](/uploads/visibility-repo-vscode.png "Which Repo"){:class="screenshot"}

### What branch are they currently on?

As useful as it is to know a fellow developer is online, a common question teammates ask each other is ***what branch are you on?***
With the enhanced presence you can see the branch your teammate is currently working on. As can be seen in the screenshot below, **Ismael Juma** is currently checked out on the **fresh-checkout-2** branch within the **spark** repository.


![See which branch your teammates are on](/uploads/visibility-branch-vscode.png "Which Branch"){:class="screenshot"}

The green dot next to the file name indicates that your teammate is active in that particular file. Below **Ismael Juma** is currently active in file **log-view.js**.

![See which file your teammates are on](/uploads/visibility-file-vscode.png "Which File"){:class="screenshot"}

### Which issue are they currently working on?

Once an issue tracker has been connected, GitLive's [issue tracking](/docs/issuetracking/){:class="internal-link"} feature can be used. This allows you to share the current issue you are working on, providing your teammates with more context than the repository / branch level.

![View Issues Others are Working on](/uploads/vscode-issue-tracker-visibility.png "View Issues Others are Working on"){:class="screenshot"}

### What did your teammates change locally compared to their latest push?

Furthermore, you can drill down into an individual teammate’s working copy local changes for quick and easy problem-solving. This allows you to seamlessly understand what your teammate is referring to instead of going through a cumbersome commit-push-fetch cycle. The GitLive window shows you your teammate’s working copy changes relative to his latest pushed remote state, visualised by the number of lines added and deleted (denoted by the + and - symbols). As can be seen below, **Ismael Juma** has edited the file **log-view.js** locally. The "+" symbols next to the file implies that he has added ten lines of code in this files locally compared to his latest pushed remote state.

![See the changes in their working copy](/uploads/visibility-working-copy-vscode.png "Working Copy Changes"){:class="screenshot"}

### Live Difference View

You can also use GitLive to see which lines have been changed by your teammate. All you have to do is click on a filename, and a diff view visualising your teammates local changes compared to his latest pushed remote state opens up.

![See the changes in their working copy](/uploads/vscode-diff-view.png "Diff View"){:class="screenshot"}


[Suggest an Edit to this Page](https://github.com/GitLiveApp/GitLive/edit/master/_sections/visibility-vscode.md){:class="uk-button uk-button-success"}

