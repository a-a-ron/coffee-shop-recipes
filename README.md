# Pluralsight Course: Git Fundamentals

## Course Resources

### Steve's coffee shop recipe project

You can download the following zipped folder to have Steve's coffee shop recipes at the beginning. Use this project to following along in the course.
  - [coffee-shop-recipes.zip](https://github.com/a-a-ron/coffee-shop-recipes/files/10885432/coffee-shop-recipes.zip)

### Bash script for "How to Modify and Fix Your Commits" 

Use the following script to generage the 6 files to follow along with `git amend`, `git reset`, and `git reflog`. 

```bash
for d in {1..6}; do touch "file${d}.md"; git add "file${d}.md"; git commit -m "adding file ${d}"; done
```

If you need one for powershell, you can use the following;

```powershell
for ($d=1; $d -le 6; $d++) { Out-File file$d.md; git add file$d.md; git commit -m "adding file$d.md"; }
```

## Next Steps

### Customizing your terminal or command prompt

There are a lot of options out there, and it depends on what you decide to use and what operating system you're using.

**Windows**
- https://learn.microsoft.com/en-us/windows/terminal/tutorials/custom-prompt-setup

**Mac**
- https://medium.com/@charlesdobson/how-to-customize-your-macos-terminal-7cce5823006e
- https://www.makeuseof.com/customize-zsh-prompt-macos-terminal/

### Visualizing Git

![Screen Shot 2023-03-12 at 9 18 43 PM](https://user-images.githubusercontent.com/6351798/224600449-7fd00cf2-4667-4358-9f7d-8165892161bf.png)


Here is a linked to my forked repository that you can use as a sandbox environment to visualize git commands.
- https://a-a-ron.github.io/visualizing-git/

### Git's official documentation

![Screen Shot 2023-03-12 at 9 18 06 PM](https://user-images.githubusercontent.com/6351798/224600467-6cb766c3-5a35-4760-b079-6de1b84e1036.png)

- https://git-scm.com/
