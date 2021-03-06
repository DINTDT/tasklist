# TaskList

**STATUS: Seems to be working as intended on Chrome (Desktop and Mobile). Hasn't been tested on other browsers**

A simple task list made in HTML. All of the code is embedded into the HTML, so all that is need is the single file and can work offline.

The base HTML contains a *Save* link and an initial Task.

Click the task's name to rename it.

The [x] button (or pressing Ctrl+Space) will remove the task. If it has subtasks, you will be asked to confirm. The initial task cannot be removed (unless you try really hard).

The [+] button (or pressing Space) will create a new task under the current one, and will prompt you to give it a name. You can ignore this and name it later.

The [▲] button (or pressing Right) will hide all the subtasks of the current one. When the subtasks are hidden, the button will change to [▼], and pressing it (or pressing Left) will instead show all it's subtasks. A task with no subtasks will have its Collapse/Expand button disabled.

Additionally, there are other keyboard shortcuts. The "*current*" task will be highlighted in blue, and you can change the *current* with the Up and Down arrows. Press [H] to see all available shortcuts.

The *Save* link on the top will prompt you with a filename. The current HTML page will be downloaded and saved with the given name. **Note:** Everytime you save a task list, the HTML file will be downloaded again, so it might get sent to your Downloads folder every time.
