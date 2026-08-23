# Exact push steps

This package is designed to be copied directly into the **root of the existing local `electronics` repository**.

## 1. Extract this ZIP

Extract `electronics_repo_ready.zip` somewhere short, for example:

`C:\electronics_ready\`

## 2. Open the existing cloned repository

In GitHub Desktop, with `varshneyrushil/electronics` selected:

**Repository → Show in Explorer**

Do **not** delete the hidden `.git` folder.

## 3. Copy the ready package into the repo

Open the extracted `electronics_repo_ready` folder.

Select **everything inside it** (`README.md`, `projects`, `images`, `reports_public`, `.gitignore`, etc.) and copy it into the root of your local `electronics` folder.

When Windows asks whether to replace existing files such as `README.md`, `CAPTIONS.md`, or the CSV indexes, choose **Replace**.

The package deliberately contains the existing public portfolio too, so unchanged files will simply remain unchanged in Git.

## 4. Check GitHub Desktop

Return to GitHub Desktop.

You should mainly see:

- new `projects/` files;
- new `.gitignore` and `.gitattributes`;
- an updated `README.md`;
- the new motor-driver-interface image;
- small index/caption updates.

You should **not** see `.git` being added or deleted.

## 5. Commit

Use:

**Summary**

`Add PCB source projects and organize electronics portfolio`

**Description**

`Add recovered PCB/CAD source, manufacturing files and project documentation for Mars Rover Manipal and early electronics projects; update portfolio navigation and provenance notes.`

Click **Commit to main**.

## 6. Push

Click **Push origin**.

## 7. Verify on GitHub

Open the repository page and check:

- the README images render;
- `projects/mars-rover-manipal/` opens correctly;
- the STM32 and motor-driver-interface project links work;
- PDFs under `reports_public/` still open;
- no professional/private files are present.

## 8. Do not upload the holdback package

A separate `electronics_repo_holdback_review.zip` is for your local review only. It contains material that should not be public by default.
