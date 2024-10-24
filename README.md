# FFP-Project

## Table of Contents
- [FFP-Project Mission](#ffp-project-mission)
  - [Our Core Values](#our-core-values)
- [Plan (Going Public)](#plan-going-public)
- [Version Control Strategy](#version-control-strategy)
  - [Branch Structure](#branch-structure)
  - [Commit Guidelines](#commit-guidelines)
  - [Release Management](#release-management)
  - [Pull Request Process](#pull-request-process)
  - [CI/CD Integration](#cicd-integration)
  - [Documentation Requirements](#documentation-requirements)
  - [Code Review Process](#code-review-process)
  - [Merge Strategy](#merge-strategy)
  - [Backporting Process](#backporting-process)
  - [Tagging Strategy](#tagging-strategy)
  - [Maintenance](#maintenance)
  - [Commit Message Conventions](#commit-message-conventions)
    - [Required Prefixes](#required-prefixes)
    - [Additional Best Practices](#additional-best-practices)

## FFP-Project Mission

FFP (Far From Perfect) is committed to fostering continuous improvement in both knowledge and software development through open-source collaboration. 
We believe that progress comes through iteration, learning from experience, and maintaining transparent, community-driven development practices.

### Our Core Values

1. **Continuous Learning**: We commit to constant knowledge expansion, believing that every challenge is an opportunity to learn
2. **Software Evolution**: We create and improve software solutions iteratively, focusing on real-world value over theoretical perfection
3. **Open Source Forever**: We maintain unwavering dedication to open-source principles, ensuring our work remains accessible and community-driven
4. **Community First**: We build and nurture a collaborative environment where everyone can contribute and grow

## Plan (Going Public)

- [ ] Build GitHub presence
  - [x] Create organization account
  - [ ] Create project over all repos
  - [ ] Create repos for FFP-Engine, SoundGuardian and TracerViewer
  - [ ] Create repo for homepage
  - [ ] Configure organization
    - [ ] Set up issue templates
    - [ ] Create contribution guidelines
    - [ ] Create code of conduct
    - [ ] Set up project boards
    - [ ] Define coding standards
  - [ ] Beautify organisation page before going public
  - [ ] Go public 2024-12-01

- [ ] Configure Google Workspace for FFP-Project
  - [ ] Create Calendar for going public
  - [ ] Set up shared documentation spaces
  - [ ] Create project tracking templates

- [ ] Build Youtube Channel for FFP-Project
  - [ ] Beautify channel page
  - [ ] Create content strategy
  - [ ] Prepare initial videos for launch
  - [ ] Create channel art and branding

- [ ] Rent v-server for FFP-Project
  - [ ] Setup server for C# projects
  - [ ] Setup server for Homepage
  - [ ] Use GitHub CI to deploy to v-server
  - [ ] Configure SSL certificates
  - [ ] Set up monitoring and backup systems
  - [ ] Document server architecture

- [ ] Build Homepage for FFP-Project (mkdocs)
  - [ ] Create protected section for CV and other private stuff
  - [ ] Connect to SoundGuardian documentation
  - [ ] Connect to AccountManager documentation
  - [ ] Connect to TracerViewer documentation
  - [ ] Connect to FFP-Engine documentation
  - [ ] Add blog
  - [ ] Add setup overview
  - [ ] Add project gallery
  - [ ] Set up analytics
  - [ ] Create sitemap
  - [ ] Implement search functionality
  - [ ] Create contact forms

- [ ] Add SoundGuardian project to GitHub organization
  - [ ] Create SoundGuardian repository
  - [ ] Add Documentation (mkdocs and docfx/doxygen)
  - [ ] Create CI pipeline
  - [ ] Publish the App to the website guardian.ffp-project.net
  - [ ] Create user guides
  - [ ] Set up version control strategy
  - [ ] Go public 2024-12-01

- [ ] Add AccountManager project to GitHub organization
  - [ ] Add Documentation (mkdocs and docfx/doxygen)
  - [ ] Create CI pipeline
  - [ ] Publish the App to the website guardian.ffp-project.net
  - [ ] Create user guides
  - [ ] Set up version control strategy
  - [ ] Go public 2024-12-01

- [ ] Add TracerViewer project to GitHub organization
  - [ ] Add Documentation (mkdocs and doxygen)
  - [ ] Create and beautify repository
  - [ ] Work off todo list (see at bottom)
  - [ ] Create user guides
  - [ ] Set up version control strategy
  - [ ] Go public 2024-12-01

- [ ] Add Engine project to GitHub organization
  - [ ] Add Documentation (mkdocs and doxygen)
  - [ ] Create and beautify repository
  - [ ] Create plan for going public
  - [ ] Set up version control strategy
  - [ ] Go public 2025-01-01

- [ ] Pre-Launch Preparation
  - [ ] Security audit for all projects
  - [ ] Cross-project documentation review
  - [ ] Test all deployment pipelines
  - [ ] Prepare launch announcements
  - [ ] Create initial release notes
  - [ ] Test all inter-project connections
  - [ ] Verify all documentation links

- [ ] Community Setup
  - [ ] Set up GitHub Discussions for each project
  - [ ] Create community guidelines
  - [ ] Set up issue labels and templates
  - [ ] Create contribution workflows
  - [ ] Set up project boards for community tasks

## Version Control Strategy

### Branch Structure
- [ ] Set up protected main branch
  - [ ] Require pull request reviews
  - [ ] Enable status checks
  - [ ] Set up branch protection rules

- [ ] Create standard branches
  - [ ] main (production)
  - [ ] develop (integration)
  - [ ] release/* (release preparation)
  - [ ] feature/* (new features)
  - [ ] bugfix/* (bug fixes)
  - [ ] hotfix/* (urgent production fixes)

### Commit Guidelines
- [ ] Create commit message templates
  - [ ] Define prefix conventions (feat:, fix:, docs:, etc.)
  - [ ] Set up commit message validation
  - [ ] Document examples for good commits

### Release Management
- [ ] Define versioning scheme (Semantic Versioning)
  - [ ] Major version (x.0.0) - Breaking changes
  - [ ] Minor version (0.x.0) - New features
  - [ ] Patch version (0.0.x) - Bug fixes
  
- [ ] Set up release workflow
  - [ ] Create release checklist template
  - [ ] Define release branch naming (release/v1.2.3)
  - [ ] Set up automated changelog generation
  - [ ] Define release notes template
  - [ ] Configure automated version tagging

### Pull Request Process
- [ ] Create PR templates
  - [ ] Feature template
  - [ ] Bug fix template
  - [ ] Documentation template
  
- [ ] Define PR guidelines
  - [ ] Code review checklist
  - [ ] Testing requirements
  - [ ] Documentation requirements
  - [ ] Definition of Done criteria

### CI/CD Integration
- [ ] Set up automated workflows
  - [ ] Build validation
  - [ ] Unit test execution
  - [ ] Code quality checks
  - [ ] Documentation generation
  - [ ] Release automation

### Documentation Requirements
- [ ] Create documentation for version control
  - [ ] Branch strategy guide
  - [ ] Commit message guide
  - [ ] Release process guide
  - [ ] PR process guide
  
- [ ] Set up version-specific documentation
  - [ ] Configure documentation versioning
  - [ ] Set up documentation deployment per version

### Code Review Process
- [ ] Define review guidelines
  - [ ] Code quality standards
  - [ ] Testing requirements
  - [ ] Performance considerations
  - [ ] Security checks

### Merge Strategy
- [ ] Define merge requirements
  - [ ] Squash and merge for features
  - [ ] Regular merge for releases
  - [ ] Fast-forward only for hotfixes
  
- [ ] Set up merge automation
  - [ ] Auto-merge for approved PRs
  - [ ] Auto-delete merged branches
  - [ ] Conflict resolution guidelines

### Backporting Process
- [ ] Define backporting strategy
  - [ ] Criteria for backporting
  - [ ] Process for cherry-picking
  - [ ] Testing requirements for backports

### Tagging Strategy
- [ ] Define tag conventions
  - [ ] Release tags (v1.2.3)
  - [ ] Pre-release tags (v1.2.3-beta.1)
  - [ ] Development tags (v1.2.3-dev)
  
- [ ] Set up tag automation
  - [ ] Automated tag creation
  - [ ] Tag protection rules
  - [ ] Tag signing requirements

### Maintenance
- [ ] Set up regular maintenance tasks
  - [ ] Branch cleanup schedule
  - [ ] Tag cleanup policy
  - [ ] Repository size monitoring
  - [ ] Access review schedule

### Commit Message Conventions

#### Required Prefixes
Format: `<prefix>: <description>`

- **feat:** A new feature
  - Example: `feat: add dark mode support`
  - Use for any new functionality additions

- **fix:** A bug fix
  - Example: `fix: resolve null reference in login process`
  - Use for any bug corrections

- **refactor:** Code changes neither fixing bugs nor adding features
  - Example: `refactor: simplify authentication logic`
  - Use for code improvements and restructuring

- **docs:** Documentation changes
  - Example: `docs: update installation guide`
  - Use for README, documentation files, code comments

- **style:** Code style/formatting changes
  - Example: `style: format according to style guide`
  - No functional code changes

- **test:** Test-related changes
  - Example: `test: add unit tests for user service`
  - Including new or fixing existing tests

- **perf:** Performance improvements
  - Example: `perf: optimize database queries`
  - Use for performance-focused changes

- **ci:** CI/CD changes
  - Example: `ci: update GitHub Actions workflow`
  - For pipeline and automation changes

- **build:** Build system changes
  - Example: `build: update NuGet dependencies`
  - For dependency and build configuration changes

- **chore:** Maintenance tasks
  - Example: `chore: remove unused dependencies`
  - For non-src/non-test maintenance work

- **revert:** Commit reversal
  - Example: `revert: return to version 1.2.3`
  - Include the reverted commit hash in description

#### Additional Best Practices
1. Use imperative mood in description ("add" not "added")
2. Keep description under 50 characters if possible
3. Add detailed explanation in commit body if needed
4. Reference issues/tickets where applicable

**Example of complete commit message:**

feat: add user authentication system

- Implement JWT token generation
- Add password hashing
- Create login/logout endpoints
