# Contributing to FHE Security Handbook

Thank you for your interest in contributing to the FHE Security Handbook! This guide helps maintain the quality and accuracy of our security-focused documentation.

## Ways to Contribute

### 1. Report Issues
- **Inaccuracies**: Found outdated information or incorrect technical details? Open an issue.
- **Missing Content**: Suggest new topics, vulnerabilities, or patterns we should cover.
- **Broken Links**: Report dead links to papers, documentation, or tools.

### 2. Submit Pull Requests
- Fix typos, grammar, or formatting issues
- Update outdated references or version numbers
- Add new vulnerability patterns or secure coding examples
- Improve existing explanations or diagrams

### 3. Share Research
- Link relevant academic papers (especially from IACR ePrint)
- Document new attack vectors or mitigations
- Contribute audit findings (anonymized if needed)

## Contribution Guidelines

### Content Standards

1. **Accuracy First**: All technical claims must be verifiable
   - Cite academic papers with full references (ePrint, conference proceedings)
   - Link to official documentation, not blog posts
   - Avoid speculation; mark unconfirmed information clearly

2. **Security Focus**: This is a security handbook
   - Prioritize secure patterns over convenience
   - Include both vulnerable and secure code examples
   - Explain the "why" behind security recommendations

3. **No Hallucinations**: We maintain strict accuracy
   - Don't invent project names, tool names, or statistics
   - Verify all paper citations exist before adding
   - Use phrases like "check official sources" for rapidly changing information

### Code Examples

```solidity
// ❌ VULNERABLE: Show what NOT to do
function badPattern() { ... }

// ✅ SECURE: Show the correct approach
function goodPattern() { ... }
```

- Always pair vulnerable patterns with secure alternatives
- Include comments explaining the security impact
- Test code examples where possible

### Formatting

- Use [GitHub Flavored Markdown](https://github.github.com/gfm/)
- Use admonitions for important callouts:
  ```markdown
  > [!WARNING]
  > Critical security information here
  
  > [!NOTE]
  > Helpful context here
  ```
- Keep tables aligned and readable
- Use mermaid diagrams for architecture (technical components only)

### References

When adding citations:
```markdown
| Paper Title | Authors | Year | Significance |
|-------------|---------|------|--------------|
| [Full Title](https://eprint.iacr.org/YYYY/XXXX) | Author et al. | YYYY | Brief impact |
```

Preferred sources:
- IACR ePrint Archive
- Major conferences (CRYPTO, EUROCRYPT, CCS, USENIX Security)
- Official protocol documentation
- Peer-reviewed journals

## Pull Request Process

1. **Fork** the repository
2. **Create a branch**: `git checkout -b fix/description` or `feat/description`
3. **Make changes** following the guidelines above
4. **Test locally**: Ensure markdown renders correctly
5. **Submit PR** with a clear description of changes

### PR Checklist

- [ ] All new references verified to exist
- [ ] Code examples tested (if applicable)
- [ ] No specific bounty amounts or dates that will become outdated
- [ ] Diagrams show only technical architecture (not organizational info)
- [ ] Follows existing formatting conventions

## Review Process

1. Maintainers will review for technical accuracy
2. Security claims may require additional verification
3. Feedback will be provided in PR comments
4. Once approved, changes will be merged

## Questions?

**Contact the maintainer:**
- 𝕏 (Twitter): [@thisvishalsingh](https://x.com/thisvishalsingh)
- Telegram: [@thisvishalsingh](https://t.me/thisvishalsingh)

Or open a GitHub issue for:
- Clarification on contribution guidelines
- Discussion of proposed major changes
- Reporting security issues in the handbook itself

---

**Note**: This handbook focuses on Zama fhEVM and Fhenix CoFHE implementations. Contributions should align with this scope while remaining applicable to general FHE security principles.
