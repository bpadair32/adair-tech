---
title: Projects
slug: projects
---

## What I'm Tinkering With

Here's a peek at some personal projects I've been working on. They're all available on GitHub under the MIT license, so feel free to check them out!

A quick note: These projects were built to scratch my own particular itches. I'm happy to share them with the world, but I created them primarily for myself. If you find them useful - awesome! If you have ideas or bug fixes, I'd love to see your issues or pull requests. That said, I'll only implement features that I personally find valuable, so if we don't see eye-to-eye on something, remember that forking is your friend! That's the beauty of open source.

### DataForge

This is the static site generator that powers the website you're looking at right now. I built DataForge because most existing SSGs felt like using a sledgehammer to hang a picture frame - they're powerful but way more complex than what I needed for my personal site.

DataForge is deliberately minimal, focused on making it dead simple to maintain a clean personal site without a lot of fuss. It uses Python with Jinja templates and Markdown for content - straightforward tools that get the job done without unnecessary complexity.

[Check out DataForge on GitHub](https://github.com/bpadair32/DataForge)

### docker-image-alma9-systemd

Ever tried testing Ansible playbooks that need systemd in a Docker container? Most OS containers strip systemd out, which is a pain when you need it for testing. This image solves that problem by packaging Alma Linux 9 with systemd included.

It's a simple tool, but it's saved me countless hours of frustration when testing ansible playbooks that interact with system services.

[View docker-image-alma9-systemd on GitHub](https://github.com/bpadair32/docker-image-alma9-systemd)

### aws-org-create-role

This one came directly from a recurring headache at my day job: needing to create identical IAM roles across multiple AWS accounts in an organization. While there are many ways to tackle this problem, I found that a targeted Python script was the fastest solution for my workflow.

The script is straightforward but effective - it gets the job done quickly and without unnecessary complications.

[Explore aws-org-create-role on GitHub](https://github.com/bpadair32/aws-org-create-role)

### MyBrief

My newest experiment! MyBrief is a Python tool that leverages AI to summarize long articles, helping me get the gist of content without spending ages reading.

This project is still in its infancy, and I'm not sure how far I'll take it. Like many side projects, its future depends entirely on how interesting it remains to me over time. But the core idea - using AI to make reading more efficient - is something I find genuinely useful.

[See MyBrief on GitHub](https://github.com/bpadair32/myBrief)
