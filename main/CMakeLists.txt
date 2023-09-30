set(component_srcs "mcp3002.c")

idf_component_register(SRCS "${component_srcs}"
                       INCLUDE_DIRS "."
                       REQUIRES driver)

