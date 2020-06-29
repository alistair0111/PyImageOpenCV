# The 7 steps to build a bubble sheet scanner and grader

### To accomplish this, our implementation will need to satisfy the following 7 steps:<br><br>

Step #1: Detect the exam in an image.<br>
Step #2: Apply a perspective transform to extract the top-down, birds-eye-view of the exam.<br>
Step #3: Extract the set of bubbles (i.e., the possible answer choices) from the perspective transformed exam.<br>
Step #4: Sort the questions/bubbles into rows.<br>
Step #5: Determine the marked (i.e., “bubbled in”) answer for each row.<br>
Step #6: Lookup the correct answer in our answer key to determine if the user was correct in their choice.<br>
Step #7: Repeat for all questions in the exam.<br>