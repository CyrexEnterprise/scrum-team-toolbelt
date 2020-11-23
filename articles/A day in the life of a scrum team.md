# A day in the life of a Scrum Team
At Cloudoki we start up projects in Scrum, experienced and novices alike. This mix has allowed us to gather the best experiences and share them with new teams, each time again.

"[The agile scrum](https://scrum.org)" is one of the more successful organisational frameworks and fundamental to our ability to deliver products reasonably within time, with the user on center stage.

Each kind of company and product has its own implementation of agile methods and ceremonies, depending on their size, legacy and market. Since we've worked with all the flavours we think there might be something in our guide, "A day in the life of a scrum team", for any reader.

This guide is based on our collective experiences. We will break them down in [Roles](#roles), [Tools](#tools), [Time-line](#timeline) and [Ceremonies](#ceremonies). Although your personal mileage may vary, we hope the documentation will bring you some new insights and practical usability to your project - even if it is your first. "A day in the life of a scrum team" is intended for onboarding new Cloudoki family members and clients as well.

All readers are welcome to promote and contribute to this guide. An interactive (git) tool-belt has been released to support your suggestions and improvements.

# Why we scrum
> The feeling of having impact is what makes a product team thrive.

## To build good products
We might be kicking in open doors here: building a good product is hard. First, the company needs to realise its customers are in need for a service that is oriented to them - the user - and not the other way around. Second, that service needs to be defined in a user-centric story and a roadmap planned for early release, not to be perfect. Lastly, a workable framework needs to be set up with competent stakeholders and **internal freedom**. The agile scrum.

In general, we notice both increased team member happiness as client satisfaction the more experienced we become in agile scrums.

## To minimise management
Contrary to some beliefs, throwing money and managers at a project has no effect on its chances of success. A competent team, however small, with a single Sponsor (management [SPOC](https://www.cyberdefinitions.com/definitions/SPOC.html) / budget overlord) and adequate tools will move a mountain. A well balanced, happy team capitalises on the confidence it is entrusted - the feeling of having impact is what makes a product team thrive.

An agile scrum team is always a bigger collective of roles than members and never a fixed set-up. At Cloudoki we try to keep our management involvement at 20%.

## To keep customers happy
Customers are not helped with a perfect service that never arrives because it's forever stuck in development. By releasing early and maintaining a lean roadmap that is subject to user-driven change, that precious commodity called "customer loyalty" materialises out of thin air and hard team efforts.

Stable, customer oriented feature releases require respect for the scrum framework from all stakeholders. Since scrum is intentionally flexible, the risk of one role leaning too hard on the process exists, but always with consequences down the roadmap.

# Scrum concepts

## Roles
In "A day in the life of a scrum team", we define 11 team roles, carried by on average 5 to 8 revolving profiles. Logically, most profiles take up more than a single role in the team - and that is to be encouraged. In practise, we tend see bloated teams under-achieve in relative output compared to smaller, boot-strapped ones.

The magic of a good team selection happens by the Sponsor and the Product Owner, when budget and competences are matched during the scrum team setup.


Roles | abbr. | | entries
:---|:---|:---|:---
Scrum Master | SM | Manager of the scrum, focussed on the sprint | [git](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/roles/scrum-master.md)
Architect |  Arch | Tech lead of the product, usually senior engineer | [git](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/roles/architect.md)
Engineers |  Tech | The tech team turning user stories into product features | [git](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/roles/engineer.md)
Release engineer | Release |  Specialised engineer managing the continuous release pipeline ("CI/CD") | [git](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/roles/release-engineer.md)
Tester |  Test | Specialist engineer guarding acceptable product quality | [git](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/roles/tester.md)
Functional Analyst | Analyst |  Maintaining the flow and service dependencies of the product | [git](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/roles/functional-analyst.md)
Story-teller | Story |  Writer of the user stories and feature acceptance criteria | [git](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/roles/story-teller.md)
Product Designer | UX |  Measuring the user needs and translating them into good experiences ("UX") | [git](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/roles/product-designer.md)
[Product Owner](/a-day-in-the-life-of-a-po-day-one/) |  PO | Story-teller and serving leader | [Day 1](/a-day-in-the-life-of-a-po-day-one/), [Day 2](/a-day-in-the-life-of-a-po-day-two/), [Day 3](/a-day-in-the-life-of-a-po-day-three/) and [git](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/roles/product-owner.md)
Product Manager |  PM | Project based "internal" PO (Cloudoki specific) | [git](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/roles/project-manager.md)
Tribe Scrum Master | TSM | In enterprise tribes, the liaison between product teams | [git](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/roles/tribe-scrum-master.md)
Sponsor | | Management point-of-contact and budget overlord | [git](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/roles/sponsor.md)

_We encourage you to [contribute](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/roles) by sharing your experience in this series._

![Scrum Team](https://github.com/Cloudoki/scrum-team-toolbelt/blob/master/articles/resources/scrum-team.png?raw=true)

## Tools
The management of a modern team and product entirely depends on matching tools, both organisational as technical. We typically involve about 11 tools in a product scrum. Our list is opinionated, so feel extra welcome to [contribute](https://github.com/Cloudoki/scrum-team-toolbelt) with your preferred tools and experiences.

Tools | maintainers | entries
:---|:---|:---|
Project management | PO, SM |
Ceremonies runbook | SM |
[Feature roadmap](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/tools/technical-roadmap) | PO, Sponsor | [git](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/tools/technical-roadmap)
Wireframes | UX, Analyst, Story |
[User stories](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/tools/user-stories) | Story, Analyst, Arch| [git](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/tools/user-stories)
Functional diagrams | Arch, Analyst |
Sprint planning | SM, Tech, Analyst |
[The changelog](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/tools/changelog) | SM, Release, Test | [git](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/tools/changelog)
Release plan | PM, Release, Arch, Test |
CI/CD management | Release |
End-to-end testing | SM, Test |

<!--[Project management](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/tools/project-management)-->
<!--[Ceremonies runbook](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/ceremonies)-->
<!--[Wireframes](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/tools/wireframnes)-->
<!--[Functional diagrams](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/tools/flow-diagram)-->
<!--[The release plan](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/tools/release-plan)-->
<!--[CI/CD management](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/tools/cicd-management)-->
<!--[End-to-end testing](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/tools/e2e-testing)-->

_We maintain our scrum team toolbelt reference and repository at GitHub. [github.com/Cloudoki/scrum-team-toolbelt](https://github.com/Cloudoki/scrum-team-toolbelt)_

## Time-line
The agile development time-line wildly varies per project, but usually starts with customer input, followed by the design phase, some more customer feedback, development and first release - also called "MVP" ("Minimal Viable Product"). We like to apply the "Product Lifecycle" method, [read more about this soon](#todo).

![API Lifecycle](https://github.com/Cloudoki/scrum-team-toolbelt/blob/master/articles/resources/API-Lifecycle.png?raw=true)

### The sprint
The most visible partitioning of the scrum time-line is the "sprint". A sprint is a repeating, fixed amount of time and ceremonies acting as the real muscle of the scrum framework. The sprint is used both as high-level partitioning for the roadmap assessment, as deep level best-effort assessment of the amount of work ("tickets") that can be completed within each given sprint.

Going back and forth between the accuracy of the feature roadmap planning and the accomplished deliveries by the team, allows the Product Owner to adapt and predict realistic outcomes of the product investment.

A sprint in Cloudoki consists of 2 weeks, typically resulting in 9+1 worked days.
[The Product Owner articles](/a-day-in-the-life-of-a-po-day-one/) are broken down in those 10 days, for in-depth insights.

## Ceremonies
Scrum ceremonies are pre-defined events with a role-based target audience and function. Scrum ceremonies are repetitive in nature, usually linked to the sprint sequence. To keep the management overhead under control, we are quite limiting in the ceremonies, so your mileage may vary. [Suggest changes](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/ceremonies/).

Ceremonies | frequency | stake-holders | entries
:---|:---|:---|:---
Stand-up | daily or every 2 days | SM, Tech, Test, Analyst, UX | [git](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/ceremonies/stand-up.md)
Demo | every sprint end | All | [git](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/ceremonies/demo.md)
Changelog | every sprint end | SM, Test, TSM, Release, Arch, Analyst | [git](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/ceremonies/changelog.md)
Retrospective | every sprint end | SM, Test, Tech, UX, Analyst | [git](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/ceremonies/retrospective.md)
Release meeting | every next sprint last day | Release, SM, Sponsor, Arch, PO, TSM | [git](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/ceremonies/release-meeting.md)
Sprint planning | every sprint 2nd week | SM, Arch, Analyst, PO | [git](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/ceremonies/sprint-planning.md)
Sprint refinement | every sprint start | SM, Analyst, Tech | [git](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/ceremonies/sprint-refinement.md)
[Hackfriday](/tag/hackfridays) | every sprint end Friday | All | [git](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/ceremonies/hackfriday.md)

_The ceremonies are broken down in the contributing articles._

# What's next?
Indifferent if you are about to join a scrum team or learning about the general framework, we'd advise you to select a "persona" (role) next. By looking at the interactions from the point of view of your persona, you'll start to understand who you will be interacting with on a day-to-day basis and which tools are most impactful on your professional life.

> [A day in the life of a PO, day one](/a-day-in-the-life-of-a-po-day-one)

If you end a persona's "[happy flow](https://www.the-reference.com/en/blog/frederiktaevernier/2019/do-you-know-your-happy-flow)" through a scrum sprint and come to the conclusion that your time has come to make career changes, consider [applying for a great job at Cloudoki](https://savvy.bamboohr.com/jobs/)!

<!--
## Some rules of thumb
* Best sprints have a **2 weeks** length, so do CI cycles
* Deployment from testing all to production takes 2 cycles
* **Business** has responsibility over feature acceptance
* **Business** has responsibility over hotfixes
* Hotfixes can **only** be up-cycled 1 stage
* Critical bugs are no hotfixes, they are critical bugs
* An PO mostly **doesn't** live in the current sprint
-->

---
### About the authors
[Rui Molefas](https://blog.cloudoki.com/author/rui/) and [Koen Betsens](https://blog.cloudoki.com/author/koenbetsens/) are the founders of Cloudoki and on constant guard to improve and adapt our scrums.

### To-do
Following entries will be provided over the next weeks and months.
* Product lifecycle explained

### Contribute
We would like to invite each member of any scrum team to document their sprint journey and share it with us.

Improvements and elaborations are tracked on [GitHub](https://github.com/Cloudoki/scrum-team-toolbelt/issues). Please read our [contribution guidelines](https://github.com/Cloudoki/scrum-team-toolbelt/tree/master/CONTRIBUTING.md) before opening a new improvement request or submitting a reference.

### Released articles
* [A day in the life of a PO, day one](/a-day-in-the-life-of-a-po-day-one)
* [A day in the life of a PO, day two](/a-day-in-the-life-of-a-po-day-two)
* [A day in the life of a PO, day three](/a-day-in-the-life-of-a-po-day-three)
