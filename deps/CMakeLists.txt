#ask_build_sourcey_dependency(libuv)
#if(BUILD_DEPENDENCIES AND BUILD_DEPENDENCY_libuv) 
#  add_subdirectory(libuv)
#endif()

#ask_build_sourcey_dependency(RtAudio)
#if(BUILD_DEPENDENCIES AND BUILD_DEPENDENCY_RtAudio) 
#  add_subdirectory(RtAudio)
#endif()

#ask_build_sourcey_dependency(jsoncpp)
#if(BUILD_DEPENDENCIES AND BUILD_DEPENDENCY_jsoncpp) 
#  add_subdirectory(jsoncpp)
#endif()

#ask_build_sourcey_dependency(http_parser)
#if(BUILD_DEPENDENCIES AND BUILD_DEPENDENCY_http_parser) 
#  add_subdirectory(http_parser)
#endif()

#ask_build_sourcey_dependency(zlib)
#if(BUILD_DEPENDENCIES AND BUILD_DEPENDENCY_zlib) 
# add_subdirectory(zlib)
#endif()

#ask_build_sourcey_dependency(pugixml)
#if(BUILD_DEPENDENCIES AND BUILD_DEPENDENCY_pugixml) 
#  add_subdirectory(pugixml)
#endif()

#ask_build_sourcey_dependency(libstrophe)
#if(BUILD_DEPENDENCIES AND BUILD_DEPENDENCY_libstrophe) 
#  add_subdirectory(libstrophe)
#endif()

#if(WITH_OPENSSL AND NOT OPENSSL_FOUND)    
#  add_subdirectory(openssl)
#endif()

#if(WITH_MEMLEAKDETECT AND NOT MEMLEAKDETECT_FOUND)
#  add_subdirectory(MemLeakDetect)
#endif()
