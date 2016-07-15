This is my story for how I came to appreciate the agile development process.

"Of all the agile methodologies, Scrum is unique because it introduced the idea of “empirical process control.” That is, Scrum uses the real-world progress of a project — not a best guess or uninformed forecast — to plan and schedule releases."

## The basic idea
Thesis: Project management and software development processes can be improved. 
Here are areas of software implementaion that can be improved:
* Managing Projects & Teams *people skills*
* Requirements & Design *eliciting & evaluating requirements*
* Process Improvement *project mgmt?*
* Testing & QA
* Development                       
* Metrics        
* SOA
* Security

## No pain no gain. 
#### Key pain areas
  * Disconnect between what the user wanted and what was developed
  * People didn't actively participate in writing or reviewing design and requirement documents
  * Large surprises would pop up and eat great swaths of development time.
  * Sometimes the large surprises didn't occur until we had the program in beta
  * Confusion about priorities. People assumed that features would be in a release, or had already been done
  * Lots of buzzwords, but not a lot of problem definition
  * Partially implemented features
  * Single developers would become wedded to their code: "for better or for worse"
  
#### Secondary pain areas
  * Poor morale due to poor reception of features and hard work
  * Much development time spent on researching the details of the feature without proper direction from users
  * Too many projects at once -- lack of focus
  * Users were despairing of ever seeing features they asked for years ago
  
#### We had failed previously
  * We had tried using an agile framework for development, but didn't use scrum. 
  * We focused on reprioritizing, but didn't have a single product owner to provide a clear voice
  * We focused on getting user feedback, but then translated that into an SRS which was implemented in a waterfall method
  * We tried to sashimi our features, but we didn't timebox our development into "potentially shippable" code every 2 weeks
  * We were doing "scrum but..."

## An Epiphany
Then I went to a workshop taught by Tamara Sulaiman from Applied Scrum.
She had us play the "Scrum Game" where we implemented a project using the Scrum framework (in a compressed timeframe where 2 hours = one sprint)
It was such a good experience I figured I'd try to bring Scrum to work.

## Our process
Here's what we did:

#### Create the vision document for the feature
 * Get management support
 * Consensus was that we were going to focus on this feature for the project
 * Mgmt had two dates:
 ** 04/01/09 - demo at the Convention (6 months away)
 ** 05/01/09 - Enter code freeze - no new features (7 months away)
 * Reality acknowledged that smaller projects would appear in the course of the project
 
#### Gather stories.
 * Interviewed 4 offices who wanted the feature
 * Gathered stakeholders in a room to review the vision document
 * Gathered stakeholders in a room to tell stories
 
#### Talk about the stories
 * Make sure every story has a workflow
 * Story should have the form "as a (person) I want (to do something) so that (beneficial result)"
 * Keep the stories visible
 * hand out sticky pads and let everyone write
 * no more detail than fits on a sticky pad
 
#### Size the stories
 * Here's an [article on estimating relative sizes](http://epf.eclipse.org/wikis/openup/core.mgmt.common.extend_supp/guidances/guidelines/agile_estimation_A4EF42B3.html)
 * Similar to prioritization.
 * Assess the actual sizes of the stories. If the story will take longer than 2 weeks to implement, then it's too large: break it down
 * Get a big room
 * Put a story on the wall, then ask people whether the next story is larger or smaller
 * Position the stories by relative sizes, and it's ok to overlap
 * The stories in the middle are medium, and lower down are large and x-large
 * The stories above the medium are small and x-small
 * assign points: x-small = 1, small = 2, medium = 4, large = 8, x-large = 16
 
#### Prioritize stories
 * Get a big room
 * Put a story on the wall, then ask people whether the next story is more or less important. This is an Insertion sort
 * Talk about why it's more or less important
 ** Business value  ( # users * potential income)
 ** Technical considerations (riskier sooner)
 ** Technical costs
 * Position the stories horizontally, and no story should overlap with another
 * When you're all done review the order, performing a bubble sort if you want to change priorities
 
#### Agree on first, second and third release milestones
 * What's the minimal functionality that can be released into the wild?
 * What's the next level after that?
 * These are critical milestones, but should tie in with business value
 * at this point you might consider cutting XL stories that are low priority
 
#### Develop a burndown chart based on sizes
 * put all the stories into a spreadsheet, on a tab called Stories
 * We didn't ever actually do the burndown chart...
 
#### Work on the #1 priority story for 2 weeks (sprint)
 * Sprint Planning - what are we working on, and how?
 ** The goal is to deliver value to the customer at the end of each sprint.
 * break story into functional tasks
 * Design
 ** Low-tech prototype
 ** Business rules
 ** UI
 ** Where to store this info?
 * Implement
 * Test against the story
 * Build
 * Smoke test
 * Functional and non-functional testing
 * Fix bugs
 * Add small enhancements
 * Document
 
#### Functional review with everyone that's interested
 * Review resolutions from last time
 * Present the stories
 * Discuss functionality
 
#### Process review with everyone that's involved
 * What was good about the process so far?
 * What could be improved?
 * What are we going to try to improve for the next two weeks?
 
#### Track bugs from previous sprints

#### Add enhancements from previous sprints as new stories

#### When we got to release criteria #1, release to actual beta site

#### Release criteria #2, give to 2nd beta site

#### Repeat sprints until we complete all stories, or we reach code freeze date

### Comments on the process
* If a bug is introduced during the sprint, try to fix it before the end of the sprint.
* If the bug is discovered after the sprint, then put it in the tracking system.
* Out of scope enhancements - put those into bug tracking system.
* In sprint enhancements - try to incorporate according to the story
* Out of sprint enhancements - put onto the wall (product backlog) for prioritization
* Maintain a mirror of the wall stories in a spreadsheet.
** The spreadsheet is easier to carry around than the wall
** Helps if anyone accidentally knocks the wall features on the floor

## lessons learned
* Try to size all the stories at once, with the same units
**  We were trying to estimtate the sizes in detail.
**  We kept putting off sizing the stories, only doing the most immediate stories.
**  Because of this, we didn't have any idea of the project burndown, since we didn't know how much work was left to do.
**  2 or 3 months into the project (of 6 months) we finally sized the remaining stories.
**  Problem was, these stories had a different scale than the others, which still blows the burndown as a graphic.
* Don't assign units. Put the stories into a spectrum from x-small to x-large. The ones in the middle are medium.
* Write ID#s on the back of the stories. This helps keep stories associated with the spreadsheet
* Write the whole story. If you have notes, put them on the back of the card
* Put the stories into a value statement: "as a(n) X, I want to Y so I can Z"
* Make sure the Product Owner really is involved.
* 2 week sprints are essential. People rarely remembered 4 weeks ago.
* People tend to get conversational during a daily scrum meeting, or want to solve problems.   Take these items out of the scrum, scheduling them immediately after the daily scrum if necessary
* Visibility is everything. We created an alpha station. The sales person used it, and complained about a feature.  This was good.
* Scrum is intense. It keeps you focused on the value every day. So, it's hard to find time for
** Slacking
** Web browsing
** Learning
** Wondering / Exploring
* Instead you focus on applied learning, empirical results, and long periods of concentration.
* This is great for productivity, but you may want to schedule some slack time.

## Questions that remain
* How to work 2 week sprints with vacations, holidays?
* How to capture design work?  Screens, business rules, programming constraints?
* How to transistion from 2-week sprints to a released piece of software?
* How to involve management and sales in this visibility process when they don't want to participate?
* What happens when the project’s mostly done, but there are still small items…?
* Still keep the sprint cycle?

## Further links
* [Excellent Scrum Cheat Sheet](http://www.scribd.com/doc/2370861/Scrum-Cheat-Sheet)
* [PNSQC Presentation on 9 Low-tech tips for Project Management](http://mxmossman.blogspot.com/2013/11/9-low-tech-tips-for-agile-project.html)
* [Scrum Methodology - learn scrum](http://scrummethodology.com/)
* [Why do scrum? 10 good reasons for Scrum](http://www.agile42.com/cms/blog/2009/06/16/10-good-reasons-scrum/)
* [Tips on managing the product backup](http://www.agilejournal.com/articles/columns/column-articles/1741-product-backlog-rules-of-thumb)
* [Definition of done](http://www.scrumalliance.org/articles/106-definition-of-done-a-reference)
