set(COMPONENT_SRCDIRS
        "fmt"
        )

set(COMPONENT_ADD_INCLUDEDIRS
        "."
        )

target_compile_definitions(${COMPONENT_TARGET} PUBLIC -DESP32)
target_compile_options(${COMPONENT_TARGET} PRIVATE -fno-rtti)