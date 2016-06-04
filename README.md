# Best Practices in Open Source

*Trent Oswald, `trentoswald``@``therebelrobot.com`, @therebelrobot*

*National Day of Civic Hacking, June 4th 2016*


*Note: this is more useful after going through the slides, but feel free to poke around ;)*

## Additional Readings

[Branching model](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow) vs [Forking model](https://www.atlassian.com/git/tutorials/comparing-workflows/forking-workflow)

[code slide plugin](https://github.com/thejameskyle/spectacle-code-slide)

## Contact Info

name | email | slack | irc | github  
---- | ----- | ----- | --- | ------ 
Trent Oswald | `trentoswald``@``therebelrobot.com` | @therebelrobot (sfbrigade, cfa) | @therebelrobot (freenode) | https://github.com/therebelrobot

## Slide content

```js
function Best_Practices_for (openSource) {
  // Trent Oswald 
  //    Infrastructure Core Team Lead - c4sf 
  //    therebelrobot.com - @therebelrobot
  // National Day of Civic Hacking, 6/4/16

  openSource !== freeLunch()
  openSource === trust()

  trust.access_source()
  trust.legally()
  trust.contribute()
  trust.governance_and_management()
  trust.upgrading_and_mantaining()
  trust.safe_space_to_work()

  var howDoIEstablishThisTrust = function () {
      releaseOfSourceCode() 
            // Github, Gitlab, Bitbucket, etc 
    publicAndPermissiveLicense()  // choosealicense.org tldrlegal.com
            // LICENSE
            // MIT, ISC
            // Apache 2
            // GPLv3
            // WTFPL
    contributingGuide()  // branch management, pull request policies, style guides
            // CONTRIBUTING.md
            // How to get started
            // How to add/request new features
            // Issue triaging
            // Language Translating
            // Interacting with the Community
            // Branch Management Flow
            // Pull Request Policies
            // Coding Style Guides
    workInTheOpen() 
            // Meeting Minutes
            // Github Issues
            // Slack
            // Google Hangouts on Air
    changelogAndVersioning() 
            // CHANGELOG.md // http://keepachangelog.org
            // Semantic Versioning // http://semver.com
    testingAndCoverage() 
            // unit testing
            // integration testing 
            // testing coverage // http://codeclimate.com
    codeOfConduct() 
            // CODEOFCONDUCT.md
            // Contributor Covenant // http://contributor-covenant.org/
    upToDateDocumentation() 
       // Its not open unless its documented.
       // Its not useful unless its current.
  }
} 
```
