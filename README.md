# TaskList

**STATUS: Seems to be working correctly on Chrome. Hasn't been tested on other browsers**

A simple task list made in HTML. All of the code is embedded into the HTML, so that it can work offline.

The base HTML contains a *Save* link and a sample Task.

Click the task's name to rename it.

The [+] button will create a new task under the current one, and will prompt you to give it a name. You can ignore this and name it later.

The [▲] button will hide all the subtasks of the current one. When the subtasks are hidden, the button will change to [▼], and pressing it will instead show all it's subtasks.

The [x] button will remove the task. If it has subtasks, you will be asked to confirm. The initial task cannot be removed (unless you try really hard).

The *Save* link on the top will prompt you with a filename. The current HTML page will be downloaded and saved with the given name. **Note:** Everytime you save a task list, the HTML file will be downloaded again, so it might get sent to your Downloads folder every time.
