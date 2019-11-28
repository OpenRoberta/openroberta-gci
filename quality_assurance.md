## Quality Assurance

Some of these tasks require you to test specific functionalities and find bugs.
Usually, you should be somewhat familiar with the lab already, then you can try out weird combinations of blocks, wacky values and mess all over the place.

All of these tasks require no hardware and are either done with the simulation or the Lab itself.

In general you should follow these steps:

- When testing a specific robot system use all of the available blocks
- Hover over the blocks to get a tooltip or open the help ("?") to get a description
- Keep your programs and broadly document everything you try
- For robots that can not compile programs directly (greyed out play button) use the token `NOCONNCT` to compile programs, for these the popup "There is no robot connected..." means the program compiled successfully
- If there are multiple types of a robot system (e.g. EV3's have leJOS, dev and c4ev3) try your programs with every one of them

If something unexpected happens, e.g. you get an error where there shouldn't be one, report the problem, either

- create a [GitHub Issue](https://github.com/OpenRoberta/openroberta-lab/issues/new/choose) with the "Bug report" template or
- follow the [Bug report template](https://github.com/OpenRoberta/openroberta-lab/blob/master/.github/ISSUE_TEMPLATE/bug_report.md) in your description.

Follow the instructions in the template and provide a step-by-step guide on how to reproduce the bug.
If a program is the cause of the bug, add the exported XML as well.

In case you do not find any issues provide some of your test programs and let us know what you tried in a small write up.
