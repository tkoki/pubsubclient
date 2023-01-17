set(srcs
    src/PubSubClient.cpp
    )

set(includedirs
    src
    )

idf_component_register(INCLUDE_DIRS ${includedirs} SRCS ${srcs} REQUIRES arduino)
