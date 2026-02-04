# Submission Guidelines for Student Contributions

## Overview

This document provides detailed instructions for students preparing and submitting their research contributions to the knowledge management repository. Strict adherence to these guidelines is required for acceptance of submissions.

## Directory Structure Requirements

### Student Folder Organization

Each student must create a personal directory within the `/submissions` folder following this exact structure:

```
submissions/unitXYZ
└── lastname-firstname/
    ├── research-paper.md
    ├── references.md
    └── supplementary/
        └── [optional supporting materials]
```

### Naming Conventions

1. **Student Folder Name**:
   - Format: `lastname-firstname` (all lowercase)
   - Use hyphens to separate names
   - No spaces, special characters, or accents
   - Example: `garcia-maria`, `smith-john`

2. **Required File**: `research-paper.md`
   - This is the primary submission document
   - Must be in Markdown format (.md extension)
   - Must follow the structure outlined in this document

3. **References File**: `references.md`
   - Separate document containing all bibliographic references
   - Must use consistent citation format (IEEE, APA, or ACM)
   - Alphabetically ordered by author surname

4. **Supplementary Materials** (optional):
   - Place in `supplementary/` subdirectory
   - May include diagrams, charts, tables, or additional documentation
   - Must be referenced from the main research paper
   - Acceptable formats: PNG, JPG, SVG, PDF (for figures)

---

## Research Paper Structure

The `research-paper.md` file must conform to the following structure:

### 1. Front Matter

```markdown
---
title: "Complete Title of Research Paper"
author: "Student Full Name"
student_id: "Your Student ID"
date: "YYYY-MM-DD"
topic_area: "Primary Topic from Syllabus Alignment"
keywords: ["keyword1", "keyword2", "keyword3"]
---
```

### 2. Abstract

- **Length**: 150-250 words
- **Content**: Concise summary of research question, methodology, key findings, and conclusions
- **Style**: Single paragraph, past tense for completed work
- **Purpose**: Enable readers to quickly determine paper's relevance

### 3. Introduction

- **Subsections**:
  - Background and Context
  - Problem Statement or Research Question
  - Objectives
  - Scope and Limitations
  - Paper Organization

- **Length**: Approximately 500-750 words
- **Purpose**: Establish the significance of the topic and frame the research

### 4. Literature Review

- **Content**: Synthesis of existing research and technical literature
- **Requirements**:
  - Minimum 10 credible sources (peer-reviewed articles, conference papers, technical standards, authoritative books)
  - Critical analysis, not merely summary
  - Identification of research gaps or areas of controversy
  - Proper in-text citations

- **Length**: Approximately 1000-1500 words

### 5. Methodology (if applicable)

For research involving experiments, implementations, or systematic analysis:

- Research design or approach
- Data collection methods
- Analysis techniques
- Tools and technologies used
- Validation procedures

### 6. Main Body / Discussion

- **Content**: Detailed exposition of your topic
- **Organization**: 
  - Logical flow with clear section headings
  - Each major point in separate subsection
  - Use of figures, tables, and examples where appropriate

- **Requirements**:
  - Demonstrate deep understanding of topic
  - Connect theory to practice
  - Analyze strengths, weaknesses, opportunities, and challenges
  - Support claims with evidence from credible sources

- **Length**: Approximately 2000-3000 words

### 7. Critical Analysis or Case Study (if applicable)

- Evaluation of specific implementation, technology, or methodology
- Comparative analysis of alternative approaches
- Lessons learned or best practices identified

### 8. Conclusion

- **Content**:
  - Summary of key findings
  - Implications for practice or future research
  - Recommendations
  - Limitations of current work
  - Future research directions

- **Length**: Approximately 300-500 words

### 9. Acknowledgments (optional)

- Recognition of guidance from instructors, peers, or collaborators
- Disclosure of AI tool usage (required if applicable - see academic-integrity-ai.md)

---

## Formatting Requirements

### Markdown Formatting

1. **Headings**:
   - Use hierarchical heading structure (# for title, ## for sections, ### for subsections)
   - Maintain consistent heading levels
   - Use descriptive, concise headings

2. **Text Formatting**:
   - Use `**bold**` for emphasis sparingly
   - Use `*italics*` for technical terms, book titles, or emphasis
   - Use `code` for inline code, commands, or technical terminology
   - Use code blocks with language specification for longer code examples

3. **Lists**:
   - Use numbered lists for sequential steps or ordered items
   - Use bullet points for unordered items
   - Maintain consistent indentation for nested lists

4. **Tables**:
   - Use Markdown table syntax for tabular data
   - Include descriptive headers
   - Provide table captions

5. **Figures and Images**:
   - Store images in `supplementary/` directory
   - Use relative paths: `![Figure 1: Caption](./supplementary/figure1.png)`
   - Provide descriptive alt text and captions
   - Number figures sequentially

### Citation Format

**In-text Citations:**

Choose one format and use it consistently throughout your paper:

- **IEEE Style**: Use numbered citations [1], [2], etc.
- **APA Style**: Use author-date format (Smith, 2023)
- **ACM Style**: Use numbered citations [1], [2], etc.

**Reference List:**

- Must be comprehensive and accurate
- Include all cited works
- Follow chosen citation style consistently
- Verify all URLs are accessible
- Include DOI numbers when available

---

## Content Requirements

### Academic Rigor

1. **Source Quality**:
   - Prioritize peer-reviewed academic publications
   - Use recent sources (prefer last 5 years for rapidly evolving topics)
   - Verify credibility of online sources
   - Include seminal works for historical context

2. **Depth of Analysis**:
   - Go beyond surface-level description
   - Demonstrate critical thinking
   - Synthesize information from multiple sources
   - Present balanced perspective on controversial topics

3. **Original Contribution**:
   - While this is a review/analysis paper, demonstrate original thinking
   - Provide unique synthesis or perspective
   - Connect concepts in novel ways
   - Draw meaningful conclusions

### Language and Style

1. **Formal Academic Writing**:
   - Use third person perspective (avoid "I" and "we" unless describing your own research)
   - Employ precise, technical language
   - Avoid colloquialisms and informal expressions
   - Use complete sentences and proper grammar

2. **Clarity and Precision**:
   - Define technical terms on first use
   - Use consistent terminology throughout
   - Avoid ambiguous pronouns
   - Keep sentences clear and concise

3. **Objectivity**:
   - Present evidence-based arguments
   - Acknowledge limitations and alternative viewpoints
   - Avoid unsupported opinions or bias
   - Distinguish facts from interpretations

---

## Length Requirements

- **Minimum Total Length**: 3,500 words (excluding references and front matter)
- **Maximum Total Length**: 6,000 words
- **Abstract**: 150-250 words
- **References**: Minimum 10 sources

Word count should reflect substantive content, not filler or redundancy.

---

## Prohibited Content

The following are explicitly prohibited in all submissions:

1. **Executable Code**: 
   - No programming code intended for execution
   - Pseudocode is acceptable for algorithm explanation
   - Code snippets used for illustration must be clearly marked as examples

2. **Plagiarism**:
   - Unattributed copying of text, ideas, or figures
   - Self-plagiarism from previous work without disclosure
   - Paraphrasing without citation

3. **Non-Academic Sources as Primary References**:
   - Wikipedia or similar crowd-sourced encyclopedias
   - Personal blogs without established authority
   - Marketing materials or vendor white papers (except as primary sources for case studies)

4. **Inappropriate Content**:
   - Discriminatory or offensive material
   - Confidential or proprietary information
   - Copyrighted material used without permission

---

## Submission Checklist

Before submitting your pull request, verify that you have:

- [ ] Created properly named student folder in `/submissions` directory
- [ ] Included `research-paper.md` with all required sections
- [ ] Included `references.md` with properly formatted citations
- [ ] Verified all internal links and image references work correctly
- [ ] Checked spelling, grammar, and punctuation
- [ ] Ensured all sources are properly cited
- [ ] Completed academic integrity declaration (see academic-integrity-ai.md)
- [ ] Followed pull request submission process outlined in README.md
- [ ] Met minimum word count requirement (3,500 words)
- [ ] Included minimum 10 credible references
- [ ] Used formal academic writing style throughout
- [ ] Verified no executable code is included
- [ ] Confirmed alignment with syllabus topics (see syllabus-alignment.md)

---

## Review and Revision Process

### Initial Submission Review

Submissions will be evaluated based on:
1. Compliance with structural and formatting requirements
2. Academic writing quality
3. Depth and rigor of research
4. Proper citation and referencing
5. Alignment with course objectives

### Feedback and Revisions

- Reviewers will provide specific, actionable feedback through pull request comments
- Students must address all requested revisions
- Multiple revision cycles may be required
- Updated submissions should include response to reviewer comments

### Acceptance Criteria

Papers will be accepted when they:
- Meet all technical requirements
- Demonstrate appropriate academic rigor
- Show satisfactory response to reviewer feedback
- Achieve minimum score on assessment rubric (see assessment-rubric.md)

---

## Support and Resources

### Writing Resources

- University writing center consultations
- Academic writing guides and tutorials
- Citation management tools (Zotero, Mendeley, EndNote)
- Grammar and style checking tools

### Technical Resources

- Markdown syntax guides and editors
- Git and GitHub tutorials
- GitHub Markdown preview feature
- Template files and examples (in `/submissions/README.md`)

### Getting Help

If you encounter difficulties:
1. Consult this document and related repository documentation
2. Review example submissions (if available)
3. Attend office hours or TA sessions
4. Open an issue in the repository with specific questions
5. Contact course instructor via official communication channels

---

## Important Notes

- **Late Submissions**: Subject to penalties outlined in assessment-rubric.md
- **Incomplete Submissions**: Will not be reviewed until all requirements are met
- **Academic Integrity Violations**: Will result in serious consequences as outlined in university policy
- **Technical Issues**: Report immediately; document with screenshots or error messages

By following these guidelines carefully, you will ensure your submission is properly formatted and ready for academic review.
