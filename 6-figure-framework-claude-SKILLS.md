To perfectly structure these layers, use the 6-Field Build Framework, which consists of the following components:
1. Name As discussed previously, this must be a short, kebab-case label (e.g., "weekly-status-report" or "youtube-title-generator") that describes exactly what the skill does
.
2. Trigger (Description) This field is critical because it tells Claude exactly when to activate the skill
. You must provide a highly specific description and a clear trigger command, such as, "Use whenever asked to create a presentation" or "Use whenever Guru shares a video concept"
. If this isn't set up correctly, Claude might get it wrong and the skill will never fire
.
3. Output You must strictly define what the final output should look like
. For instance, you can specify that the output must match exact visuals, formatting, or brand themes
.
4. Dependencies If your skill requires external resources to function properly, list them here. This includes external tools, system connectors (like vidIQ for YouTube analysis), reference files, or specific brand assets like logos and starter templates
.
5. Step-by-Step Instructions & Human-in-the-Loop Provide a highly detailed, ordered process (e.g., Step 0: Plan before you build, Step 1, Step 2) for Claude to execute
. Crucially, you should include a "Human-in-the-loop" instruction
. This tells Claude that if it has any doubts or needs to make changes based on your content, it must pause and ask you questions instead of hallucinating or making assumptions
. You should also define the expected output for each individual step
.
6. Rules and Constraints (Edge Cases) Finally, you must predict what could go wrong and set firm boundaries
. This involves creating strict rules about what Claude should not do. For example, you can dictate exact style rules, tell it which colors or logos it must use, and explicitly state "never use this" for elements you want to avoid
.
The Ultimate Goal: Build Systems, Not Just Skills Once you master building individual skills using this framework, the sources strongly advise that you stop thinking about them as isolated tools
. The most professional setups combine multiple skills, connectors, and external databases (like an Obsidian wiki) into a complete automated system or plugin
. By learning to design systems that actually work together, you dramatically increase your productivity and ensure that AI amplifies your career rather than replacing it