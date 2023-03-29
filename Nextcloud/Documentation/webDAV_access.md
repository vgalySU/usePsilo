# Accessing Nextcloud through a webDAV protocol

It turns out that the server is already configured for webDAV access (server side).

Now, client side may be a bit tricky to configure.

## Mount point on Linux
You should be able to mount your nextcloud account on a remote linux machine using the webdav url https://psilo.sorbonne-universite.fr/remote.php/dav/files/<username>/,
your <username> and password for PSILO and the instructions available
[here](https://docs.nextcloud.com/server/latest/user_manual/fr/files/access_webdav.html#creating-webdav-mounts-on-the-linux-command-line)

This is not obvious to do but let's say for intermediate linux users.

## Using a dedicated client
You can use Cyberduck, a webDAV client for MacOS X. Just remember to use the correctly formed url.

There is probably a window equivalent to this client, look at the doc !
  
## Mount point on a Mac
Last but not least, the webDAV mounting works natively in MacOS X, using the Cmd-K key combination and the url mentioned above.

You are ending up in all cases with your nextcloud account mounted in your remote user file system.

This said, I am standing on my very first impression: reorganizing a file system using a remote mounting point looks odd to me.
I would definitely do it directly on the nextcloud web interface and its commands `move`, `copy`, `rename`, etc...

On a last note, webDAV is fun but not particularly adapted to non expert users, IMHO. Moreover your are manipulating the file over the network which is therefore limiting your operation.
However, for the transfer of very large files or folder, this may be a valuable option instead of transfering them by drag & drop on the web interface of Nextcloud.

