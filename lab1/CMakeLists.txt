add_executable(Lab1 lab1.cpp)

target_link_libraries(Lab1 PRIVATE
        ${OpenCV_LIBS}
        )
