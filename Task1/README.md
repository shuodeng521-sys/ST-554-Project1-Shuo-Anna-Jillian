Each group member should provide feedback on the other group members’ work. Be detailed and specific where possible. The quality of this feedback can play a part in your grade.

You can provide feedback to your group members in many different ways (live in a meeting, offline, or however else you devise) but the feedback must be documented here! 

Please replace “Feedback giver #x” with a group member’s name below and add feedback as a bulleted list below. Note: There is a pencil icon on the top right of the README file (when you are viewing the README.md file) that allows you to edit.

- Feedback giver #1 Shuo Deng
  1. Add more markdown narrative (your notebook is code heavy)
     Example: Add a markdown narrative before the "gradient descent for b₀ and b₁."  
     Gradient Descent for b0 and b1
     We now optimize both parameters simultaneously. At each iteration, we compute approximate slopes with respect to b0 and b1 using difference quotients, then update both values until convergence.
     This extends the  gradient descent idea from a single parameter to a two‑dimensional surface.
  2.Improve Code Comments
    Example: Add comments inside the gradient descent update step for the constant c.
     Approximate slope of RMSE at the current value of c
    slope = diff_quotient_c(y, cur, delta)
    Gradient descent update: move opposite the slope to reduce RMSE
    new = cur - slope * step_size
  3.Add a Brief Interpretation After Each Result
    Example:Add a short interpretation after the printed result for the best constant c.  
  The optimal constant prediction is approximately 10.28, which is close to the sample mean.
  This matches the theoretical result that the RMSE‑minimizing constant is the mean of the response.
  4. Add a final summary section at the end of the notebook
  
- Feedback giver #2
  + item
