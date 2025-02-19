# Create a library called "defense_secure_comm"
add_library(defense_secure_comm_lib defense_secure_comm.cpp)

# Specify include directories for the library
target_include_directories(defense_secure_comm_lib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/../../include)
