# ✔️ Design Reviews
Sharing work and gathering feedback can happen at any time within the design process. We do this most frequently by sharing mocks and having open discussions in issues.
Design Reviews are a dedicated space for Product Designers to give and receive specific and sometimes in-depth feedback on ideas and possible solutions. Other benefits include:
* Discover what others are working on.
* Identify any overlapping work.
* Help surface opportunities for where group work should overlap.
* Encourage the practice of sharing ones work.

We default to asynchronous design reviews so everyone can participate. Asynchronous Design Reviews are very similiar to their synchronous equivalent: designers share their work and provide context so their peers can offer valuable and constructive feedback. Product Design Managers are encouraged to coordinate Design Reviews on a regular candence with their teams.

In practice, this is what it means for designers:
1. Identify one issue where you have many open questions or the one you're most excited to work on.
2. Decide what the best format is to give others a glimpse into the work you need feedback on: It could be anything from an issue, a short text blurb, screenshots, a Figma file, or a short, up-to 5-minute walkthrough recording of the problem you are trying to solve.
3. Remember to share the customer problem, known constraints, and what kind of feedback you need. Be specific about what you want feedback on and also what you do not want feedback on, and where you want the feedback to be provided. Read more about employing multimodal communication.
4. Post your item with a short description to the #ux-coworking Slack channel and any other channel where you'd like to get feedback (e.g. your Groups channel, etc.). Be sure to provide a link to the item requiring review as well as a link to the location where feedback should be left. Capturing feedback in issues will ensure you can refer back to it later, whereas Slack messages will eventually disappear.
5. If you're recording a video, it's recommended (but not required) to default to using Zoom as your recording tool. Please make sure to upload the video to our GitLab Unfiltered YouTube channel, because it serves as the single-source-of-truth for videos and makes them easily searchable and accessible to the wider GitLab community. Set the visibility to "Public" (unless your video contains confidential information), and add it to the "UX" playlist (and any other relevant playlists). For more information, see our YouTube uses and access page.
6. Comment on your feature issue with a link to the video and links to all references made (example), such as related issues, epics, or Figma files. Also add those reference links to the video's description, so that everyone can follow and participate (example).
7. You can also open an issue dedicated to capturing feedback (example), and attach all references and information needed for review within the issue description. This will allow the threads to focus solely on providing and discussing feedback. Attach this issue as related to the main feature issue.

### 👐 Who to include in design reviews
Deciding who to include in a design review, whether an informal share or a request for feedback around specific questions, can be daunting when you are new to GitLab or a team. Here are a few guides:
* Your Product Manager, Engineering Manager, Frontend Engineers and Product Design Manager should always have opportunities to review and provide feedback on all of your work. The easiest way to do this is to include them on the issue so it's more of a collaboration through the design process than a formal review request.
* The peer designers of your Section are excellent reviewers at any time in your process.
* If your work impacts other Stages, include those counterparts.
* If your work touches navigation, global headers/footers, a change to a Pajamas pattern, or something else with broad impact, always ask for a UX Dept review in the #ux_coworking Slack channel or mention @gitlab-com/gitlab-ux/designers in GitLab. For navigation changes, also follow this guidance from the Foundations team.
* Sometimes the list of reviewers includes people from other Departments, such as Customer Success, Sales or Marketing. For example, if you are using brand assets in a way that different from brand guidelines, you should provide an opportunity for that team to give feedback. If you aren't sure who to include in your design review process, ask your Product Design Manager.

# 📝 Partnering with UX or Technical Writers
Any additions or changes to UI text require review by the group's Technical Writer. You should discuss plans and ideas during the Product Design phase. UI text includes button or menu labels, error messages in the UI or in log files, user-assistance microcopy, notification emails, and any other text that may be surfaced in the UI. Changes to UI text often have a far-reaching effect on documentation steps.

* Ensure the issue and MR have the UI text label.
* Add the documentation label. Documentation changes resulting from UI text changes follow the Documentation for a product change workflow.
* Message the Technical Writer for the group in the design issue to request a review, including any specific files or lines they should review, and how to preview or understand the location/context of the text from the user's perspective. You can also message the writer in the MR to perform a final check of the agreed text.
* Finalizing the UI text should be a collaboration between the Product Designer and the Technical Writer to produce the best possible usable and accurate text-based solution.
* Often team members from Product, Marketing, Legal or other departments will have their own requirements for UI copy. To reduce back-and-forth revisions and design-by-committee, the Product Designer is recommended to ask these team members to provide the goals for what the text needs to communicate, rather than ideas for the text itself.

# 🔍 Partnering with UX Research
UX Researchers work closely with Product Managers and Product Designers to ensure research projects are focused and provide answers to design questions.
* Ensure you follow the Collab cycle if you are conducting the research yourself
* Ensure you follow the process to document research findings

### Refine MVC
* UX issues have a tendency to expand in scope. Work with your PM and developers to revisit which aspects of the design are “must-haves” versus those that can be pushed until later. Document non-MVC concepts and research in new issues, marking the new issues as related to the original issue. If you’re ever unsure how to split apart large issues, work with your Product Design Manager.
* If developers need to begin before you have validated your designs, and a planning pivot to another validated UX issue or perhaps dev debt issues is not an option, then look for high confidence and low risk changes devs can start work on while you validate the remainder of the solution. To mitigate these scenarios, PMs and UXers should work together to get 1-2 months ahead, so that the Build track always has well-validated product opportunities ready to start.
* Developers should be able to build a working feature within one release. If a feature is too large to build within one release, work with your PM and Engineering team to determine the best way to split the feature into smaller segments.
For iteration inspiration watch our Product Designers discuss iteration at GitLab.

### Present an MVC solution
* After you've validated your solution with users, propose just one solution. Proposing multiple alternative solutions for others to pick undermines your position as a UX expert and leads to design by committee. If you have a good reason to propose multiple alternative solutions, make sure to explain why.
* When sharing asynchronously in an issue, make sure your audience has the context necessary to understand your proposal and how they can help. Is it clear who will use the solution and what it will enable them to accomplish? Do you need feedback or assistance from stakeholders? If so, on what specifically? Or, are you looking for approval? To make reviewing easier, have you highlighted things that changed since the last review?
* Consider using the collapsed content sections to include information that would support points being made without distracting the reader from the main point. This is demonstrated in this issue comment around using analytics about file sizes.
* @mention your Product Design Manager on the issue for feedback. Product Design Managers have a broader view of work that's happening across the product, enabling them to provide feedback that is helpful for maintaining strategic alignment, a consistent level of quality, and functional consistency.
* Frame design discussions around the customer and the problem being solved, not the UI or functionality itself. When presenting, start with the current state and how it fails to meet user needs, and then walk through the proposed solution from the user’s point of view. As the discussion unfolds, continually tie everything back to the user’s experience and needs.
* Anticipate questions that others might have, and try to answer them in your proposal comments. You don’t have to explain everything, but try to communicate a bit of your rationale every time you propose something. This is particularly important when proposing changes or challenging the status quo, because it reduces the feedback loop and time spent on unnecessary discussions. It also builds the UX Department’s credibility, because we deal with a lot of seemingly subjective issues.
* Consider using the questions as headings in framing your proposal
* Keep the SSOT updated with what’s already agreed upon so that everyone can know where to look. This includes images or links to your design work.
* If you’re working with design files, follow the instructions in the GitLab Design project contribution guidelines and regularly commit them.
* If you are proposing a solution that will introduce a new UX paradigm, or change an existing one, please consider the following:
  * Will this pattern be inconsistent with other areas of the application?
  * Will other areas of the application need to be updated to match?
  * Does this new pattern significantly improve the user experience?
  * If you decide that it is worth changing/updating the pattern, follow the steps outlined in our component lifecycle documentation.

