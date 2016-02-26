# Metro

Welcome to Metro, an SS13 remake inspired by the book and videogame Metro 2033.

Our goal is to redefine the standard exhibited by nearly all SS13 servers. Rules will be nonexistent, and administrators will have little to no influence on the game world. There will be no wiki - all knowledge of how the game works will have to be assembled by players themselves. The atmosphere will be bleak, the game unforgiving, with death around every corner.

### Short Roadmap

###### Stage 1

- [ ] Round Handling
- [ ] Design Finalizations
- [ ] Game Mechanics Refactors
- [ ] Lore Creation

###### Stage 2

- [ ] Feature Additions
- [ ] Map Creation

###### Stage 3

- [ ] Junk Code Removal
- [ ] Aesthetic Overhaul
- [ ] Final Bug Fixes

### Guide to Committing

This is **extremely** important. Failure to adhere to these guidelines will cause your pull requests to be **rejected**.

1. Create a branch from your master, and title it whatever feature that you intend to work on. For example: If you plan on refactoring weapons, entitle the branch weapon-refactors (or something). Be specific.
2. Pull your new branch down onto your desktop. Switch to that branch on your desktop.
3. Practice **atomic commits**. This is the practice of committing small segments of code at a time, often with relevance to one another. For example, if you decide to refactor ten weapons in your weapon-refactors branch, commit your changes after every weapon. That way, if the 10th weapon has faulty code, we don't have to pick and choose between taking or leaving all of it. We can simply remove that one commit.
4. Once you are done, push your changes to your remote branch.
5. Open a pull request to the master branch (not your fork's master) explaining what you changed.
6. If your pull request is accepted, open another pull request with your fork's master as the base, and merge the new changes onto your master.
