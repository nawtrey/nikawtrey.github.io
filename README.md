# Personal Website

Source files for my personal website and professional project portfolio, hosted using GitHub Pages.

The site highlights selected technical projects involving:

- scientific computing
- automation tools
- performance analysis
- workflow optimization

Live site:
https://nikawtrey.github.io

## Adding New Projects

Projects displayed on the homepage are generated automatically from files inside the `_projects/` folder using Jekyll collections.

### Steps

1. Copy an existing project file in `_projects/` (or use one as a template).
2. Rename the file using lowercase hyphenated format: `my-new-project.md`
3. Update the project fields in the front matter:

   ```yaml
   ---
   title: Project Title
   order: 10
   role: One-line role/context description
   problem: One-sentence problem statement
   solution:
   - Contribution or implementation detail
   - Contribution or implementation detail
   impact:
   - Outcome or result
   - Outcome or result
   links:
   - label: Publication
       url: https://example.com
   ---
   ```

### Field Notes

- title — Project name shown on the homepage
- order — Controls display order (smaller numbers appear first)
- role — Brief description of your role and context
- problem — Short description of the challenge solved
- solution — List of key technical contributions
- impact — List of outcomes (performance, scale, automation, etc.)
- links — Optional list of publication or repository links
