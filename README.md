# Tailwind CSS @apply Directive Error: Undefined Utility Class

This repository demonstrates a common but easily overlooked error in Tailwind CSS: using the `@apply` directive with an undefined utility class.

## The Bug

The bug arises when you use the `@apply` directive with a utility class that isn't defined in your `tailwind.config.js` or isn't loaded through a plugin.  This often results in build errors or unexpected behavior in your application.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install` (or `yarn install` if you prefer).
3. Attempt to build or run the application.  You'll likely see a build error similar to this: 'Undefined utility class'.

## The Solution

The solution involves either:

* **Correcting the class name:** Double-check your class name for typos and ensure it's consistent with your `tailwind.config.js` file.
* **Including necessary plugins:** If the class is defined in a plugin, verify that the plugin is properly installed and configured in your `tailwind.config.js`.

## Bug File (bug.html):

This demonstrates the incorrect usage of the @apply directive.

## Solution File (solution.html):

This demonstrates the correct usage of the @apply directive.
