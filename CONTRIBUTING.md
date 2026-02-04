# Contributing to Awesome Microsoft Copilot Prompts

Thanks for considering contributing! This library succeeds because of real practitioners sharing production-tested prompts.

## 🎯 What We're Looking For

We accept prompts that meet these criteria:

### ✅ Quality Standards

1. **Production-Tested**
   - You've used this prompt in actual work (not theoretical)
   - It's solved a real business problem
   - You can describe the outcome

2. **Copilot-Specific**
   - Works specifically with Microsoft 365 Copilot
   - Not just generic AI prompts that work anywhere
   - Leverages Copilot's integration with Office apps

3. **Clear Business Value**
   - Solves a specific use case
   - Saves meaningful time or improves quality
   - Applicable to multiple users in similar roles

4. **Well-Documented**
   - Includes use case description
   - Specifies target personas
   - Notes which M365 app it's for
   - Provides context on when/how to use it

### ❌ What We Don't Accept

- Generic prompts that work with any AI ("Write me a blog post")
- Unverified or theoretical prompts
- Prompts focused on personal/consumer use cases
- Duplicates of existing prompts
- Low-effort submissions without documentation

## 📝 Submission Format

When submitting a new prompt, use this template:

```markdown
### [Prompt Name]

**Use Case:** [One-line description of the problem this solves]

**Target Personas:** [Who would use this - be specific about roles]

**Works In:** [Outlook / Excel / Word / PowerPoint / Teams / Copilot Studio]

**Tags:** `microsoft-copilot`, `[category]`, `[function]`, `[app]`

**Prompt:**

\```
[Your actual prompt text here - be specific and actionable]
\```

**Example Outcome:**
[Optional but encouraged: Show what Copilot produces with this prompt]

**Customization Tips:**
[Optional: How users can adapt this for their specific needs]

**Contributed by:** [@your-github-username](https://github.com/your-username)
```

## 🚀 How to Contribute

### Option 1: Submit an Issue (Easiest)

1. Go to [Issues](../../issues)
2. Click "New Issue"
3. Choose "Submit a Prompt"
4. Fill in the template
5. We'll review and add it to the appropriate category

### Option 2: Submit a Pull Request (Preferred)

1. **Fork this repository**

2. **Create a branch**
   ```bash
   git checkout -b add-prompt-[descriptive-name]
   ```

3. **Add your prompt** to the appropriate file:
   - Role-specific prompts → `/prompts/role-specific/[category].md`
   - Power user prompts → `/prompts/power-users/`
   - Outlook prompts → `/prompts/outlook/`

4. **Follow the format** shown in existing prompt files

5. **Update the main README.md** if you're adding a new category

6. **Commit your changes**
   ```bash
   git commit -m "Add [prompt name] for [use case]"
   ```

7. **Push to your fork**
   ```bash
   git push origin add-prompt-[descriptive-name]
   ```

8. **Open a Pull Request** with:
   - Clear description of the prompt
   - Which business problem it solves
   - How you've tested it
   - Target users

## ✅ Review Process

1. **Initial Review** (1-3 days)
   - We check if it meets quality standards
   - Verify it's Copilot-specific
   - Confirm it's not a duplicate

2. **Testing** (if needed)
   - We may test the prompt in Copilot
   - Request clarifications or adjustments

3. **Merge**
   - Once approved, we'll merge your PR
   - You'll be credited in the file and contributors list

## 🎨 Style Guidelines

### Prompt Writing

- **Be specific:** Replace generic placeholders like [THING] with concrete examples
- **Structure clearly:** Use numbered lists or bullet points for multi-part prompts
- **Add context:** Tell Copilot what you're trying to achieve
- **Define scope:** Specify timeframes, data sources, output format

**Example of a good prompt:**
```
Analyze emails from the last 30 days containing "budget review". 
Create a summary table with:
1) Date of each discussion
2) Key decisions made
3) Outstanding action items
4) Budget impact (if mentioned)
5) Responsible parties

Format as a table suitable for pasting into an executive update.
```

**Example of a weak prompt:**
```
Summarize my emails about the budget
```

### Documentation

- **Use Case:** One clear sentence describing the problem
- **Target Personas:** Specific job titles (not "anyone")
- **Prompt Text:** Use code blocks for easy copying
- **Tags:** Include relevant tags for discoverability

## 🏆 What Makes a Great Contribution

The best contributions are prompts that:

1. **Solve a recurring problem** (saves 30+ minutes weekly)
2. **Work across industries** (not hyper-specific to one company)
3. **Demonstrate Copilot's capabilities** (showcases what makes Copilot unique)
4. **Include real examples** (show actual output or use cases)

## 🤔 Not Sure If Your Prompt Qualifies?

Open an issue and describe:
- The business problem you're solving
- How you currently use the prompt
- What results you get

We'll help you refine it into a contribution!

## 📧 Questions?

- **General questions:** Open a [Discussion](../../discussions)
- **Prompt submissions:** Use [Issues](../../issues)
- **Technical problems:** Open an [Issue](../../issues)
- **Direct contact:** [LinkedIn](https://linkedin.com/in/mathieukessler) or [X/Twitter](https://x.com/nerdychefsai)

## 🙏 Thank You!

Every contribution makes this library more valuable for enterprise Copilot users worldwide. Your real-world experience helps others work smarter.

---

**Made with ❤️ by the community, for the community.**
