# Student Submissions Directory

## Overview

This directory contains individual student research paper submissions for the knowledge management repository course. Each student maintains their own subdirectory with their research paper and supporting materials.

---

## Directory Structure

```
submissions/
├── README.md (this file)
├── Unit1
├──--- lastname-firstname/
│     ├── research-paper.md
│     ├── references.md
│     └── supplementary/
│         └── [figures, diagrams, etc.]
└──--- [additional student directories...]
```

---

## Quick Start for Students

### Step 1: Create Your Directory

Create a new directory following the naming convention:

```bash
mkdir lastname-firstname
cd lastname-firstname
```

**Important**: Use your actual last name and first name in lowercase, separated by a hyphen.

### Step 2: Create Required Files

Create the two required files in your directory:

1. **research-paper.md**: Your main research paper
2. **references.md**: Your bibliography

### Step 3: Use the Template

Start with the following template for your `research-paper.md`:

```markdown
---
title: "Your Research Paper Title"
author: "Your Full Name"
student_id: "Your Student ID"
date: "YYYY-MM-DD"
topic_area: "Topic from Syllabus Alignment"
keywords: ["keyword1", "keyword2", "keyword3"]
---

# Your Research Paper Title

## Abstract

[150-250 word summary of your research]

## 1. Introduction

### 1.1 Background and Context

[Provide context for your research topic]

### 1.2 Problem Statement

[Clearly state the problem or research question]

### 1.3 Objectives

[List your research objectives]

### 1.4 Scope and Limitations

[Define what is and is not covered]

### 1.5 Paper Organization

[Outline the structure of your paper]

## 2. Literature Review

[Comprehensive review of existing research and literature]

## 3. Methodology (if applicable)

[Describe your research approach, methods, or analytical framework]

## 4. [Main Content Sections]

[Detailed exposition of your topic with appropriate subsections]

## 5. Analysis and Discussion

[Critical analysis and discussion of findings]

## 6. Conclusion

[Summary, implications, and future research directions]

## Acknowledgments

[Include AI usage declaration here if applicable]

---

**Word Count**: [Your word count]
```

### Step 4: Create References File

Template for `references.md`:

```markdown
# References

## Bibliography

[List all your references in your chosen citation format - IEEE, APA, or ACM]

### Example Entries

**IEEE Format**:
[1] A. Author, "Title of article," *Journal Name*, vol. X, no. Y, pp. ZZZ-ZZZ, Month Year.

**APA Format**:
Author, A. A. (Year). Title of article. *Journal Name*, Volume(Issue), pages. DOI

**ACM Format**:
Author Name. Year. Title of article. *Journal Name* Volume, Issue (Month Year), pages. DOI
```

---

## Submission Workflow

### 1. Fork and Clone Repository

```bash
# Fork the repository on GitHub
# Clone your fork locally
git clone https://github.com/YOUR-USERNAME/conocimiento.git
cd conocimiento
```

### 2. Create Feature Branch

```bash
git checkout -b your-name/your-topic
```

### 3. Create Your Directory and Files

```bash
cd submissions
mkdir lastname-firstname
cd lastname-firstname
# Create your research-paper.md and references.md files
```

### 4. Work on Your Research Paper

- Write incrementally
- Commit frequently with meaningful messages
- Push your changes regularly to your fork

```bash
git add .
git commit -m "Add research paper on [topic]"
git push origin your-name/your-topic
```

### 5. Submit Pull Request

When ready for review:

1. Go to the original repository on GitHub
2. Click "New Pull Request"
3. Select your branch
4. Fill out the PR template with:
   - Research topic summary
   - Syllabus alignment reference
   - Submission guidelines compliance confirmation
   - Academic integrity declaration

---

## File Naming Conventions

### Student Directory Name
- **Format**: `lastname-firstname`
- **Rules**: All lowercase, no spaces, use hyphens
- **Examples**:
  - `garcia-maria`
  - `smith-john`
  - `rodriguez-carlos`

### Required Files
- `research-paper.md` (exact name, all lowercase)
- `references.md` (exact name, all lowercase)

### Supplementary Materials
- Store in `supplementary/` subdirectory
- Use descriptive names: `figure1-architecture.png`, `table1-comparison.pdf`
- Keep file sizes reasonable (< 5MB per file)

---

## Content Requirements Summary

### Research Paper

**Minimum Requirements**:
- 3,500 words minimum (excluding references)
- At least 10 credible academic sources
- All required sections (see template above)
- Proper citations throughout
- Formal academic writing style
- No executable code

**Quality Standards**:
- Original analysis and synthesis
- Critical thinking demonstrated
- Clear, well-organized structure
- Professional presentation
- Proper grammar and spelling

### References

**Requirements**:
- Consistent citation format (IEEE, APA, or ACM)
- Complete bibliographic information
- Alphabetically ordered
- All in-text citations included
- URLs verified and accessible
- DOI numbers included when available

---

## Common Mistakes to Avoid

1. **Incorrect Directory Name**:
   - ❌ `Maria Garcia` (has space)
   - ❌ `García-Maria` (has accent)
   - ✅ `garcia-maria` (correct)

2. **Missing Required Files**:
   - ❌ Only `research-paper.md` without `references.md`
   - ✅ Both files present

3. **Incorrect File Names**:
   - ❌ `Research-Paper.md` (wrong capitalization)
   - ❌ `my_research.md` (wrong name)
   - ✅ `research-paper.md` (correct)

4. **Content Issues**:
   - ❌ Under 3,500 words
   - ❌ Fewer than 10 sources
   - ❌ Missing abstract or conclusion
   - ❌ No citations in text
   - ❌ Including executable code

5. **Citation Problems**:
   - ❌ Inconsistent citation format
   - ❌ Missing citations for paraphrased content
   - ❌ Wikipedia as primary source
   - ❌ Broken or unverified URLs

---

## Getting Help

### Before You Submit

Review the following documents carefully:
1. `/submission-guidelines.md` - Complete formatting and content requirements
2. `/assessment-rubric.md` - Grading criteria and expectations
3. `/syllabus-alignment.md` - Topic selection and learning outcomes
4. `/academic-integrity-ai.md` - Academic integrity and AI usage policies

### During Development

- Attend office hours with questions
- Use writing center resources for academic writing help
- Consult library services for research and citation assistance
- Review example submissions (if available)

### Technical Issues

If you encounter Git/GitHub issues:
1. Check GitHub's documentation and guides
2. Ask for help during TA sessions
3. Open an issue in the repository (for non-urgent questions)
4. Contact instructor for urgent technical problems

---

## Peer Review Guidelines

Students may be asked to review peer submissions. When reviewing:

1. **Be Constructive**: Provide helpful, specific feedback
2. **Be Respectful**: Maintain professional tone
3. **Be Specific**: Reference particular sections or issues
4. **Be Thorough**: Review all aspects using the rubric
5. **Be Timely**: Complete reviews within assigned timeframe

### Review Focus Areas

- Clarity and organization
- Depth of research and analysis
- Citation accuracy and completeness
- Writing quality and grammar
- Adherence to submission guidelines

---

## Examples and Templates

### Supplementary Directory Structure

```
lastname-firstname/
├── research-paper.md
├── references.md
└── supplementary/
    ├── figure1-system-architecture.png
    ├── figure2-performance-comparison.png
    ├── table1-feature-matrix.pdf
    └── appendix-survey-results.md
```

### Sample Section: Citing Figures

```markdown
## 4. System Architecture

The proposed architecture consists of three main layers as illustrated in Figure 1.

![Figure 1: Three-tier system architecture](./supplementary/figure1-system-architecture.png)
*Figure 1: Three-tier system architecture showing presentation, business logic, and data layers*

As shown in Figure 1, the presentation layer handles all user interactions...
```

### Sample In-Text Citation

**IEEE Style**:
```markdown
Recent studies have shown significant improvements in performance [1], [2]. 
According to Smith et al. [3], this approach reduces latency by up to 40%.
```

**APA Style**:
```markdown
Recent studies have shown significant improvements in performance (Johnson, 2023; Lee & Wang, 2024).
According to Smith et al. (2023), this approach reduces latency by up to 40%.
```

---

## Quality Checklist

Before submitting your pull request, verify:

- [ ] Directory name follows `lastname-firstname` format
- [ ] Both `research-paper.md` and `references.md` files exist
- [ ] Front matter is complete and accurate
- [ ] All required sections are present
- [ ] Word count meets minimum requirement (3,500+ words)
- [ ] At least 10 credible sources cited
- [ ] All sources are cited in text and listed in references
- [ ] Citation format is consistent throughout
- [ ] No grammatical or spelling errors
- [ ] Formal academic tone maintained
- [ ] No executable code included
- [ ] All figures/tables have captions and are referenced in text
- [ ] AI usage declaration included (if applicable)
- [ ] Files use relative paths for any internal links
- [ ] All external links are verified and working

---

## Frequently Asked Questions

**Q: Can I submit work in progress for early feedback?**
A: Yes! Open a draft pull request and request early feedback. Mark it as "WIP" or "Draft" in the title.

**Q: What if my topic isn't explicitly listed in syllabus-alignment.md?**
A: Schedule a consultation with the instructor to discuss topic approval before beginning work.

**Q: Can I include code examples?**
A: Small code snippets for illustration are acceptable, but no executable programs. Use pseudocode when possible.

**Q: How should I cite software or tools?**
A: Follow your chosen citation format's guidelines for software citation, including version numbers and URLs.

**Q: Can I update my submission after it's merged?**
A: Yes, you can submit improvement PRs to your own directory to refine your work.

**Q: What if I find an error after submission?**
A: Submit corrections as quickly as possible via pull request comments or a new PR.

---

## Important Dates and Deadlines

Refer to the course syllabus and official announcements for:
- Topic selection deadline
- Draft submission dates (if applicable)
- Final submission deadline
- Peer review assignment dates
- Revision deadlines

---

## Academic Integrity Reminder

All submissions must:
- Represent your original individual work
- Properly cite all sources
- Disclose AI tool usage appropriately
- Adhere to academic honesty standards

Violations will result in serious academic consequences. See `/academic-integrity-ai.md` for complete policy.

---

## Success Tips

1. **Start Early**: Give yourself time for thorough research and writing
2. **Choose Wisely**: Select a topic you're genuinely interested in
3. **Research Deeply**: Go beyond surface-level sources
4. **Write Iteratively**: Draft, revise, refine multiple times
5. **Seek Feedback**: Use office hours and writing center resources
6. **Proofread Carefully**: Check grammar, spelling, citations
7. **Test Your Links**: Verify all internal and external links work
8. **Review Rubric**: Understand how you'll be evaluated
9. **Follow Guidelines**: Adherence to format requirements matters
10. **Ask Questions**: Better to clarify than to guess incorrectly

---

Good luck with your research and writing! We look forward to your contributions to the knowledge base.
