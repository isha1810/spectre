# Distributed under the MIT License.
# See LICENSE.txt for details.

set(LIBRARY "Test_ValenciaDivClean")

set(LIBRARY_SOURCES
  Test_ValenciaDivClean.cpp
  )

add_test_library(
  ${LIBRARY}
  "Evolution/Systems/GrMhd/ValenciaDivClean"
  "${LIBRARY_SOURCES}"
  ""
  )