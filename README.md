Pastebin
API
tools
faq
paste
Search...

Login Sign up
SHARE
TWEET
Rajatapaus
 Week 2 instructions
Rajatapaus
Sep 14th, 2026 (edited)
29
0
Never
Add comment
Not a member of Pastebin yet? Sign Up, it unlocks many cool features!
 4.23 KB | None |  
     
Goal: Practice branching, working together on a shared repository, and resolving a merge conflict.
 
Prerequisites
- Have Git installed
- Have a GitHub account
- Set up authentication
 
Repository visibility: keep the repository Public. This makes it easier for the teacher to review your work during grading.
 
Step 1 — Form a group of 2-4 people
 
Step 2 — Create your own repository and initial index.html
 
Each of you:
- Create a new public GitHub repository
- Clone it to your computer using VS Code
- Add an index.html file with the following content, choosing any fictional character you like:
  - <title> the character's name
  - <h1> the character's name
  - <img> a placeholder image with src="https://placehold.co/300x200" and a suitable alt text
  - <ul> an empty list
- Commit and push your initial version
 
- You can use example code template bottom
 
Step 3 — Invite your collaborators
 
In your own repository on GitHub: Settings -> Collaborators. Add your partner(s). They accept the invitation and clone your repository to their computer.
 
Step 4 — Build the character page together using branches
 
Choose one repository your group will work on together. You can start working simultaneously.
 
Owner of the chosen repository:
- Create a feature branch (e.g. add-image)
- Replace the placeholder image with a real image of your character (use any online image URL)
- Update the alt text
- Commit and push your branch
- Merge the branch into main locally, and push main
 
Collaborator(s):
- Create your own feature branch, add at least one strength to every other fictional character
- Add at least one item to the <ul> list, an attribute, a strength or a weakness of the character
- Commit and push your branch
- Merge it into main locally, and push main
 
Discuss on any problems encountered during the process. 
 
Step 5 — Create a merge conflict on purpose
 
Working on the same repository as Step 4:
- All partners create new feature branches from main
- All partners modify the same line, the <title> element, in a different way
- All commit and push the changes
- Try merge your branch into main, and push main
- When conflict encountered, take a screenshots of the process, talk with your partner(s) how to resolve the situation, which version to keep or combine them, how to resolve the conflict and complete the merge.
 
Step 6 — Discuss with your partner(s)
 
Before submitting, take a few minutes to talk together:
- Did you use git status, and did it help you understand what was going on?
- What was different between step 4 and step 5?
 
Submission (one submission per group)
 
One member of your group submits the PDF on Moodle on behalf of the whole group. 
- Include the names of all group members on the first page of the PDF
- Name the file with everyone's names
 
The PDF should include:
1. Link to the repository your group worked on together
2. Screenshot of git log --oneline --graph --all from that repository, showing the merge commits and branch history
3. Screenshot of the resolved merge conflict
 
Assessment: Pass / Fail
 
Your submission passes if it includes all three items above and demonstrates a genuine attempt at all steps.
 
Bonus (optional — if you have extra time)
 
Bonus 1: Repeat Steps 4-5 in another group member's repository. Rotate roles.
 
Bonus 2: Pull request workflow. Instead of merging directly, create a new feature branch, open a pull request on GitHub, have your partner review and comment, then merge.
 
Bonuses are optional — pass/fail is based on completing the core exercise.
 
 
 
 
<!DOCTYPE html>
 
<head>
  <title>Our favourite characters</title>
</head>
<body>
  <h1>Shrek</h1>
  <img src="https://upload.wikimedia.org/wikipedia/en/4/4d/Shrek_%28character%29.png?utm_source=en.wikipedia.org&utm_campaign=parser&utm_content=thumbnail_unscaled">
  <ul>
    <li>Unbeatable in swampland</li>
    <li>Can live with optimal diet of onions</li>
  </ul>
</body>
</html>
 
 
<body>
  <h1>Donkey</h1>
  <img src="https://upload.wikimedia.org/wikipedia/en/6/6c/Donkey_%28Shrek%29.png?utm_source=en.wikipedia.org&utm_campaign=imageinfo&utm_content=thumbnail_unscaled">
  <ul>
    <li>Good with dragons</li>
    <li>Loyal to Shrek</li>
  </ul>
</body>
</html>
Add Comment
Please, Sign In to add comment
Public Pastes
I made $15,000 * 2 hours
CSS | 16 min ago | 0.99 KB
✅ API Glitch (Docs Leak)
CSS | 18 min ago | 0.99 KB
arasaka
C | 9 hours ago | 3.14 KB
new
C | 11 hours ago | 3.06 KB
old
C | 12 hours ago | 3.06 KB
ExcercisesIntroduction2ProgrammingPart-Time
C# | 1 day ago | 4.79 KB
notes
1 day ago | 0.06 KB
tkounter.py
PowerShell | 1 day ago | 0.57 KB
create new paste  /  syntax languages  /  archive  /  faq  /  tools  /  night mode  /  api  /  scraping api  /  news  /  pro
privacy statement  /  cookies policy  /  terms of service /  security disclosure  /  dmca  /  report abuse  /  contact

By using Pastebin.com you agree to our cookies policy to enhance your experience.
Site design & logo © 2026 Pastebin
We use cookies for various purposes including analytics. By continuing to use Pastebin, you agree to our use of cookies as described in the Cookies Policy.  OK, I Understand
Not a member of Pastebin yet?
Sign Up, it unlocks many cool features! 
