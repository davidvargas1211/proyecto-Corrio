# Architecture

The implementation intentionally uses a small client-side stack:

- React 19 and TypeScript
- Vite 8
- One semantic landing composition with reusable visual sections
- Local component state for the two-step assessment demonstration
- CSS variables for candidate design tokens and responsive layout rules

There are no environment variables, network calls, analytics scripts, payment APIs, databases or server routes.

## Interaction model

- Navigation anchors scroll to real sections.
- The mobile navigation has an explicit open state and closes with Escape.
- The assessment accepts an optional amount and validates zero/invalid entered values.
- The second step validates company name and email.
- Completion uses a short local-only loading state, then confirms that nothing was sent or stored.
- FAQ uses native `details` and `summary` controls.

## Accessibility foundations

The build uses semantic headings, native controls, persistent labels, associated error messages, visible focus styling, keyboard-accessible navigation, reduced-motion rules and responsive reflow. Browser-assisted accessibility QA remains a required delivery gate.
