---
title: "VPATs and Technical Writers"
date: 2023-05-18
---

Global Accessibility Awareness Day is celebrated on the third Thursday in May every year. One of my favourite accessibility quotes in the scope of modern technology is by the inventor of the internet himself, Tim Berners-Lee: "The power of the Web is in its universality. Access by everyone regardless of disability is an essential aspect."[^1] 

That powerful statement reshaped some of my views when I first heard it, and as I've learned more in the past few years, I've noticed more companies committing to improving the accessibility of their products. One of the starting points for companies is to start filling out the *Voluntary Product Accessibility Template (VPAT).* This template was created by the Information Technology Industry Council (ITI) as a standardized format for vendors to acknowlege and report the accessibility features of their products and services. The *VPAT* helps organizations and consumers assess whether the accessibility level of a product or service meets their needs.

The following versions of the *VPAT*[^2] exist to align with different markets and contract requirements:
- VPAT 2.4 Rev 508: This version aligns with the revised Section 508 standards to meet the U.S. Federal accessibility standard.
- VPAT 2.4 Rev EU: This version aligns with the EN 301 549, which is the European Union’s standard for accessibility.
- VPAT 2.4 Rev WCAG: This version aligns with the WCAG 2.1 or ISO/IEC 40500 (equivalent to WCAG 2.0) and WCAG2.1 guidelines. The Web Content Accessibility Guidelines (WCAG) are technical standards on web accessibility developed by the World Wide Web Consortium (W3C).
- VPAT 2.4 INT: This version incorporates all three of the standards above.

The engineering teams are responsible for several portions of the templates becuase they are related to how the product was built, but some of the template is related to support documention. This is a good chance for you to review your documentation and make sure it supports the accessiblity needs. It's imperative that you are honest in your review, because someone who is using your documentation is going to notice if something that affects them is documented in appropriately, and they'll lose faith in your product if you've tried to hide something. The point of this document is to acknowledge the current state and document it so that showe who are affected know what to expect. 

I'm most familiar with the INT version, so I'll walk through the template as technical writers interact with it, and then talk through some ways to proceed with the information you've gathered.

Level A
- 1.1.1 Non-text Content (Level A)
- 1.2.1 Audio-only and Video-only (Prerecorded)
- 1.2.3 Audio Description of Media Alternative (Prerecorded)
- 1.2.1 Info and Relationships
- 1.3.2 Meaningful Sequence
- 1.3.3 Sensory Characteristics
- 1.4.1 Use of Color
- 1.4.2 Audio Control
- 2.1.1 Keyboard
- 2.1.2 No Keyboard Trap
- 2.2.1 Timing Adjustable
- 2.2.2 Pause, Stop, Hide
- 2.3.1 Three Flashes or Below Threshold
- 2.4.1 Bypass Blocks
- 2.4.2 Page Titled
- 2.4.3 Focus Order
- 2.4.4 Link Purpose (In Context)
- 3.1.1 Language of Page
- 3.2.1 On Focus
- 3.2.2 On Input
- 3.3.1 Error Identification
- 3.3.2 Labels or Instructions
- 4.1.1 Parsing
- 4.1.2 Name, Role, Value

Level AA
- 1.2.4 Captions (Live)
- 1.2.5 Audio Description (Prerecorded)
- 1.4.3 Contrast (Minimum)
- 1.4.4 Resize Text
- 1.4.5 Images of Text
- 1.4.11 Non-text Contrast
- 1.4.12 Text Spacing
- 1.4.13 Content on Hover or Focus
- 2.4.5 Multiple Ways
- 2.4.6 Headings and Labels
- 2.4.7 Focus Visible
- 3.1.2 Language of Parts
- 3.2.3 Consistent Navigation
- 3.4.2 Consistent Identification
- 3.3.3 Error Suggestion
- 3.3.4 Error Prevention (Legal, Financial, Data)
- 4.1.3 Status Messages

Level AAA
- 1.2.6 Sign Language (Prerecorded) 
- 1.2.7 Extended Audio Description (Prerecorded) 
- 1.2.8 Media Alternative (Prerecorded) 
- 1.2.9 Audio-only (Live) 
- 1.3.6 Identify Purpose (Level AAA 2.1 only)
- 1.4.6 Contrast (Enhanced) 
- 1.4.7 Low or No Background Audio 
- 1.4.8 Visual Presentation 
- 1.4.9 Images of Text (No Exception) 
- 2.1.3 Keyboard (No Exception) 
- 2.2.3 No Timing 
- 2.2.4 Interruptions 
- 2.2.5 Re-authenticating 
- 2.2.6 Timeouts (Level AAA 2.1 only)
- 2.3.2 Three Flashes 
- 2.3.3 Animation from Interactions (Level AAA 2.1 only)
- 2.4.8 Location 
- 2.4.9 Link Purpose (Link Only) 
- 2.4.10 Section Headings 
- 2.5.5 Target Size (Level AAA 2.1 only)
- 2.5.6 Concurrent Input Mechanisms (Level AAA 2.1 only)
- 3.1.3 Unusual Words 
- 3.1.4 Abbreviations 
- 3.1.5 Reading Level 
- 3.1.6 Pronunciation 
- 3.2.5 Change on Request 
- 3.3.5 Help 
- 3.3.6 Error Prevention (All) 

As you can see, documentation falls under a lot of criterion on the template. For full descriptions of each of the criterion, see [Web Content Accessibility Guidelines (WCAG) 2.0](https://www.w3.org/TR/2008/REC-WCAG20-20081211/). But to break it down into general statements, we can use a more general checklist.

Does your content have 

[^1]: [IPO Press Announcement](https://www.w3.org/Press/IPO-announce)
[^2]: [VPAT Template](https://www.itic.org/policy/accessibility/vpat)
