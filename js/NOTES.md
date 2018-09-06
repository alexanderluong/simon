Challenges and solutions:
1.) I initially was confused about what the objective even was for the Easy Task. 
  --> I took a more thorough look at the README.md in order to grasp the task. 
2.) I took a look at the Mozilla JavaScript docs to implement the delay for the noteboxes.
  source: https://developer.mozilla.org/en-US/docs/Web/API/WindowOrWorkerGlobalScope/setTimeout

Thoughts:
1.) For the easy task, since I want to disable the other noteboxes while one is playing, I'm thinking about using an array. For every notebox that's pressed, I'll add it to the end of the array. The array will be reading the first notebox. If there's no note currently playing, I'll play the note and shift the array.
2.) I wasn't sure what the units of NOTE_DURATION were in. After a quick google search, it's in milliseconds. I'm going to set a new variable for the timeout to 2500 for the requirements of the easy task.
3.) I didn't read the documentation carefully and was confused when the notes started to play by themselves. I was able to comment out the auto playing.
4.) I'll need to clear the queue after the notes are played and enable all the noteboxes again.
