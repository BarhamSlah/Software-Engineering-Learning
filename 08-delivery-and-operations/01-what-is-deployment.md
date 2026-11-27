# What Is Deployment?

- **Phase:** 8 — Delivery and Operations
- **Status:** Needs learning

## Simple definition

**Deployment** is the process of releasing a software version to an environment where it can run and be used.

## Simple example

Your Java banking application works on your laptop. Customers cannot use it just because it runs on your computer.

A team may:
1. Prepare and build the application.
2. Configure the environment.
3. Put the application on a server or hosting platform.
4. Start it and check that it works.
5. Make it available to users.

That release process is deployment.

## Local vs. production

| Environment | Meaning |
|---|---|
| Local/development | Runs on a developer's computer |
| Test/staging | Used to check a release before real users rely on it |
| Production | The live environment used by real users or systems |

## Deployment vs. GitHub push

- **Push:** Sends commits to a remote Git repository such as GitHub.
- **Deployment:** Releases the application to an environment where it can run.

They are different actions. A team may automate deployment after changes are merged, but that is a chosen workflow, not the meaning of push itself.

## Key idea

Deployment moves a built application into an environment where it can be used. It is not simply uploading source code.