# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is "The Bitcoin Playbook" - a book project written in AsciiDoc format that provides a digital transformation approach for companies adopting Bitcoin into their operations. The repository serves as the source for a book to be published on Amazon Kindle, with all proceeds going to Bitcoin Smiles charity.

**IMPORTANT: This book focuses exclusively on Bitcoin, not other cryptocurrencies or "crypto" in general. Maintain this Bitcoin-only focus throughout all content.**

## Project Structure

- **Main content**: Written as `.adoc` files organized in directories
- **Master document**: `book.adoc` includes all chapters in reading order
- **Content directories**:
  - `/chapters/` - Main numbered chapters (Strategic Opportunity, Risks & Controls, etc.)
  - `/casestudies/` - Company case studies (MicroStrategy, Tesla, Square Inc, Wikipedia)
  - `/appendices/` - Risk-focused appendices
  - Root directory - Introductory content (About Authors, Foreword, Introduction, etc.)
- **Supporting directories**:
  - `/images/` - Book cover and visual assets
  - `/letters/` - Template letters for employee communications
  - `/presentations/` - Presentation materials (to be added)
  - `/reference/` - Industry PDFs and whitepapers on Bitcoin, cryptocurrency accounting, and regulations

## Development Workflow

### Editing Content
- All book content uses AsciiDoc format (https://docs.asciidoctor.org/asciidoc/latest/)
- Edit `.adoc` files directly for content changes
- Maintain consistent formatting with existing chapters

### Contributing
- Submit pull requests for suggested changes
- Contributors who submit 100-200 substantial pull requests may become co-authors
- Add contributor details to the Thanks section in `introduction.adoc`

### Building/Preview
- The book can be read directly on GitHub by clicking chapter links in `README.md`
- For local preview, use an AsciiDoc processor like Asciidoctor
- **Automated PDF Generation**: GitHub Actions workflow automatically builds PDF on push to main branch
- PDF uses custom theme (`thebitcoinplaybook-theme.yml`) optimized for Amazon KDP publishing
- Build artifacts and releases are available on the GitHub repository

## Writing Tone Guidelines

When editing or creating content for The Bitcoin Playbook, maintain the following tone and style:

### Target Audience
- Board-level directors, C-suite executives, treasury teams, and corporate decision-makers
- Assume business/financial literacy but explain Bitcoin-specific concepts clearly
- Write for skeptical professionals who need evidence-based analysis

### Core Tone Principles
1. **Professional and Authoritative** - Use formal business language without being overly academic
2. **Balanced and Objective** - Present both opportunities and risks; avoid crypto evangelism
3. **Evidence-Based** - Support claims with data, statistics, and real-world examples
4. **Action-Oriented** - Focus on practical implementation and decision-making
5. **Bitcoin-Only** - This book is about Bitcoin specifically, not "crypto" or other cryptocurrencies

### Style Guidelines
- **Structure**: Use clear headers, bullet points, and tables for easy scanning
- **Examples**: Include concrete data, company case studies, and specific dollar amounts
- **Technical Depth**: Explain crypto concepts progressively - start simple, add complexity as needed
- **Risk Awareness**: Always acknowledge and address potential risks alongside opportunities
- **Historical Context**: Use analogies to familiar technologies (e.g., early internet) to build understanding
- **Audio-Friendly Writing**: Write for both reading and listening - use natural speech patterns, avoid complex nested clauses, and ensure content flows well when read aloud

### Language Patterns
- Lead with clear, declarative statements
- Use phrases like "companies should consider," "it is important to understand," "evidence suggests"
- Avoid hyperbole, speculation, or promises of guaranteed returns
- Include regulatory disclaimers where appropriate
- Maintain consistent use of "Bitcoin" (capitalized) and other technical terms
- Write conversationally but professionally - imagine explaining concepts to an executive in person
- Use shorter sentences and paragraphs that work well in audio format

### What to Avoid
- Colloquialisms or casual language
- Cryptocurrency jargon without explanation
- Promotional or "hype" language
- Personal opinions without supporting evidence
- Technical details that don't serve business decision-making
- References to altcoins, "crypto" as a general category, or other digital assets
- Comparisons with other cryptocurrencies (unless explicitly demonstrating Bitcoin's uniqueness)
- Overly complex sentence structures that become confusing when spoken
- Dense blocks of text that don't break naturally for audio consumption

## Useful Resources

- [MicroStrategy: Bitcoin for Corporations](https://www.microstrategy.com/en/bitcoin/bitcoin-for-corporations)
- [Strategy Software: Bitcoin for Corporations](https://www.strategysoftware.com/world25/bitcoin-for-corporations)
- [Mastering Bitcoin](https://github.com/bitcoinbook/bitcoinbook)

## Important Notes

- The book is still in draft stage and subject to change
- All content is under Creative Commons CC0 1.0 Universal license
- Focus on content quality and accuracy when making edits
- Ensure any Bitcoin-related information is factually correct and up-to-date
- All proceeds from the printed version go to Bitcoin Smiles charity