.. _fixing-issues:
.. _fixingissues:

=================================
Finding Issues (or creating new ones)
=================================

When you feel comfortable enough to want to help tackle issues by trying to
create a patch to fix an issue, you can start by looking at the `"good first issue"
label`_. These issues *should* be ones where it should take no longer than a
day or weekend to fix. But because the classification is typically done
at triage time it can turn out to be inaccurate, so do feel free to leave a
comment if you think the classification no longer applies.

The `"actionable" label`_ denotes issues that have a solution identified but not 
yet implemented. 

< information about other labels here >

For the truly adventurous looking for a challenge, you can look for issues that
are not considered easy and try to fix those. It must be warned, though, that
it is quite possible that a bug that has been left open has been left into that
state because of the difficulty compared to the benefit of the fix. It could
also still be open because no consensus has been reached on how to fix the
issue (although having a patch that proposes a fix can turn the tides of the
discussion to help bring it to a close). Regardless of why the issue is open,
you can also always provide useful comments if you do attempt a fix, successful
or not.

Do I have to ask before working on an issue?
===============================================

Source: https://github.com/pytorch/pytorch/wiki/%5BDraft%5D-The-PyTorch-Contribution-Process#contributing-faq

Absolutely not. Nor do we "lock" issues and only allow a single person to work 
on them. Even if an issue is assigned you are free to work on it and submit a 
pull request for it. If there are multiple pull requests addressing the same 
issue then the one that is the highest quality (or that came first, if multiple 
have the same quality) will be accepted. 

Best practices for Creating Issues
=====================================
.. TODO: fill this

Want to make a feature change to PyTorch?
=========================================

Source: https://github.com/pytorch/pytorch/wiki/How-to-propose-feature-changes-to-PyTorch

Over half the commits made to pytorch every week come from the wider open source community.  Sometimes researchers have a certain feature that they want to see implemented, companies have hardware they want to support, or a developer found a bug they really need fixed.

With such a large number of commits coming in, PyTorch needs a process for managing it all to keep the codebase maintainable. For smaller changes, like a five line bug fix, this takes the form of a regular PR review.  Make a change, submit a PR, and a core pytorch contributor will review it soon.

But sometimes you'll want to contribute a larger change, like an enhancement to an existing function or even a brand new feature. Submitting a 1,000 line PR for a feature no one has heard about rarely results in a good experience (for neither the reviewer nor the coder).

For larger changes like this, we have a more indepth process that's similar in spirit to a design review. It ensures that the feature you're working on becomes something the core owners are happy to accept and maintain going forward.

The Request for Comments
========================

To propose a new feature, you'll submit a Request For Comments (RFC).  This RFC is basically a design proposal where you can share a detailed description of what change you want to make, why it's needed, and how you propose to implement it.

It's easier to make changes while your feature is in the ideation phase vs the PR phase, and this doc gives core maintainers an opportunity to suggest refinements before you start code.  For example, they may know of other planned efforts that your work would otherwise collide with, or they may suggest implementation changes that make your feature more broadly usable.

Here are `detailed instructions on how to submit an RFC <https://github.com/pytorch/rfcs/blob/master/README.md>`_


.. _"good first issue" label: https://github.com/pytorch/pytorch/labels/good%20first%20issue

.. _"actionable" label: https://github.com/pytorch/pytorch/labels/actionable


.. TODO: add something about no active core developer for the area?
