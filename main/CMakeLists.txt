idf_component_register(SRC_DIRS          "."
                       PRIV_INCLUDE_DIRS ".")

target_link_libraries(${COMPONENT_LIB} PUBLIC fmt::fmt)
