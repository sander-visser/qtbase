#! [cmake_use]
find_package(Qt6 COMPONENTS PrintSupport REQUIRED)
target_link_libraries(mytarget Qt::PrintSupport)
#! [cmake_use]
