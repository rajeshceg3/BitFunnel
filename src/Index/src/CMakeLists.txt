# BitFunnel/src/Index/src

set(CPPFILES
    Placeholder.cpp
)

set(WINDOWS_CPPFILES
)

set(POSIX_CPPFILES
)

set(PRIVATE_HFILES
DocumentLengthHistogram.h
)

set(WINDOWS_PRIVATE_HFILES
)

set(POSIX_PRIVATE_HFILES
)

COMBINE_FILE_LISTS()

add_library(Index ${CPPFILES} ${PRIVATE_HFILES} ${PUBLIC_HFILES})
set_property(TARGET Index PROPERTY FOLDER "src/Index")
set_property(TARGET Index PROPERTY PROJECT_LABEL "src")