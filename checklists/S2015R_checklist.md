Checklist for S2015R milestone (GitHub issues labeled "Summer 2015 redeploy")

**Developer**
- [ ] Review outstanding issues, mark what will be addressed for redeploy (@ariel-phet and original developer). Then mark these issues with a milestone.
- [ ] Look over the code review checklist, decide if code review should be redone, https://github.com/phetsims/phet-info/blob/master/checklists/code_review_checklist.md
- [ ] Review and update licensing info (source code and images/audio)
  - [ ] Double check relevant entries in https://github.com/phetsims/sherpa/blob/master/third-party-licenses.md
- [ ] Standardize the string keys, since they will be difficult to change later
- [ ] Identify any strings in sims that should move to another repository, move them now
- [ ] Publish RC version and test matrix
- [ ] Address RC issues

**QA**
- [ ] stringTest=double
- [ ] stringTest=long
- [ ] stringTest=X (short strings)
- [ ] stringTest=rtl (right-to-left)
- [ ] showPointerAreas (touchArea=red, mouseArea=blue)
- [ ] Full screen test
- [ ] Perform RC testing

**Design/Admin**
- [ ] Rosetta test (Opening sim to trusted translators for beta)
- [ ] Check teacher tips are up to date
- [ ] Check sim primer is up to date
