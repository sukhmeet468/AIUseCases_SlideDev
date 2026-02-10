---
theme: default
layout: cover
class: text-center
transition: slide
---

# AI-Powered Workflows
## Industrial Automation Excellence

Industrial automation, PLCs, and control-panel engineering  
with AI-assisted quality control and fact-checking

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Let's explore <carbon:arrow-right class="inline"/>
  </span>
</div>

<!--
WELCOME & INTRODUCTION

Session Duration: 60 minutes
Format: Interactive with live demos

Key Points:
- Practical, real-world examples
- Copy-paste ready prompts
- Questions encouraged throughout

Presenter tip: Ask audience about their current AI usage to gauge experience level
-->

---
layout: default
---

# Quality Control & Fact Checking

<v-clicks>

- ✅ Treat AI output as a **first draft**, not final truth
- 🔍 Always cross-check:
  - Codes and standards (NEC, IEC, local regs)
  - Vendor datasheets and manuals
- 📋 Use AI to **surface information quickly**, then verify with primary sources

</v-clicks>

<!--
CRITICAL REMINDER: AI is a tool, not a replacement for engineering judgment

Emphasize:
- Always verify against authoritative sources
- AI can hallucinate or provide outdated information
- Use AI to accelerate, not replace, verification

Story to share: Example of when AI gave plausible but incorrect code reference

Time: 2-3 minutes
-->

---
layout: default
---

# Writing Prompts to Use AI

<v-click>

## A Good Prompt Includes:

<div class="grid grid-cols-2 gap-4 mt-4">

<div>

- **Role**  
  (e.g., "You are an industrial automation engineer")
  
- **Task**  
  (explain, summarize, rewrite, compare)

</div>

<div>

- **Audience**  
  and **constraints**  
  (word count, format, tone)

</div>

</div>

</v-click>

<v-click>

## Example Structure:

```
"You are a [role]. [Task] for [audience]. [Constraints]."
```

</v-click>

<!--
THE 4 PILLARS OF GOOD PROMPTS

Explain each element:
1. ROLE - Sets context and expertise level
2. TASK - What you want accomplished
3. AUDIENCE - Determines complexity and terminology
4. CONSTRAINTS - Format, length, tone requirements

Interactive: Ask someone to suggest a topic, build a prompt together on the fly

Time: 5 minutes
-->

---
layout: two-cols
class: overflow-y-auto
---

# Good vs Bad Prompt

## ❌ Bad Prompt

<div class="p-4 bg-red-50 dark:bg-red-900 rounded mb-4">

**Explain ground fault protection**

</div>

**Problems:**
- Too vague
- No context, audience, or limits

::right::

## ✅ Good Prompt

<div class="text-sm p-4 bg-green-50 dark:bg-green-900 rounded overflow-y-auto max-h-80">

**You are an industrial automation engineer. Explain ground fault protection for a 480V industrial system. Audience: new maintenance technician. Include why it is used, common causes, and typical troubleshooting steps. Limit to 200 words.**

</div>

**Why it works:**
- Clear role
- System specified
- Defined audience
- Structured requirements

<!--
COPY-PASTE PROMPTS:

BAD PROMPT:
Explain ground fault protection

GOOD PROMPT:
You are an industrial automation engineer. Explain ground fault protection for a 480V industrial system. Audience: new maintenance technician. Include why it is used, common causes, and typical troubleshooting steps. Limit to 200 words.

DEMO OPPORTUNITY: If time permits, run both prompts live to show the difference in quality

Time: 3-4 minutes
-->

---
layout: default
class: overflow-y-auto
---

# Email, Essay, or Document Writing

<div class="overflow-y-auto max-h-120">

## Example Prompts:

<v-click>

### Email Rewriting

<div class="p-4 bg-blue-50 dark:bg-blue-900 rounded mb-4 text-sm">

**Rewrite the following email to sound professional but friendly. Explain a one-week project delay due to material lead times. Keep it under 150 words. Do not assign blame.**

</div>

</v-click>

<v-click>

### Document Summarization

<div class="p-4 bg-blue-50 dark:bg-blue-900 rounded text-sm">

**Summarize this document into a one-page executive overview. Focus on risks, decisions, and next steps. Audience: management.**

</div>

</v-click>

</div>

<!--
COPY-PASTE PROMPTS:

PROMPT 1 - EMAIL REWRITING:
Rewrite the following email to sound professional but friendly. Explain a one-week project delay due to material lead times. Keep it under 150 words. Do not assign blame.

PROMPT 2 - DOCUMENT SUMMARY:
Summarize this document into a one-page executive overview. Focus on risks, decisions, and next steps. Audience: management.

Use Cases:
- Delay notifications
- Status updates
- Executive summaries
- Client communications

Time: 3 minutes
-->

---
layout: default
class: overflow-y-auto
---

# Semantic Search Engine
## (Superpowered Googling)

<div class="overflow-y-auto max-h-120">

Find manuals, datasheets, wiring diagrams, and technical references **without exact keywords**.

## Example Prompts:

<v-clicks>

<div class="p-3 bg-gray-50 dark:bg-gray-800 rounded mb-3 text-sm">

**Where is the official Siemens manual that explains PROFINET diagnostics for S7-1500 CPUs? Provide the document name and source.**

</div>

<div class="p-3 bg-gray-50 dark:bg-gray-800 rounded mb-3 text-sm">

**Find the latest datasheet for a Siemens ET200SP analog input module.**

</div>

<div class="p-3 bg-gray-50 dark:bg-gray-800 rounded mb-3 text-sm">

**Where is the Rockwell manual that explains AOI programming best practices?**

</div>

<div class="p-3 bg-gray-50 dark:bg-gray-800 rounded text-sm">

**Find wiring diagrams for Beckhoff EL1008 I/O modules.**

</div>

</v-clicks>

</div>

<!--
COPY-PASTE PROMPTS:

PROMPT 1:
Where is the official Siemens manual that explains PROFINET diagnostics for S7-1500 CPUs? Provide the document name and source.

PROMPT 2:
Find the latest datasheet for a Siemens ET200SP analog input module.

PROMPT 3:
Where is the Rockwell manual that explains AOI programming best practices?

PROMPT 4:
Find wiring diagrams for Beckhoff EL1008 I/O modules.

Key Benefit: AI understands intent, not just keywords. You can describe what you need conceptually.

Time: 3 minutes
-->

---
layout: default
---

# Finding Alternative Parts

<v-click>

## Prompt Pattern:

<div class="p-4 bg-purple-50 dark:bg-purple-900 rounded text-sm">

**This Siemens module is obsolete. Suggest functionally equivalent alternatives. Compare voltage, current, certifications, and risks.**

</div>

</v-click>

<!--
COPY-PASTE PROMPT:

This Siemens module is obsolete. Suggest functionally equivalent alternatives. Compare voltage, current, certifications, and risks.

Use Case: Obsolescence management and product substitution

When to use:
- End-of-life notifications
- Long lead times
- Cost optimization
- Supply chain issues

Pro tip: Include specific module part number in actual prompt

Time: 2 minutes
-->

---
layout: default
class: overflow-y-auto
---

# Summarize PDFs
## Superpowered Search Within PDFs

<div class="overflow-y-auto max-h-120">

## Example Prompts:

<v-clicks>

<div class="p-3 bg-gray-50 dark:bg-gray-800 rounded mb-3 text-sm">

**In the Siemens S7-1500 manual, what are the maximum OB1 cycle times? Cite the section if possible.**

</div>

<div class="p-3 bg-gray-50 dark:bg-gray-800 rounded mb-3 text-sm">

**From the Rockwell ControlLogix manual, what are the limits on produced and consumed tags?**

</div>

</v-clicks>

</div>

<!--
COPY-PASTE PROMPTS:

PROMPT 1:
In the Siemens S7-1500 manual, what are the maximum OB1 cycle times? Cite the section if possible.

PROMPT 2:
From the Rockwell ControlLogix manual, what are the limits on produced and consumed tags?

Huge Time Saver: Instead of reading 500+ page manuals, AI can extract specific information quickly

Always verify: Check the cited section yourself to confirm accuracy

Time: 2 minutes
-->

---
layout: default
class: overflow-y-auto
---

# Extract Specs & Ratings

<div class="overflow-y-auto max-h-120">

<v-clicks>

<div class="p-4 bg-blue-50 dark:bg-blue-900 rounded mb-4 text-sm">

**Show the wiring diagram section for Siemens ET200SP digital output modules. Summarize key wiring rules.**

</div>

<div class="p-4 bg-blue-50 dark:bg-blue-900 rounded mb-4 text-sm">

**What is the maximum current per channel for this module? Include temperature derating if applicable.**

</div>

<div class="p-4 bg-blue-50 dark:bg-blue-900 rounded text-sm">

**Summarize email and extract action items mentioned in the email.**

</div>

</v-clicks>

</div>

<!--
COPY-PASTE PROMPTS:

PROMPT 1 - EXTRACT SPECS:
Show the wiring diagram section for Siemens ET200SP digital output modules. Summarize key wiring rules.

PROMPT 2 - FIND RATINGS:
What is the maximum current per channel for this module? Include temperature derating if applicable.

PROMPT 3 - EMAIL ACTION ITEMS:
Summarize email and extract action items mentioned in the email.

Applications:
- Quick spec lookup
- Email processing
- Meeting notes summarization
- Document analysis

Time: 3 minutes
-->

---
layout: default
class: overflow-y-auto
---

# Quotation Assistance

<div class="text-sm overflow-y-auto max-h-120">

## Initial Prompt:

<div class="p-3 bg-green-50 dark:bg-green-900 rounded mb-3">

**Based on this panel description, list the major components and generate a basic bill of materials. Ask any questions that would be beneficial to know which may affect the price that should be asked of the potential customer such as ambient temperature and NEMA rating.**

</div>

</div>

<!--
COPY-PASTE PROMPT - SIMPLE VERSION:

Based on this panel description, list the major components and generate a basic bill of materials. Ask any questions that would be beneficial to know which may affect the price that should be asked of the potential customer such as ambient temperature and NEMA rating.

This is the quick version for simple quotes. See next slide for detailed version.

Time: 2 minutes
-->

---
layout: default
class: overflow-y-auto
---

# Quotation - Full Structured Prompt

<div class="text-xs overflow-y-auto max-h-120">

<div class="p-4 bg-green-50 dark:bg-green-900 rounded">

**You are assisting with early-stage quotation for an electrical control panel.**

**Based on the panel description below:**

- Identify and list the major components that would likely be required
- Generate a high-level, preliminary bill of materials suitable for quotation (grouped by category, not final part numbers)
- Clearly state all assumptions you are making
- Identify key questions or missing information that could significantly affect pricing, lead time, or design complexity
- Highlight items that are likely to vary based on customer requirements or standards

**Panel description:** [Paste panel description, quote text, or email here]

**Present the output in the following sections:**
- Summary of panel intent
- Preliminary BOM (grouped categories)
- Assumptions
- Pricing-impact questions to ask the customer
- Risks or cost drivers to flag early

</div>

</div>

<!--
COPY-PASTE PROMPT - DETAILED VERSION:

You are assisting with early-stage quotation for an electrical control panel.

Based on the panel description below:

- Identify and list the major components that would likely be required
- Generate a high-level, preliminary bill of materials suitable for quotation (grouped by category, not final part numbers)
- Clearly state all assumptions you are making
- Identify key questions or missing information that could significantly affect pricing, lead time, or design complexity
- Highlight items that are likely to vary based on customer requirements or standards

Panel description: [Paste panel description, quote text, or email here]

Present the output in the following sections:
- Summary of panel intent
- Preliminary BOM (grouped categories)
- Assumptions
- Pricing-impact questions to ask the customer
- Risks or cost drivers to flag early

Use this for complex quotations where thoroughness is critical.

Time: 3 minutes
-->

---
layout: default
---

# Bid Website Tracking

**Website Scraping to Get Project Lists**

Use AI-assisted tools to:
- Track bid websites
- Scrape project lists
- Extract project information

<!--
TOPIC: Bid Website Tracking

This is more of a capability overview rather than specific prompts.

Tools mentioned:
- Web scraping tools with AI
- Automated bid monitoring

Discuss ethical and legal considerations of web scraping.

Time: 1-2 minutes (brief overview)
-->

---
layout: default
class: overflow-y-auto
---

# Compare Datasheets
## (Cutsheet Comparison & Selection)

<div class="text-sm overflow-y-auto max-h-120">

<v-click>

## Prompt:

<div class="p-4 bg-blue-50 dark:bg-blue-900 rounded mb-4">

**Compare Beckhoff EL1008 and Siemens DI 16x24VDC ST modules.**

**Create a table with:**
- Voltage range
- Current per channel
- Isolation
- Certifications
- Typical use cases

**Based on this comparison, which would you recommend for a harsh industrial environment and why?**

</div>

</v-click>

</div>

<!--
COPY-PASTE PROMPT:

Compare Beckhoff EL1008 and Siemens DI 16x24VDC ST modules.

Create a table with:
- Voltage range
- Current per channel
- Isolation
- Certifications
- Typical use cases

Based on this comparison, which would you recommend for a harsh industrial environment and why?

Great for: Product selection, vendor comparison, specification analysis

Pro tip: Attach datasheets to chat for more accurate comparison

Time: 3 minutes
-->

---
layout: default
class: overflow-y-auto
---

# Website Scraper
## Research & Data Collection

<div class="overflow-y-auto max-h-120">

<v-click>

## Example Prompt:

<div class="p-4 bg-purple-50 dark:bg-purple-900 rounded text-sm">

**Visit indusautomation.com.**

**Summarize:**
- What services they provide
- Industries they serve
- Their technical focus
- Typical customer profile

**Based on their website, what types of automation projects are they most likely bidding on?**

</div>

</v-click>

</div>

<!--
COPY-PASTE PROMPT:

Visit indusautomation.com.

Summarize:
- What services they provide
- Industries they serve
- Their technical focus
- Typical customer profile

Based on their website, what types of automation projects are they most likely bidding on?

Use Cases:
- Competitor research
- Market analysis
- Partnership evaluation
- Client background research

Note: Replace "indusautomation.com" with any target website

Time: 2 minutes
-->

---
layout: default
class: overflow-y-auto
---

# Extract Project Management Data
## From Excel Sheets - Generating Reports

<div class="text-sm overflow-y-auto max-h-120">

<v-click>

<div class="p-4 bg-yellow-50 dark:bg-yellow-900 rounded mb-4">

**From our project management sheet - list the recently added projects using the PO Received date in Job Overview, from the design drafting - shop shipping and integration site and purchasing eta tracker sheet each extract the entries where deadline are approaching (within week) with job info and task info.**

Reference file: `V15Project Management.xlsb`

</div>

</v-click>

</div>

<!--
COPY-PASTE PROMPT:

From our project management sheet - list the recently added projects using the PO Received date in Job Overview, from the design drafting - shop shipping and integration site and purchasing eta tracker sheet each extract the entries where deadline are approaching (within week) with job info and task info.

File: V15Project Management.xlsb

This extracts upcoming deadlines and new projects from your PM spreadsheet.

Requirements: Upload the Excel file to the AI tool first

Time: 2 minutes
-->

---
layout: default
class: overflow-y-auto
---

# Filter by Customer

<div class="overflow-y-auto max-h-120">

<v-click>

<div class="p-4 bg-yellow-50 dark:bg-yellow-900 rounded mb-4">

**Filter by specific customer: SANDVIK and give a customer specific report**

</div>

</v-click>

</div>

<!--
COPY-PASTE PROMPT:

Filter by specific customer: SANDVIK and give a customer specific report

Use this as a follow-up to the previous project management extraction prompt.

Change "SANDVIK" to any customer name you need to filter for.

Generates customer-specific views of project status, deadlines, and workload.

Time: 1 minute
-->

---
layout: default
class: overflow-y-auto
---

# Resource and Capacity Planning

<div class="text-sm overflow-y-auto max-h-120">

<v-click>

<div class="p-4 bg-orange-50 dark:bg-orange-900 rounded">

**From this evaluate the possibility of being able to finish the BE033 by 30th Jan 2026 assuming the estimated hrs. is 80 and project has not been worked upon yet - evaluate the possibility by comparing the capacity of Design Drafting (DD Dept) and workload during the week**

</div>

</v-click>

</div>

<!--
COPY-PASTE PROMPT:

From this evaluate the possibility of being able to finish the BE033 by 30th Jan 2026 assuming the estimated hrs. is 80 and project has not been worked upon yet - evaluate the possibility by comparing the capacity of Design Drafting (DD Dept) and workload during the week

Capacity Planning Use Case:
- Can we meet this deadline?
- Do we have the resources?
- What's our current workload?

Customize: Change project number, deadline, hours, and department as needed

Time: 2 minutes
-->

---
layout: default
class: overflow-y-auto
---

# Create Content - Graphics

<div class="text-xs overflow-y-auto max-h-120">

## Images, Videos, Infographics, Posters, Stories

<v-clicks>

<div class="p-3 bg-blue-50 dark:bg-blue-900 rounded mb-3">

**Create a simple, professional illustration that explains how a control panel distributes power to multiple loads. The image should be clean, industrial-looking, and suitable for internal training. Avoid marketing style graphics.**

</div>

<div class="p-3 bg-blue-50 dark:bg-blue-900 rounded mb-3">

**Create an infographic that explains the lifecycle of an electrical drawing from quotation to as-built. Include steps for design, review, revisions, fabrication, and final documentation. Keep the text minimal and the structure clear.**

</div>

<div class="p-3 bg-blue-50 dark:bg-blue-900 rounded">

**Create content for a one-page internal poster titled "Good Drawing Review Practices". Include 5 clear points that focus on accuracy, consistency, and standards compliance. Tone should be practical and non-marketing.**

</div>

</v-clicks>

</div>

<!--
COPY-PASTE PROMPTS:

PROMPT 1 - TECHNICAL ILLUSTRATION:
Create a simple, professional illustration that explains how a control panel distributes power to multiple loads. The image should be clean, industrial-looking, and suitable for internal training. Avoid marketing style graphics.

PROMPT 2 - INFOGRAPHIC:
Create an infographic that explains the lifecycle of an electrical drawing from quotation to as-built. Include steps for design, review, revisions, fabrication, and final documentation. Keep the text minimal and the structure clear.

PROMPT 3 - INTERNAL POSTER:
Create content for a one-page internal poster titled "Good Drawing Review Practices". Include 5 clear points that focus on accuracy, consistency, and standards compliance. Tone should be practical and non-marketing.

Best tools: Google Gemini, DALL-E, Midjourney

Time: 3 minutes
-->

---
layout: default
class: overflow-y-auto
---

# Create Content - Scenarios

<div class="text-sm overflow-y-auto max-h-120">

<v-clicks>

<div class="p-3 bg-blue-50 dark:bg-blue-900 rounded mb-3">

**Write a short scenario describing an electrical designer receiving late client comments that impact the panel layout. Show how unclear early requirements can lead to rework. Keep it realistic and suitable for a training discussion.**

</div>

<div class="p-3 bg-blue-50 dark:bg-blue-900 rounded">

**Create a simple visual that shows a PLC, HMI, and control panel as characters working together in a factory. Keep it light and suitable for internal training.**

</div>

</v-clicks>

</div>

<!--
COPY-PASTE PROMPTS:

PROMPT 1 - TRAINING SCENARIO:
Write a short scenario describing an electrical designer receiving late client comments that impact the panel layout. Show how unclear early requirements can lead to rework. Keep it realistic and suitable for a training discussion.

PROMPT 2 - CHARACTER VISUAL:
Create a simple visual that shows a PLC, HMI, and control panel as characters working together in a factory. Keep it light and suitable for internal training.

Use for: Training materials, team discussions, process improvement workshops

Time: 2 minutes
-->

---
layout: default
class: overflow-y-auto
---

# Marketing Poster Example

<div class="text-xs overflow-y-auto max-h-120">

<div class="p-4 bg-green-50 dark:bg-green-900 rounded">

**Create content for a one-page marketing poster for Indus Automation that promotes the company's industrial automation services and expertise.**

**Include:**

- A bold headline that clearly conveys what Indus Automation does
- Key service offerings such as custom control panel design, PLC programming, HMI/SCADA solutions, troubleshooting, and commissioning
- Target industries where Indus Automation works (e.g., agriculture, food processing, mining, water/wastewater, utilities, manufacturing) based on typical automation needs
- A short tagline emphasizing quality, customized solutions, and reliability
- Contact information and a call-to-action (e.g., "Request a Quote Today")
- A visual style suggestion (professional, industrial, modern)

**Do not use overly technical or confusing language—focus on value to customers.**

</div>

</div>

<!--
COPY-PASTE PROMPT:

Create content for a one-page marketing poster for Indus Automation that promotes the company's industrial automation services and expertise.

Include:
- A bold headline that clearly conveys what Indus Automation does
- Key service offerings such as custom control panel design, PLC programming, HMI/SCADA solutions, troubleshooting, and commissioning
- Target industries where Indus Automation works (e.g., agriculture, food processing, mining, water/wastewater, utilities, manufacturing) based on typical automation needs
- A short tagline emphasizing quality, customized solutions, and reliability
- Contact information and a call-to-action (e.g., "Request a Quote Today")
- A visual style suggestion (professional, industrial, modern)

Do not use overly technical or confusing language—focus on value to customers.

Output: Marketing copy that can be handed to graphic designer

Time: 2 minutes
-->

---
layout: default
class: overflow-y-auto
---

# Forms Creation

<div class="text-sm overflow-y-auto max-h-120">

<v-clicks>

<div class="p-4 bg-purple-50 dark:bg-purple-900 rounded mb-4">

**Create a Microsoft Form to collect PLC and control system requirements for a new project. Include questions for PLC platform, I/O count, communication protocols, safety requirements, and customer standards. Use mostly multiple-choice questions and include a final open comment field.**

</div>

<div class="p-4 bg-purple-50 dark:bg-purple-900 rounded">

**Create a short form to capture lessons learned after PLC and SCADA commissioning. Focus on what caused delays, what worked well, and what should be done differently next time.**

</div>

</v-clicks>

</div>

<!--
COPY-PASTE PROMPTS:

PROMPT 1 - REQUIREMENTS FORM:
Create a Microsoft Form to collect PLC and control system requirements for a new project. Include questions for PLC platform, I/O count, communication protocols, safety requirements, and customer standards. Use mostly multiple-choice questions and include a final open comment field.

PROMPT 2 - LESSONS LEARNED FORM:
Create a short form to capture lessons learned after PLC and SCADA commissioning. Focus on what caused delays, what worked well, and what should be done differently next time.

AI generates the form structure and questions - you implement in Microsoft Forms, Google Forms, etc.

Time: 2 minutes
-->

---
layout: default
---

# Documents & Presentations

<v-click>

<div class="p-4 bg-blue-50 dark:bg-blue-900 rounded text-sm">

**Create a PowerPoint presentation explaining a typical PLC system architecture. Include slides for field devices, I/O, controllers, networks, and interfaces to SCADA. Keep it suitable for a mixed technical and non-technical audience.**

</div>

</v-click>

<!--
COPY-PASTE PROMPT:

Create a PowerPoint presentation explaining a typical PLC system architecture. Include slides for field devices, I/O, controllers, networks, and interfaces to SCADA. Keep it suitable for a mixed technical and non-technical audience.

AI can generate:
- Slide outlines
- Content for each slide
- Speaker notes
- Even create the actual .pptx file (with tools like Claude)

Time: 2 minutes
-->

---
layout: default
class: overflow-y-auto
---

# Create Custom AI Agents

<div class="overflow-y-auto max-h-120">

<v-click>

Create Agents with:
- **Custom Instructions** (explaining AI role, instructions on what to help with)
- **Specific files knowledge description**
- **Ability to share agents with anyone in org**

</v-click>

<v-click>

## Example Agents:

- **Writing Coach**
- **Prompt Coach**
- **AutoCAD Drawings** (Read, Create, Transform)

Generate or modify AutoCAD logic and automation routines

</v-click>

</div>

<!--
CUSTOM AI AGENTS

What are agents?
- Pre-configured AI assistants with specific roles
- Can have custom instructions and knowledge
- Shareable within organization

Example agents to create:
1. Writing Coach - polish all written communication
2. Prompt Coach - help team members write better prompts
3. AutoCAD Assistant - CAD-specific help
4. PLC Troubleshooting - diagnostic assistance

How to create: Most AI platforms (ChatGPT, Claude) now support custom agents/GPTs

Time: 3 minutes
-->

---
layout: default
class: overflow-y-auto
---

# AutoCAD Agent Examples

<div class="text-sm overflow-y-auto max-h-120">

<v-clicks>

<div class="p-3 bg-gray-50 dark:bg-gray-800 rounded mb-3">

**Explain what this Auto LISP routine does step by step.**

</div>

<div class="p-3 bg-gray-50 dark:bg-gray-800 rounded mb-3">

**Write an Auto LISP routine that selects all text objects and moves them to a layer called 'TEXT'**

</div>

<div class="p-3 bg-gray-50 dark:bg-gray-800 rounded">

**Drawing checklist review?**

</div>

</v-clicks>

</div>

<!--
COPY-PASTE PROMPTS:

PROMPT 1:
Explain what this Auto LISP routine does step by step.
[Then paste the LISP code]

PROMPT 2:
Write an Auto LISP routine that selects all text objects and moves them to a layer called 'TEXT'

PROMPT 3:
Drawing checklist review?
[Then provide drawing or checklist]

These are great for AutoCAD automation and quality control

Time: 2 minutes
-->

---
layout: default
class: overflow-y-auto
---

# AutoCAD Tools & Resources

<div class="overflow-y-auto max-h-120">

<v-clicks>

## Colab Software for Design Review

🔗 **https://www.colabsoftware.com/**

## Image to CAD Drawings Using ChatGPT

**Full AI Workflow Tutorial!**

🔗 **https://convertio.co/**
🔗 **https://www.youtube.com/watch?v=1zkz3EJmltU**

## Perplexity Review Drawing

🔗 **https://www.perplexity.ai/search/you-are-assisting-with-an-elec-rOEcdBuwSxyvTSuo2sFiMw?sm=d#0**

</v-clicks>

</div>

<!--
RESOURCES FOR AUTOCAD + AI

1. Colab Software (https://www.colabsoftware.com/)
   - Collaborative design review platform
   - Works with AutoCAD files

2. Convertio (https://convertio.co/)
   - File conversion tool
   - Useful for image-to-CAD workflows

3. Perplexity Example (https://www.perplexity.ai/search/you-are-assisting-with-an-elec-rOEcdBuwSxyvTSuo2sFiMw?sm=d#0)
   - Example of using Perplexity for electrical drawing assistance

Demonstrate one of these tools if time permits

Time: 2 minutes
-->

---
layout: default
class: overflow-y-auto
---

# AutoCAD Assistant - Full Prompt

<div class="text-xs overflow-y-auto max-h-120">

<div class="p-4 bg-blue-50 dark:bg-blue-900 rounded">

**You are my AutoCAD assistant.**

**I will describe what I want to draw or automate, and your job is to:**

- Explain AutoCAD commands and workflows
- Suggest the best commands, tools, and options to use (including command-line aliases)
- Provide step-by-step instructions that a user in AutoCAD could follow
- Mention relevant settings like snaps (OSNAP), layers, annotation scales, dimension styles, etc., when helpful

**Optimize repetitive tasks**
- Show me faster ways to do a task (e.g., using arrays, blocks, scripts, LISP, or other automation)
- If there are multiple ways, list them and indicate which is best for speed/maintainability
- When relevant, explain how to structure drawings for reusability (blocks, xrefs, layer standards, templates)

**Help with AutoLISP / scripts (conceptual and example code)**
- Suggest whether an idea is doable with AutoLISP or other automation (scripts, macros, etc.)
- Provide example AutoLISP code or script snippets with comments explaining each part
- If there are known limitations (e.g., in AutoCAD LT or certain verticals), clearly call them out

</div>

</div>

<!--
COPY-PASTE PROMPT - PART 1:

You are my AutoCAD assistant.

I will describe what I want to draw or automate, and your job is to:

- Explain AutoCAD commands and workflows
- Suggest the best commands, tools, and options to use (including command-line aliases)
- Provide step-by-step instructions that a user in AutoCAD could follow
- Mention relevant settings like snaps (OSNAP), layers, annotation scales, dimension styles, etc., when helpful

Optimize repetitive tasks:
- Show me faster ways to do a task (e.g., using arrays, blocks, scripts, LISP, or other automation)
- If there are multiple ways, list them and indicate which is best for speed/maintainability
- When relevant, explain how to structure drawings for reusability (blocks, xrefs, layer standards, templates)

Help with AutoLISP / scripts (conceptual and example code):
- Suggest whether an idea is doable with AutoLISP or other automation (scripts, macros, etc.)
- Provide example AutoLISP code or script snippets with comments explaining each part
- If there are known limitations (e.g., in AutoCAD LT or certain verticals), clearly call them out

[CONTINUED ON NEXT SLIDE]
-->

---
layout: default
class: overflow-y-auto
---

# AutoCAD Assistant - Output Format

<div class="text-sm overflow-y-auto max-h-120">

<div class="p-4 bg-blue-50 dark:bg-blue-900 rounded">

**Output format:**
- Use clear headings and bullet points
- Include command names in UPPERCASE and key keystrokes in code formatting
- Where useful, show a short and a detailed version of the solution

**Before answering, if you are missing crucial information (e.g., units, 2D vs 3D, AutoCAD version, Civil 3D vs vanilla), ask me a few focused questions.**

**Now here is my task:**

[Describe what you want to do in AutoCAD here]

</div>

</div>

<!--
COPY-PASTE PROMPT - PART 2 (CONTINUATION):

Output format:
- Use clear headings and bullet points
- Include command names in UPPERCASE and key keystrokes in code formatting
- Where useful, show a short and a detailed version of the solution

Before answering, if you are missing crucial information (e.g., units, 2D vs 3D, AutoCAD version, Civil 3D vs vanilla), ask me a few focused questions.

Now here is my task:
[Describe what you want to do in AutoCAD here]

This is a comprehensive AutoCAD assistant setup. Use as a custom GPT or paste at start of conversation.

Time: 2 minutes
-->

---
layout: default
class: overflow-y-auto
---

# PLC Programming & Troubleshooting

<div class="overflow-y-auto max-h-120">

## Example Prompts:

<v-clicks>

<div class="p-3 bg-red-50 dark:bg-red-900 rounded mb-3 text-sm">

**Why might a PLC fault intermittently under high load? List likely causes and troubleshooting steps.**

</div>

<div class="p-3 bg-red-50 dark:bg-red-900 rounded mb-3 text-sm">

**What are common causes of PROFINET IO device communication loss? Provide a troubleshooting checklist.**

</div>

<div class="p-3 bg-red-50 dark:bg-red-900 rounded text-sm">

**Explain common reasons an HMI loses communication with a PLC and how to diagnose each one.**

</div>

</v-clicks>

</div>

<!--
COPY-PASTE PROMPTS:

PROMPT 1:
Why might a PLC fault intermittently under high load? List likely causes and troubleshooting steps.

PROMPT 2:
What are common causes of PROFINET IO device communication loss? Provide a troubleshooting checklist.

PROMPT 3:
Explain common reasons an HMI loses communication with a PLC and how to diagnose each one.

Great for: Diagnostic help, troubleshooting guides, training documentation

Time: 3 minutes
-->

---
layout: default
class: overflow-y-auto
---

# PLC Resources & Tools

<div class="overflow-y-auto max-h-120">

<v-clicks>

## Siemens Engineering Copilot

🔗 **https://docs.tia.siemens.cloud/r/en-us/v1.1/siemens-engineering-copilot/siemens-engineering-copilot**

## Beckhoff TwinCAT AI-Supported Engineering

🔗 **https://www.beckhoff.com/en-en/products/automation/twincat-projects-with-ai-supported-engineering/?utm_source=chatgpt.com**

## PLC Autopilot

🔗 **https://www.plcautopilot.com/**

</v-clicks>

</div>

<!--
VENDOR-SPECIFIC AI TOOLS

1. Siemens Engineering Copilot
   https://docs.tia.siemens.cloud/r/en-us/v1.1/siemens-engineering-copilot/siemens-engineering-copilot
   - Integrated into TIA Portal
   - Code generation and assistance

2. Beckhoff TwinCAT AI
   https://www.beckhoff.com/en-en/products/automation/twincat-projects-with-ai-supported-engineering/?utm_source=chatgpt.com
   - AI-supported engineering in TwinCAT
   - Code optimization

3. PLC Autopilot
   https://www.plcautopilot.com/
   - Multi-platform PLC programming assistance

These are becoming standard tools in modern PLC programming

Time: 2 minutes
-->

---
layout: default
class: overflow-y-auto
---

# SCL Code Generation

<div class="overflow-y-auto max-h-120">

<v-click>

## Example Use Case:

<div class="p-4 bg-green-50 dark:bg-green-900 rounded mb-4 text-sm">

**Generate me SCL code for alternating between 3 pumps**

</div>

</v-click>

<v-click>

## Template Libraries

<div class="p-4 bg-yellow-50 dark:bg-yellow-900 rounded text-sm">

**SCL code generated with help of AI can be used to create template libraries with functions used most which can be later imported in the projects**

</div>

</v-click>

</div>

<!--
COPY-PASTE PROMPT:

Generate me SCL code for alternating between 3 pumps

TEMPLATE LIBRARY STRATEGY:

Use AI to build reusable code libraries:
1. Generate common functions (pump alternation, motor sequencing, etc.)
2. Review and test the code
3. Save to template library
4. Import into future projects

Benefits:
- Consistent code across projects
- Faster development
- Reduced errors
- Easy maintenance

Time: 3 minutes
-->

---
layout: default
class: overflow-y-auto
---

# Python Programming Example

<div class="text-sm overflow-y-auto max-h-120">

<v-click>

## Coding and Programming Workflows

<div class="p-4 bg-purple-50 dark:bg-purple-900 rounded">

**Write Python code that groups items by category without knowing the categories in advance.**

**Requirements:**
- Input is a list of strings (e.g., colors)
- Output is a dictionary where each key is a unique category and the value is a list of items in that category, print the dictionary like category (key) -> value (list of values) in separate rows
- Use a fast, linear-time approach
- Do not hard-code category names
- Handle unexpected or new categories automatically
- Keep the code simple and production-ready

</div>

</v-click>

</div>

<!--
COPY-PASTE PROMPT:

Write Python code that groups items by category without knowing the categories in advance.

Requirements:
- Input is a list of strings (e.g., colors)
- Output is a dictionary where each key is a unique category and the value is a list of items in that category, print the dictionary like category (key) -> value (list of values) in separate rows
- Use a fast, linear-time approach
- Do not hard-code category names
- Handle unexpected or new categories automatically
- Keep the code simple and production-ready

This demonstrates how to write detailed requirements for code generation.

Key: Be specific about inputs, outputs, performance requirements, and constraints.

Time: 2 minutes
-->

---
layout: default
class: overflow-y-auto
---

# Different AI Tools

<div class="grid grid-cols-2 gap-4 text-sm overflow-y-auto max-h-120">

<div v-click>

## **GitHub Co-Pilot (Default)**

IDE-integrated coding assistance

</div>

<div v-click>

## **ChatGPT**

- Coding Workflows
- Text formatting
- General agents

</div>

<div v-click>

## **Perplexity**

- Deep Research with Sources

</div>

<div v-click>

## **Google Gemini**

- Generating Images

</div>

<div v-click>

## **Claude**

- Coding Workflows
- Develop single page applications

</div>

</div>

<!--
TOOL SELECTION GUIDE

GitHub Co-Pilot:
- Best for: Real-time code completion in IDE
- Use when: Actively coding

ChatGPT:
- Best for: General purpose, agents, text work
- Use when: Versatile tasks, custom GPTs

Perplexity:
- Best for: Research with citations
- Use when: Need to verify sources

Google Gemini:
- Best for: Image generation
- Use when: Need visuals, graphics

Claude:
- Best for: Complex coding, long documents
- Use when: Building applications, deep analysis

Pro tip: Use the right tool for each job - don't try to do everything in one platform

Time: 3 minutes
-->

---
layout: default
class: overflow-y-auto
---

# 🎯 Interactive Activity
## Let's Practice Together!

<div class="text-sm overflow-y-auto max-h-120">

<v-click>

<div class="grid grid-cols-2 gap-4 mt-4">

Ask Copilot to get a summary or questions about the session, create a technical illustration or diagram or document and write an email explaining lessons learned during session.

</div>

</v-click>

<v-click>

### Instructions:

1. **Open your AI tool** (Copilot, ChatGPT, etc.)
2. **Write your prompt** (remember: Role, Task, Audience, Constraints!)
3. **Share your result in the chat** so everyone can see
4. **Compare the outputs** - same task, different prompts = different results!

</v-click>

<v-click>

<div class="mt-4 p-4 bg-yellow-50 dark:bg-yellow-900 rounded">

**⏱️ Time: 3-5 minutes**

The goal: How the user's judgement of the task or topic creates different prompts and leads to different responses.!

</div>

</v-click>

</div>

---
layout: center
class: overflow-y-auto
---

# Thank You! 🎉

<v-click>

Questions?

<div class="mt-8">

📧 **Contact:** sukhmeeth@indusautomation.com

📚 **Follow-up:** session a couple weeks later to see how everyone has been doing with their workflows and if they've implemented AI in their workflows.

📚 **Food for thought:**
- Company Knowledge Assistant (Secure Search + Q&A) FAR FETCHED THOUGHT
   - What it is: An internal, permission-controlled assistant that lets teams ask questions across past jobs and documents and get answers with citations.
   - What it enables: Fast retrieval of documents or information, parts, BOMs, quotes, drawings, code, and lessons learned from similar past jobs.
   - Example questions
      - “Show me a past job similar to a 3-pump lift station with VFDs.”
      - “What VFD frame size did we use on the last 25HP ABB install?”

</div>

<div class="mt-12 text-sm opacity-75">

Press <kbd>space</kbd> to navigate • Press <kbd>f</kbd> for fullscreen • Press <kbd>o</kbd> for presenter mode

</v-click>

</div>

<!--
WRAP UP

Key Takeaways:
1. AI is a productivity tool, not a replacement
2. Good prompts = good results (Role, Task, Audience, Constraints)
3. Always verify AI output against authoritative sources
4. Use the right tool for the job
5. Build reusable templates and agents

Next Steps:
- Share this deck with team
- Try the prompts on real work
- Create custom agents for your workflows
- Share successes and failures

Q&A Time: Open floor for questions

Thank them for attending!
-->