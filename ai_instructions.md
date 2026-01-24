Can you make a microservice using Go as described in the jira_ticket.md file.

# Rules for development
- I want code quality checks to be run after every change to ensure code quality. If any of the commands fail I want you to fix the problem before continuing on with the next task
  - `go fmt`
  - `go test`
  - `go vet`
- I want the code to be created following a test driven development process to build it. Write the test first, write the minimal amount of code to make it pass (even if it seems silly), then refactor.
  - This should apply for each section of code you build, from each package, all the way down to the functions
- The go code should be idiomatic and if it's not explain your reasoning in a comment
  - Check it before submitting your answer
