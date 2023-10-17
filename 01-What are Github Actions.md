# Github Actions
> Workflow automation service by github. Automates all kind of repository related processes and actions.

## CI / CD (method for automating app development and deployment)

#### CI
> code changes are automatically build, test and merged with the existing code.
#### CD
> After integration, new application or package is published automatically.

Github Actions = CI/CD + Code & Repository Management(code reviews/issue management etc.).

## Key Elements

### Workflows
- Attached to a git Repository
- Contain one or more Jobs
- Triger on Events

### Jobs
- Define a runner (execution environment[Linux, Mac or Windows])
- Contain one or more steps
- Run in parallel(default) or sequential
- Can be conditional

## Steps 
- Execute a shell script or an action
- Can use custom or third party action
- Steps are executed in order
- can be conditional