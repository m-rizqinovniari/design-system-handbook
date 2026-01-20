---
title: Glossary
sidebar_position: 99
---

# Glossary

A glossary of important terms in design systems used throughout this learning module.

## A

**Accessibility**
Standards and design practices that ensure digital products can be used by everyone, including users with disabilities. Includes color contrast, keyboard navigation, and screen reader support.

**Adaptive Design**
A design approach that adjusts not only layout but also interaction patterns based on device capabilities, input methods, and user context. Goes beyond responsive design.

**Affordances**
Visual cues that suggest how an element can be used. For example, buttons look pressable, sliders look draggable.

**Atomic Design**
A methodology that breaks down interfaces into a hierarchy of components: atoms, molecules, organisms, templates, and pages. Developed by Brad Frost.

**Atoms**
The most basic UI elements that cannot be broken down further without losing meaning. Examples: buttons, input fields, labels, icons, and design tokens.

## B

**Base Tokens**
See **Foundational Tokens**.

**Brand Guidelines**
Documents that define brand identity across all media, including logos, colors, typography, and brand voice. Different from UI style guides that focus on digital interfaces.

**Breakpoints**
Points in responsive design where layout changes to accommodate different screen sizes. Typically defined in pixels or relative units.

## C

**Centralized Governance**
A design system governance model where a core design system team has full authority over all decisions. Suitable for small to mid-size organizations.

**Code Implementations**
Front-end components and libraries that implement the design system in code. Bridges design and software engineering.

**Color Contrast Ratio**
A measure of the difference in luminance between two colors, typically text and background. WCAG standards require a minimum ratio of 4.5:1 for normal text and 3:1 for large text.

**Color Theory**
The structured study of how colors interact, how they are perceived by humans, and how they can be combined to create meaning. In UI design, color becomes a communication system.

**Component-Based Design**
A design approach that focuses on creating reusable UI components using systematic methods, ensuring consistency in appearance and behavior.

**Component Granularity**
The level of detail or size of components in a system. Decisions about how small or large components should be designed, with implications for reusability and flexibility.

**Component Tokens**
Tokens that define how individual UI components use design values. Examples: `button.primary.background.default`, `input.border.focused`.

**Components**
Reusable UI elements such as buttons, inputs, modals, and navigation. Enable reuse and faster product development.

**Complex Components**
Components composed of multiple smaller components, managing state (loading, error, empty), and often involving business logic. Examples: data tables with sorting, filtering, and pagination.

**Consistency**
In scalable systems, consistency means **predictability**—users can anticipate how the interface behaves, and teams can anticipate how to build features.

**Continuous Improvement**
An iterative process for improving the design system based on feedback, usage, and evolving needs. Involves structured feedback cycles.

## D

**Dark Mode**
A visual theme that uses dark colors as the primary background, reducing eye strain in low-light conditions and saving power on OLED screens.

**Design Debt**
The accumulation of short-term design decisions that create long-term problems, such as inconsistency, duplication, and maintenance difficulties.

**Design Patterns**
Proven solutions to recurring interaction problems. Examples: navigation drawer, multi-step form, notification system. Captures not only visuals but also behavior, accessibility, and edge cases.

**Design Principles**
High-level values that guide decisions in a design system. Ensure coherence and decision-making alignment across teams.

**Design System**
A structured collection of reusable components, shared principles, and documented standards that guide how digital products are designed and built. A living, evolving, and operational system.

**Design Tokens**
Named, reusable variables that store design decisions such as colors, spacing, typography, and motion in a technology-agnostic format. Single source of truth that connects design tools, codebases, and platforms.

**Distributed Governance**
A governance model where ownership is pushed to individual product teams. Teams can extend or modify the system independently, often guided by shared principles rather than strict rules.

**Documentation**
Guidelines for the usage and behavior of components and patterns. Enables correct adoption and implementation. Without documentation, even well-designed systems fail.

## E

**Edge Cases**
Unusual or unexpected usage scenarios that may not be handled by standard components. Must be handled without breaking system consistency.

**Elevation Tokens**
Tokens that represent depth through shadows or z-index layers. Important in material-inspired or layered UIs.

**Error State**
A component state that indicates something has gone wrong or input is invalid. Must provide clear and actionable feedback.

## F

**Federated Governance**
A governance model where a core team maintains the core system, while representatives from product teams contribute changes and advocate for local needs. Balances scale with collaboration.

**Feedback**
Confirmation that an action has occurred. Examples: loading indicators, success messages, error alerts. Ensures users understand the results of their interactions.

**Foundational Tokens**
Also called primitive or base tokens. Store raw, context-free values such as color values (`#FFFFFF`, `#0A2540`), font families (`Inter`, `Roboto`), and base spacing units (`4px`, `8px`). Intentionally non-semantic.

**Foundations**
Often implemented as design tokens. Includes colors, typography, spacing, and motion. Creates visual and functional consistency.

**Figma**
A collaborative design tool that has evolved into the central nervous system for design systems. Supports component libraries with variants, design tokens through styles, and team publishing.

## G

**Governance**
How decisions are made, who makes them, and how those decisions are enforced or evolved over time. Without clear governance, design systems often drift into chaos.

**Grid System**
An underlying structure that organizes content into columns and rows, ensuring visual consistency and predictability. Grids are the invisible scaffolding that holds layouts together.

## H

**Hierarchy**
A visual structure that shows the importance of elements. Created through size, weight, color, and spacing. Helps users scan content quickly.

## I

**Interaction Design**
Focus on how users act and how systems respond. Determines what happens when users engage with the interface.

**Inconsistency**
A problem that arises when UI elements look or behave differently across different parts of a product, forcing users to relearn basic patterns.

## L

**Layout System**
Rules that govern how content is arranged in space. Includes grids, containers, and columns that ensure consistent structure.

## M

**Material Design**
A comprehensive design system introduced by Google in 2014. Built on the metaphor of physical materials, with a focus on depth, shadows, and predictable motion.

**Molecules**
Groups of atoms combined to form functional units. Examples: search field with label and button. Begin to express intent and functionality.

**Motion Tokens**
Tokens that define transitions, duration, and easing for animations and feedback. Ensures consistency in motion across the system.

## O

**Organisms**
Relatively complex components composed of molecules and atoms. Examples: header, navigation bar, product card, or comment section. Often define clear regions of an interface.

## P

**Pages**
Specific instances of templates populated with real content. The most concrete level and closest to what users actually see.

**Pattern Library**
Documentation of recurring design patterns and how to use them. Different from component libraries that focus on individual UI elements.

**Patterns**
Common solutions to recurring problems. Reduces cognitive load and design debt. Examples: form patterns, navigation patterns, feedback patterns.

**Primitive Tokens**
See **Foundational Tokens**.

## R

**Responsive Design**
A design approach that allows layouts to adapt flexibly across different screen sizes and devices. Uses fluid grids, flexible images, and breakpoints.

**Reusability**
The ability of components or patterns to be used across different contexts without modification. An important quality in scalable design systems.

## S

**Semantic Tokens**
Tokens that build on foundational tokens by assigning meaning and usage context. Explain *why* a value exists, not just *what* it is. Examples: `color.text.primary`, `color.background.surface`.

**Semantic Versioning**
A versioning scheme that uses the format MAJOR.MINOR.PATCH (e.g., 2.3.1) to communicate the impact of changes. Borrowed from software engineering.

**Spacing System**
A set of predefined spacing values used consistently throughout a design. Typically built from a base unit (e.g., 4px or 8px) and constructed as multiples.

**Spacing Tokens**
Tokens that control margins, padding, and layout gaps. Usually follow a scale to enforce rhythm and prevent arbitrary values.

**States**
Temporary conditions of a component based on interaction or system status. Examples: default, hover, active, focused, disabled, loading, error.

**Storybook**
A tool for building, testing, and documenting UI components in isolation. Serves as a bridge between design and code, enabling designers and developers to discuss the same component with shared context.

**Style Guide**
A document that focuses primarily on visual rules such as colors, typography, and spacing. Different from design systems that include components, documentation, and governance.

**Style Dictionary**
A tool for managing and transforming design tokens into platform-specific formats. Enables a single source of truth for tokens consumed by various platforms.

## T

**Templates**
Define page-level structure without real content. Combine organisms into layouts that demonstrate how components fit together.

**Theming**
The ability to change the visual appearance of a product without changing its underlying structure or behavior. Includes branding, user preferences, and dark mode.

**Typography System**
The disciplined arrangement of text to make content readable, scannable, and meaningful. Defines how text behaves across an interface, not just which font is used.

**Typography Tokens**
Tokens that define font families, sizes, weights, line heights, and letter spacing. Often work together as *typography sets*.

## U

**UI Kit**
A collection of reusable visual components such as buttons, inputs, modals, icons, and layout patterns. Typically lacks deep documentation or code parity compared to a full design system.

**Usage Guidelines**
Documentation that explains when and how to use components or patterns, as well as when *not* to use them. Important for correct adoption.

## V

**Variants**
Structural or contextual differences in components. Different from states which are temporary. Examples: primary vs secondary, small vs large, destructive vs neutral.

**Versioning**
The process of managing changes in a design system by assigning clear version numbers. Enables predictability, accountability, and rollback capability.

**Visual Rhythm**
A predictable pattern of spacing that guides the eye through an interface. Helps users anticipate structure and reduces cognitive load.

## W

**WCAG (Web Content Accessibility Guidelines)**
Accessibility guidelines that ensure web content is accessible to all users. Widely used standards for digital accessibility, including color contrast requirements and keyboard navigation.
