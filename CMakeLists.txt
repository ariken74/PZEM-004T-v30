
cmake_minimum_required(VERSION 3.5)

idf_component_register(SRCS "src/PZEM004Tv30.cpp"
                       INCLUDE_DIRS "src" 
                       REQUIRES arduino)

