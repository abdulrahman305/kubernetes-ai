# Pull Request Template

## Description

Please include a summary of the changes and the related issue. Please also include relevant motivation and context. List any dependencies that are required for this change.

Fixes #(issue)

## Type of change

Please delete options that are not relevant.

- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] This change requires a documentation update

## How Has This Been Tested?

Please describe the tests that you ran to verify your changes. Provide instructions so we can reproduce. Please also list any relevant details for your test configuration.

- [ ] Test A
- [ ] Test B

**Test Configuration**:
* Firmware version:
* Hardware:
* Toolchain:
* SDK:

## Checklist:

- [ ] My code follows the style guidelines of this project
- [ ] I have performed a self-review of my own code
- [ ] I have commented my code, particularly in hard-to-understand areas
- [ ] I have made corresponding changes to the documentation
- [ ] My changes generate no new warnings
- [ ] I have added tests that prove my fix is effective or that my feature works
- [ ] New and existing unit tests pass locally with my changes
- [ ] Any dependent changes have been merged and published in downstream modules

## Using `gitauto` for Pull Requests

To streamline the pull request process, we have integrated `gitauto` into our repository. Follow these steps to use `gitauto`:

1. **Install `gitauto`**:
   - Ensure that `gitauto` is installed and configured on your local machine. You can find the installation instructions in the [gitauto documentation](https://example.com/gitauto-docs).

2. **Create a Branch**:
   - Use `gitauto` to create a new branch for your feature or bug fix:
     ```sh
     gitauto branch create feature-or-bugfix-name
     ```

3. **Make Changes**:
   - Make your changes in the new branch.

4. **Commit and Push**:
   - Use `gitauto` to commit your changes and push the branch to your forked repository:
     ```sh
     gitauto commit -m "Description of your changes"
     gitauto push
     ```

5. **Submit a Pull Request**:
   - Use `gitauto` to submit a pull request:
     ```sh
     gitauto pull-request create
     ```

6. **Review Process**:
   - Your pull request will be reviewed by the maintainers. Please address any feedback and make necessary changes.

7. **Merge**:
   - Once approved, your changes will be merged into the main branch.
