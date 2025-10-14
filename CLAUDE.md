# Claude Code Guidelines for This Repository

This document provides guidelines for Claude Code when assisting with this repository to ensure Apache 2.0 license compliance and maintain proper attribution.

## Repository Context

This is a **personal fork** of the [Deep Learning for Biology](https://github.com/deep-learning-for-biology/dlfb) companion repository. It is licensed under **Apache 2.0**.

- **Original Authors**: Charles Ravarani and Natasha Latysheva
- **Original Repository**: https://github.com/deep-learning-for-biology/dlfb
- **Fork Purpose**: Working through the book, adding Chapter 1 content and learning materials

## Apache 2.0 Compliance Checklist

When making changes to this repository, ensure:

### ✅ Always Required:
- [ ] `LICENSE` file remains intact and unmodified
- [ ] All new code files include Apache 2.0 header (see template below)
- [ ] Git commits document what was changed
- [ ] Original copyright notices are preserved

### ✅ When Making Significant Additions:
- [ ] Update `NOTICE` file to list new modifications
- [ ] Update README "About This Fork" → "Changes from Original" section
- [ ] Use the commit message template below

### ✅ Periodically (Monthly or Per Chapter):
- [ ] Review `NOTICE` file for completeness
- [ ] Verify README accurately reflects all changes
- [ ] Ensure all new notebooks include proper attribution

## File Header Template

For any new Python files (`.py`) created:

```python
# Copyright 2025 Brandon Nieves
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
#
# This file is part of a fork of the Deep Learning for Biology project
# Original work: Copyright 2025 Charles Ravarani and Natasha Latysheva

```

For Jupyter notebooks (`.ipynb`), add a markdown cell at the top:

```markdown
---
**License**: Apache 2.0
**Original Work**: Deep Learning for Biology by Charles Ravarani and Natasha Latysheva
**This Fork**: Additional content by Brandon Nieves

Based on the [Deep Learning for Biology](https://github.com/deep-learning-for-biology/dlfb) repository.
---
```

## Commit Message Template

For significant changes (new chapters, major features):

```
[Type] Brief description of change

Detailed explanation of:
- What was added/changed
- Why it was added/changed
- Any notable implementation details

Modified files:
- path/to/file1.py: description
- path/to/file2.ipynb: description

🤖 Generated with [Claude Code](https://claude.com/claude-code)

Co-Authored-By: Claude <noreply@anthropic.com>
```

Types: `[chapter]`, `[feature]`, `[fix]`, `[docs]`, `[chore]`, `[env]`

## When to Update NOTICE File

Update `NOTICE` when you:
1. **Complete a new chapter** notebook
2. **Add significant new functionality** (e.g., new utilities, tools, or modules)
3. **Make architectural changes** to the repository structure
4. **Add new dependencies** or change environment setup significantly

## Development Workflow

### Starting a New Chapter:
1. Create notebook: `notebooks/chapter_X_topic.ipynb`
2. Add license header cell (see template above)
3. Work through chapter, adding code and notes
4. Commit with descriptive messages
5. When chapter complete: Update `NOTICE` and README

### Adding Utilities/Tools:
1. Add file header (see template above)
2. Document in README if significant
3. Update `NOTICE` if it's a major addition
4. Commit with clear description

### Making Environment Changes:
1. Update `.gitignore` if needed
2. Document in README if affects setup process
3. Test thoroughly
4. Commit with clear instructions

## What NOT to Do

❌ **Never** modify or remove the `LICENSE` file
❌ **Never** remove original copyright notices from existing files
❌ **Never** claim original work as your own
❌ **Never** remove attribution to Charles Ravarani and Natasha Latysheva
❌ **Never** change the license to something incompatible with Apache 2.0

## Quick Reference

**Original Repository**: https://github.com/deep-learning-for-biology/dlfb
**License**: Apache 2.0 (full text in `LICENSE`)
**Original Authors**: Charles Ravarani and Natasha Latysheva
**This Fork**: Personal learning repository by Brandon Nieves

## Questions?

When in doubt about license compliance:
1. Check the [Apache 2.0 License](http://www.apache.org/licenses/LICENSE-2.0)
2. Refer to Section 4 (Redistribution requirements)
3. Ensure attribution is clear and modifications are documented

---

**Last Updated**: January 2025
