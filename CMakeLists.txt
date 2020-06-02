
cmake_minimum_required(VERSION 3.17)

Project(LatexTemplate NONE)

set(CMAKE_MODULE_PATH ${CMAKE_MODULE_PATH} "${CMAKE_SOURCE_DIR}/cmake/Modules/")

include(UseLATEX)

add_latex_document(main.tex 
	IMAGE_DIRS images
	FORCE_PDF)


