# Activity 5 – Collaborative Coding with GitLens and Live Share

## Objective

The objective of this activity was to learn collaborative coding using **GitLens** and **Live Share** in Visual Studio Code.

## Tools Used

* Visual Studio Code
* GitLens
* Live Share
* Git
* GitHub
* GCC / MinGW-w64

## Activities Completed

### GitLens

* Installed the GitLens extension in VS Code.
* Viewed the commit history of the repository.
* Used GitLens blame to identify who changed each line of code.
* Viewed the history of the `hello.c` file.
* Checked commit messages, authors, and dates.

### Live Share

* Installed the Live Share extension.
* Started a Live Share collaboration session.
* Joined the session using the shared link.
* Collaboratively edited the `hello.c` program.
* Used Follow and Focus Participants features.
* Compiled and executed the program using the shared terminal.

## Code Added

A new `greet()` function was added to the Hello World program.

```c
void greet(const char *name) {
    printf("Hello, %s! Welcome to your GitHub portfolio.\n", name);
}
```

The function was called from `main()`:

```c
greet("Ada");
```

## Collaboration Log

**Pairing Partner:** Preetham K
**GitHub Username:** Preetham K

We worked together using **VS Code Live Share** to add the `greet()` function to the Hello World program. We then used **GitLens** to check the commit history and verify the changes.

### What I Learned

I learned how GitLens helps track who made changes to a file and when the changes were made. I also learned how Live Share allows multiple developers to work on the same project in real time.

## Git Commits

### Commit 1

```text
Add greet() function — paired with [Partner Name] via Live Share
```

### Commit 2

```text
Update README with collaboration log
```

## Reflection

### 1. How did GitLens help you?

GitLens helped me identify who changed specific lines of code and when the changes were made. It also helped me view the commit and file history.

### 2. Advantage and limitation of Live Share

**Advantage:** It allows two developers to edit and work on the same code in real time.

**Limitation:** A stable internet connection is required for smooth collaboration.

### 3. Why are collaborative commits valuable?

Collaborative commits demonstrate that a student can use Git and GitHub and work effectively with other developers on a shared project.
