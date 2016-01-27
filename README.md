# convkey
A script to extract OTR private keys from the Conversations app on an Android phone

I think [Conversations][conversations] is a great xmpp client for Android.
But sometimes I want to use a desktop client, and want to use the same [OTR][otr]
private key for the desktop that I do in Conversations. So I wrote the
following script to extract private OTR keys. The output is given in both
raw hex and in (base64'd) [libotr][libotr] format, so it can be imported into virtually
any xmpp client that supports OTR.

With a little cleverness, the script could be adapted to modify or add OTR
keys to the Conversations database. That is left as an exercise for the reader.

There are versions of the script for both rooted and nonrooted phones.

The script is available at:
<a href="https://github.com/rxcomm/convkey">https://github.com/rxcomm/convkey</a>
