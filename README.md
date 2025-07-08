# Singularity-Website
Official website for Singularity at the University of Waikato!🎉🤖

### Contributing
Club members are welcome to contribute! Whether it's bug fixes, new features, or desin improvements. Please follow the steps below to get started.🤗

1. Check Existing Issues

    Go to the Issues tab and see if someone else is already working on your idea or bug.
    If not, create a new issue describing what you'd like to add or fix.
2. Fork & Clone the Repository

    ```bash
    git clone https://github.com/Amekn/Singularity-Website.git
    ```

3. Create a New Branch

    Name the branch clearly to describe the purpose of your work.
    ```bash
    git checkout -b username/feature
    ```

4. Make Your Changes

    Add, Commit, and push your code.

    ```bash
    git add .
    git commit -m "Details about the commit"
    git push origin username/feature
    ```

5. Open a Pull Request

    Navigate to the repository on GitHub and click "**Compare & pull request**"

### Staying Updated with the Main Branch

To keep your fork up to date with the original repository:

    ```bash
    git remote add upstream https://github.com/Amekn/Singularity-Website.git
    git fetch upstream
    git checkout main
    git rebase upstream/main
    ```

Resolve conflicts if needed, then:

    ```bash
    git push origin main
    ```

You can now rebase your feature branch:

    ```bash
    git checkout username/feature
    git rebase main
    ```

Then push again and GitHub will update your PR.



