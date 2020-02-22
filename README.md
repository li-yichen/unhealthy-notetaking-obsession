# unhealthy-notetaking-obsession
experiments in note-taking
## usage and requirements
### goals/usage
reading notes (research?), journaling/day-logging, to-do lists<br>
user: humanities student, basic laptop with very little storage or ram on an *antique* cpu, does not understand programming, loses stuff a lot, easily distracted, almost always abandons tasks
### requirements
#### requirements for notes content/features
- [x] everything needs to be aligned (except for paper)
- [x] searchable (except for class notes requiring constant drawing) (all digital notes searchable)
- [x] tagged (i.e. "adu", "social-skills") (reason: easy retrival) (update: satisfied by emacs)
- [x] linked (hierarchy for class notes) (update: satisfied by emacs, html)
- [x] minimal interface (reason: distraction) (update: satisfied by emacs)
  -  [x] writes as unformatted text and reads as formatted (i.e. html) (also reason: save time used to switch formatting options by cursor)
  -  [x] minimal signs of graphic interface, including no buttons/dropdowns (i.e. text formatting options in microsoft word or pages) and minimal color except those that serve a function (i.e. blue interface for Things)
- [ ] does not require computer for non-computer tasks (reason: distraction) (update: partially satisfied by interactive/printing daily planner)
- [ ] does not require convoluted/time-consuming upkeep once format is established (i.e. see below json attempt)(reason: just so it is actually usable)
#### requirements for software type
- [x] does not die with fancy softwares & can be exported (reason: self-explanatory) (update: satisfied by emacs (which will probably exist until i die) and html)
- [x] does not require commercial software (reason: see above, and privacy) (update: satisfied by GNU emacs)
- [ ] lightweight / integrates as much as possible with most useful existing stuff on my laptop / eliminates as much as possible most useless existing stuff on my laptop (reason: laptop space) (update: partially satisfied by html, which saves space compared to .word or .pdf.
## tagging/notation methods
### text notes
for use with any text-based notes (handwritten or digital)
#### labels
- [G] game (games history)
- [E] exhibition & [A] art (art history)
- [A] architecture & [E] art (architecture history)
- [L] literature (i.e. [L] shah-nama) *bias exists bc earlier works are often classified as [L] instead of [R]*
- [R] reference to earlier scholars (i.e. [R] foucault, discipline and punishment)
*all books or textual works are formatted with «» for easy identification*
- [T] technology
- [M] methodology
#### notations
- "-verb-" for easy reading (i.e. it is -associated with- another thing)
- "->" leads to, or consequence, or implies
- "«»" for books or papers
## comparison of methods by purpose
### classes
method | active time  | description | features | medium | pro | con | status
--- | --- | --- | --- | --- | --- | --- | ---
numbered bifold rotated ruled paper | 2018/06-2019/06 | ruled paper used in landscape orientation for easier hand movement and drawing of arrows to earlier notes, w/ page numbers on upper right corners | `numbered` `dated` `optimal for hand movement` | `paper` | see description | easy to lose | `obsoleted`
numbered bifold rotated ruled notebook | 2019/08-present | same as above, but harder to lose | `numbered` `dated` `optimal for hand movement` `bound` | `paper` | same as above | requires daily scanning/digitization to ensure it's not lost | `in use`
^pdf from above & folders & html | 2019/04-present | one folder per class, each with index.html file as well as dated .html files for section notes, also links to pdf files of lecture slides | `pdf` `linked` `dated` | `paper` `html` `folders` | html enables typing without distraction of seeing a bunch of buttons or moving cursors to click stuff (i.e. in word or pages), can display any file readable in web browser, links for easy browsing, writes as non-distracting unformatted text but reads as hierarchical and formatted | html tags `convoluted writing`, html tags not customizable (see text note table of legends), lacks: actual tags | `in use`
folders containing scanned lecture notes and emacs files with org-mode, exports to html | 2019/10-present | same as above, but has tags | `pdf` `linked` `dated` | `org-mode` `emacs` `paper` `html` `folders` | finally has tags! can perform other orgmode functions also, also no longer have to painfully hand-type html elements | steep learning curve, emacs not as pretty as html | `in use`
### books
method | active time  | description | features | medium | pro | con | status
--- | --- | --- | --- | --- | --- | --- | ---
github repository | 2019/03-2019/04  | one readme file for keeping track of books, one .md file for each book | `searchable` | `github` | `organized` | `online(hehehe` `unnecessary computer` `convoluted writing` | `failed`
"paper twitter" reading notes | 2019/09-present | ruled paper used in landscape orientation, cut into smaller rectangular pieces, uses above table of legends, write page number on each piece of paper, then insert into page in book | `numbered` `dated` `optimal for hand movement` | `paper` | `no-computer` | `non-searchable`, damages book spine when too many notes are inserted | `trial`
### journaling/logging
method | active time | description | features | medium | pro | con | status
--- | --- | --- | --- | --- | --- | --- | ---
json | 2019/08 | .json file with "date","documentation","conclusions" for date, logs(wake up time, sleep amount, meals, things bought, medications), and conclusions (aka "life lessons" learnt) | `dated` `searchable` | `json` | organized, repeatable | `convoluted writing` | `failed`
designed planner w classes | 2009-present | booklet-printed planner, weekly, hourly time table with time slots for classes (pencil to plan, pen to record), daily large text fields for to-do lists.| `dated` | `json` | organized, repeatable `no-computer` | `non-searchable` | `in use`
python hourly time table generator with weather and clothes | 2020/1-present | planner that prints time table every morning via interactive survey, which includes dividing a day's task into modules (exercise, social, homework, research) and some options under modules. also contains hourly temperature and wind, and recommended clothes (based on simple if statement) | `dated` | `json` | organized, repeatable `no-computer` | code very convoluted | `in use`
## journal about notes
### helpful resources about emacs, lisp, orgmode (to a complete beginner)
* [resources on the right bar of r/emacs](https://www.reddit.com/r/emacs/)
* [Rainer König's OrgMode serie on Youtube](https://www.youtube.com/watch?v=sQS06Qjnkcc&list=PLVtKhBrRV_ZkPnBtt_TD1Cs9PJlU0IIdE)
