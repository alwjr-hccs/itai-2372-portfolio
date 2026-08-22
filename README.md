# itai-2372-portfolio
I T A I 2 3 7 2 - A R T I F I C I A L I N T E L L I G E N C E A P P L I C A T I O N S
Applied AI Studio - Run It in Your Browser
Nothing to install. Nothing to set up on your own computer.
Fall 2026 - Houston Community College - Prof. Yuexin Mao
The app lives here
https://github.com/maoyuexin/applied-ai-studio
Open that link, then follow the steps below. You get your own private copy that only you can see, so you
cannot break anything for anyone else.
Part 1 - Before you start
Required - a free GitHub account
1. Create one at github.com if you do not have one already. You need it for this course anyway, because your
portfolio lives there.
That is the only thing you must have. You can start using the app straight away.
Optional - the GitHub Student Developer Pack
The Student Pack is free for students and is the only way to get GitHub Copilot at no cost. Apply at
education.github.com/pack with your HCC email. Approval usually takes a few days.
It is optional, and you should not wait for it. Without Copilot the app still works - only the Ask Studio chat page is
unavailable, and the AI Fit Analyzer hands you a ready-made outline instead of writing one about your own
problem. Apply in week 1 and carry on in the meantime.
Part 2 - Open the app
You do not need to fork or copy anything. Go straight to my repository and open a codespace from it - GitHub
lets you do that on any public repository, and it builds you a private copy that only you can see. You will never be
asked to push anything back.
1. Go to github.com/maoyuexin/applied-ai-studio and sign in.
2. Click the green Code button near the top right.
3. Choose the Codespaces tab, then Create codespace on main.
4. Wait. The first time takes a few minutes. The terminal finishes by saying "Applied AI Studio is ready."
5. In the terminal at the bottom, type npm run dev and press Enter.
6. A box appears saying the app is running on port 5173. Click Open in Browser.
If you miss that box: click the Ports tab next to the terminal, find 5173, and click the small globe icon. The web
address is private to you.
ITAI 2372 - Applied AI Studio Quickstart Page 2 of 3
Checkpoint - did you see "Applied AI Studio is ready."?
That line at step 4 is how you know setup finished. If it never appeared, the next step fails with "bash: npm:
command not found".
Reconnecting never repairs it. Delete the codespace, create a new one, and you lose nothing.
Part 3 - Using the app without Copilot
In your first week the Student Pack is usually still being approved, so Copilot is not connected. That is expected.
Page Without Copilot
Industry Workflows Works fully. Six complete business workflows to explore.
Online Order demo Works fully. Place an order and step it through.
AI Fit Analyzer Works. See the box below for exactly what happens.
Ask Studio The only page that needs Copilot. It will say so plainly.
No Copilot yet? This is what the AI Fit Analyzer does
Fill in the boxes and press Generate five-stage workflow. Instead of an error you get a blue-green note
reading "Starter outline - written without AI", followed by a complete five-stage outline with five decisions
already marked.
Edit any part of it, choose a decision, and score it exactly as you otherwise would. Nothing is missing from the
exercise. When Copilot is switched on later, the same button writes an outline from your own problem
description instead.
Ask Studio and Copilot - nothing to set up
There is nothing to install and nothing to sign in to. The Copilot software is installed for you during setup, and
your codespace already knows who you are.
The only thing that decides whether Ask Studio works is whether your GitHub account has Copilot. If it does, the
page works straight away. If it does not, the page says so, and everything else keeps working. When your Student
Pack is approved it simply starts working - there is no step to come back and do.
Your codespace signs in as you, not as your instructor. You are always using your own GitHub account.
Part 4 - When you are finished
Codespaces stop on their own once you close the tab, so normally you do nothing. To tidy up,
github.com/codespaces lets you stop or delete them - deleting one loses nothing.
ITAI 2372 - Applied AI Studio Quickstart Page 3 of 3
Part 5 - If something goes wrong
What you see What to do
"bash: npm: command not
found"
Setup did not finish, so the tools were never installed. Reconnecting will not fix it.
Delete the codespace and create a new one.
The page is blank, or says it
cannot connect
Check that npm run dev is still running in the terminal. Start it again if it is not.
"Starter outline - written
without AI"
Nothing is wrong. Copilot is simply not connected yet. Carry on - the outline can be
edited and scored.
"You appear to be offline",
or the codespace will not
connect
This is usually GitHub itself, not you. Check githubstatus.com first. If anything there
is red or orange, wait - there is nothing for you to fix.
Anything else, or you have
no idea what happened
Delete the codespace and create a new one. This is a normal move, not a failure.
