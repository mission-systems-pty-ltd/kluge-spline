project( "kluge-spline" )
file( GLOB_RECURSE includes RELATIVE ${CMAKE_CURRENT_SOURCE_DIR} src/*.h )
install( DIRECTORY src DESTINATION include )
INSTALL( FILES ${includes} DESTINATION include/kluge/spline )