> # **Andrew D. France**
> My SourceHut profile [here](https://sr.ht/~itsmeforlua/)
>---

---
##### Quick Access
> [AUR: autodock4](https://aur.archlinux.org/packages/autodock4) - Automated docking of flexible ligands to proteins(for arch linux)
  > - [Source Control](https://github.com/ItsMeForLua/aur-autodock4.git)
>
>  [AUR: autogrid4](https://aur.archlinux.org/packages/autogrid4) - Autogrid4 is a support software for docking programs such as AutoDock4 and Autodock-GPU
  > - [Source Control](https://github.com/ItsMeForLua/aur-autogrid4) 
> 
> [Lisp: cl-freelock](https://github.com/ItsMeForLua/cl-freelock) - lock free queue data structures library for common lisp
>
> [Lisp: cl-win32](https://github.com/ItsMeForLua/cl-win32) - Master/package repo for cl-win32-types and cl-win32-errors (WIP)
> 
> [Lean4: ln_messagepack](https://github.com/ItsMeForLua/ln_messagepack) - the lean4 messagepack serialization library (beta)
> 
> [PDB-library](https://github.com/ItsMeForLua/pdb-library) - personal PDB molecule library
---

### **Connect**

- **GitHub:** [ItsMeForLua](https://github.com/itsmeforlua)
- **Email:** andrewforlua@gmail.com
  - _n.b.,_ For my work email, you will need to email andrewforlua@gmail with your intention.

**(5/31/26 Note:** Recently I've been looking more into nix-shell, and it seems very promising. I will be incorporating it into github actions for my repos. Though, it's only compatable with linux, so windows runners are out of the questions in this case.

**(5/04/26) Note:** I'm no longer using Jenkins, because of the resource requirements, extra complexity, etc. It was a hard decision to make, but, github CI/CD is more lightweight, more straightforward, etc.

---

I am currently in college; majoring first in biochemistry(BS), plus a minor in applied mathematics, with the idea that I may then pursue a masters in applied mathematics. My career goals are that of bioinformatics, currently working on AWS certifications, currently in continued education cGMP training (panthera biosolutions). I have taken a 9.5 CEU credit biotechnology course, and am BACE certified (via the university of Florida). Additionally, I am looking into getting a flow cytometry certification once I can find one. I do have certifications of completions for flow cytometry courses from biorad, but those aren't certifications.

My main programming languages are lisp, lua, and recently I've been learning more C. I do know some R, and am trying to improve my ability to use biopackage libraries. I do know some python, though I tend to not enjoy using it, but I'll use it when needed. Most of my projects are simply my own projects, so, I naturally tend to use languages I actually enjoy writing in.

I have an interest in lean4 as well, though, it is hard to retain memory of how to do things in that language, because right now it is in the development phase, thus each update is borderline backwards-breaking.

I also do tutoring for general chemistry, biology, and recently have been deciding on possibly doing tutoring for the BACE exam.

I am in the process of transferring my github projects to sourcehut. My projects will remain on github, but I will be supporting and preferring sourcehut. My thought process behind this decision can be summarized [here](https://sfconservancy.org/GiveUpGitHub/).

---

### TODO
This section displays what I plan to do currently regarding my projects. Most of my projects have a TODO.md, but it's still necessary for me to split time between projects.
- [ ] cl-freelock needs its API-usage ~wiki-~ pages updated: I've already written multiple pages-worth for all 23 symbols; I'm just refining. **Edit 5/4/26:** I will actually be making the API-usage wiki pages as HTML in github pages.
- [ ] I will add a github actions yml to Rust2d.
- [ ] I need to hand over the perl libraries I currently manage on CPAN to other users since I no longer plan on using Perl. Inlinelua can go to the users who previously really wanted to own it.
- [ ] I will be adding vale as github CI/CD. Specifically for README's and documentation proof reading.

#### Still Working On
_Meaning I have not abandoned_
- [ ] Helping update the clasp install scripts for Roswell.
- [ ] Helping cl-messagepack with benchmarks.

#### TODO - Later
- [ ] I will use github actions to automatically create issue reports for `cl-win32-types` and `cl-win32-errors` when the upstream API has changes.
- [ ] I will fix the one non-critical warning from RCBOR's rust build-system for CRAN submission, as per CRAN's sys-admin recommendations.
  > This can wait since it's non-critical
