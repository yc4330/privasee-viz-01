# d3-privacy-policy-viz
 
## An overview and some takeaways

This project is a cute viz about the boring privacy policies of top 100 free apps in app store.

### Big Apps are watching you!
<<<<<<< HEAD

=======
>>>>>>> 69ffbd2dda1d7d073f08bca15c198617a4d8a9fb
index.html shows how GPT scores them using the rubric I provide.

Although they are already the best apps, GPT has been very strict in scoring them - among the 40 points full mark, a majority of the apps only get half of the scores.

Warning: the score is done by AI, without fack checking.

### AI and Third-Party in privacy policies
<<<<<<< HEAD

=======
>>>>>>> 69ffbd2dda1d7d073f08bca15c198617a4d8a9fb
index2.html shows where AI-related keywords or "third-party" appears in the privacy policies. 

Apps gather user data to train their models and the trend is rising - yet many privacy policies doesn't even mention it. 

Third-party information usage needs to get user consent - they don't have an special section. The word is scattered everywhere.

## Data Gathering and Cleaning

Privacy policies are scraped from apple app store, where they have a fixed position to store the privacy policy links for each app. 

Then the text is cleaned and split into sentences - not done very carefully. Some sentences are still sticked together.

GPT-4o model is applied to each cleaned text using OpenAI API (which cost about $5). You can find the detailed rubrics and the prompt in GPT.ipynb.

<<<<<<< HEAD
## Challenges I encountered

### How to create smiley faces and make them blink randomly

### How to draw a density wave graph and use gradient color to fill it

### How to 
=======
## challenges I encountered

>>>>>>> 69ffbd2dda1d7d073f08bca15c198617a4d8a9fb

