> 📘 This note is part of my personal learning journal while reading *Software Engineering for Data Scientists*.
> Some sentences are quoted directly from the book for educational purposes only.  
> All rights belong to the original author and publisher.


## Key point:

### 1. Deploying Code - CI/CD

#### Continuous Integration

When a codebase is committed to version control,
- **Build** the project
- Run the **tests**
- Checks that everything works
- Alert developers to fix if an issue exists

#### Continuous Delivery

After CI pipeline has run,
- Code is **ready to be deployed**
- Need a **manual final step** to review and them deploy it

#### (OR) Continuous Deployment

After all Tests pass,
- Code is automatically deployed to production

### 2. Automation Example

Important concepts:

#### A> Pre-Commit Hooks
- Automation before Commit
- A lightweight way to automate small tasks which are often done (eg. formatting, lining)

#### B> Git Actions

#### C> Cloud Deployments

- Docker container - an isolated environment with installed dependencies for running the API

#### D> Deploying an API on Google Cloud

#### E> Security Practice



---
tags: [personal-note, SE4DS, learning, non-commercial]
