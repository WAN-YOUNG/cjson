cmake_minimum_required(VERSION 2.8.5)
project(cJSON-lib)
aux_source_directory(. CJSON_SRC)
add_library(cjson SHARED ${CJSON_SRC})