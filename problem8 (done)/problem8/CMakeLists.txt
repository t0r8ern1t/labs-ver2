cmake_minimum_required(VERSION 3.15) # �������� ������ CMake.
									 # ���� ������ ������������ ���������
									 # ������ ��������, ��������� ��������� �����.

set(PROJECT_NAME test)				 # ��� �������		 

project("${PROJECT_NAME}")





set(CMAKE_CXX_STANDARD 17)			 # ������������� 17 �������� �����

set(CMAKE_CXX_EXTENSIONS OFF)

set(CMAKE_CXX_STANDARD_REQUIRED TRUE)


include_directories("/")



add_executable("${PROJECT_NAME}" problem8.cpp trapezoid.hpp trapezoid.cpp)
