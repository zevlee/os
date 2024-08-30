# Zev Lee OS &nbsp; [![bluebuild](https://github.com/zevlee/os/actions/workflows/build.yml/badge.svg)](https://github.com/zevlee/os/actions/workflows/build.yml)

My personal OS image. There's nothing complicated going on here. I just added
the packages I wanted and removed the ones I didn't.

## My Changes

I based my image from the `silverblue-nvidia` build of Universal Blue. That way
I have the necessary drivers and codecs pre-installed while still sticking
fairly close upstream to Fedora Silverblue.

I used rpm-ostree to install the base packages I want, most of which are
developed by the GNOME software team. I don't want to install these as
flatpaks.

For flatpaks, I have everything that I want installed listed in the recipe
file.

That's about it. As of the time of writing, I don't have any crazy
configurations set.
