
cmake_minimum_required( VERSION 3.13 )

project( letsberational )

set(SRCS erf_cody.cpp rationalcubic.cpp normaldistribution.cpp lets_be_rational.cpp)
add_library(lbr SHARED ${SRCS})

