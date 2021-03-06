Download File and Folder Descriptions

* Using Visual ARIA to Physically See and Learn How ARIA Works.pdf : CSUN presentation printout.

* Files\* : Example and exercise materials for illustrating Visual ARIA functionality.

How Visual ARIA Works

The JavaScript for Visual ARIA is first loaded using roles.js, which then dynamically loads all relevant CSS files that comprise the cascading logic for Visual ARIA.

Configuration settings can be modified at the top of roles.js to set the base local or remote folder path, plus the millisecond delay for evaluating the text alternative computation and role monitoring sequence for the dynamic loader. Visual ARIA will recursively load itself into nested iframe documents when permitted by the browser's same-origin policy.

Instructions

1. Open the files within the Files folder in sequence using the numbered HTM files.

2. Load Visual ARIA using either the local copy or the public bookmarklet, available at
http://whatsock.com/training/matrices/visual-aria.htm

3. Observe the new information displayed that conveys where ARIA is being used.

4. Hover the mouse over various elements and observe the Name and Description computation that is displayed for interactive widget roles. This matches the naming computation described at
http://www.ssbbartgroup.com/blog/how-the-w3c-text-alternative-computation-works/

5. Use the keyboard to set focus to interactive widgets and observe how Visual ARIA conveys additional information for the element that has focus, especially when focus is set on the same elements that include ARIA roles.

How to Interpret Visual ARIA Feedback

When observing interactive widget roles, the colors for Visual ARIA will change depending on the circumstances of interaction. For example, When adding the attribute role="button" to an element, it will convey an orange color on black background, but when focus is set on the same element, it will turn green on a white background to convey that the correct element has focus. Additionally, if the wrong element has focus, such as setting focus to an element inside of an element with role="button", a red color on yellow background will be used to convey an incorrect use of ARIA that may result in accessibility issues for assistive technology users.

Moreover, when interactive widget roles are used and focus is set to one such element, Visual ARIA will suggest keyboard interactions that match the design paradigm for that widget type. In the case of role="button" for example, Visual ARIA will suggest that Space and Enter should activate, and in the case of single tab stop widget roles such as role="radio", role="tab", role="menuitem", role="option", and so on, Visual ARIA will then suggest that the arrow keys should be used to move focus.

This is meant to guide education and development regarding the accompanying scripting behaviors that should be used when building interactive widgets, thus matching all of the ARIA 1.1 role usage algorithms documented at http://whatsock.com/training/matrices/ .

The files within this archive may be modified and changed to try out different ARIA roles, which is an encapsulated testing environment for experimenting with ARIA role usage.

Additional instructions and color combination details are available at
http://whatsock.com/training/matrices/visual-aria.htm#instructions-for-use