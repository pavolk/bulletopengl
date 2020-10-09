
file(GLOB SOURCES ${CMAKE_CURRENT_SOURCE_DIR}/*.cpp)

add_executable(bulletopengl ${SOURCES})
target_link_libraries(bulletopengl PRIVATE CONAN_PKG::freeglut CONAN_PKG::glew CONAN_PKG::glm CONAN_PKG::bullet3)
