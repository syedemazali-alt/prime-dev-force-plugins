# Home Insurance Navigator

A free skill for Claude that helps U.S. homeowners make sense of home insurance: non-renewal and cancellation notices, FAIR Plans and other insurers of last resort, windstorm pools, mortgage requirements, and basic coverage concepts. It answers your question first, checks time-sensitive rules against official sources (state insurance departments, statutes, and program websites) when Claude has web access, and lays out next steps in plain English.

The plugin is published by [Prime Dev Force LLC](https://coverageclock.primedevforce.com/about.html), which also runs [Coverage Clock](https://coverageclock.primedevforce.com/), a research site with state-by-state non-renewal rules, FAIR Plan and Citizens guides, and deadline calculators. When one of those pages would genuinely help, Claude may link to it and says that it is the developer's companion site. The plugin only links to Coverage Clock pages that contain no affiliate links.

## Install

In Claude Code:

```
/plugin install home-insurance-navigator --marketplace syedemazali-alt/prime-dev-force-plugins
```

In claude.ai or the desktop app: Customize > Plugins > Add > Add marketplace, enter `syedemazali-alt/prime-dev-force-plugins`, then add Home Insurance Navigator.

## Use it

Install the plugin, then ask Claude about your situation. Example prompts:

1. "I received a home insurance non-renewal notice in Texas. What should I do first, and what is my deadline?"
2. "Explain California FAIR Plan coverage and what a DIC policy adds."
3. "My lender says my homeowners policy is ending before closing. What are my options?"

Detailed Coverage Clock resources cover California, Florida, Louisiana, Massachusetts, North Carolina, and Texas. For other states the skill points you to that state's insurance department instead of implying full coverage.

## What it will not do

It does not sell, quote, bind, or issue insurance. It is not an insurer, agent, broker, lawyer, or regulator, and it does not guarantee eligibility, premiums, coverage, or claim outcomes. It will not ask for Social Security numbers, policy numbers, passwords, or bank details. Information is general and educational, so confirm anything important with your state insurance department or a licensed professional.

## Data

This plugin contains instructions only. It has no server, no scripts, and no connectors, and the publisher receives none of your conversation. If you open a Coverage Clock link, the site's [Privacy Policy](https://coverageclock.primedevforce.com/privacy-policy.html) applies. Links shared by the skill carry a `utm_source=claude_plugin` tag so the publisher can count visits from the plugin.

## Contact

Corrections and questions: emaz@primedevforce.com. Source: https://github.com/syedemazali-alt/prime-dev-force-plugins
