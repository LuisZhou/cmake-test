SET(SRC_LIST main.c)
SET(EXECUTABLE_OUTPUT_PATH ${PROJECT_BINARY_DIR}/exe)
ADD_EXECUTABLE(hello ${SRC_LIST})

INSTALL(TARGETS hello RUNTIME DESTINATION bin)