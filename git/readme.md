# Commit Ettiqute

- [My commit message workflow](https://dev.to/shreyasminocha/how-i-do-my-git-commits-34d)
- [The seven rules of a great Git commit message](https://chris.beams.io/posts/git-commit/#seven-rules)

## Write better commits with a custom template

### Basic git commit template:

```
# If applied, this commit will…

# Explain why this change is being made

# Provide links to any relevant tickets, articles or other resources
```


# Custom log formatting

- [Advanced Git log](https://www.atlassian.com/git/tutorials/git-log)

Set up custom `git log` formatting with a template:

```bash
git log --pretty=format:"%Cred%h %Creset%s by %Cgreen%an" --graph --decorate --abbrev-commit
```
