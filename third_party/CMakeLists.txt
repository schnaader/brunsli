# Copyright (c) Google LLC 2019
#
# Use of this source code is governed by an MIT-style
# license that can be found in the LICENSE file or at
# https://opensource.org/licenses/MIT.

if (NOT TARGET gtest_main)
  add_subdirectory(googletest EXCLUDE_FROM_ALL)
endif ()
