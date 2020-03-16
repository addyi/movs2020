# Git

##  What is Git?

- Why do we need it?
- Alternatives?
- History
- What is GitHub?
- ...

**Possible resources:**

- [Git](https://git-scm.com/)
- [Atlassian Tutorials](https://www.atlassian.com/git/tutorials)

**Your research:**

- YOUR NOTES

## How to setup Git?

- Installation
- Identity
- Editor

**Your research:**

- YOUR NOTES


## How to use Git?

- Important commands
- Workflow

<!--- git init, staging, restore, commit, branches, checkout-->

**Your research:**

- YOUR NOTES

**Interactive tutorials:**

- [LearnGitBranching](https://learngitbranching.js.org/)
- [KataCoda Git course](https://www.katacoda.com/courses/git/)

## Working together / Contributing

- What is Git Flow?
- What is GitHub Flow?
- What is an Pull Request?
- What is an Merge Request?
- What is an SSH key?
- Why is that interesting for Git?


**Your research:**

#### What is GitFlow?
- GitFlow ist eine Workflow nachdem mit Git in Teams gearbeitet werden kann
- Es gibt (meist) 5 Arten von branches
  - Master: hier liegt ein immer lauffähige Version
  - Develop: hier wird vom Master gepulled und alle features reingepushed
  - Feature: Für jedes Feature wird ein Branch aufgemacht, hier werden die Features entwickelt und in den Developer branch gepushed
  - Release: Ein Release wird erstellt, sobald genug features auf dem Developer Branch gesammelt wurden
  - Hotfix: falls ein schneller Hotfix gemacht werden muss, wird hier vom Master gebranched und in den developer und master gepushed

#### What is GitHub Flow?  
- "einfachere" Variante von GitFlow:
 - Branch zum Master wird erzeugt, auf dem entwickelt wird
 - Sobald eine Änderung fertig ist, wird ein Pull Request erzeugt
 - über diesen kann nun in GitHub selbst diskutiert und ggf. Verbesserungen durchgeführt werden (CodeReview)
 - Anschließend (wenn alle zufrieden) wird der Branch gemerged

#### What is an Pull Request?
- Ein Pull Request ist "die Bitte um Aufnahme von Änderungen" in einem Branch

#### What is an Merge Request?
- Das gleiche wir Pull Request bei GitHub in GitLab

#### Why is that interesting for Git?
##### GitFlow/GitHub Flow:
  - "Struktur" in die Arbeit bringen / Zusammenarbeit erleichtern
  - Master ist immer produktiv (und sauber)

##### Pull Request / Merge Request:
  - CodeReview
  - Diskussion über Änderungen
  - Verbessern von Änderungen


**Possible resources:**

- [Comparing work flows]
- [GitHub Flow]
- [Connecting to GitHub with SSH]
- [ssh-keygen]
- ["Upgrade" to Ed25519]


## Collaboration Features

- (GitHub) Organisation
- Wiki
- Readme/Markdown
- License
- Project board
- Pages
- Settings walk through





[Comparing work flows]: https://www.atlassian.com/git/tutorials/comparing-workflows
[GitHub Flow]: https://guides.github.com/introduction/flow/

[Connecting to GitHub with SSH]: https://help.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh
["Upgrade" to Ed25519]: https://medium.com/risan/upgrade-your-ssh-key-to-ed25519-c6e8d60d3c54
[ssh-keygen]: https://www.ssh.com/ssh/keygen
