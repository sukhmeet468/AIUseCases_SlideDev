---
theme: default
transition: slide-left
layout: cover
class: text-center
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

---
layout: default
class: overflow-y-auto
---

# Email, Essay, or Document Writing

<div class="overflow-y-auto max-h-120">

## Example Prompts:

<v-click>

### Email Rewriting

<div class="p-4 bg-blue-50 dark:bg-blue-900 rounded mb-4">

**Rewrite the following email to sound professional but friendly. Explain a one-week project delay due to material lead times. Keep it under 150 words. Do not assign blame.**

</div>

</v-click>

<v-click>

### Document Summarization

<div class="p-4 bg-blue-50 dark:bg-blue-900 rounded">

**Summarize this document into a one-page executive overview. Focus on risks, decisions, and next steps. Audience: management.**

</div>

</v-click>

</div>

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

<div class="p-3 bg-gray-50 dark:bg-gray-800 rounded mb-3">

**Where is the official Siemens manual that explains PROFINET diagnostics for S7-1500 CPUs? Provide the document name and source.**

</div>

<div class="p-3 bg-gray-50 dark:bg-gray-800 rounded mb-3">

**Find the latest datasheet for a Siemens ET200SP analog input module.**

</div>

<div class="p-3 bg-gray-50 dark:bg-gray-800 rounded mb-3">

**Where is the Rockwell manual that explains AOI programming best practices?**

</div>

<div class="p-3 bg-gray-50 dark:bg-gray-800 rounded">

**Find wiring diagrams for Beckhoff EL1008 I/O modules.**

</div>

</v-clicks>

</div>

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

---
layout: default
class: overflow-y-auto
---

# Summarize PDFs
## Superpowered Search Within PDFs

<div class="overflow-y-auto max-h-120">

## Example Prompts:

<v-clicks>

<div class="p-3 bg-gray-50 dark:bg-gray-800 rounded mb-3">

**In the Siemens S7-1500 manual, what are the maximum OB1 cycle times? Cite the section if possible.**

</div>

<div class="p-3 bg-gray-50 dark:bg-gray-800 rounded mb-3">

**From the Rockwell ControlLogix manual, what are the limits on produced and consumed tags?**

</div>

</v-clicks>

</div>

---
layout: default
class: overflow-y-auto
---

# Extract Specs

<div class="overflow-y-auto max-h-120">

<v-clicks>

<div class="p-4 bg-blue-50 dark:bg-blue-900 rounded mb-4">

**Show the wiring diagram section for Siemens ET200SP digital output modules. Summarize key wiring rules.**

</div>

## Finding Ratings

<div class="p-4 bg-blue-50 dark:bg-blue-900 rounded mb-4">

**What is the maximum current per channel for this module? Include temperature derating if applicable.**

</div>

<div class="p-4 bg-blue-50 dark:bg-blue-900 rounded">

**Summarize email and extract action items mentioned in the email.**

</div>

</v-clicks>

</div>

---
layout: default
class: overflow-y-auto
---

# Quotation

<div class="text-sm overflow-y-auto max-h-120">

## Initial Prompt:

<div class="p-3 bg-green-50 dark:bg-green-900 rounded mb-3">

**Based on this panel description, list the major components and generate a basic bill of materials. Ask any questions that would be beneficial to know which may affect the price that should be asked of the potential customer such as ambient temperature and NEMA rating.**

</div>

## Full Structured Prompt:

<div class="p-4 bg-green-50 dark:bg-green-900 rounded">

**You are assisting with early-stage quotation for an electrical control panel.**

**Based on the panel description below:**

- Identify and list the major components that would likely be required
- Generate a high-level, preliminary bill of materials suitable for quotation (grouped by category, not final part numbers)
- Clearly state all assumptions you are making
- Identify key questions or missing information that could significantly affect pricing, lead time, or design complexity
- Highlight items that are likely to vary based on customer requirements or standards

**Panel description:** [Paste panel description, quote text, or email here]

</div>

</div>

---
layout: default
class: overflow-y-auto
---

# Quotation (continued)

<div class="text-sm overflow-y-auto max-h-120">

## Present the output in the following sections:

<div class="grid grid-cols-2 gap-4">

<div>

- Summary of panel intent
- Preliminary BOM (grouped categories)
- Assumptions

</div>

<div>

- Pricing-impact questions to ask the customer
- Risks or cost drivers to flag early

</div>

</div>

</div>

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

---
layout: default
class: overflow-y-auto
---

# Website Scraper
## Research & Data Collection

# Bid Website Tracking or Scraping

**Website to get a list**

Use AI-assisted tools to:
- Track bid websites
- Scrape project lists
- Extract project information

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

---
layout: default
class: overflow-y-auto
---

# Extracting Project Management Data
## Resource and Capacity Scheduling Data from Excel Sheets

<div class="text-sm overflow-y-auto max-h-120">

<v-click>

## Generating Reports

<div class="p-4 bg-yellow-50 dark:bg-yellow-900 rounded mb-4">

**From our project management sheet - list the recently added projects using the PO Received date in Job Overview, from the design drafting - shop shipping and integration site and purchasing eta tracker sheet each extract the entries where deadline are approaching (within week) with job info and task info.**

Reference: `V15Project Management.xlsb`

</div>

</v-click>

</div>

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

---
layout: default
class: overflow-y-auto
---

# Create Content

<div class="overflow-y-auto max-h-120">

## Graphics – Images, Videos, Infographics, Poster, Story

<v-clicks>

<div class="p-3 bg-blue-50 dark:bg-blue-900 rounded mb-3 text-sm">

**Create a simple, professional illustration that explains how a control panel distributes power to multiple loads. The image should be clean, industrial-looking, and suitable for internal training. Avoid marketing style graphics.**

</div>

<div class="p-3 bg-blue-50 dark:bg-blue-900 rounded mb-3 text-sm">

**Create an infographic that explains the lifecycle of an electrical drawing from quotation to as-built. Include steps for design, review, revisions, fabrication, and final documentation. Keep the text minimal and the structure clear.**

</div>

<div class="p-3 bg-blue-50 dark:bg-blue-900 rounded text-sm">

**Create content for a one-page internal poster titled "Good Drawing Review Practices". Include 5 clear points that focus on accuracy, consistency, and standards compliance. Tone should be practical and non-marketing.**

</div>

</v-clicks>

</div>

---
layout: default
class: overflow-y-auto
---

# Create Content (continued)

<div class="text-sm overflow-y-auto max-h-120">

<v-clicks>

<div class="p-3 bg-blue-50 dark:bg-blue-900 rounded mb-3">

**Write a short scenario describing an electrical designer receiving late client comments that impact the panel layout. Show how unclear early requirements can lead to rework. Keep it realistic and suitable for a training discussion.**

</div>

<div class="p-3 bg-blue-50 dark:bg-blue-900 rounded mb-3">

**Create a simple visual that shows a PLC, HMI, and control panel as characters working together in a factory. Keep it light and suitable for internal training.**

</div>

</v-clicks>

</div>

---
layout: default
class: overflow-y-auto
---

# Marketing Poster Example

<div class="text-xs overflow-y-auto max-h-120">

<v-click>

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

</v-click>

</div>

---
layout: default
class: overflow-y-auto
---

# Forms

<div class="overflow-y-auto max-h-120">

<v-clicks>

<div class="p-4 bg-purple-50 dark:bg-purple-900 rounded mb-4 text-sm">

**Create a Microsoft Form to collect PLC and control system requirements for a new project. Include questions for PLC platform, I/O count, communication protocols, safety requirements, and customer standards. Use mostly multiple-choice questions and include a final open comment field.**

</div>

<div class="p-4 bg-purple-50 dark:bg-purple-900 rounded text-sm">

**Create a short form to capture lessons learned after PLC and SCADA commissioning. Focus on what caused delays, what worked well, and what should be done differently next time.**

</div>

</v-clicks>

</div>

---
layout: default
---

# Documents, Presentations, Excel Files

<v-click>

<div class="p-4 bg-blue-50 dark:bg-blue-900 rounded text-sm">

**Create a PowerPoint presentation explaining a typical PLC system architecture. Include slides for field devices, I/O, controllers, networks, and interfaces to SCADA. Keep it suitable for a mixed technical and non-technical audience.**

</div>

</v-click>

---
layout: default
class: overflow-y-auto
---

# Create Agents

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
- **AutoCAD Drawings** (Read, Create, Transform): Generate or modify AutoCAD logic and automation routines

</v-click>

</div>

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

## Perplexity Review Drawing

🔗 **https://www.perplexity.ai/search/you-are-assisting-with-an-elec-rOEcdBuwSxyvTSuo2sFiMw?sm=d#0**

</v-clicks>

</div>

---
layout: default
class: overflow-y-auto
---

# AutoCAD Assistant Prompt

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

---
layout: default
class: overflow-y-auto
---

# AutoCAD Assistant Prompt (continued)

<div class="text-sm overflow-y-auto max-h-120">

<div class="p-4 bg-blue-50 dark:bg-blue-900 rounded">

**Output format**
- Use clear headings and bullet points
- Include command names in UPPERCASE and key keystrokes in code formatting
- Where useful, show a short and a detailed version of the solution

**Before answering, if you are missing crucial information (e.g., units, 2D vs 3D, AutoCAD version, Civil 3D vs vanilla), ask me a few focused questions.**

**Now here is my task:**

[Describe what you want to do in AutoCAD here]

</div>

</div>

---
layout: default
class: overflow-y-auto
---

# PLC Programming, HMI & SCADA
## Troubleshooting

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

---
layout: default
class: overflow-y-auto
---

# Coding and Programming Workflows

<div class="text-sm overflow-y-auto max-h-120">

<v-click>

## Example Python Prompt:

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

---
layout: default
class: overflow-y-auto
---

# Different Tools

<div class="grid grid-cols-2 gap-4 text-sm overflow-y-auto max-h-120">

<div v-click>

## **Co-Pilot (Default)**

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

---
layout: center
class: text-center
---

# Thank You! 🎉

Questions?

<div class="mt-8">

📧 **Contact:** sukhmeeth@indusautomation.com

📚 **Follow-up:** Internal training deck on AI-assisted engineering workflows

</div>

<div class="mt-12 text-sm opacity-75">

Press <kbd>space</kbd> to navigate • Press <kbd>f</kbd> for fullscreen

</div>