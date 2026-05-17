# Gate 2 Reflection

Building this documentation site clarified something that reading about SSGs alone cannot: navigation is a code decision, not just an editorial one. In Mintlify, the sidebar is a `mint.json` config file. The page hierarchy is a folder structure. Breaking either means broken navigation, which the Vale linting step and GitHub Actions workflow would surface before a user encounters it.

The Vale integration also reinforced something practical. Linting documentation is the same class of problem as linting code. Running Vale on every pull request means style consistency is enforced at the merge level, not left to manual review. That is the same principle behind docs-as-code.

Working in Mintlify specifically deepened something relevant to my current client work. The component model — Cards, Notes, Accordions, CodeGroups — is the same pattern I use on the Lumana GitBook project. The tooling changes but the mental model carries over.
