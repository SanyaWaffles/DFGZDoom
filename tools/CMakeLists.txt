cmake_minimum_required( VERSION 3.16 )

add_subdirectory( re2c )
add_subdirectory( lemon )
add_subdirectory( zipdir )

set( CROSS_EXPORTS ${CROSS_EXPORTS} PARENT_SCOPE )
