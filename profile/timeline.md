# Timeline of Ximera Activity
# Week -9: 10/23/2023 - 10/27/2023
- Grant awarded		
## Week -8: 10/30/2023 - 11/3/2023
- Programmers need to be hired
- Online deployment is most critical. Potential authors want
to see their work deployed online.
- We need a application for stipends. This could be done in a  survey.
  - Name
  - Email
  - Institution
  - Brief description of planned work
- We also need a follow up, where the grantee gives
  - Name
  - Email
  - Institution
  - Brief description of work done
  - Link to artifact of work
  - https://docs.google.com/forms/d/e/1FAIpQLSfKXtp9vRoGfh_TI0FNKB9uwFtcQmKl57nwEGoUz-QCsb3SIQ/viewform?usp=sf_link
- Met with Andrew Maier to discuss accessibility.
  - OSU is requiring a degree of accessibility for all PhD Thesis.
  - https://github.com/AndyClifton/accessibility
  - https://libguides.lib.msu.edu/c.php?g=995742&p=8207771
  - The situation for PDF accessibility seems dire. The smart
	people on stack exchange do not have a good solution. 		
- Making github site: https://github.com/XimeraProject more reasonable.
- Applied for a Minicourse at MathFest, see Week 32.
- Xourse files, do we compile course files?
- Maybe these could be compiled in the repo, as they are just lists of activities.
- Evaluators need to be hired.
- When do announcements need to go out for the 
  - Stipends?
  - Evaluators?
  - Programmer?
- Need to add courses to https://github.com/XimeraProject
- Need to add "Releases" to PDF only ximera courses
- Add math and music as PDF only
- Got the Project Profile document (Due 12/31/2023 - Week 0)
- According to https://www.ams.org/journals/notices/202301/rnoti-p68.pdf tex4ht is still good.
## Week -7: 11/6/2023 - 11/10/2023
- Working on making github site: https://github.com/XimeraProject more
reasonable by ensuring that PDF's are created for releases. Make
"releases" for various ximera courses. Include READMEs
- See https://github.com/mooculus/mathForArchitects
- Emailed times to meet program director.
- Fowler and Snapp discussed, accessibility / tex4ht 
The issue is that \answer is fundamentally incompatible with tex4ht
- Met with DoeNet group -- 
- Grade book course markdown mock-up (this has been superseded by example here:  https://buckeyemailosu-my.sharepoint.com/:w:/g/personal/snapp_14_osu_edu/EUFQc25zoRlEs3WDey51rOIBij3GwZ0Sunoa3e0w4HRzdg?e=ZP3bhP     )

```
- DOENET Course 
- An arbitrary course name
#* End Date
- 12/31/2026
#* Description
- Blah for Math is a course that is team taught at Happy and Sad View High Schools. 
#* Instructor
- Jane Doe
- John Mak
#* Instructor Emails
- doe@school.edu
- mak@other-school.edu
#* Institution 
- Happy View High School
- Sad View High School
- Assignments
- [Prelecture](https://ximera.osu.edu/mooculus/calculus1/understandingFunctions/breakGround)
- [Graphing Assignment 1](https://www.desmos.com/calculator)
- [HW 2](https://www.geogebra.org)
- [EC](https://www.youtube.com/playlist?list=YOUR_PLAYLIST_ID)
- [HW 5](https://www.geogebra.org/classic)
```
- The End Date would give us a time when we could email the instructor letting them know that we plan to delete/archive the course data. However, we might retain record of the course for evaluation purposes. The Description, Instructor, and Institution(s) are, I think essentially irrelevant, EXCEPT for the fact that when we email students, and create courses pages (which could just be the markdown above!) we will be assuring the student that they are in the right place to do their homework.
- There needs to be an option for "who can see this?" my students/all students
- Do assignments need release dates? Can they be added at a later
  date? Maybe so... If they can simply be added to DoeNet.md file
  after it's been submitted, that might work!
- **Issues*## We need a way of describing EXACTLY which assignments are
  part of a "column" in a gradebook. The path of the URL could be used
  to do this (any assignment with the same starting path is part of
  the column) BUT we also need ways of grouping assignments into a
  single column.
##* A potential instructor (say a HS teacher) 
- Makes an account
- Uploads a (possibly pre-made) DOENET.md file
- Gets an email with a code (option to resend required)
- sends code to students (with list of student emails)
##* Students
- login with email and code.
	- Click on buttons, goto links get grades. 
##* Instructors retrieve grades
- login to gradebook
- Select course (name/desc/inst are given by md file)
- make database query (we can have predefined ones)
  E.G. Graphing Assignment 1, up to 10/30/24 13:34pm EST
- Retrieve a spreadsheet
- Return grade data to students through traditional methods.
## Week -6: 11/13/2023 - 11/17/2023
- Discussions about DOENET LEAP GDB
- Finding the denominators for the grades seems tricky
- If we get this working we could make a fun video like:  https://youtu.be/4p8vqoIVESc
  explaining that "ANY WEBSITE CAN BE AN ASSIGNMENT! Any Website? ANY WEBSITE!"
- **Fowler and Snapp meet Program Director** 9am 11/15
  - All budget changes need to be recorded
  - No real restrictions on hiring
- **Orientation** 1:30-2:30 11/16
- Set up meeting with our authorized representative
- Discussed gradebook at length.
  - A Redis solution may be viable.
  - Fowler drafted: https://docs.google.com/document/d/119Zo9SGgovmvdhwNtvOfuffweNBqxa8Bhe85TvwEtG4/
- Thinking about evaluators.
  - https://ncstrategic.com/index.html is a possibility
  - Our counterparts at a non-ximera institution might be a good idea
  - An interested teacher at a high school
  - A committee might be good.
## Week -5: 11/20/2023 - 11/24/2023
- Meet with our authorized representative to discuss
  - Stipends
  - Evaluators
  - Programmers
- Informed that all hiring will go through our HR and Fiscal Associate.
- Developed AI-hardend PDF. Issue made on GitHub: https://github.com/XimeraProject/ximeraLatex/issues/100
- Inquried about make-up/responsibilites of Evaluators. 
## Week -4: 11/27/2023 - 12/1/2023
- **Project Profile Document NOT Due** but let's try to have it done anyway.
- A meeting is set up with Henry Griffy
  - See https://www.a11y-collective.com/blog/how-accessible-are-online-stores/
  - See https://www.accessibilitychecker.org/blog/examples-of-ada-compliant-websites/
- We are considering potential evaluators
- AI Hardening has run into issues: It didn't seem to stop students, nor is it invisible on browser PDF readers (but it is invisible in evince and MuPDF).
  - https://github.com/XimeraProject/AI-Harden
## Week -3: 12/4/2023 - 12/8/2023
- Contacted potential HS teacher evaluator. 
  - May need to re-think budget.
- Need to: Contact AB concerning evaluation and graduated stipends. 
- Thu 12/7/2023 10:00 AM - 10:30 AM Meet with Henry Griffy
  - See https://www.a11y-collective.com/blog/how-accessible-are-online-stores/
  - See https://www.accessibilitychecker.org/blog/examples-of-ada-compliant-websites/
  - Perhaps we need a new repo within the XimeraProject with examples
    of accessible HTML?
  - Talk to Kenneth Berglung
  - Buttons on every page for changing formats. 
	- At top from screen-reader pov. (Could it stay? and Move to bottom?)
	- Describe current format and allow for changing at top.
  - Gradebook assignmnet interface needs to be accessible
  - Andrew Heckler (Grade database help)
  - History like YouTube of viewed Ximera pages? Can we scan the browser history and then show a history?  
- Thu 12/7/2023 Post-Award Risk Assessment Technical Assistance Webinar
- a11y repo created.
  - https://github.com/XimeraProject/a11y
## Week -2: 12/11/2023 - 12/15/2023
- Workshop (in lieu of a minicourse) MathFest application Due.
  - Probably too late, and MAA might not like us applying for two
    conflicting events.
	- Met again with Henry Griffy, Jason Nowell, Eva Dale, Elizabeth Marsch, and others about accessibility
- Rejected for MathFest MiniCourse
- Submitted Draft of Project Profile
- Emailed AB
## Week -1: 12/18/2023 - 12/22/2023
- Nowell, Fowler, and Snapp met to discuss accessibility
- Proposed activity / stipend amount document drafted
  - Perhaps can be broken into "creating" and "enhancing"
## Week 0: 12/25/2023 - 12/29/2023
- Octo-Lion Swag logo drafted
- **Project Profile Document Due** (Draft submitted Week -2. Final submitted 12/29)
## Week 1: 1/1/2024 - 1/5/2024
- Funding period begins
- Octo-Lion Swag logo done
- Stipend for AB DONE
- Send out stipend application to consortium members. DONE
 - https://go.osu.edu/ximera-flash-grant
- Hire programmer (Not done)
- Hire evaluator (Not done)
  - 1 candidate found
  - met with candidate
  - Description of activies is being written. 
- JMM 	
## Week 2: 1/8/2024 - 1/12/2024
- Evaluator selection and evalator job description
  - Broken down by quarter for the first year
  - 3 Canidates selected and contacted
  - Met with two in meeting
- Orca works with TeX in the Browser if we use '\ttfamily'
- Meet and discussed TeX in Browser
- Meet and discussed brining to market competitveness
- TeX in the browser is \Huge
- Confirmed quarterly report dates
- Created promotional-art repo
## Week 3: 1/15/2024 - 1/19/2024
- Drafted Evaluator duties https://buckeyemailosu-my.sharepoint.com/:w:/g/personal/snapp_14_osu_edu/EX06Y6feKsFGvIXNFOutn3kBlsOiQqCliVs0kbye-tKqSg?e=glGLe9
- Deployed Courses/contacted stipeds
- Helped students (will be on going)
- Needed: Data on devices/OS that use Ximera
- Initiated monthly meetings with https://www.when2meet.com/?23194278-7XiNI
- Found appoved vendor for promotional items
- Purchased Monitors (x3)/Webcam
## Week 4: 1/22/2024 - 1/26/2024
- Checked in with potential evaluators (3) 
- set up "office hour" for Tues Jan 30th (4pm-5pm)
- Met with potential programmer
- Got lead for an additional programmer
- Met to discuss TeX in the browser
- Purchased stickers (Critical Math, Mission Patch)
## Week 5: 1/29/2024 - 2/2/2024
- Met with potential programmer
- Gradebook? Who can see this? All students? My Studnets?
- EG of gradebook: https://github.com/Doenet/service
- First "office hour" Tues Jan 30th (4pm-5pm)
- 2 Potential programmers (Plan to Meet Fri 11am EST 2/9)
- DVI2tty could help with accessibility
- Reviewed Flash-grant applications 
  - (4/6 accepted without qualification) 
  - One clarified
  - One postponed until a gradebook database can be deployed
## Week 6: 2/5/2024 - 2/9/2024
- Set up payment for flash grant
- Set up next office hour https://www.when2meet.com/?23604050-iAZMf
- 2 Potential programmers (Meet Fri 11am EST 2/9)
- Drafted programmer duties https://buckeyemailosu-my.sharepoint.com/:w:/g/personal/snapp_14_osu_edu/EUFQc25zoRlEs3WDey51rOIBij3GwZ0Sunoa3e0w4HRzdg?e=ZP3bhP
- Sent programmers supplier form
- Exhibitor Booth for MathFest Reserved, conf number P2NKC4J8JN6 MathFest 8/7--8/10 in Indianapolis.
- Set up spreadsheet for stipends.
## Week 7: 2/12/2024 - 2/16/2024
- Promotional stickers arrived
- Meet with flash grant recipient, established workflow
- Drafting "scope of work" programmers
- Proof of concept of "Ximera digital puppet" https://github.com/XimeraProject/promotional-art/tree/master/octolion
- Established "pain-points" of PDF publishing 
  - TOC (sections within \sectionstyle, \chapterstyle)
## Week 8: 2/19/2024 - 2/23/2024
- Looking for device use data: Check back
- Contacted by user at Yale, who is patching xake.
  - Docker as fallback
- Worked with flash grant recipient
- Mailed stickers to programmers
- Working with JN on TOC issues
- Emailed Evaluators
- Sent stickers Program Director
- Attended OTP office hours
- Should plan to email AB an update prior to the 1st QR
- Met with additional potential evaluator.
## Week 9: 2/26/2024 - 3/1/2024
- Meet with programmers
- Ximera office hour
- Designed DOENet LEAP Mission Patch
- Confirmed all evaluators 
- Working with HR to Pay evaluators
- Meet with programmers
- Connections to Donet ML
- Plans with DoeNet developers
- User Needs document created https://buckeyemailosu-my.sharepoint.com/:w:/g/personal/snapp_14_osu_edu/EUEg5mxF40RLtFYFgXFxlhQBH2bTYKt4RzHRN2QKSJZOHA?e=JE3grK
- Mockup of MD for course created https://github.com/XimeraProject/.github/blob/main/profile/coursePrototype.md
## Week 10: 3/4/2024 - 3/8/2024
- awarded flash grants 
- Meeting with DOENet ML
- send stickers to flash grant awards
- send stickers evaluators
- Grade DB with when2meet interface discussed
- https://www.numbas.org.uk/
- https://set.kuleuven.be/voorkennis/zc-en/prep/rekenen/breuken
- Working on getting evaluators paid
## Week 11: 3/11/2024 - 3/15/2024
- Meet KU Leuven 
- Talk to potential evaluator
- Met with Fowler
- Drafting Evaluator Scope of work
## Week 12: 3/18/2024 - 3/22/2024
- Worked with HR to hire programmers
- Worked with HR to hire evaluators
- Met with researcher in Online Courseware
- Met with Yale, KU Leuven, U. Florida, concerning docker and ximeraLatex
- Inital planning for XV1 (Ximera Virtural Workshop) Docker, and XimeraLaTeX to CTAN
- XV1 and XV2 documents drafted
- la-carte linear algebra minicourses conceived
## Week 13: 3/25/2024 - 3/29/2024
- Working with HR to get programmers hired 
- Working with HR to get first evaluator hired
- Drafted XV1 plan in https://github.com/XimeraProject/workshops
- Planning Linear Algebra a la carte
- All key participants of XV1 and XV2 are on board
## Week 14: 4/1/2024 - 4/5/2024
- Working with HR to get programmers hired 
- Working with HR to get first evaluator hired 
- Learned of MathFest Event
- Programmers hung up. More bids needed
- Ximera off hours
- la-carte
- set times for XV1
## Week 15: 4/8/2024 - 4/12/2024
- Met with scalac.io (twice, marking and engineers)
- Try to help PZ deploy (SSH issues)
- Try to help CM deploy
- Discussed various short courses
- Applied for talk at MathFest
- Set up meetings with new schools
## Week 16: 4/15/2024 - 4/19/2024
- JF, DG, BS, discussed short courses. 
- Met with scalac, got proposal, limited scope of work.
- Met with Dennison for potential collaboration
- Set up meeting with infomics
- Reached out to Paul
- Meet with collaborator on short LA
- Attempting to hire OSU evaluator
## Week 17: 4/22/2024 - 4/26/2024
- Meet with infomics
- Working to hire evaluator!
- https://www.when2meet.com/?24763363-vyRhd
- Scheduled Monthly meeting
- Contacted AB
- PM has detailed comments
- Send info to both scalac and infomics
- Wrote more detailed hiring info for data specialist
## Week 18: 4/29/2024 - 5/3/2024
- **First quartely report due 4/30**
- Email P. Zachlin about Flash Grant Stipend
- Email A. Davis about Flash Grant Stipend
- Ximera Monthly Meeting
- One step further to programmers
- recieved Scalac proposal to meet
- Met AB
- XV1 Begins
- Meet with Authors/Developers 
- PM Suggest when2meet model to difficult for average teacher.
  - Further suggest -- direct LTI integration with off the shelf solution for small cases
## Week 19: 5/6/2024 - 5/10/2024
- XV1
  - Combined document classes from UF, OSU, KU Leuven
  - Added features to Ximera documentclass
  - submitted the document class to CTAN
## Week 20: 5/13/2024 - 5/17/2024
- AD gave us this: 
  Englebrecht, J., & Harding, A. (2005). Teaching undergraduate mathematics on the internet. Part 1: Technologies and taxonomy. Educational Studies in Mathematics, 58, p. 235-252.
- Fixed critical bug in cls
- Created Makefile for CTAN deploy
- Met with University of Cincinnati
- Met with Embry-Riddle Aeronautical University
- Critical bug in OSU tikz deploy found
  - we belive it is in the CLS -- however, patching ximera.cls did not solve the problem
  - we belive upgrading the OSU server to Ubuntu 18.04.6 LTS (Bionic Beaver) will solve the issue
- la-carte linear algebra course is official at OSU
## Week 21: 5/20/2024 - 5/24/2024
- Working on la-carte linear algebra 
- Met with WO for talk at TUG 2024
- Still working on programmers
- WO suggestion that when "answered" that we replace with what the author types.
## Week 22: 5/27/2024 - 5/31/2024
- Working on la-carte linear algebra
- Ximera Evaluators paperwork known
- Travel to TUG 2024
## Week 23: 6/3/2024 - 6/7/2024
- Email C. Merriman about Flash Grant Stipend
 - https://github.com/clairemerriman/Number-Theory-Notes/blob/withPDFs/MAT255Sp24/CourseSpring24.pdf
## Week 24: 6/10/2024 - 6/14/2024
- Met with Doenet about LEAP gradebook
- Met with AD and PZ primariy 
  - To show https://ximera.osu.edu/linearalgebrav3
  - Discussed editorial review. AD and Snapp have started
    https://github.com/XimeraProject/editorialReview
    with the goal of making an objective review rubric
  - Need for bringing to market level competitiveness: 
    - GitLab Docker stuff
    - Easy print styles
    - see: https://sites.google.com/view/lin-alg-interactive-intro/home
- installed docker
- Project Hydra: instructions for deploying in Docker  
- Met Fowler
- Met JN
- Programmers
- Met HR concerning evaluators
## Week 25: 6/17/2024 - 6/21/2024
- Met with AB
  - Need more presence in HS
  - Need more presence in OH
  - In the Surface/deep/transfer trichotomy, Ximera excells at Surface
- Programmers at buyer
- Doenet, embed in Ximera
  - same tech could be used with pretext
- Evaluators, meet with HR CJ/EM
- Working on Docker deploy at OSU
- https://www.doenet.org/library  (see display)
- Docker setup IMPORTANT: Because deploy server is running out of memory.  
- Clone examples repo from GitHub. 
  - Edit file from web browser and compiling them 
  - (GitLab combined with Visual Studio)
  - Test different verisons of Xake
- gpg keys are current hang up.
- Next steps: ./build.sh serve
  - check precalc/calc/annaDavis
## Week 26: 6/24/2024 - 6/28/2024
- Immediate work: Test docker on la-carte, Anna Davis, precalc
  - Once this works, we need to set up for multiple deploy
- We can work on Xake -- and server
- Goal of moving to gitlab
## Week 27: 7/1/2024 - 7/5/2024
- Deployment is working sans sage support
- Docker depolyment of local server is being tested
- Flash grants were awarded. 
- Email B. Ramsey about Flash Grant Stipend
- Ximera Monthly Meeting 7/3 2pm
- Contract awarded for Gradebook
## Week 28: 7/8/2024 - 7/12/2024
- Met with Doenet
- Met with WO, AD, PZ, for docker deploy. 
  - Successifully deployed la-carte from my machine, AD deployed from their machine
    - This is huge, becuase it is proof of concept that we can move away from our single deploy server.
  - BUG in Ximera LaTeX: Image hides images! (NONISSUE)
  - Quarterly waterfall diagram produced
  - Met with Infonomics
    - Instructor Story 1
      - One off
    - Instructor Story 2
      - Multiple 
    - Instructor Story 3
      - Canvas
    - Instructor Story 4
      - k-12 Personal Identify Id is an issue
- See if TB would be interested in helping online
- Modulus should be able to be used as a clicker
- Grade-my-math: 
  - User types in a math question and an answer
  - Output a grade.
- Met with Evaluators
- Met with authors and fixed author problems
- Met with TB concerning Ximera and github pages
- Met with CM concerning examples. Removed testing grounds.
## Week 29: 7/15/2024 - 7/19/2024
- Met WO
- Talk at TUG 2024
- made repo ximeraDemo
- Met CB and ZK evaluators
- Modulus should be able to be used as a clicker
- Grade-my-math: 
  - User types in a math question and an answer
  - Output a grade.
- Met with authors and fixed author problems
- Met with TB concerning Ximera and github pages
- Met with CM concerning examples. Removed testing grounds.
- Met with JA, JN, JF, about Doenet collaboration
- Drafted quarterly report
- Now thinking: 
  - Ximera Server should be decentralized
    - Essentially, it will only display Ximera, and report to the:
  - Ximera gradebook should be more centralized, some open, some closed, some sharing data in aggregate
  - Deploy should be via docker
## Week 30: 7/22/2024 - 7/26/2024
- Introduced to JK of https://tailorswiftbot.godaddysites.com/our-services
- Met with KA
  - KEEP Track of How many people are at MathFest/TALK Etc
- Drafted MathFest booth slides
- Purchased MathFest Booth equip
- Drafted MathFest XimeraInfoSheet
- Met Tailor Swift Bot
- JA: List of activites
- Met: WO
  - Need a "firstSteps" repo
  - write a VS code extension / settings.json
    - Have buttons for regular users to use. DONE
- Quarterly report submitted.
- NEED TO Email all schools (DONE)
- Working on TechBrief
## Week 31: 7/29/2024 - 8/2/2024
- **Second quartely report due 7/30**
  - Done
- Ximera Office Hr.
- multiple meetings with WO -- we think we have a deploy process
- modulusWrapUrl( ... ) which takes a URL and wraps it in the current course contxt so if a learner leaves a modulus activity, the stay within the moduluis universe
- Start with youtube
- Many Ximera deploy meetings
- Figured out how to make new gpg keys
- purchased projector/stands/screen/power-strip
- purchased case -- DELAYED
## Week 32: 8/5/2024 - 8/9/2024
- Started hand2ximera
- MathFest, 8/7/2024-8/24/2024, booth reserved, conf number P2NKC4J8JN6
- 200 Handouts given away
  - AD Presentation 50 
  - SD Presentation 40
  - 16 emails
- At mathfest
- Met Programmers -- time stamps are part of student completion data.
  - progress a single number or a monotonic "time-series"  (we want it to be a time-series)
  - Page state is also recorded, but one could have an empty page, and perfect score. (just most recent)

## Week 33: 8/12/2024 - 8/16/2024
- Solved abstract issue (JN) -- needs to be commited to git
- Help KS deploy
- Made Big-Math 5000 Data vis
- Help BR deploy
- Promised to Exhibit at mathFest 25
- Emailed LaTeX-Project and TeX4ht developers
- Meeting Austin Acc.
- CM documentation. 
## Week 34: 8/19/2024 - 8/23/2024
- Meet MH about TeX4ht
- Helped people deploy
- Ordered T-shirts
- Connected to accessible PDF developers
- Worked on Ximera User Manual
## Week 35: 8/26/2024 - 8/30/2024
- Meet with AI
- Worked with authors
- Set up Monthly meeting
- Ximera Server button added to VS code
## Week 36: 9/2/2024 - 9/6/2024
- Monthly meeting
- Met Tailor Swift Bot, 
- WO, JF, TSB, BS, met with MH for TeX4ht/Make4ht support
- mooculus/calculus compiles
- Met with programmers
- AI math compiles
- Met with evaluators to construct surveys
- Email A. Davis about Flash Grant Stipend
- Email P. Fatheddin about Flash Grant Stipend
- Email J. Sheldon about Flash Grant Stipend
- Flash grant stipends awarded.
## Week 37: 9/9/2024 - 9/13/2024
- GPG Key issue -- keys expired -- solved by end of week.
- Meet David S.
- Various tex4ht improvements
- PF talked to Course coordinators
- t-shirts arrived -- but error in order.
## Week 38: 9/16/2024 - 9/20/2024
## Week 39: 9/23/2024 - 9/27/2024
## Week 40: 9/30/2024 - 10/4/2024
- Email C. Merriman about Flash Grant Stipend
## Week 41: 10/7/2024 - 10/11/2024
- Project Director Conf in October (not necessarily at this date)
## Week 42: 10/14/2024 - 10/18/2024
## Week 43: 10/21/2024 - 10/25/2024
## Week 44: 10/28/2024 - 11/1/2024
## Week 45: 11/4/2024 - 11/8/2024
## Week 46: 11/11/2024 - 11/15/2024
## Week 47: 11/18/2024 - 11/22/2024
## Week 48: 11/25/2024 - 11/29/2024
## Week 49: 12/2/2024 - 12/6/2024
- Jason Nowell New validators
## Week 50: 12/9/2024 - 12/13/2024
## Week 51: 12/16/2024 - 12/20/2024
- Email A. Incognito about Flash Grant Stipend
## Week 52: 12/23/2024 - 12/27/2024
## Week 53: 12/30/2024 - 1/3/2025
- Email W. Obbels about Flash Grant Stipend
## Week 54: 1/6/2025 - 1/10/2025
- JMM 1/8--1/11
## Week 55: 1/13/2025 - 1/17/2025
## Week 56: 1/20/2025 - 1/24/2025
## Week 57: 1/27/2025 - 1/31/2025
## Week 58: 2/3/2025 - 2/7/2025
## Week 59: 2/10/2025 - 2/14/2025
## Week 60: 2/17/2025 - 2/21/2025
## Week 61: 2/24/2025 - 2/28/2025
## Week 62: 3/3/2025 - 3/7/2025
## Week 63: 3/10/2025 - 3/14/2025
## Week 64: 3/17/2025 - 3/21/2025
## Week 65: 3/24/2025 - 3/28/2025
## Week 66: 3/31/2025 - 4/4/2025
## Week 67: 4/7/2025 - 4/11/2025
## Week 68: 4/14/2025 - 4/18/2025
## Week 69: 4/21/2025 - 4/25/2025
## Week 70: 4/28/2025 - 5/2/2025
## Week 71: 5/5/2025 - 5/9/2025
## Week 72: 5/12/2025 - 5/16/2025
## Week 73: 5/19/2025 - 5/23/2025
## Week 74: 5/26/2025 - 5/30/2025
## Week 75: 6/2/2025 - 6/6/2025
## Week 76: 6/9/2025 - 6/13/2025
## Week 77: 6/16/2025 - 6/20/2025
## Week 78: 6/23/2025 - 6/27/2025
## Week 79: 6/30/2025 - 7/4/2025
## Week 80: 7/7/2025 - 7/11/2025
## Week 81: 7/14/2025 - 7/18/2025
## Week 82: 7/21/2025 - 7/25/2025
## Week 83: 7/28/2025 - 8/1/2025
## Week 84: 8/4/2025 - 8/8/2025
- MathFest 2025 6-9.
## Week 85: 8/11/2025 - 8/15/2025
## Week 86: 8/18/2025 - 8/22/2025
## Week 87: 8/25/2025 - 8/29/2025
## Week 88: 9/1/2025 - 9/5/2025
## Week 89: 9/8/2025 - 9/12/2025
## Week 90: 9/15/2025 - 9/19/2025
## Week 91: 9/22/2025 - 9/26/2025
## Week 92: 9/29/2025 - 10/3/2025
## Week 93: 10/6/2025 - 10/10/2025
## Week 94: 10/13/2025 - 10/17/2025
## Week 95: 10/20/2025 - 10/24/2025
## Week 96: 10/27/2025 - 10/31/2025
## Week 97: 11/3/2025 - 11/7/2025
## Week 98: 11/10/2025 - 11/14/2025
## Week 99: 11/17/2025 - 11/21/2025
## Week 100: 11/24/2025 - 11/28/2025
## Week 101: 12/1/2025 - 12/5/2025
## Week 102: 12/8/2025 - 12/12/2025
## Week 103: 12/15/2025 - 12/19/2025
## Week 104: 12/22/2025 - 12/26/2025
## Week 105: 12/29/2025 - 1/2/2026
## Week 106: 1/5/2026 - 1/9/2026
## Week 107: 1/12/2026 - 1/16/2026
## Week 108: 1/19/2026 - 1/23/2026
## Week 109: 1/26/2026 - 1/30/2026
## Week 110: 2/2/2026 - 2/6/2026
## Week 111: 2/9/2026 - 2/13/2026
## Week 112: 2/16/2026 - 2/20/2026
## Week 113: 2/23/2026 - 2/27/2026
## Week 114: 3/2/2026 - 3/6/2026
## Week 115: 3/9/2026 - 3/13/2026
## Week 116: 3/16/2026 - 3/20/2026
## Week 117: 3/23/2026 - 3/27/2026
## Week 118: 3/30/2026 - 4/3/2026
## Week 119: 4/6/2026 - 4/10/2026
## Week 120: 4/13/2026 - 4/17/2026
## Week 121: 4/20/2026 - 4/24/2026
## Week 122: 4/27/2026 - 5/1/2026
## Week 123: 5/4/2026 - 5/8/2026
## Week 124: 5/11/2026 - 5/15/2026
## Week 125: 5/18/2026 - 5/22/2026
## Week 126: 5/25/2026 - 5/29/2026
## Week 127: 6/1/2026 - 6/5/2026
## Week 128: 6/8/2026 - 6/12/2026
## Week 129: 6/15/2026 - 6/19/2026
## Week 130: 6/22/2026 - 6/26/2026
## Week 131: 6/29/2026 - 7/3/2026
## Week 132: 7/6/2026 - 7/10/2026
## Week 133: 7/13/2026 - 7/17/2026
## Week 134: 7/20/2026 - 7/24/2026
## Week 135: 7/27/2026 - 7/31/2026
## Week 136: 8/3/2026 - 8/7/2026
## Week 137: 8/10/2026 - 8/14/2026
## Week 138: 8/17/2026 - 8/21/2026
## Week 139: 8/24/2026 - 8/28/2026
## Week 140: 8/31/2026 - 9/4/2026
## Week 141: 9/7/2026 - 9/11/2026
- Plan no-cost extension (if applicable)
## Week 142: 9/14/2026 - 9/18/2026
## Week 143: 9/21/2026 - 9/25/2026
## Week 144: 9/28/2026 - 10/2/2026
## Week 145: 10/5/2026 - 10/9/2026
## Week 146: 10/12/2026 - 10/16/2026
## Week 147: 10/19/2026 - 10/23/2026
## Week 148: 10/26/2026 - 10/30/2026
## Week 149: 11/2/2026 - 11/6/2026
## Week 150: 11/9/2026 - 11/13/2026
## Week 151: 11/16/2026 - 11/20/2026
## Week 152: 11/23/2026 - 11/27/2026
## Week 153: 11/30/2026 - 12/4/2026
- DEADLINE for no-cost extension
## Week 154: 12/7/2026 - 12/11/2026
## Week 155: 12/14/2026 - 12/18/2026
## Week 156: 12/21/2026 - 12/25/2026
## Week 157: 12/28/2026 - 12/31/2026
- Last day of funding
## Week 158: 1/1/2027
- Report is due in approximately 120 days
