# OpenSSH-7.4p1
A backdoored version of OpenSSH 7.4 used to capture user credentials when using 
password based authentication.

This is a backdoored version of OpenSSH 7.4 built on CentOS 7 x86_64. 

The source code has been modified so that user credentials are written out to a
file when password authentication is being used. This is to be used for
educational and debugging purposes ONLY. I take NO responsibility if the code
shown here is used for malicious intent.

I literally hacked this up in a space of 5 minutes when a colleague asked me to
assist with a last minute demonstration that they were performing. I though I'd
put it up on GitHub in the rare instance that anyone else needed it for
whatever reason. I'm almost certain that this could've been done in a better
way, but given the time constraint I just implemented whatever worked.
