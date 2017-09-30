# OSS Project Checklist

## Pre-checks
- [ ] Able to explain your project in a tweet ?
- [ ] Choose a name for the project
- [ ] Check if domain name / App name is available ?
- [ ] List and learn tools required for the project
- [ ] Prepare mock-up and one page design document, if needed to explain to collaborators
- [ ] List previous / similar implementations and learn from them
- [ ] Start a blog post to document the journey ( if time permits ) Mention idea + helpful resources.
- [ ] Ask if project could be solved in a modular way by dividing into sub-problems and creating a separate project for the sub-problems.

## Project Creation
- [ ] Create a Repository in any of the Source Control Management sites
    - Github ( Free public repos )
    - Gitlab ( Free public and private repos + CI  + docker registry )
    - Bitbucket ( Free public and private repos )
- [ ] Create a README.md (check below for more)
- [ ] Create a LICENSE file (choose one before)
- [ ] Create a CODE_OF_CONDUCT.md
- [ ] Create a CONTRIBUTING.md
- [ ] Create a .gitignore
- [ ] Create [Gitter](https://gitter.im) chatroom (if needed)

## README.md Checklist
- [ ] Title
- [ ] Logo
- [ ] Badges
- [ ] Description
- [ ] Prerequisite for using software ( if any )
- [ ] Install
- [ ] Example Usage
- [ ] Screenshots and GIFs
    - For command line apps, try [asciinema](https://asciinema.org/)
    - For mac GUI screenshots, use [Cmd+Shift+3] or [Cmd+Shift+4] or [Cmd+Shift+4,SpaceBar]
    - For mac GUI GIF creation, try [kap](https://getkap.co/)
    - For Ubuntu GUI Screenshots, use [Shift+PrintScr] or [Shutter](http://shutter-project.org/)
    - For Ubuntu GUI GIF creation, try [silentcast](https://github.com/colinkeenan/silentcast)
- [ ] Contributors
- [ ] Backers and Sponsors
- [ ] Attributions ( mention 3rd party libs used etc. )
- [ ] Security
    - [ ] Post maintainer's PGP fingerprint for reporting security vulnerabilities
    - [ ] Share [keybase](https://keybase.io/) profile for making the reporting process easier.

## Coding Phase
- [ ] Install required developer tools
    - [ ] Compiler
    - [ ] Linter
    - [ ] Formatter
    - [ ] Build Tool
    - [ ] Other
- [ ] Organise files and folders that will help readers to find code easily
- [ ] Basic code complete
- [ ] Write tests and keep watch on code coverage
- [ ] Setup CI
- [ ] Host the documentation of the code somewhere if the project is a software library 
- [ ] Use Github issues ( or other tools ) for tracking backlogs
- [ ] Encourage OSS culture by having labels like "help wanted" "easy-to-contribute" etc.
- [ ] Contribute to other OSS projects on which the current project is dependent on ( if possible )
    - File bug reports
    - Improve docs
    - Suggest feature
    - Learn by reading code

## Release Phase
- [ ] Package software in CI or manually in local
- [ ] Publish in registries (npm, docker hub etc.) or markets (Android store, App Store etc.)
- [ ] Create the release version, description, link for downloading the release etc. in release page ( example: Github release page)

## Post-release
- [ ] Publish the blog post
- [ ] [Tweet](https://twitter.com/)
- [ ] [Hackernews](https://news.ycombinator.com/)
- [ ] [Product Hunt](http://producthunt.com/)
- [ ] Send PR to `awesome-*` github repository
- [ ] [Redit](https://www.reddit.com)
- [ ] [Hashnode](https://hashnode.com/)
- [ ] [Linkedin](https://www.linkedin.com/)
- [ ] Edit Wikipedia pages (if related)
- [ ] Prepare slides and give talks (if possible)