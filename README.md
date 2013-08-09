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


License
-
smac is distributed under the following BSD-style license.

Copyright (c) 2013 SFU RCG. All Rights Reserved. Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

- Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

- Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

- The name of the author may not be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

