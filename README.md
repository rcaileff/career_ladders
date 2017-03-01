<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [What Is this?](#what-is-this)
- [What's inside?](#whats-inside)
- [Structure](#structure)
- [Definitions](#definitions)
- [Why Ugly Markdown?](#why-ugly-markdown)
  - [Generating Table of Contents (TOC)](#generating-table-of-contents-toc)
- [Feedback](#feedback)
- [Licensing](#licensing)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# What Is this?
[Enova](http://www.enova.com) has decided to open source its career ladders. You can find background on why we created new ladders [here](http://www.builtinchicago.org/node/126918) and why we open sourced them [here](https://www.enova.com/blog/open-sourcing-engineering-ladders/).

# What's inside?
There's 6 ladders contained:
* core_engineer - This is the basis of every team member, regardless of your specific focus.
* software_engineer - Software Engineer Ladder
* software_ui_engineer - Software UI Engineer Ladder
* software_test_engineer - Software Test Engineer Ladder
* mobile_engineer - Mobile Engineer Ladder

After you become a Lead Engineer, you can select to either go into the Individual Contributor track or the Mangement track:

* individual_contributor - Principal Engineer Ladder
* mangement - Manager Ladder

# Structure
Each position is meant to build on the position before it. So a Sr. Software Engineer II is expected to fulfill everything found in the Software Engineer I, II and Sr. Software Engineer I descriptions.

The ladders also progress in terms of what each position impacts: starting with a project, moving to your team, core, SE, tech and, finally, to the company.

# Definitions
Within the ladders there's some Enova specific terminology:
* Core - We have organized teams focused on either specific products or internal operations. These core teams don't change that often. This is the bulk of our team.
* Ranger - The remaining engineers are broken out into 4 person ranger teams. These teams are assigned every 6 weeks during a company wide prioritization process known as EPG.
* SE - Software Engineering
* Architecture Council - Large, cross functional team made up of members of SE, IT, Analytics, Data Services and TechOps that help organize company wide projects and initiatives.

# Why Ugly Markdown?
Markdown doesn't represent tables / matrices well. GFM only supports single line table cells, so they wouldn't work here. If you have some suggestions, please, open up an issue, or better yet, submit a PR.

## Generating Table of Contents (TOC)
The TOCs in the readme files were generated using doctoc.

To regenerate the TOCs, run
'''
doctoc .
'''
in the project directory. It recusively scans all .md files and adds TOC.

To install doctoc, run
'''
npm install -g doctoc
'''

For more details, visit the doctoc git repo: https://github.com/thlorenz/doctoc.

# Feedback
Feedback is welcome. Feel free to ping [Griffin Caprio](http://www.twitter.com/gcaprio) with questions or comments.

# Licensing
These Career Ladders are released by [Enova](http://www.enova.com) under the
[MIT License](https://github.com/enova/tokyo/blob/master/LICENSE).
