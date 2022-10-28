# Community Software Analysis Proposal
Please edit this file and push to your repository.

## Software: *Eilmer: An 11-century Benedictine monk*

*Eilmer is a hypersonic flow solver built on a finite-volume formulation that is capable of solving the Navier-Stokes equations in 2D and 3D computational domains, discretised with structured or unstructured grids. Multiple slope limiters are implemented to ensure numerical stability near shocks and regions of strong gradients. *

### Stats

| Description | Your answer |
|---------|-----------|
| Repository URL |https://github.com/gdtk-uq/gdtk|
| Main/documentation website |https://gdtk.uqcloud.net/docs/all-the-docs/about/|
| Year project was started |2015|
| Number of contributors in the past year | 14 |
| Number of contributors in the lifetime of the project |21|
| Number of distinct affiliations |2-5|
| Where do development discussions take place? |GitHub/GitLab issues|
| Typical number of emails/comments per week? |4|
| Typical number of commits per week? |12|
| Typical commit size | 210 |
| How does the project accept contributions? | pull requests|
| Does the project have an automated test suite? | yes|
| Does the project use continuous integration? | no |
| Are any legal/licensing steps required to contribute? | no|

### Install and run

Check the following boxes when complete or add a note below if you
encountered a problem.

- [-] I have installed the software
- [-] I have run at least one example
- [-] I have run the test suite
- [ ] The test suite passes


### Notes/concerns/risks

Eilmer was installed with sucess on my personal machine (Apple M1). I ran an example case and obtained correct results. I ran a regression test on the
gas dynamics section and found that all cases passed except for one. Specifically, one case failed to find a "cea2 exe file". However, cea is a NASA tool 
used to compute chemical nonequilibrium cases, and I do not have it installed. Although this is odd that the installation instructions did not require it,
I do not believe that it is required. If I choose to continue this project I will try to resolve this issue. Otherwise, the code seems to be behaving as expected.

#### Note on copyright
Students retain copyright on any work done in completion of a CU
course, so you are authorized to sign a [contributor license
agreement (CLA)](https://en.wikipedia.org/wiki/Contributor_License_Agreement),
affirm a [developer's certificate of
origin (DCO)](https://en.wikipedia.org/wiki/Developer_Certificate_of_Origin),
etc.  If you have concerns about this, please note them and/or reach
out to Jed directly.
