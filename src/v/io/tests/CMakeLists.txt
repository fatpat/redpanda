rp_test(
  UNIT_TEST
  GTEST
  USE_CWD
  BINARY_NAME io
  SOURCES
    common.cc
    common_test.cc
    cache_test.cc
    interval_map_test.cc
    persistence_test.cc
    page_test.cc
    page_set_test.cc
  LIBRARIES
    v::gtest_main
    v::io
    absl::btree
)
