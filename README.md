# pyros-channel
A Guix channel to retrieve pyros related packages.

# Use it now !

Add the Pyros channel on top of the latest guix (likely the default on your machine)

Your `~/.config/guix/channels.scm` should contain :

```
;; Add pyros to Guix default channels.
(cons (channel
        (name 'pyros)
        (url "https://github.com/pyros-dev/pyros-channel.git")
        (branch "master"))
      %default-channels)

```

# ROS Channel

I am currently not aware of any ROS Channel for Guix, so ros dependencies are embedded in this channel.
As soon as a ROS Channel is made and maintained, we should depend on it.

# Guix
For more information about Guix : https://www.gnu.org/software/guix
For more information about channels : https://www.gnu.org/software/guix/manual/en/html_node/Channels.html

