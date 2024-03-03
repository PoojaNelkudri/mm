pip install pre-commit
pre-commit install

If you're using a Linux machine, you can still install `pre-commit`, but the installation process might vary depending on your system setup and preferences. Here's how you can install `pre-commit` on a Linux machine:

1. **Using pip**:
   
   If you have Python and pip installed, you can install `pre-commit` using pip. Open a terminal and run:

   ```bash
   pip install pre-commit
   ```

   This will install `pre-commit` globally on your system.

2. **Using Package Manager**:

   Some Linux distributions provide `pre-commit` as a package in their package repositories. You can use your package manager to install it. For example:

   - On Debian/Ubuntu:

     ```bash
     sudo apt-get update
     sudo apt-get install pre-commit
     ```

   - On Fedora/RHEL/CentOS:

     ```bash
     sudo yum install pre-commit
     ```

   - On Arch Linux:

     ```bash
     sudo pacman -S pre-commit
     ```

   Use the appropriate command based on your Linux distribution.

Once `pre-commit` is installed, you can proceed with setting up the pre-commit hooks for your repositories as described earlier. Remember to run `pre-commit install` in each repository after installation to set up the hooks.
