# Commit Message Naming

Consist of two parts:
- Subject: Short informative summary of the commit
- Body: More detailed explanatory text if needed

## Subject:
- Short and descriptive (max 50 chars)
- Capitalized
- In present tense
- Not end with period

Example:
```
Implement perp orderbook worker thread 
```

## Body:
- Separated with a blank line from the subject
- Explain what, why, etc.
- Max 72 chars
- Each paragraph capitalized

Example:
```
Implement worker thread logic for submitting orders on the perpetual orderbook to reduce worker load.  

Worker thead is used to distribute tasks and reduce latency to trading engine.
```

## Conventional Commits

Commit messages may use [Conventional Commits](https://www.conventionalcommits.org/en/) format. It provides guidelines to create a better commit history log, making easier to have automated tasks around it (e.g. automated changelogs).

It is preferred not to follow this standard, but if curious, please refer to [Conventional Commits docs](https://www.conventionalcommits.org/en/) for more details.
