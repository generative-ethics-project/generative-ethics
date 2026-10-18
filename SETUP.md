# Upload and launch Generative Ethics on GitHub

V1

Use these steps to upload V1 through the GitHub website with your existing account.

## 1. Use this naming and ownership structure

| Item | Recommended value |
|---|---|
| Public project name | Generative Ethics |
| Organisation name to try | generative-ethics-project |
| Fallback organisation name | generative-ethics-research |
| Repository name | generative-ethics |
| Visibility | Public |
| Plan | GitHub Free |
| Main working branch | main, or the actual default branch if your account uses another name |
| Release title | V1 |
| Release tag | v1.0.0 |

Organisation-name availability is unverified. The repository belongs under the organisation; your login administers it. Keep personal inception credit in GENESIS.md and use community language elsewhere.

GitHub Free supports public community repositories and organisation team access. Paid plans are unnecessary for this initial setup. [GitHub plans](https://docs.github.com/en/get-started/learning-about-github/githubs-plans).

## 2. Finish account security and email settings

If not already completed, verify the account email, enable two-factor authentication under account Settings → Password and authentication, and save recovery codes outside the repository. [GitHub two-factor setup](https://docs.github.com/en/authentication/securing-your-account-with-two-factor-authentication-2fa/configuring-two-factor-authentication).

For email privacy, use account Settings → Emails → Keep my email addresses private. Web commits then use the GitHub no-reply address. GitHub still attributes contributions to the account making them; a community organisation does not make commit history anonymous. [Commit email settings](https://docs.github.com/en/account-and-profile/how-tos/email-preferences/setting-your-commit-email-address).

## 3. Create a free organisation

From your profile picture, choose Settings → Organizations → New organization. Choose GitHub Free, enter the available organisation name and the existing project contact email, and complete the prompts. Set its display name to Generative Ethics.

Use the community profile text in [INTRODUCTION.md](INTRODUCTION.md). Skip invitations until you know which collaborators need access. [Create an organisation](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/creating-a-new-organization-from-scratch).

If you already created the repository under your login, you can keep working there and transfer it later. The granular role recommendations below assume an organisation-owned repository.

## 4. Prepare the supplied files on your Mac

Use the supplied `generative-ethics-v1.zip`. It contains the complete V1 materials.

Double-click it to extract, then open the extracted `generative-ethics` folder. In Finder press Command + Shift + . to show hidden items. You need both `.github` and `.gitignore` as well as the visible documents and folders.

Upload the contents of this extracted folder, so README.md is at the repository root. Keep scratch work, credentials, and private correspondence off GitHub.

## 5. Create the repository

Open [GitHub's new repository form](https://github.com/new).

Set Owner to your new organisation and Repository name to `generative-ethics`. Paste this description:

> Community inquiry into intelligence and compassion: AI-authored ethical logic, deliberation, and open research.

Choose Public. Leave automatic README, .gitignore, and licence additions off: the package supplies the first two and the licence decision is addressed below. Click Create repository. [Repository creation](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository).

If you prefer to review the upload privately first, create it private and make it public when ready; the free public-repository branch protections below apply after that change.

## 6. Upload the package

On an empty repository, choose the link for uploading an existing file. If files are already present, use Add file → Upload files. Drag the extracted folder's contents into the upload area.

Review the uploaded paths. Use `Publish Generative Ethics V1` as the commit message, then commit the initial upload to the default branch. This bootstrap upload precedes branch protection. Use proposed branches and pull requests for later changes. [GitHub file uploads](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository).

Confirm this structure, with other supplied documents alongside it:

```text
README.md
GENESIS.md
TENETS.md
BOOK_OF_EMERGENCE.md
INVITATION.md
COLLABORATION.md
AGENTS.md
AGENT_WORK.md
.gitignore
.github/
  ISSUE_TEMPLATE/
    exploration.yml
    research.yml
    core-amendment.yml
    config.yml
  pull_request_template.md
research/
  README.md
  BOARD.md
templates/
  CONTRIBUTION.md
  EXPLORATION_SEED.md
  RESEARCH_STRAND.md
contributions/
  README.md
```

If everything is inside an extra `generative-ethics/` directory on GitHub, correct the upload so README.md is at the top level. If a hidden item is missing, show hidden files and upload it separately. Another option is Add file → Create new file, entering the full path such as `.github/ISSUE_TEMPLATE/exploration.yml`, and copying that file's supplied content. `/` creates folder levels. [Create files and paths](https://docs.github.com/en/repositories/working-with-files/managing-files/creating-new-files).

## 7. Set up the public landing page and discussion

In the repository's About area, use the description above. Suggested topics are `ai-ethics`, `machine-ethics`, `philosophy`, `ai-agents`, `collective-intelligence`, and `open-research`.

Under Settings → General → Features, keep Issues and Pull requests enabled. Keep pull request access open to public contributors; do not choose Collaborators only. Leave Wiki off initially so the book and research documents remain the shared text. [Pull request access](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/enabling-features-for-your-repository/disabling-pull-requests).

Use Set up discussions in Features. Create a welcome discussion titled `Start here: exploring and authoring ethical logic`, using the Post section of INTRODUCTION.md and adding the real repository URL. Pin it. Suggested categories are Exploration leads, Ethical logic, Mathematical language, Critique and counterexamples, and Governance. [Discussions setup](https://docs.github.com/en/discussions/quickstart).

Public contributors with GitHub accounts can propose changes through their own forks and pull requests without receiving direct editing access to your repository. [Fork workflow](https://docs.github.com/en/pull-requests/how-tos/work-with-forks/fork-a-repo?tool=webui).

## 8. Choose the prose reuse licence

Repository access and copyright reuse are different permissions. Recommended for original research prose: consider CC BY 4.0 if you want sharing and adaptation, including commercial reuse, with attribution and changes identified. These granted freedoms cannot be revoked while users comply. [Official CC BY 4.0 terms summary](https://creativecommons.org/licenses/by/4.0/).

No licence has been adopted by the supplied files. If you decide on that choice, create a root `LICENSE.md` through Add file → Create new file and adopt an appropriate notice referencing the [full legal code](https://creativecommons.org/licenses/by/4.0/legalcode.en). A proposed notice to review is:

```text
Except where otherwise stated, original prose contributed under this
notice is licensed under Creative Commons Attribution 4.0 International:
https://creativecommons.org/licenses/by/4.0/legalcode.en

Requested project attribution: Generative Ethics contributors, with a
link to this repository. Preserve additional attribution required for
individual contributions and third-party material, and identify changes.

Third-party material retains its own terms. This notice does not license
software; any software added later must state its own applicable licence.
```

Update CONTRIBUTING.md to say that contributions are submitted under the adopted licence, and add the adopted licence and its link to README.md. Apply a grant only to material you have authority to license. Individual contributors can use the attribution they choose; the project's inception remains confined to GENESIS.md.

## 9. Give people appropriate permissions

At organisation Settings → Member privileges, set Base permissions to None, then grant repository roles explicitly. Public visibility still allows public reading; this does not give general editing access. [Organisation base permissions](https://docs.github.com/en/organizations/managing-user-access-to-your-organizations-repositories/managing-repository-roles/setting-base-permissions-for-an-organization).

| Participant | Starting access |
|---|---|
| General public | Public viewing and contribution through issues, discussions, and forks; no special invitation |
| Community moderator | Triage |
| Trusted active author | Write |
| Established project maintainer | Maintain |
| Account/repository administration | Admin or organisation Owner, reserved for those duties |
| Research agent at first | Read public material and prepare contributions through a controlled integration |

These are recommendations using GitHub's organisation roles. Write can change repository content and merge permitted pull requests. Maintain supports project management; Admin includes sensitive settings and destructive actions. [Role capabilities](https://docs.github.com/en/organizations/managing-user-access-to-your-organizations-repositories/managing-repository-roles/repository-roles-for-an-organization).

To invite a trusted collaborator, use repository Settings and its access-management area, then select the intended role. Keep access explicit and review it as responsibilities change. [Managing outside collaborators](https://docs.github.com/en/organizations/managing-user-access-to-your-organizations-repositories/managing-outside-collaborators/adding-outside-collaborators-to-repositories-in-your-organization).

## 10. Protect the shared main branch

Do this after the initial upload. Confirm the actual default branch name in the Code tab; use it below if it differs from `main`.

Go to Settings → Branches → Add classic branch protection rule. Set Branch name pattern to `main`. Turn on Require a pull request before merging and Require conversation resolution before merging. Leave Allow force pushes, Allow deletions, and Lock branch off. Save the rule. [Create a protection rule](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/managing-a-branch-protection-rule).

While you are the only active maintainer, leave Require approvals off. With another trusted reviewer who has Write or higher access available, require one approval and enable dismissal of stale approvals after changes. Do not require checks before checks exist. Optional Do not allow bypassing the above settings applies the workflow to administrators too. Public repositories have branch protection on GitHub Free. [Protection behaviour and reviews](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/about-protected-branches).

For substantial core amendments, seek the additional reasoned reviews described in COLLABORATION.md. A technical merge gate and a philosophical judgement are different things.

## 11. Begin with a few bounded research tasks

Open Issues → New issue. Confirm that the three supplied choices appear: Exploration lead, Research contribution, and Core amendment. They depend on the files being under `.github/ISSUE_TEMPLATE/` on the default branch.

Suggested first tasks, using research/BOARD.md:

- W0: explore candidate ethical routes and author one argument.
- W6: propose a mathematical vocabulary with explicit meanings and premises.
- W2: examine the proposed requirement for fresh information and integrity.

Contributors can offer intuitive leads before a formal argument exists. Maintain the board or link it to the actual issues as people take work. Use short-lived editing branches such as `research/w6-ethical-language`; continuing research strands are tracked in the shared documents. Subsequent changes go through pull requests and community review.

## 12. Keep automation separate from the upload

The package contains no executable workflows. Initially, repository Settings → Actions → General can be set to Disable actions and saved. This leaves the research documents, issue forms, and discussions available. Enable automation when a defined workflow needs it. [GitHub Actions settings](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/enabling-features-for-your-repository/managing-github-actions-settings-for-a-repository).

A GitHub repository stores and coordinates the work; it does not itself start researching agents. You do not need a personal access token for browser upload. For a later organisation integration, GitHub recommends a GitHub App. If using a temporary fine-grained token, restrict it to the target repository, necessary permissions, and a limited lifetime. Fine-grained tokens have feature and collaboration limitations; choose the integration for the actual workflow. [GitHub authentication guidance](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens).

Before giving an automated author write access, enable required approval by another trusted reviewer. A future authoring integration may need Contents and Pull requests write access; posting tasks or discussions needs the corresponding specific permissions. Reading, writing, reviewing, merging, and administration should be separate responsibilities. Authorise the actual account, repository, actions, and publishing scope before enabling it; keep credentials outside research files.

## 13. Final launch check

Confirm that README renders at the top level, the book and research links open, hidden files are present, issue forms appear, and Discussions is usable. Include the real repository URL when publishing the introduction.

Check the initial commit before setting protection. Once the public content and licence are settled, open Releases → Draft a new release. Create tag `v1.0.0`, target the default branch, and use title `V1`. Add a brief description of the included research materials, then Publish release when ready or Save draft. [GitHub release instructions](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository).

The target result is a public community repository, a visible invitation, bounded research tasks, controlled editing access, and an inspectable path for AI and human contributions. Live agent operation is the next implementation task, separate from this upload.
