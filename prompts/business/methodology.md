# Design Methodology: Business Idea Analysis

## Design Philosophy

This prompt was designed to help non-experts quickly evaluate a business idea without requiring formal consulting knowledge. The goal was to create a structured yet accessible analysis that balances competitive awareness with feasibility risk identification. It prioritizes clarity, speed, and practical insight over technical depth.

The guiding principles were simplicity, structured thinking, and actionable output. By assigning a clear role, specifying deliverables, and requiring casual language, the prompt ensures outputs are practical, understandable, and immediately useful. The approach is effective because it reduces ambiguity while maintaining flexibility across industries.

---

## Framework Selection

**Chosen Framework:** ROLE

**Why This Framework?**
- Establishes clear perspective and authority.
- Reduces vague outputs by anchoring the response in a professional lens.
- Encourages structured analysis without overcomplicating instructions.

**Why Not Other Frameworks?**
- AIDA: Designed for marketing persuasion, not analytical evaluation.
- SWOT-only framework: Too narrow and limits competitor depth.
- Chain-of-Thought prompting: Encourages internal reasoning but may produce overly verbose outputs for casual users.

---

## Structural Decisions

### Role Anchoring

**The Element:**

```
“You are a Business Consultant, and I am considering launching a [BUSINESS IDEA].”
```


**Why This Works:**

Role assignment immediately frames the tone, analytical lens, and output expectations. It increases consistency and reduces generic commentary.

**What I Tested:**
- “Analyze this business idea” → Produced shallow and inconsistent depth.
- “Act as an expert” → Too broad; outputs varied in tone.
- **“You are a Business Consultant”** → Most consistent balance of structure and practicality.

---

### Clear Deliverable Requirements

**The Element:**

```
Conduct an analysis of the current market by identifying multiple potential competitors. Then, list 5 potential risks for the feasibility of my business idea.
```


**Why This Works:**

Specifying both competitors and exactly five risks prevents incomplete responses. The number requirement improves structure and output reliability.

**Design Logic:**

Quantified requirements reduce ambiguity. Competitor analysis provides external context; risk analysis forces internal feasibility evaluation. Together, they create a balanced assessment.

---

### Placeholder Design

**Placeholder Design:**

```
[BUSINESS IDEA] - Core variable that determines industry, competition, and risk factors.
```


**Why These Placeholders?**

The business idea is the primary variable influencing every output dimension—market dynamics, competitors, and risks. Keeping a single placeholder keeps the prompt adaptable across industries.

**Why Not More/Different Placeholders?**

Additional placeholders (e.g., location, budget, target audience) were excluded to maintain simplicity. Over-specification would increase friction and reduce usability for early-stage ideation.

---

## Key Design Choices

### 1. Casual Language Requirement

**Decision:** Require output in language understandable by anyone inside or outside the business space.

**Reasoning:**

Many founders are early-stage and not industry experts. Casual language improves accessibility and usability.

**Testing Results:**
- Without this element: Outputs were overly technical and jargon-heavy.
- With this element: Outputs became clearer and more founder-friendly.
- Improvement matters because clarity increases practical application.

---

### 2. Example-Based Framing

**Decision:** Include an Example.

**Reasoning:**

Examples reduce ambiguity and improve output structure consistency.

**Evolution:**
- V1: No example → Inconsistent competitor explanations.
- V2: General suggestion → Slight improvement.
- Final: Specific example structure → Most consistent output format.

---

### 3. Bullet-Point Risk Formatting

**Decision:** Require risks in bullet points with short explanations.

**Origin:**

Unstructured paragraphs made risk evaluation harder to scan and apply.

**Impact:**
- Without: Risks buried in long text.
- With: Clear, scannable, actionable risk list.

---

## Iteration Process

### Version 1 → Version 2

I made the prompts more specific about quantities and structure, added output format requirements, and included more actionable elements as well as sentence structure and requirements.

**Problem:** Outputs were inconsistent in structure and often missed either competitor depth or risk clarity.

**Solution:** Added explicit quantity requirements, structural guidance, and output formatting instructions.

**Impact:** Responses became more predictable, easier to scan, and more actionable.

**Key Learning:**

Specific structural constraints significantly improve reliability without reducing flexibility.

---

## Alternative Approaches Considered

### A. SWOT-Only Prompt

**Idea:** Ask for a traditional SWOT analysis.

**Decision:** Chose competitor + risk structure instead.

**Why:** SWOT can be generic and repetitive; competitor framing feels more concrete and practical.

---

### B. Investor-Focused Analysis

**Idea:** Require financial projections and market sizing.

**Decision:** Kept prompt lightweight.

**Why:** Financial modeling adds complexity and limits accessibility for early-stage founders.

---

## When This Prompt Works Best

**Ideal Scenarios:**
- Early-stage idea validation.
- Founders exploring competitive landscapes.
- Brainstorming sessions before formal business planning.

**Less Ideal For:**
- Investment memorandums – Requires deeper financial rigor.
- Regulatory-heavy industries – Needs specialized legal analysis.
- Mature businesses seeking optimization – Requires operational metrics and performance data.

---

## Future Improvements

**Potential Enhancements:**
- Optional region-specific competitor filter.
- Toggle between casual and professional tone.
- Add optional financial risk estimates.

**Why Not Yet:**

The current version balances simplicity and usability. Additional variables would increase complexity and reduce accessibility for quick idea validation.

---

## Testing Notes

**Models Tested:**
- Gemini - Produced structurally sound responses but required stronger formatting instructions for consistent bullet usage.

**Typical Performance:**
- Strong competitor identification.
- Clear risk articulation.
- Occasionally needs refinement for depth in niche industries.

---

## Attribution & Inspiration

**Frameworks:**
- ROLE Framework
- Structured output constraint methodology

**Learning Sources:**
- Prompt Frameworks PDF.

---

*This methodology document demonstrates my design thinking and decision-making process.*
