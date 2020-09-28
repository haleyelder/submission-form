# survey-form

Goals 
- [ ] Accesssibility practice 
    - resources/guides
        - https://webaim.org/techniques/forms/controls
        - https://digital.gov/resources/introduction-accessibility/
        - http://web-accessibility.carnegiemuseums.org/code/forms/
        - https://developer.mozilla.org/en-US/docs/Learn/Accessibility/HTML
        - https://www.deque.com/blog/anatomy-of-accessible-forms-best-practices/
        - https://developers.google.com/web/fundamentals/accessibility
            - aria labels, tabindex, semantics, etc
        - https://accessibility.18f.gov/?=dg
        - https://designsystem.digital.gov/components/form-templates/
    - visual (color, contrast, limited visibility)
    - touch/keyboard (tabbing, mobile type)
    - screenreaders
    - semantic
- [ ] light house testing (v1 run through and updates to do below)
    - Background and foreground colors do not have a sufficient contrast ratio.
    - Heading elements are not in a sequentially-descending order (h4 failing element)
    - <html> element does not have a [lang] attribute
    - Form elements do not have associated labels (ran into issue with using materialize items)
    - Links to cross-origin destinations are unsafe. Add `rel="noopener"` or `rel="noreferrer"` to any external links to improve performance and prevent security vulnerabilities.
    - Document does not have a meta descriptionDescription text is empty. Meta descriptions may be included in search results to concisely summarize page content. Learn more.
- [ ] materialize practice

