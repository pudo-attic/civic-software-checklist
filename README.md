Civic Software Checklist
========================

A growing number of civil society organisations and news organisations
produce software. This document collects tips to tackle two common
challenges they face:

* **Sharing your code** with others in such a way that it actually invites
  collaboration, rather than just `token` open source code.

* Reducing the **risk from contractors** that work on a project for some
  time and then move on to other clients. It's important that the code
  they leave behind can be understood and extended by others. 

Both issues can be addressed by following the (mostly non-technical)
strategies laid out here.

**Note:** This is a collaborative document. Please feel free to submit
pull requests to suggest changes. The goal of this document is to be as
concise and understandable as possible. If you see any fluff, help cut it
away!

### What to release as open source software
### Practices for releasing open source sofware

* Avoid **not invented here** syndrome. Another group may have already
  solved the problem you're dealing with, so spend some time on
  research. If their solution looks overly complex, think twice: while
  this may be a sign of bad code, it could also be an indicator that
  their project is mature and has learned to deal with many different
  concerns. 
* It's usually **cheaper to adapt than to re-build**. Your idea is probably
  special to you, but experience shows that starting a new project has a 
  fixed cost that will eat up a significant part of your budget.
* When you release code, think about **separating tools from projects**.
  For example, in a crowd-sourcing effort, you might want to separate
  the mechanism you use to collect data (e.g. text messages) from the
  code that is specific to the topic of your project (e.g. potholes).
* Keep your code up to date. You might want to surprise the world with
  a big, new feature sometimes, but that should not be a reason to stop
  sharing your code until that new thing is done. Big, infrequent
  updates kill collaboration.
* When people announce their intention to contribute to your project,
  invite them to submit some code as early as possible. Save discussions
  on product design and general strategy for later.
* When people contribute, try to include their changes, even if they're
  not on your roadmap. Take time to review the code, and if it needs
  improvement, guide contributors through making the necessary changes.

### Things you need to set up for your open source project

* **A license**. Explicitly defining the terms of re-use is the key to
  opening your software. Never write your own licenses, but instead use
  either the GPL family of licenses (which force others to contribute 
  their own changes and derived products), or use an MIT/BSD license for
  utilities and web platforms where sharing all related software is not
  practical.
  [TODO: Find a better comparison online and link to that.]
* Set up a **public code repository**. Code sharing platforms like
  GitHub enable developers to work togeter easily. They improve your
  internal development workflow as well.

### References

* Noah Veltman's best practices

