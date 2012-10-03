===========
Communication
===========

:Author:    $Author$
:Date:      $Date$

Abstract
========

Here we want to list the most basic rules and means of communication.

.. note:: so far, the problems discussed are general -- the rules which
     we have come up with have been approved by the development team.  We
     believe strongly, that they work for everyone, though.

Problem Statement
=================

In talks with members of our company it became apparent that we have different
ideas on which communication method is appropriate at what time.  For instance,
developers often need to be let alone because they're 'in the zone' --
disturbing them means a big loss of productivity for a extended amount of time.
On the other hand, if a team member needs some information, he needs a way to
get at least the request for the information out.

Also, different people have different habits -- one is disturbed by the
slightest noise, the other happily gets his work done in a crowded kitchen
area.

Another challenge is that our company is located in oslo, ravensburg and
bamberg.  Also, people are working on site -- i.e. on the customers premise.

These circumstaces can lead to frustration at all parties -- the one never gets
hold on the only guy which can help, and the other one never gets anything done
in an efficient way because of interruptions.

Goals
=====

Get some minimal set of rules in place, which counter the problems listed in
the previous section.

Proposed Solution
=================

We need that by specifying the time frame for communication types solves
a big part of the problem.

The other key is the concept of having different areas for different work.

We think that by rules and tools alone, we cannot solve the problem at all.

Definition
----------

In the context of this document we'll use the following terms:

**asynchronous communication**
  When this communication method is used, both communication partners
  communicate in the same time frame -- if the *receiver* does not take the
  call, no communication takes place.  The *caller* gets an immediate response.
  Examples would be normal phone calls, direct in-person communication.
  Depending on the actual use case, instant messaging systems belong also into
  this category.

**synchronous communication**
  This type of communication allows the *receiver* to defer the communication to
  a later time.  Examples would be E-Mail and text messages (SMS).

Time frame for synchronous and asynchronous communication
---------------------------------------------------------

We specify the time frame for *synchronous* and *asynchronous* communication as
follows:

+---------------+--------------+---------------------------------------------+
| Time          | method       | explanation                                 |
+===============+==============+=============================================+
| 09:00 - 09:30 | synchronous  | standup comedy / coffee time / morning talk |
+---------------+--------------+---------------------------------------------+
| 09:30 - 12:00 | asynchronous | developer work                              |
+---------------+--------------+---------------------------------------------+
| 14:00 - 16:00 | asynchronous | developer work                              |
+---------------+--------------+---------------------------------------------+
| 16:00 - 17:00 | synchronous  | developer work                              |
+---------------+--------------+---------------------------------------------+

Work Zones
----------

We'd like to define the following work zones:

**socializing area**
  A place where ad-hoc, unspecific direct communication is possible.  Here, almost
  no rule is in place -- basically anything goes.

  Think "coffee house", "bar"

**concentrated work / silence zone**
  This is an zone where people can get their work done in silence.  Phone calls,
  discussions, loud activity is frowned upon.

  Think "library", "think tank".

**ad-hoc mixed area**
  This is a place where people can take a seat and start working.  There's no
  fixed assigned place -- no one owns a specific seat.  People from different
  working areas which need a space to collaborate may temporarily move there.
  Freelancers and customers have their place here.

  Think "shared office"

**meeting zone**
  This is the place to go for meetings and discussions.  People inside the meeting
  area are to be considered discussing *private* things, they're not to be disturbed.

  Think "private -- no entry"

.. vim: set ft=rst tw=75 nocin nosi ai sw=4 ts=4 expandtab:

