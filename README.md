# ci-demo

This is a demo project showcasing Continuous Integration (CI) with GitHub Actions.

## 🛠️ What’s Inside

This project includes:
- A simple `add(a, b)` function located in `src/add.js`
- A unit test using Jest in `__tests__/add.test.js`
- A GitHub Actions workflow in `.github/workflows/ci.yml` to automatically lint and test code on every push or pull request

## ✅ Modifications Made

To enhance the CI pipeline and make the build pass, the following updates were made:

- **Bug Fix:** Corrected the `add` function to properly return the sum of two numbers.
- **Branch Coverage:** Updated the workflow to trigger on all branches, not just `main`.
- **Node Version Upgrade:** Changed Node.js version from `20` to `22` in the workflow.
- **Dependency Caching:** Added caching for `node_modules` using `actions/cache@v4` to speed up builds.

## 🚀 Getting Started

### Install dependencies

```bash
npm install
