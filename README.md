# MOVED TO CODEBERG

## Migrating from GitHub to Codeberg

Many developers are shifting from GitHub to [Codeberg](https://codeberg.org/), a European, community-driven platform. This move is largely fueled by a desire for greater data sovereignty and a commitment to open-source ethics.
Why Developers are Leaving GitHub
- **Corporate Ownership**: Concerns over Microsoft’s influence on data privacy and potential censorship.
- **Legal Risks**: Hosting with US-based companies subjects data to American jurisdiction, specifically laws like the **Patriot Act**, **CLOUD Act** and **FISA**, which allow broad government surveillance and data access.
- **Performance**: Increasing reports of GitHub becoming bloated or unreliable, particularly with CI/CD tools.
- **AI Ethics**: Friction regarding GitHub Copilot and the use of open-source code for training proprietary models.

## Why Choose Codeberg?
- **Non-Profit Governance**: Operated by a European non-profit dedicated to transparency, not shareholders.
- **Legal Protections**: Benefiting from stricter European data protection regulations.
- **Seamless Transition**: Offers a familiar Gitea-based interface that minimizes the learning curve.
- **Community First**: Focuses on serving the developer community rather than monetizing user data.

[https://codeberg.org/olibf/runax](https://codeberg.org/olibf/runax)

# Run a program in windows as a different user

## a bit of history
The reason for this little tool for me was that in the company I was working we had
use two different active directory users for our work. Most tasks could be done by the
main user account but all development tasks had to be executed as a different user.
So we had to start Visual Studio another dev tools as a different user every time.
Even though, it's possible to start a program as a different user by right-clicking
and selecting 'Run as different user', I kind of find the usability of this approach
unsatisfactory. The same is with the built-in command 'runas'.

Both the above options are far more sophisticated, sanitised and generally bullet
prove than this little project. I just wanted to be able to start a program without
any parameters but with a username and password in one command. That's what it
currently does.

This project needs cleanup and more documentation. Let's say it's on my todo list.

Handle with care and (more importantly) HAVE FUN!

Cheers! Oli
