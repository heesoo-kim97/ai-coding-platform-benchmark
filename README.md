# ai-coding-platform-benchmark

4 major questions

Q1. Speed
Which platform builds the required application fastest?

Q2. Accuracy
Which platform produces the most functionally correct application?

Q3. Efficiency
Which platform requires the fewest prompts/iterations and lowest cost?

Q4. Reliability
Which platform introduces the fewest defects when modifying existing code?

Speed Vs Quality
Does faster generation actually lead to more defects?

Prompts vs Accuracy
Does additional iteration improve quality?

Cost vs Quality
Does spending more AI compute actually produce better results?

Complexity vs Performance
Does the performance gap between platforms widen as requirements become more complex?

Brainstorming:

Test replit, Lovable, Bolt, Claude

Screen Recording - record the experiement on OBS Studio. For later use to demonstrate the experiement

Important:
- Prompt: Have the script of the inital prompt that was provided to AI
- Screenshot: first generated application (result)
- Major error: If something fails, capture the error
- Correction prompt: Shows how you instructed the AI to fix it.
- Final application: shows the completed result
- Raw experiment log:

| Trial | Platform | Event          | Timestamp | Duration | Prompt # | Result  |
| ----- | -------- | -------------- | --------- | -------: | -------: | ------- |
| 01    | Bolt     | Initial prompt | 10:02:15  |        — |        1 | Started |
| 01    | Bolt     | First build    | 10:11:43  |     9:28 |        1 | Partial |
| 01    | Bolt     | Fix filter     | 10:15:20  |     3:37 |        2 | Passed  |
| 01    | Bolt     | Add KPI        | 10:18:44  |     3:24 |        3 | Passed  |

Speed Recording:

Start -> Submit standaridized prompt -> AI generates application -> Run tests -> Fix failures using stadardized prompts -> Run tests again -> 12/12 requirements pass -> stop

Time to Functional Completion = Stop Timestamp - Start Timestamp

T1 - Time to First Build
- How long until the platform produces its first usable application

T2 - Time to Functional Completion
- How long until all required functionality passes

T3 - Time to Final Version
- How long until the final standardized modification is complete and passes regression testing

Self-Q: How do we know the distinction between usable application vs functional completness?

