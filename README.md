# **Andrew D. France**

---
##### Quick Access
> [AUR: autodock4](https://aur.archlinux.org/packages/autodock4) - Automated docking of flexible ligands to proteins(for arch linux)
  > - [Source Control](https://github.com/ItsMeForLua/aur-autodock4.git)
> 
> [Lisp: cl-freelock](https://github.com/ItsMeForLua/cl-freelock) - lock free queue data structures library for common lisp
> 
> [Lean4: ln_messagepack](https://github.com/ItsMeForLua/ln_messagepack) - the lean4 messagepack serialization library (beta)
> 
> [PDB-library](https://github.com/ItsMeForLua/pdb-library) - personal PDB molecule library
---

### **Connect**

- **GitHub:** [ItsMeForLua](https://github.com/itsmeforlua)
- **Email:** andrewforlua@gmail.com

**(5/14/26) Update:**
This semester is over for me, so over the summer, I will be working on my projects.
Also, I will be updating a couple of the licenses in a couple of my repos, because I learned that if a repo was mostly made with AI, then it can't really be licensed. I also want to favor academic honesty, so for the couple of repos that are mostly AI made, I will add a disclaimer. This does not effect the licenses of my main repos like cl-freelock, fplot, etc, as those are indeed mostly written by me, which you can probably tell by the code being weird-- a symptom of the fact that I have not been programming for decades; rather, less than a decade. This only affects smaller repos like magickPDF and the lisppad-scheme graphing module.
I also think transparency is important when it comes to AI use, as AI-generated code should be reviewed with more scrutiny in certain contexts to be absolutely sure the code is up to standard.
WIP repos such as ["Graphing Continuous Geometry in Racket"](https://github.com/ItsMeForLua/Graphing-Continuous-Geometry-In-Racket-Guide) are pretty much 0% AI in terms of what is written, as I do not value AI generated prose at all, and I actually think it tends to be horrid.
  - Also, I want to clarify something regarding my commit history. My projects were all commited maybe just a couple months apart. But this isn't really a reflection of how long it took me to make them, rather, I had made these projects on my own time quite a ways before even publishnig them on github. Then eventually I realized I probably should publish on github, especially for my portfolio, so that's why the summer of 2025 produced so many large projects from me. They weren't neccesarily produced in that time frame, though, I did program morning to morning everyday all summer, so that helped in some cases.


**(5/04/26) Note:** I'm no longer using Jenkins, because of the resource requirements, extra complexity, etc. It was a hard decision to make, but, github CI/CD is more lightweight, more straightforward, etc.

**(03/27/26) Note:** I'm depricating my use of perl, despite previously listing it as one of my known languages. Perl just generally goes against my code philosophies, and its testing enviroments are very impractical. I love perl, because I think it's cool, but, since the code that made if fast for parsing and regex is open source, and made in C, many other programming languages have adopted that code, and can be just as fast(if not faster).

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
