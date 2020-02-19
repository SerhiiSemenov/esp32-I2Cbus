FILE(GLOB SOURCES *.cpp)
idf_component_register(SRCS ${SOURCES} INCLUDE_DIRS ".")

component_compile_options(PUBLIC "-DI2CBUS_COMPONENT_TRUE=1")
