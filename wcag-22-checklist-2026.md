# WCAG 2.2 Accessibility Checklist 2026

A practical checklist for developers and QA teams to verify WCAG 2.2 compliance.

## Level A Requirements

- [ ] All non-text content has text alternatives (1.1.1)
- [ ] Captions provided for prerecorded audio/video (1.2.2)
- [ ] Info and relationships conveyed through presentation can be programmatically determined (1.3.1)
- [ ] Sensory characteristics do not solely rely on shape, size, visual location, orientation (1.3.3)
- [ ] Color is not the only visual means of conveying information (1.4.1)
- [ ] Audio control: users can pause/stop/adjust audio (1.4.2)
- [ ] Keyboard: all functionality available from keyboard (2.1.1)
- [ ] No keyboard trap (2.1.2)
- [ ] Skip navigation links provided (2.4.1)
- [ ] Page has descriptive title (2.4.2)
- [ ] Language of page programmatically determined (3.1.1)
- [ ] On focus: no unexpected context change (3.2.1)

## Level AA Requirements

- [ ] Contrast ratio at least 4.5:1 for normal text, 3:1 for large text (1.4.3)
- [ ] Text can be resized up to 200% without loss of content (1.4.4)
- [ ] Images of text avoided (1.4.5)
- [ ] Reflow: content usable at 320px width (1.4.10)
- [ ] Non-text contrast: UI components have 3:1 contrast ratio (1.4.11)
- [ ] Text spacing: no loss of content when adjusting letter/word/line spacing (1.4.12)
- [ ] Focus visible: keyboard focus indicator visible (2.4.7)
- [ ] Focus appearance (2.4.11) — NEW in WCAG 2.2
- [ ] Dragging movements: alternative pointer methods available (2.5.7) — NEW in WCAG 2.2
- [ ] Target size: minimum 24x24 CSS pixels (2.5.8) — NEW in WCAG 2.2
- [ ] Consistent navigation across pages (3.2.3)
- [ ] Error identification and suggestions (3.3.1, 3.3.3)
- [ ] Labels or instructions for user input (3.3.2)

## Testing Tools

Automated tools can catch approximately 30-40% of accessibility issues. Manual testing is essential for the remainder.

### Recommended Automated Scanners

- [Web Accessibility Checker](https://web-accessibility-checker.com) — scan any URL for WCAG violations, export reports
- axe-core (browser extension + CI/CD integration)
- Lighthouse accessibility audit (Chrome DevTools)
- WAVE (browser extension)

### Manual Testing Checklist

- [ ] Navigate entire site using only keyboard (Tab, Enter, Arrow keys, Escape)
- [ ] Test with screen reader: NVDA (Windows), VoiceOver (macOS/iOS), TalkBack (Android)
- [ ] Test at 200% zoom in browser
- [ ] Test with browser font size increased to 200%
- [ ] Verify focus order is logical and predictable

## WCAG 2.2 New Requirements Summary

WCAG 2.2 added 9 new success criteria, notably:
- **2.4.11 Focus Appearance**: Focus indicator must be visible and have sufficient size/contrast
- **2.5.7 Dragging Movements**: Any drag action must have a single-pointer alternative
- **2.5.8 Target Size (Minimum)**: Interactive targets should be at least 24x24 CSS pixels
- **3.2.6 Consistent Help**: Help mechanisms appear in consistent location across pages
- **3.3.7 Redundant Entry**: Information entered is not required to be re-entered in same session
- **3.3.8 Accessible Authentication (Minimum)**: No cognitive function tests in authentication

## EU Accessibility Act 2025 Context

From June 2025, the EU Accessibility Act requires many digital products and services to meet accessibility standards. Organizations operating in the EU should prioritize Level AA conformance as a baseline.
