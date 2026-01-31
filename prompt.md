Can you make a microservice using Go as described in the jira_ticket.md file.

# Rules for development
- Please run code quality checks after every change. If any of the commands fail, fix the problem before continuing on with the next task
  - `go fmt`
  - `go test`
  - `go vet`
  - `staticcheck`
- I want the code to be created following a test driven development process to build it. Write the test first, write the minimal amount of code to make it pass (even if it seems silly), then refactor.
  - Please follow TDD for every section of code created, this goes for every function all the way to every package
- The go code should be idiomatic and if it's not explain your reasoning in a comment
  - Check if the code is idiomatic before submitting your answer
