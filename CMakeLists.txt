cmake_minimum_required(VERSION 3.16)
project(stb_image)

# Add the STB Image library
add_library(stb_image STATIC
	"stb_image/stb_image.h"
	"stb_image/stb_image.c"
)

# Specify the include directories for stb_image
target_include_directoriesstb_image PUBLIC
	${CMAKE_CURRENT_SOURCE_DIR}/stb_image
)
