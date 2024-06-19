# Requirements validation

2 types of projects:
- Business-driven
  - Fixing reported bugs
    - Steps:
      1. Validate the bug
      2. Prioritize the bug
      3. Estimate the fix complexity
      4. Assign the bug to a developer or team
  - Updating existing features or adding new features
    - Steps:
      1. Review requirements - are there any parts in the requirements that are not reasonable according to your best business knowledge?
      2. Review feasability - are there any parts in the requirements that are technolofically not feasible?
         - Examples:
           - asking for data that is not available
           - asking for functionality where runtime complexity is too large for the problem space
      3. Review cost efficiency - are there any parts in the requirements that are too expensive to implement vs. the value it adds to the business?
         - Examples:
           - spending 3 months of developer time for a feature where the estimated saving is $100 / year - the developer salary will make the ROI very small
      4. Iterate with business on the requirements until the requirements satisfy business value (1), technical feasability (2) and cost efficiency (3) 
- Technology-driven
  - No functionality change
    - Business does not need to approve it
    - Types:
      - Refactor code or data structures resulting in performance improvement
      - Refactor code or data structures with no performance improvement
  - Functionality change
    - Business needs to approve it
    - Types:
      - Fixing bugs that are not (yet) visible to business, but critical

# Split the project into sizeable tasks

Each task should have:
- Technical specification
- Concrete deliverable
- Time estimate
