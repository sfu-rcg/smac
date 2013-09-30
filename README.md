Simple Maillist API Client
=====================
SMAC is a command-line client for the SFU maillist REST API. It is probably not useful to you if you're not part of Simon Fraser University somehow.


Requirements
-

- Python 2.6-ish
- requests module: http://docs.python-requests.org/


Features
-

- create/read/update/delete mailing lists
- create/read/update/delete mailing list members
- toggle "delivery" and "manager" flags for list members


Limitations
-
- Doesn't deal with courselists. The API hooks are available, however.
- Can't push maillists to Active Directory groups yet (we have code but no access to test it)
- Given a maillist-controlled Active Directory group, we have no way of assigning it GID
 - ... automatically
 - ... let alone a unique one
 - and smac does not attempt to solve this problem.
- I'm not so great with the clever, concise Python techniques.

Feedback welcome here or at warren@sfu.ca.


Version
-
0.4, 20-Jun-2013