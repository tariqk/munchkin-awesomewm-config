============================================================
 Tariq Kamal's Configuration for the Awesome Window Manager
============================================================

What it says on the tin. Basically what's happening here is that I'm trying to learn both org-babel and lua to customize awesome at the same time. This seemed like the best way to accomplish both tasks. Plus, I've always been fascinated by the weird, impractical, yet strangely compelling concept of `Literate Programming`_.

.. _Literate Programming: http://en.wikipedia.org/wiki/Literate_programming

This machine's configuration
============================

- Debian Wheezy
- Emacs, installed from `the emacs-snapshot packages`_

  + Emacs has, of course, `org-mode`_ built-in.

- The `Literate Programming fork of the emacs-starter-kit`_
- The `awesome window manager`, ver. 3.4.13 (Octopus)

.. _the emacs-snapshot packages: http://emacs.naquadah.org/
.. _Literate Programming fork of the emacs-starter-kit: http://github.com/eschulte/emacs24-starter-kit
.. _org-mode: http://www.orgmode.org/
.. _awesome window manager: http://awesome.naquadah.org/

You could say that the inspiration for the whole project stemmed from me looking at the emacs24-starter-kit, remembering what a *pain in the ass* files in the ``.emacs.d`` directory was, versus a more literate approach.

And since `org-babel`__ is language-agnostic (at least when it comes to tangling org-files to the resulting source-code, and I needed a way to organize the awesome. file, I figured, what the heck. Can't do any harm, and besides, org-mode does help organize how I think.

.. __: http://orgmode.org/worg/org-contrib/babel/

Project Roadmap
===============

- Complete the annotation of the awesome configuration file.
- Add features (i.e widgets, tools and apps) in a modular, documented way.

The repo in itself should serve the following functions:

- Allow me to backup my awesome profile in a safe, reversible manner that allows for experimentation.
- Safely add multiple features with git's branching infrastructure.
- Act as an annotated commentary on the awesome configuration, while helping out n00bs to awesome and lua like myself.
