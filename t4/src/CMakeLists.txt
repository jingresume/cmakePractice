INCLUDE_DIRECTORIES(/tmp/usr/t3/include/hello)
LINK_DIRECTORIES(/tmp/usr/t3/lib)
ADD_EXECUTABLE(main main.cpp)
TARGET_LINK_LIBRARIES(main hello)


