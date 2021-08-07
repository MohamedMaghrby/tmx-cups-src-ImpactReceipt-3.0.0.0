cmake_minimum_required(VERSION 2.8)
add_executable(rastertotmir
	filter/TmImpactReceipt.c
)
target_link_libraries(rastertotmir cupsimage cups)
