Figma  solved this with plugins and their Community (which allows users to create plugins, as well as templates, or share designs): as users grow, more plugins will be created, making the product better for everyone, and spurring more designs to be created (virtuous circle).

This, of course, comes with its set of issues:
- This difficulty is best seen in Figma’s engineering blog posts on building their plugin system. Within a month of [their post](https://www.figma.com/blog/how-we-built-the-figma-plugin-system/) on how they decided the architecture for plugins, they [learned of vulnerabilities](https://www.figma.com/blog/an-update-on-plugin-security/) in their approach and had to switch it out.
- Ensuring the platform can be trusted is not just a matter of technical architecture. Figma doesn’t just host plugins, they also have a centralized [approval process](https://help.figma.com/hc/en-us/articles/360039958914-Plugin-Review-Guidelines), more similar to Apple’s app store than to Sketch’s approach. Plugins that want to be listed must pass Figma’s policies around safety, business, usability, and legal.

For more, see [[Why Figma Wins]]

