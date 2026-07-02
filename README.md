# # My Portfolio Website

## About This Project
This is my personal portfolio website built as part of 
Panaversity Lecture 6 assignment.

## How I Built It
1. Wrote my information in Markdown format
2. Used claude.ai to convert Markdown to HTML
3. Improved the design through multiple prompt iterations
4. Published on GitHub Pages

## Prompts I Used
-prompt 1: You are an expert frontend developer. Build me a 
WORLD-CLASS, stunning single-page portfolio website 
in ONE complete self-contained HTML file 
(all CSS and JS inside, no external files).

════════════════════════════════
DESIGN STYLE
════════════════════════════════
- Dark theme: background #0B0F14
- Primary accent: mint green #7CF2C0
- Secondary accent: soft blue #7C9CF2
- Fonts: Google Fonts — Space Grotesk (headings), 
  Inter (body), JetBrains Mono (code/logo)
- Overall feel: premium AI engineer portfolio, 
  like a senior developer's personal site

════════════════════════════════
NAVIGATION BAR (fixed top)
════════════════════════════════
- Left: code-style logo  < Javeria />  in JetBrains Mono
- Center nav links: 01 About · 02 Skills · 
  03 Projects · 04 Contact
- Numbers in mint green, text in white
- Hamburger menu on mobile
- Frosted glass effect: backdrop-filter blur

════════════════════════════════
HERO SECTION (full viewport height)
════════════════════════════════
- Animated typing effect cycling these titles:
  "Agentic AI Engineer"
  "Cloud-Native Developer"  
  "Prompt Engineer"
  "MCP Specialist"
- Big bold name: JAVERIA HASNAIN
- Subtitle from About Me section
- Two CTA buttons:
  * "View My Work" (mint green filled)
  * "GitHub Profile" linking to https://github.com/bintesharif
- Subtle animated SVG grid or dot-pattern background
- Scroll-down indicator arrow with bounce animation

════════════════════════════════
ABOUT SECTION (numbered 01)
════════════════════════════════
- Two-column layout: text left, animated SVG right
- Bio text from Markdown
- Three stat cards below:
  * "7+" Skills
  * "AI Native" Developer
  * "Karachi" Based
- Fade-in on scroll

════════════════════════════════
SKILLS SECTION (numbered 02)
════════════════════════════════
- Left sidebar with category tabs (like Haseeb Ijaz):
  * AI & AGENTS
  * DEVELOPMENT
  * TOOLS & WORKFLOW
  * ENGINEERING
- Active tab has mint green left border
- Right: 2-column skill cards for each category
- Each card: skill name in mint green, 
  one-line description in gray
- Skills from my Markdown:
  AI & AGENTS: CrewAI, OpenAI Agents SDK, MCP, n8n
  DEVELOPMENT: Python, AI Spec-Driven Development
  TOOLS & WORKFLOW: n8n, Prompt Engineering
  ENGINEERING: Context Engineering, Cloud-Native AI
- Hover: card lifts with mint green border glow
- Tab switch: smooth fade transition via JS

════════════════════════════════
PROJECTS SECTION (numbered 03)
════════════════════════════════
- Dark card grid (2 columns desktop, 1 mobile)
- Each card includes:
  * Project title in white bold
  * Short description
  * Tech tags as mint green pill badges
  * GitHub button with arrow icon
- Cards: background #151A22, border #1E2530
- Hover: card lifts, border glows mint
- Projects to include:
  1. "Agentic AI Portfolio" — Personal portfolio 
     built with AI-assisted Markdown→HTML workflow. 
     Tags: HTML, CSS, AI-Assisted
     Link: https://github.com/bintesharif
  2. "Multi-Agent Systems" — Exploring CrewAI 
     and OpenAI Agents SDK for autonomous workflows.
     Tags: Python, CrewAI, OpenAI SDK
     Link: https://github.com/bintesharif
  3. "AI Automation Flows" — Building intelligent 
     n8n automation pipelines with AI nodes.
     Tags: n8n, Automation, MCP
     Link: https://github.com/bintesharif

════════════════════════════════
CONTACT SECTION (numbered 04)
════════════════════════════════
- Center-aligned, big heading: "Let's Build Together"
- Three contact cards side by side:
  * Email icon → bintesharif08@gmail.com
  * WhatsApp icon → 03151383022  
  * GitHub icon → github.com/bintesharif
- Each card: dark bg, hover mint glow
- City badge: "📍 Karachi, Pakistan"

════════════════════════════════
FOOTER
════════════════════════════════
- "Built by Javeria Hasnain · Panaversity 2025"
- Social icon row: GitHub, LinkedIn, Email
- Thin mint green top border

════════════════════════════════
ANIMATIONS & INTERACTIONS
════════════════════════════════
- Page load: sections fade in top-to-bottom
- Scroll: IntersectionObserver fade-in for each section
- Typing effect in hero (loop forever)
- Skill tab switch: JS fade transition
- Project card hover: translateY(-6px) + border glow
- Nav links: mint underline slide on hover
- Scroll progress bar at very top of page 
  (thin mint green line)
- Smooth scroll for all nav links

════════════════════════════════
MOBILE RESPONSIVE
════════════════════════════════
- Hamburger menu that slides open/closes
- Skills: horizontal scrollable tab pills on mobile
- Project cards: single column
- Hero text smaller on mobile
- All sections full-width on phone

════════════════════════════════
MY INFORMATION (Markdown)
════════════════════════════════
-prompt 2:Add these premium features to my portfolio:
1. Particle or floating dot animation in hero background
2. A "Currently Learning" badge that pulses in nav
3. Glassmorphism effect on contact cards
4. Custom scrollbar styled in mint green
5. "Back to top" button appears after scrolling down
Still keep single HTML file.
-prompt 3:Final polish pass on my portfolio:
1. Make sure ALL animations are smooth (60fps feel)
2. Add meta tags for SEO (title, description, og tags)
3. Add favicon emoji 🤖 in tab title
4. Make sure mobile hamburger menu opens/closes properly
5. Double-check ALL links work correctly
6. Grade this page out of 10 and list what you improved
# improvement
8. and maltipe and more prompt for inhancement portfolio website 

# Javeria Hasnain

## About me
Agentic AI Engineer in Training | Panaversity Student 
| Aspiring Cloud-Native & Artificial Intelligence Expert

## Skills
- Python Developer
- CrewAI
- OpenAI Agents SDK
- n8n
- AI Spec-Driven Development
- Prompt & Context Engineering
- MCP (Model Context Protocol)

## Projects
GitHub: https://github.com/bintesharif

## Contact
- Email: bintesharif08@gmail.com
- WhatsApp: 03151383022
- City: Karachi, Pakistan

════════════════════════════════
OUTPUT RULES
════════════════════════════════
- Give me ONE complete HTML file
- All CSS inside <style> tag
- All JS inside <script> tag
- No external file dependencies
- Include Google Fonts via CDN link only
- Code must be clean and production-ready

## Live Link
https://bintesharif.github.io/penaversity_class_6_assigment/

## Tools Used
- claude.ai (AI tool)
- GitHub Pages (hosting)
