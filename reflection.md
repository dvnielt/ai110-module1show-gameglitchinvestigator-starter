# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
- List at least two concrete bugs you noticed at the start  
  (for example: "the hints were backwards").

--- the hard difficulty is broken, the new game button doesnt start, secrets were the answer iteslf, score function is broken, submite guess button doesnt properly store guesses, hints are broken, new game button is broken (doesnt clear guesses list as well), 

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).

-For this project i just used claude code and cursor native ai (autocomplete)
-One thing claude suggested was changing the hard coded values "1 to 100" to use the 'low' and 'high' variables instead so the numbers change based on which difficulty is selected.
-One thing claude did reccommend changing was to remove the 'except: TypeError' code on lines 41-47.

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
- Did AI help you design or understand any tests? How?

-I decided a bug was actually fixed when i verified the results by running the app and using the test cases
-One test i ran manually was the difficulty settings, it showed that my code worked when i saw i implemented it correctly
-AI helped me design and understand all of the tests for each individual bug i listed (and that it found)

## 4. What did you learn about Streamlit and state?

- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?

--- Reruns keep the UI always in sync by re-executing your code, and session state is where you remember what happened before, so your app can feel continuous instead of resetting every time.

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
- What is one thing you would do differently next time you work with AI on a coding task?
- In one or two sentences, describe how this project changed the way you think about AI generated code.

-A strategy from this project that i want to reuse in the future is most definitely bug tracking and creating specific test cases for each bug that was fixed
-One thing i would do differently is most likely ask the AI to create a sperate file of all changes and then manually edit my main files instead of having it make edits to my original files.
-This project didnt really change the way i think or thought about AI generated code, but it showed me new ways on how to debug that i will be using in the future.
