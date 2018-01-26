# Copyright (C) 2008-2017 TrinityCore <http://www.trinitycore.org/>
# Copyright (C) 2005-2011 MaNGOS project <http://getmangos.com/>
#
# This program is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 2 of the License, or
# (at your option) any later version.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this program; if not, write to the Free Software
# Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA  02111-1307  USA
#

<<<<<<< HEAD:dep/recastnavigation/CMakeLists.txt
add_subdirectory(Detour)
add_subdirectory(Recast)
=======
## Process this file with automake to produce Makefile.in

## Sub-directories to parse
SUBDIRS = include lib src

if TRI_BUILD_ACE
SUBDIRS += ACE_wrappers
endif

## Additional files to include when running 'make dist'
#  Nothing yet.
>>>>>>> [svn] * Auto detect if ACE is already installed and use it.:dep/Makefile.am
