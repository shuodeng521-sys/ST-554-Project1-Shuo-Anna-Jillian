Each group member should provide feedback on the other group members’ work. Be detailed and specific where possible. The quality of this feedback can play a part in your grade.

You can provide feedback to your group members in many different ways (live in a meeting, offline, or however else you devise) but the feedback must be documented here! 

Please replace “Feedback giver #x” with a group member’s name below and add feedback as a bulleted list below. Note: There is a pencil icon on the top right of the README file (when you are viewing the README.md file) that allows you to edit.

- Feedback giver #1: Jillian
  + You need to add an introduction and markdown narrative of your thought process through the code, as per the project rubric. Feel free to grab the intro from my code, as we're allowed to share this!
  + I recommend adding additional annotation to code block #4 where you replace -200 with NAs and remove to explain those steps
  + Additional annotation should be added to the SLR and MLR MSE loops to explain each line
  + The MSE in the loops should be average MSE, not sum. This clarification was made on the Slack channel, a totally understandable interpretation of the original rubric!
  + I suggest making a table to compare the SLR to MLR MSE results
  + Though it's not required, it might be interesting to see a scatterplot of the final model's true vs predicted C6H6 data, even though this would just be training data
  + Overall, your code includes all of the required steps and functions. Great job!


- Feedback giver #Anna Giczewska
  + Overall, this is a clear, well-structured analysis with thoughtful visualizations and interpretation.
  + Explain the choice of start_day=250. This is an important modeling decision. Adding one sentence on why that cutoff was selected.
  + Brief note explaining why daily aggregation was chosen (and that results could differ at the hourly scale) would strengthen the justification for your modeling setup.
  + Since the scatter suggests errors widen at higher benzene values, a simple residual check (residuals vs fitted, or residual histogram) could give an extra information where the model performs best. 
