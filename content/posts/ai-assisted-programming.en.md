---
date: '2024-12-29T17:12:16+08:00'
title: "What I've Learned from AI-Assisted Programming"
---

Recently, I have been extensively using AI to assist with programming. Here are a few key points to discuss:

1. The current capabilities of AI-assisted programming
2. How we can effectively leverage AI
3. The impact of AI-assisted programming on average developers

### Current Capabilities

From my experience, using tools like Claude 3.5 Sonnet, AI can handle tasks ranging from project setup to specific feature development. The code it generates is comparable to that of a mid-level engineer with 3-5 years of experience. With more detailed requirements, the output can be even more structured and aligned with common software engineering practices.

If we stop here without any caveats, it's easy to draw an anxiety-inducing conclusion: Is AI going to replace programmers? This is an irresponsible statement because it doesn't specify the timeline or the exact process of replacement. What aspects will AI replace? Can it autonomously complete all tasks with just a brief description from us?

Anyone who has tried current AI programming tools would find it hard to draw such a conclusion. Predicting the future is also futile, as history shows that technology evolves and roles change. For those willing to learn, this isn't a problem. The world of computing has always been this way. When technology changes, it's not that people lose their jobs; rather, the same people take on different roles.

With the enhancement of AI programming capabilities, tools like Zed and Cursor have integrated AI into the development workflow. AI can now read existing code and develop features that align well with the current codebase, minimizing the need for extensive adjustments. Models with larger context lengths, like Claude 3.5 with its 200k context, have a significant advantage.

Especially when working with unfamiliar tech stacks, such as a front-end developer needing to develop a back-end project, AI can generate well-structured projects and database designs.

However, all of this requires a well-described set of requirements, including technical details. If we overlook these details, the AI-generated code might not meet our needs, necessitating multiple iterations to achieve the desired outcome.

For example, if we need to implement a JWT token-based authentication flow, different prompts can yield slightly different results (though prompt differences are less critical with current AI capabilities).

| Prompt | Possible Outcome |
| --- | --- |
| Implement a JWT-based authentication flow | Generates functional code |
| Implement a JWT-based authentication flow with best practices | Includes security considerations, such as adding a refresh_token |

The issue isn't the varying quality of code based on the prompt but how humans use the AI-generated code.

For instance, as a non-backend developer, I might not understand why AI includes a refresh_token in the table design or the relationship between access_token and refresh_token.

Thus, in the AI era, the skill level of developers significantly influences the quality of AI output. **The developer's expertise determines the quality of AI output.**

This is why GitHub Copilot is aptly named "Copilot" and not "Pilot." The real driver is the human, and AI is just another tool.

However, if the programmer is unfamiliar with the problem domain or unsure of the solution approach, the AI-generated code might be less usable. Issues such as library version compatibility or incorrect problem-solving strategies may arise. In such cases, human guidance is essential to direct the AI on where to start looking for issues and what potential problems to consider. Relying solely on AI to solve problems by reading code is currently unlikely to identify the critical points, leading to unresolved issues. This may improve in the future.


### How We Can Leverage AI

Continuing from the previous example, does this mean that junior developers or those unfamiliar with certain areas will be replaced by AI? Not entirely. AI can serve as a comprehensive teacher, explaining concepts like the purpose of a refresh_token.

This has a significant impact on developers, as it allows us to tackle tasks outside our usual tech stack and learn more details within our known stack.

However, this requires two prerequisites:

- The ability to ask questions
- Awareness of what you don't know

Leveraging AI effectively means improving these two abilities.

The ability to ask questions is crucial. If you can't frame and describe your problem well, AI can't provide good answers. While AI interactions are conversational, providing context and specific requirements upfront is more efficient, similar to seeking help on Reddit or GitHub.

The second point, "you don't know what you don't know," isn't a skill but a limitation. If you're unaware of an issue, you can't ask relevant questions. For example, a junior engineer might not ask about enhancing JWT security because they might not know it's a concern.

Thus, when using AI for programming, we need to broaden and deepen our understanding of programming. This circles back to the earlier point that **the developer's expertise determines the quality of AI output.**

However, the way we improve has changed. We can now enhance our skills not just by reading books and writing code but also through interactive coding with AI.

For instance, learning about dual token mechanisms for JWT, issuing refresh_tokens via http-only cookies, implementing token blacklists, and revoking device login statuses can all be learned through AI-assisted coding. This learning efficiency is exponentially higher than before, as we might not encounter such details early in our careers without AI.

Therefore, AI capabilities and human skills complement each other, accelerating human learning.

### The Impact of AI-Assisted Programming on Average Developers

Our development model has changed. Here are some personal observations:

- No longer need to write simple, repetitive code; AI can generate it, and humans can review it.
- Focus more on software architecture and design rather than specific implementations.
- Use multiple AI models to modify and optimize code.
- Learn unfamiliar coding and implementation methods from AI-generated code.
- Easily complete code in unfamiliar tech stacks.

In practice, AI can handle basic, repetitive tasks like front-end layouts, styles, and back-end CRUD operations without much issue.

The industry's demand for programmers isn't about replacement but about how to better utilize AI.

With AI, we should use it more to quickly learn unfamiliar concepts and then use that knowledge to guide AI in generating better code. Better code isn't automatically produced by AI but is based on the programmer's experience and understanding.

This is why we shouldn't worry about AI replacing humans. Instead, we should use AI to accelerate our learning.

In the future, a programmer with 3-5 years of experience might have the skill level of someone with 10 years of experience today, as everything is accelerating.

AI/acc.

### Conclusion

- Frequently use AI to develop projects and learn knowledge, architecture, and practices from it.
- Expand your knowledge base from front-end to back-end, to low-level development, and network application development.
- Focus on architecture and design.
- Improve your questioning skills.
