idf_component_register(SRCS "hello_world_main.cpp"
                       PRIV_REQUIRES "M5GFX"
                       INCLUDE_DIRS "")
target_compile_options(${COMPONENT_LIB} PRIVATE "-Wno-format")
