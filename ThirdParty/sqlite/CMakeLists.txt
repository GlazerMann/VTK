vtk_module_third_party(sqlite
  LIBRARIES vtksqlite
  INCLUDE_DIRS "${CMAKE_CURRENT_BINARY_DIR}/vtksqlite"
               "${CMAKE_CURRENT_SOURCE_DIR}/vtksqlite"
  PACKAGE SQLite3)
