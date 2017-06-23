# Pull Request Template

Every time a developer will make a pull request and a team-mate will review the work, the below points need to be checked !

## Reviewee

- [ ] PR Title = Ticket Title
- [ ] Ticket link:
- [ ] Visuals:

App Screenshot | UX Mock-up
 ------ | -------

- [ ] Flow code coverage:
- [ ] Logic unit tested
- [ ] Peer review
- [ ] Show live feature to reviewer
- Definition of done:
  - [ ] Android: Sony Experia SP
  - [ ] iOS: iPhone 6S iOS 10

## Reviewer

- [ ] Read and understand the ticket ("What" + "How")
- [ ] No missing logic test
- [ ] No missing flow typing
- [ ] No missing refactoring

## Important to know

[Private on Theodo blog: How to improve the code quality with code reviews](http://www.theodo.fr/blog/2017/02/wip-how-to-improve-the-code-quality-with-code-reviews/)

### To pay attention while coding

- Follow the code conventions of your project
- No useless rework, no code that you will have to rewrite for the next user story
- No overproduction, the code must be enough to implement the story
- No overprocessing, remove useless conditions, time consuming loops
- Use linters (or Prettier) to make sure you followed conventions
- Make sure that every unit and functional tests work
- Remove dead code, useless comments and so on

### The PR

- Be as small as possible
- Have clear and explicit commit messages
- Contain functional-working code on any commit
- Describe the steps to follow to deploy or locally test the code (dependencies to update, migrations to run, fixtures to load, cache to empty…)