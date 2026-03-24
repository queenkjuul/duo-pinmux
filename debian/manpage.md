% milkv-pinmux-duos(SECTION) | duo-pinmux command
%
% "March 17 2026"

[comment]: # The lines above form a Pandoc metadata block. They must be
[comment]: # the first ones in the file.
[comment]: # See https://pandoc.org/MANUAL.html#metadata-blocks for details.

[comment]: # pandoc -s -f markdown -t man package.md -o package.1
[comment]: # 
[comment]: # A manual page package.1 will be generated. You may view the
[comment]: # manual page with: nroff -man package.1 | less. A typical entry
[comment]: # in a Makefile or Makefile.am is:
[comment]: # 
[comment]: # package.1: package.md
[comment]: #         pandoc --standalone --from=markdown --to=man $< --output=$@
[comment]: # 
[comment]: # The pandoc binary is found in the pandoc package. Please remember
[comment]: # that if you create the nroff version in one of the debian/rules
[comment]: # file targets, such as build, you will need to include pandoc in
[comment]: # your Build-Depends control field.

[comment]: # Remove the lines starting with `[comment]:' in this file in order
[comment]: # to avoid warning messages from pandoc.

# NAME

duo-pinmux - program for configuring pinmux on Milk-V Duo boards

# SYNOPSIS

**duo-pinmux** [{**-p** | **-l** | **-r** _pin_ | -w _pin/func_ }]

# DESCRIPTION

This manual page documents briefly the **milkv-pinmux-duo** command.

This manual page was written for the Debian distribution because the
original program does not have a manual page.

# OPTIONS

A summary of options is included below.

pinmux for duos
duo-pinmux -p          <== List all pins
duo-pinmux -l          <== List all pins and its func
duo-pinmux -r pin      <== Get func from pin
duo-pinmux -w pin/func <== Set func to pin

**-p**
:   List all pins.

**-l**
:   List all pins and its func.

**-r** _pin_
:   Get func from pin.

**-w** _pin/func_
:   Set func to pin.

# AUTHOR

Julie Hill <queenkjuul@pm.me>
:   Wrote this manpage for the Debian system.

# COPYRIGHT

Copyright © 2026 Julie Hill

This manual page was written for the Debian system (and may be used by
others).

Permission is granted to copy, distribute and/or modify this document under
the terms of the GNU General Public License, Version 2 or (at your option)
any later version published by the Free Software Foundation.

On Debian systems, the complete text of the GNU General Public License
can be found in /usr/share/common-licenses/GPL.

[comment]: #  Local Variables:
[comment]: #  mode: markdown
[comment]: #  End:
