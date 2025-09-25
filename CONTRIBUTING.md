# 🤝 Contributing to The Algorithmic Acid Test

Welcome to the **consciousness-expanding** world of AI-augmented design research! We're excited to collaborate with researchers, designers, artists, and technologists who want to explore the boundaries between human creativity and artificial intelligence.

## 🌈 Our Philosophy

This project embodies the spirit of **"Turn on, tune in, drop out... then come back transformed."**

- **Turn on** critical thinking about AI in creative practice
- **Tune in** to boundary dissolutions in design research
- **Drop out** of traditional assumptions about creativity
- **Come back** with new frameworks for human-AI collaboration

## 🎯 Ways to Contribute

### 🔬 Research Extensions
- **Consciousness Studies**: Add new cognitive frameworks or studies
- **Design Research**: Contribute findings on AI-assisted creative processes
- **Academic References**: Enhance citations and scholarly connections
- **Empirical Data**: Share results from creativity experiments

### 🎨 Visual & Artistic Contributions
- **New Artistic Styles**: Extend the psychedelic art generation system
- **Style Guides**: Add new artist-specific prompt templates
- **Visual Improvements**: Enhance presentation aesthetics
- **Moodboard Creation**: Contribute visual references for different themes

### ⚙️ Technical Improvements
- **AI Pipeline Enhancement**: Improve content generation algorithms
- **Presentation System**: Enhance Slidev features and interactions
- **API Integrations**: Add new AI services or tools
- **Performance Optimization**: Make the system faster and more reliable

### 📚 Documentation & Education
- **Workflow Guides**: Improve setup and usage instructions
- **Academic Writing**: Enhance scholarly presentation of concepts
- **Translation**: Help translate content to other languages
- **Tutorial Creation**: Make the system more accessible

## 🚀 Getting Started

### 1. Fork & Clone
```bash
git clone https://github.com/your-username/acid-test.git
cd acid-test
```

### 2. Setup Both Components

**Presentation System:**
```bash
cd acid-test
pnpm install
pnpm dev
```

**Content Creator:**
```bash
cd content-creator
uv sync
cp ../.env.example .env
# Add your API keys to .env
```

### 3. Make Your Changes

Follow our **coding standards**:
- **Single responsibility**: One function, one purpose
- **Self-documenting names**: Code should read like prose
- **Early returns**: Reduce nesting, improve readability
- **Clean commits**: Use conventional commit format

## 📝 Contribution Guidelines

### 🎨 Visual Content Standards

**Psychedelic Art Generation:**
- Maintain authentic 1960s aesthetic principles
- Use **Einfachheit first** - single clear motifs, not complex scenes
- Follow print aesthetics: screen-print, posterization, halftone effects
- Ensure bold contrasts with hard color boundaries, no gradients
- Respect artist influences without direct appropriation

**Color Palettes:**
- Terminal-inspired base colors (`#1a1a1a` background)
- Vibrant accent colors: terminal green (`#a4e400`), electric blue, psychedelic purple
- High contrast combinations that work in presentation contexts

### 🔬 Research Standards

**Academic Rigor:**
- All claims must be supported by credible sources (preferably 2020-2025)
- Use proper citation format for academic references
- Include methodology descriptions for any studies referenced
- Maintain balance: 40% Science + 30% Poetry + 30% Practice

**Beat Generation Integration:**
- Authentic quotes from primary sources (Ginsberg, Kerouac, Burroughs)
- Contextual integration - don't just drop quotes, weave them into narrative
- Historical accuracy in representing counterculture → cyberculture evolution

### 💻 Technical Standards

**Code Quality:**
- Follow Python 3.13 standards with type hints
- Use `uv` package manager (never pip) for Python dependencies
- Follow Slidev best practices for presentation components
- Ensure all APIs have proper error handling and retry logic

**AI Integration:**
- Document prompt engineering techniques
- Include reasoning for model selection and parameters
- Provide fallback options for API failures
- Maintain separation between different AI services

## 🔄 Development Workflow

### 1. Create Feature Branch
```bash
git checkout -b feat/your-contribution-name
```

### 2. Follow Safe Development
```bash
# Create checkpoint before major changes
git add . && git commit -m "checkpoint: before implementing new feature" && git push

# Make your changes
# ...

# Test your changes
cd acid-test && pnpm dev
cd content-creator && uv run python src/test_changes.py
```

### 3. Commit with Proper Format
```bash
# Use conventional commits with emojis
git commit -m "feat: ✨ add new psychedelic art style integration"
git commit -m "docs: 📝 improve setup instructions"
git commit -m "fix: 🐛 resolve API timeout issues"
```

### 4. Create Pull Request

**PR Template:**
- **🎯 What**: Brief description of your contribution
- **🧠 Why**: Motivation and context
- **🔬 Research**: Academic backing or references (if applicable)
- **🎨 Visual**: Screenshots or examples (if visual changes)
- **✅ Testing**: How you tested your changes
- **📚 Documentation**: Updates to docs or guides

## 🧪 Research Ethics

### Responsible AI Development
- Consider bias implications in content generation
- Document limitations and potential misuse scenarios
- Respect intellectual property in style references
- Maintain transparency in AI-assisted creative processes

### Academic Integrity
- Proper attribution for all sources and influences
- Clear distinction between generated and human-authored content
- Responsible use of historical and cultural references
- Open sharing of methodologies and findings

## 🎨 Art & Culture Ethics

### Respectful Cultural References
- Beat Generation quotes: Use in educational/analytical context
- Psychedelic art influences: Stylistic inspiration, not direct copying
- Historical accuracy: Represent movements respectfully and accurately
- Contemporary relevance: Connect historical insights to modern applications

## 📋 Review Process

### Code Review Criteria
1. **Functionality**: Does it work as intended?
2. **Quality**: Follows coding standards and best practices?
3. **Documentation**: Adequately documented and explained?
4. **Ethics**: Responsible and respectful implementation?
5. **Research**: Academically sound and properly referenced?

### Design Review Criteria
1. **Aesthetic Coherence**: Fits with psychedelic theme?
2. **Usability**: Enhances presentation experience?
3. **Accessibility**: Works for diverse audiences?
4. **Authenticity**: Respectful to artistic influences?

## 🏆 Recognition

Contributors will be acknowledged in:
- **README.md** contributors section
- **Academic citations** for research contributions
- **Conference presentations** when appropriate
- **Social media** promotion of significant contributions

## 💬 Community

### Getting Help
- **GitHub Issues**: For bugs, feature requests, and discussions
- **GitHub Discussions**: For broader conversations about AI creativity
- **Email**: david@weigend.studio for research collaboration inquiries

### Communication Standards
- **Be respectful**: We're all exploring these frontiers together
- **Be specific**: Clear descriptions help everyone understand
- **Be constructive**: Critique ideas, not people
- **Be open**: Share your experiments, even if they don't work perfectly

## 🚨 What We Don't Accept

- **Plagiarism**: Copying without attribution
- **Harmful content**: Anything promoting harm or discrimination
- **Proprietary violations**: Using copyrighted material without permission
- **Low-quality contributions**: Contributions without proper testing or documentation

## 📚 Resources for Contributors

### Technical Resources
- [Slidev Documentation](https://sli.dev/)
- [Google Gemini API Docs](https://ai.google.dev/docs)
- [fal.ai Flux Documentation](https://fal.ai/models/flux)
- [Claude Code Documentation](https://docs.claude.com/claude-code)

### Research Resources
- [Transform 2025 Conference](https://kind-lab.de/transform2025/)
- [Beat Generation Archive](https://www.beatgeneration.org/)
- [Psychedelic Art History](https://psychedelicartexchange.com/)
- [Design Research Methods](https://www.designresearchsociety.org/)

### Aesthetic References
- `image-prompts/prompt-guide.md`: Comprehensive visual style guide
- `content-creator/image-prompts/`: Artist-specific reference materials
- `acid-test/pictures/`: Example generated artwork

---

## 🌊 "The Test Continues..."

> *"The algorithmic acid test dissolves everything we thought we knew about design. This isn't a bug—it's a feature."*

Your contributions help expand the boundaries of what's possible when human creativity meets artificial intelligence. Every enhancement, every new perspective, every creative experiment contributes to our collective understanding of **consciousness-expanding technology**.

**Welcome to the future of human-AI creative collaboration!** 🚀✨

---

*Questions? Ready to contribute? [Open an issue](https://github.com/dweigend/acid-test/issues) or start a [discussion](https://github.com/dweigend/acid-test/discussions)!*