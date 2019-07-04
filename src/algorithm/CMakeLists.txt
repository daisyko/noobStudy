add_subdirectory(algoLib)

add_executable(algoTester
    algoTester.cpp
)

target_link_libraries(algoTester
    algoTestLib
)

add_subdirectory(algoTestLib)