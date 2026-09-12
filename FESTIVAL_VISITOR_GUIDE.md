# Festival Visitor Guide

## Student Information

- Name: Phyo T. Oo
- Course and section: CSC350H Software Development
- Date: 12 September 2026

## Repository Evidence

- Current branch: main
- Personal Homework 2 GitHub URL: https://github.com/PhyoThihaOo32/CSC350-HW2-PHYOTHIHAOO
- Starting `git status`: on branch main|nothing to commit, working tree clean
- Starting preparation commit ID: bd125dd

## Festival Identity

- Festival name: BMCC Myanmar Thingyan Water Festival
- Location: BMCC Main Building, New York City
- Intended audience: BMCC students, faculty, staff, and the entire BMCC community
- Theme: Celebrating the Myanmar New Year through Thingyan traditions, water festivities, music, food, and cultural activities.

## Prediction Before the First Commit

1. Where does the saved change currently live?
   The saved change currently lives in the local working directory on my computer.

2. Has it been staged or committed?
   No. It has not been staged or committed yet.

## Arrival Information

- Transit or parking: Take the subway or bus to BMCC’s Main Building at 199 Chambers Street; limited street parking is available nearby.
- Entrance or meeting location: Meet at the main entrance of the BMCC Main Building on Chambers Street.

## Accessibility Information

1. Wheelchair-accessible entrances and elevators are available throughout the BMCC Main Building.
2. Accessible restrooms and designated seating areas will be available for attendees who need them.

## Visitor Reminder

Please follow BMCC safety rules and festival instructions, especially during water activities, to keep the event safe and enjoyable for everyone.

## GitHub Verification

Verified on GitHub by Phyo T. Oo.

## Commit Evidence

| Checkpoint                 | Short commit ID | Required message                              |
| -------------------------- | --------------- | --------------------------------------------- |
| Personalized guide         | 1dab442         | `docs: personalize festival visitor guide`    |
| Visitor access information | 5375500         | `docs: add visitor access information`        |
| GitHub verification        | 0e83b9d         | `docs: verify independent homework on GitHub` |
| Final reflection           | c9c893d         | `docs: complete independent Git reflection`   |

## Individual Reflection

1. What is the difference between saving a file and committing it?

Saving a file updates the file in the working directory. Committing records the staged changes as a permanent snapshot in the local Git history.

2. What is the difference between `git diff` and `git diff --staged`?

git diff shows unstaged changes in the working directory. git diff --staged shows the changes that have already been staged and are ready to be committed.

3. Why did the GitHub verification sentence not appear locally before `git pull`?

Because the change was made directly on GitHub, so it existed only in the remote repository. git pull downloaded that new commit and updated the local repository.

4. What did `-u` accomplish in `git push -u origin main`?

-u set origin/main as the upstream branch for the local main branch. After that, Git can usually use just git push or git pull.

5. What evidence proves that the local and GitHub repositories are synchronized at the end?

The local main and origin/main point to the same newest commit ID, and git status shows that the branch is up to date and the working tree is clean.
