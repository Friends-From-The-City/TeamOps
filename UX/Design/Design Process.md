# Product Design Process
## On This Page
[Define The Opportunity] (https://github.com/Friends-From-The-City/TeamOps/blob/main/UX/Design/Design%20Process.md#%EF%B8%8F-define-the-opportunity)

## 🖋️ Define The Opportunity
* Work with your PM to validate who you're designing for, what you're designing, and why you're designing it.
* Help your PM express the who/what/why as a user story. For example, "As a (who), I want (what), so I can (why/value)." If you’re asked to implement a non-evidence-based how, then ask the PM to refocus on the who/what/why, so everyone can work together to find the best how.
* Help your PM to define MVC success criteria, prioritizing MVC “must-haves” and non-MVC “should-haves” and “could-haves.” (Note that this success criteria is subject to change based on new learning from the iterative design process and customer feedback.)

## 🛑 Before You Design
#### Step 1. Generate Ideas
Part of the role of product designers is to lead and facilitate idea generation within our teams. We are all very busy working with PMs to drive forward our product roadmaps and solve known UX problems, but remember there are also undiscovered problems out there that are definitely worth solving. Here are a few activities and resources to inspire you!
* Run a sync (such as a ThinkBig! session), async, or combination workshop to generate ideas. Define a scope and invite participants from product, engineering, ux research, and other areas for best results.
* Reach out to sales, customer success or marketing counterparts for a new perspective. You can also invite these counterparts as optional attendees to your regular meetings.
* Prioritize a round of problem validation research together with Product Managers and UX research. Talk to customers about their experiences building software in a very open-ended way, see what keeps them up at night, what slows them down, and what impedes their productivity.
* Discover unknown pain points:
  * Dovetail is used to analyze data, collaborate on insights, and as our current research repository.
  * Chorus.ai is a tool used by sales reps that records and transcribes sales calls. You can search calls by keyword to narrow  in on what you listen to.
  * Zendesk is also a source of information around existing problems, although it can be a bit harder to parse through the tickets, as they aren't necessarily categorized in a way that is optimal for UX.

#### Step 2. Understand the Space
* Investigate whether there is existing UX Research in the UX Research Archive, Dovetail, or other data that could help inform your decisions and measure results. If there isn't existing UX Research, contact your UX Researcher to conduct (or guide you and your Product Manager in conducting) research for the problem.
* Consider conducting competitive analysis to inform your work. Look for terminology, functionality, and UX conventions that can help refine success criteria. Only stray from industry conventions with strategic intent, such as capitalizing on disruptive innovation opportunities. We want users to migrate from other tools to ours, and they’re more likely to be successful and satisfied when our products use conventions that are familiar based on other tools they've used.
* Consider creating user flows or journey maps to help ensure you've considered the entire workflow and also to help communicate that workflow to your team.

#### Step 3. Investigate Possible Dependencies
It is our responsibility as Product Designers to research how our work can impact other parts of the product and the work that other Product Designers are doing.
* Proactively reach out to other Product Designers (using Slack, Weekly UX Sessions, etc.) to get background information on the product area you are about to start working on and to learn how your product area depends and interacts with others.
* Identify the DRI for the product area you're about to start working on, and involve them in your design process from the beginning. If you are unsure who the DRI is, visit the Product Categories Handbook page.
* Check the Product Kickoff Review to see the list of issues that are currently planned for next release in other stages.

## 🏯 Aim towards "Sophisticated Simplicity"
There are three tenets of sophisticated simplicity to keep in mind as you're designing:
* Structure - Organization and hierarchy of content and concepts into meaningful groups and patterns
* Discovery - Ability to interact and explore that leads to learning and proficiency while being mistake adverse
* Capability - Features and function that allow a user to complete a task and process automation

An imbalance in any of these tenets can lead to a less than ideal experience.

* Structure + discovery without capability creates a simple experience that might be good for static content, but adds little functionality to make the experience more rich.
* Discovery + capability creates a robust, sophisticated, and perhaps intriguing experience, but one that is hard to master as the structure that helps guide discovery and relationships is lacking.
* Structure + capability results in sophisticated complexity where an "everything all the time" interface provides a lot of functionality, but the discovery cues that lead to learning, association, and understanding cause and effect aren't present.

An interface that achieves sophisticated simplicity will reduce friction to access basic functionality and content, provide quick access to powerful features, and help all users become more proficient at completing tasks.

**Here's a sample set of questions you can ask yourself when designing:**

1. Is the content hierarchy and flow clear?
2. Are like items grouped and are groups clearly defined?
3. Does this content or functionality need to be visible all the time and for everyone?
4. Does this content or functionality need to be present in this context? Is it helpful and necessary?
5. Does discovery allow a user to avoid mistakes or recover from them easily?
6. Is the structure in support of discovery and use of advanced capabilities?
7. Is this feature and/or capability even needed or used, or what would happen if it was removed?
8. Is everything "in reach," or is a user left wandering?

Beautifying and "unboxing" the UI
There are two evergreen design efforts that align with sophisticated simplicity:

* Beautifying the UI - Clean up a portion of the UI — from a single component to an entire page or experience — to create more consistency, organization, and aesthetic improvements. Learn more in the Beautifying our UI section of the handbook.
* Unboxing the UI - Boxes are currently overused to convey hierarchy, layout content, and divide pages into sections, but there are better ways. Learn more in this video on "Unboxing" the UI.

## ♾️ Ideate and Iterate
Iterative design at GitLab combines the two industry-standard definitions of "incremental design" and "design iteration." Put simply, iterative design is the process of breaking down design solutions into the smallest change possible that improves the user's outcome. It's getting things quickly into the product to get feedback early and guide refinement.

When applying iterative design, you should consider the longer-term strategy or vision and work with your Product Manager to plan successive releases until it's realized.

* Share design ideas in the lowest fidelity that still communicates your idea. To keep the cost of change low, only increase fidelity as design confidence grows and implementation requires.
* Ask for feedback from your PM throughout the design process to help refine your understanding of the problem and solution criteria.
* Engage engineering peers early and often. Their insight into technical costs and feasibility is essential to determining viable designs and MVCs. Also, invite design feedback, especially if you’re solving for a development workflow they’re familiar with.
* Ask for feedback from other Product Designers in Design Reviews to help improve your work. At minimum, you'll get objective feedback and new ideas that lead to better solutions. You might also get context you didn’t know you were missing industry-standard design conventions.
* Collaborate with your group's Technical Writer when the work involves substantial UI text, such as user-assistance or links back to documentation. For details on how to collaborate, see the UI text Planning and authoring section of the Technical Writing handbook. Additionally, involve your technical writer in the review process for smaller copy changes, such as UI elements labels.
* For a significant UX change, like a new workflow or feature, include your Product Design Manager in feedback sessions, as they might have input into the overall direction of the design or knowledge about initiatives on other teams that might impact your own work.
* If the team does not have a high level of confidence in a direction, there are multiple design solutions, or the direction is a significant risk, validate your proposed solution with customers/users by leveraging ux research methods. If the team has a high level of confidence in a direction or design solution and the risk is low, it's fine to gather feedback from customers only after releasing the MVC.
* Use the design and UI changes checklist to help you think through how your design will read, look, and behave.

## Deliver
* Once your work is complete and all feedback is addressed, make sure that the issue description, the SSOT, is updated with a section called "Solution". This is where you should direct people when they have questions about what should be done and how. If you use a UX issue, please update the main issue as well.
* Include your design in the "Solution" section. For small designs that don't need extra explanation or demonstration of interactions, a mock-up here is sufficient. For more involved changes, include a link to the Figma file.
* Use the design handoff checklist to make sure all design specifications are documented and you're setting up Engineers for success.
* When sharing design work, utilize both Figma's collaboration tools and GitLab's design management features. In the following table, you’ll find a few common scenarios along with the recommended tool. Use this as a starting point, and when in doubt, make the best decision that moves the design forward.

Scenario | Figma / Sketch / UXPIN | Design Management
--- | --- | ---
Co-designing within a shared file | ✔️ | 
Providing, or seeking feedback while a design is still in progress | ✔️ | 
Seeking feedback on a design with a larger audience | | ✔️
When feedback directly impacts an issue | | ✔️
Presenting design options or variations so the team can choose a direction | | ✔️
Sharing a prototype | ✔️ | 
Adding a to-do for a designer as it relates to in-progress design | ✔️ |
Adding a to-do for a designer as it relates to an issue | | ✔️
Identifying visual regressions | | ✔️
Detailed redlines or specs | ✔️ |

* If the solution needs to be broken out into smaller issues for implementation, apply the workflow::planning breakdown label and stay involved by walking PM and Engineering through the proposed solution and participating in the conversation to break down the issue.
* If the solution needs to be scheduled by PM and/or EM, apply the workflow::scheduling label and mention the responsible product manager to schedule it. It is also the Product Designer's responsibility to communicate with the assigned engineer to ensure they understand the solution.
* If the issue is meant for implementation in the current milestone, review the solution with the assigned engineer(s) and/or engineering manager. If they are comfortable with the solution, you can apply the workflow::ready for development label.
* There are times that a Product Manager might request that an issue is moved to the Build phase before the Product Designer feels that the experience meets UX Department standards. In that case, the Product Designer should create follow-on issues and/or apply the UX debt label to indicate that the product doesn’t meet UX requirements and will require immediate iteration.

## ↗️ Follow Through
* Encourage Engineers to scope down features into multiple merge requests for an easier, more efficient review process.
* When breaking down features into multiple merge requests, consider how the UX of the application will be affected. If merging only a portion of the total changes will negatively impact the overall experience, consider using a feature branch or feature flag to ensure that the full UX scope ships together.
* When breaking solutions into smaller parts, make sure to share the end design goal, so that the entire team has context. 
* Giving everyone the full picture helps developers write code aimed at achieving that goal in the future.
* Keep the issue description updated with the agreed-on scope, even if doesn’t impact your work. This is everyone’s responsibility. The issue description must be the Single Source Of Truth (SSOT), not the discussion or individual comments.
* Not all issues are scheduled immediately, which means changes are likely needed when the issue is prioritized. The Product Designer responsible for a particular stage group should be aware of open issues within their product area and work to prioritize them accordingly with their respective Product Managers, even if they are not the original designer who worked on the issue.
* To stay up to date with issues in your product area, subscribe to the label that matches your stage group.
* Review issues within your stage group label regularly.
* Actively contribute to planning meetings to ensure all open issues are being discussed and prioritized.
* When working on an issue, keep the SSOT in the description updated until the issue is closed. This applies to both text and mockups. Previous content (by a PM, for example) should be removed or archived into a separate section in the description. If the developer working on the issue ever has any questions on what they should implement, they can ask the designer to update the issue description with the design.
* For obvious changes, make the SSOT description update directly. You don’t need to wait for consensus. Use your judgement.
* When the issue is actively being worked on, make sure you are assigned and subscribed to the issue. Continue to follow both the issue and related merge request(s), addressing any additional UX issues that come up.

For changes that affect Pajamas, such as introducing a new UI component, refining an existing component, or adding significant clarity to the usage of a component, you should take the following additional steps:
* For changes that affect the user interface: Create a UX Pattern issue in GitLab Design and follow its checklist to record the new standard.
* For other changes: Create an issue and/or MR in the Design System to update the documentation.
* As applicable, create issue(s) to update areas of the application that are affected by this pattern.
* Add an agenda item to the next UX weekly call to inform everyone of those changes.
* If the change/addition is a significant one, consider adding it to the Company Call to inform the company of the changes.

## 👀 Follow-up after your changes go live
* Listen for feedback. If you receive feedback (positive or negative), create an issue to track it. This can be feedback in social media, Slack, or internet forums; internal or external.
