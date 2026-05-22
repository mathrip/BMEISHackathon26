# Contributing to BMEIS Hackathon 2026

Thank you for your interest in participating in the BMEIS Hackathon 2026! This guide will help you submit your project proposal.

## How to Submit a Project Proposal

You can submit your project proposal in two ways:

### Option A: Via Email (Simple)

1. Download the [Project Proposal Template](projects/TEMPLATE.md)
2. Fill out all sections with your project details
3. Email the completed proposal to the organizers (konrad.wagstyl@kcl.ac.uk)

This option is fine if you're not familiar with Git/GitHub.

### Option B: Via Pull Request (Recommended for Git users)

### Step 1: Fork the Repository

1. Click the "Fork" button at the top right of this repository
2. This creates a copy of the repository under your GitHub account

### Step 2: Clone Your Fork

```bash
git clone https://github.com/YOUR-USERNAME/BMEISHackathon26.git
cd BMEISHackathon26
```

Replace `YOUR-USERNAME` with your GitHub username.

### Step 3: Create a New Branch

```bash
git checkout -b project/your-project-name
```

Replace `your-project-name` with a short name for your project.

### Step 4: Add Your Project Proposal

1. Navigate to the `projects/` folder
2. Copy the [TEMPLATE.md](projects/TEMPLATE.md) file
3. Create a new file named after your project (e.g., `projects/my-awesome-project.md`)
4. Fill out all sections of the template:
   - Project Title
   - Overview
   - Data
   - GitHub Repository

### Step 5: Commit Your Changes

```bash
git add projects/your-project-name.md
git commit -m "Add project proposal: Your Project Name"
```

### Step 6: Push to Your Fork

```bash
git push origin project/your-project-name
```

### Step 7: Create a Pull Request

1. Go to your fork on GitHub
2. Click "Compare & pull request"
3. Ensure the base repository is `KCL-BMEIS/BMEISHackathon26` and the base branch is `main`
4. Add a clear title: "Project Proposal: Your Project Name"
5. In the description, briefly summarize your project
6. Click "Create pull request"

## Questions?

If you have any questions or run into issues, please:
- Open an issue in this repository
- Email the organizers (contact details on the Eventbrite page)
- Reach out via the event page

## Code of Conduct

Please be respectful and collaborative. This hackathon is about learning, sharing ideas, and building together.
