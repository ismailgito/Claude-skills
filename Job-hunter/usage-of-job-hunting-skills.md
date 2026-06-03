Let's strip away all the complexity. Here's the absolute simplest way to use this repo, treating it like a recipe book where you do the clicking/filing, and Claude does the thinking/writing.

We'll focus on just three core actions that cover 90% of the value.

🎯 The Big Picture (Don't Overthink This)
You and Claude have a simple deal:

You: Find jobs online. Copy and paste text. Save files Claude gives you.

Claude: Understands you deeply, then tailors your resume and writes your cover letter for each job.

That's it. Let's go.

Step 1: Tell Claude Who You Are (Do This Once)
Goal: Give Claude a complete picture of your career so it can write authentically for you.

What you need:

Your current resume file (PDF or Word is fine)

10 minutes

What to do:

Start a fresh chat with Claude. Name it "My Career Profile".

Copy and paste this exact prompt:

text
I need you to become my personal job application assistant. First, I'll upload my resume. Read it carefully.

Then, interview me one job at a time. For every role on my resume, ask me:
- What was your proudest specific achievement in this role? (with numbers if possible)
- What was the hardest problem you solved?
- What tools or skills did you use daily?

After we've gone through all roles, ask me:
- What 2-3 job titles are you targeting?
- Any dealbreakers? (location, salary, company type)

Finally, save all this into a detailed profile we will use for every application.
Upload your resume file right after pasting that prompt.

Answer Claude's questions. Be honest and detailed. This is the fuel for everything later.

When finished, ask Claude: "Please output the final complete profile as a single document I can copy."

Save that output to a file on your computer named my-career-profile.txt. Keep it somewhere easy to find.

✅ Done with setup forever.

Step 2: Tailor Your Resume for a Job (Repeat Per Application)
Goal: Turn your generic resume into one that looks custom-written for a specific job posting.

Time per application: 5 minutes

What to do:

Find a job you like on LinkedIn, Indeed, or any job board.

Copy the entire job description text.

Start a brand new chat (don't reuse the profile chat — Claude works better with a clean slate each time).

Copy and paste this exact prompt:

text
You are an expert resume writer.

Here is my detailed career profile:
[PASTE YOUR ENTIRE my-career-profile.txt HERE]

Here is the job I want to apply for:
[PASTE THE FULL JOB DESCRIPTION HERE]

Now, tailor my resume for this specific job. Rules:
- Rewrite my summary to be 2-3 sentences that directly match THIS job's needs.
- Rewrite every job bullet point to use keywords and language from the job description.
- Don't make anything up. If I'm missing a skill, suggest an adjacent one.
- Output the complete tailored resume.
Claude will give you a tailored resume. Review it quickly. If you want changes, just say "Make the summary shorter" or "Focus more on leadership."

Save the final version to a new folder for this application.

✅ Tailored resume done.

Step 3: Get a Cover Letter (Optional but Recommended)
Goal: Generate a cover letter that connects YOUR achievements to THEIR needs.

What to do (in the SAME chat as Step 2):

Paste this prompt:

text
Now write a cover letter for this job.

Rules:
- 250-350 words maximum.
- Sound natural, like a human wrote it.
- Connect 2-3 of my specific achievements directly to the company's needs mentioned in the job description.
- Start with "Dear Hiring Manager," and end with "Regards, [Your Name]."
Save the cover letter in the same application folder.

✅ Cover letter done.

📂 Simple Folder Setup
Create this structure once on your computer. It keeps everything clean:

text
Job-Applications/
├── my-career-profile.txt      (from Step 1)
│
├── Company-Role-1/
│   ├── job-posting.txt        (paste the job desc here to remember it)
│   ├── tailored-resume.md     (from Step 2)
│   └── cover-letter.md        (from Step 3)
│
├── Company-Role-2/
│   ├── job-posting.txt
│   ├── tailored-resume.md
│   └── cover-letter.md
│
...and so on
🔁 Your New Job Search Routine
Every time you find a job you like:

#	Action	Takes
1	Copy job description	10 sec
2	Open NEW Claude chat	5 sec
3	Paste the prompt from Step 2 (with your profile and the job desc)	30 sec
4	Review tailored resume, ask for tweaks if needed	2 min
5	Paste the prompt from Step 3 for cover letter	10 sec
6	Review cover letter, tweak if needed	1 min
7	Save both files to a new application folder	20 sec
Total per application: under 5 minutes, with a high-quality custom resume and cover letter.