aosc.sh
=======

Common libraries for AOSC bash scripts. Simply with `. aosc.sh` added to your
file, you get access to all the basic functions and important variables.

LICENSE
-------

In short: `GPL-2.0+ WITH Classpath-exception-2.0`. For bash, 'dynamic linking'
is considered as sourcing the library; while 'static linking' means m4-including
into your code where needed or in other similar methods.

```
# This program is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation, either version 2 of the License, or
# (at your option) any later version.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this program.  If not, see <http://www.gnu.org/licenses/>.
# 
# Linking this library statically or dynamically with other modules is
# making a combined work based on this library. Thus, the terms and 
# conditions of the GNU General Public License cover the whole combination.
#
# As a special exception, the copyright holders of this library give you
# permission to link this library with independent modules to produce an
# executable, regardless of the license terms of these independent modules,
# and to copy and distribute the resulting executable under terms of your
# choice, provided that you also meet, for each linked independent module,
# the terms and conditions of the license of that module. An independent
# module is a module which is not derived from or based on this library.
# If you modify this library, you may extend this exception to your version
# of the library, but you are not obligated to do so. If you do not wish to
# do so, delete this exception statement from your version.
```

If you want to include parts of the script, or 'statically-link' the library,
in your non-GPL script, add markers like
`##BEGIN GPL2+/LE SOURCE github.com/AOSC-Dev/aosc.sh` and `##END aosc.sh`
around to your sourced areas. If you are only including a few functions,
add markers like `##GPL2+/LE SOURCE github.com/AOSC-Dev/aosc.sh`above the
`func() {` line.
