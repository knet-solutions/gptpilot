11. **Technical Writer agent** writes documentation for the project.

<br>

# 🕴How's GPT Pilot different from _Smol developer_ and _GPT engineer_?

- **GPT Pilot works with the developer to create a fully working production-ready app** - I don't think AI can (at least in the near future) create apps without a developer being involved. So, **GPT Pilot codes the app step by step** just like a developer would in real life. This way, it can debug issues as they arise throughout the development process. If it gets stuck, you, the developer in charge, can review the code and fix the issue. Other similar tools give you the entire codebase at once - this way, bugs are much harder to fix for AI and for you as a developer.
  <br><br>
- **Works at scale** - GPT Pilot isn't meant to create simple apps but rather so it can work at any scale. It has mechanisms that filter out the code, so in each LLM conversation, it doesn't need to store the entire codebase in context, but it shows the LLM only the relevant code for the current task it's working on. Once an app is finished, you can continue working on it by writing instructions on what feature you want to add.

# 🍻 Contributing
If you are interested in contributing to GPT Pilot, join [our Discord server](https://discord.gg/HaqXugmxr9), check out open [GitHub issues](https://github.com/Pythagora-io/gpt-pilot/issues), and see if anything interests you. We would be happy to get help in resolving any of those. The best place to start is by reviewing blog posts mentioned above to understand how the architecture works before diving into the codebase.

## 🖥 Development
Other than the research, GPT Pilot needs to be debugged to work in different scenarios. For example, we realized that the quality of the code generated is very sensitive to the size of the development task. When the task is too broad, the code has too many bugs that are hard to fix, but when the development task is too narrow, GPT also seems to struggle in getting the task implemented into the existing code.

# 🔗 Connect with us  

🌟 **If you find GPT Pilot useful, please consider [starring the repo](https://github.com/Pythagora-io/gpt-pilot)!** It helps us grow and continue improving the project. 🌟  

💬 **Need help or have questions?**  
- Join our [Discord community](https://discord.gg/HaqXugmxr9) to connect with other users and our team.  
- Visit our [Contact Us](https://github.com/Pythagora-io/gpt-pilot/wiki/Contact-Us) page for additional support.  

📖 **Learn more about Pythagora & GPT Pilot:**  
- Explore our [Wiki](https://github.com/Pythagora-io/gpt-pilot/wiki) for in-depth documentation.  
- Check out our [FAQ](https://github.com/Pythagora-io/gpt-pilot/wiki/Frequently-Asked-Questions) for common questions and troubleshooting tips.
- Visit our [YouTube](https://www.youtube.com/@pythagoraa) channel for demos and how-to videos.
