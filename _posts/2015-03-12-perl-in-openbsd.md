---
title: Mar 12, 2015 - Perl in the OpenBSD base system
layout: article
category: meetings
excerpt: Andrew Fresh will be talking about Perl in the OpenBSD base system
---

----

Andrew Fresh will be previewing his hopeful YAPC::NA talk on Perl in the OpenBSD base system.  

Perl 5.003 was imported as part of the OpenBSD base system in 1996 by Jason Downs (downsj@) and has been used heavily ever since.  Quite a few system utilites are written in perl, one of the largest being Marc Espie's (espie@) rewrite of the package management tools and his amazing dpb (distributed package build) tool.  Andrew is the current maintainer for perl in OpenBSD and wants to share what's going on.

He'll talk about some of their local patches, those have been merged upstream and what is left.  He'll also go into some details about why it makes sense to have as part of the base system as well as how it's being used.  He'll detail some of the challenges with integrating it into the base build and what goes into importing new versions of perl as well as some ideas for future work.

OpenBSD 5.7 will be shipping in May 2015 with perl 5.20, and nearly current versions of Mojolicious, Dancer2, and DBIx::Class in the ports tree.

----
