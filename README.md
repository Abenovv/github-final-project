# This is the README.md file for the **github-final-project**

A calculator that calculates simple interest given principal, annual rate of interest and time period in years.

## Input

- `p`: principal amount
- `t`: time period in years
- `r`: annual rate of interest, expressed as a percentage

## Output

```text
simple interest = p * t * r / 100
```

## Run

The sample requires Bash and the `bc` command:

```bash
bash simple-interest.sh
```

For principal `1000`, time `2`, and annual rate `5`, the expected interest is `100.00`.

This is an educational sample. Do not use it in production; it does not validate input or implement financial product rules.

## Attribution and license

The supplied script is attributed to Upkar Lidder (IBM). Additional author: Abenovv. Supporting documentation and small script edits were prepared with AI assistance for learner review. The script retains the supplied arithmetic, clarifies the percentage formula in its comment, uses `read -r`, and quotes the final output variable. The course lab names Md Haroon Hussain as the lab author and licenses its content under Apache 2.0.

The code of conduct uses the official Contributor Covenant 2.1 template with a project-specific public issue-reporting contact. Do not include sensitive or personal information in public reports.

Code is provided under the Apache License 2.0 in `LICENSE`. Community conduct and contribution information are in `CODE_OF_CONDUCT.md` and `CONTRIBUTING.md`.
