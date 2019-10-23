# fuse-windup-rules

Here's some suggested starting rules for Windup, to make it a little easier to migrate between versions of Red Hat Fuse.

**WARNING:** These rules are not complete. They come with absolutely no warranty of their completeness or accuracy. I am providing them solely in a personal capacity, for your education and amusement :-)

To run the rules against a codebase:

    $ $WINDUP_HOME/bin/rhamt-cli --sourceMode \
        --input /path/to/your/code \
        --output /tmp/reports \
        --source fuse-karaf --target fuse-spring-boot:7

