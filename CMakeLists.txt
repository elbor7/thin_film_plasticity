cmake_minimum_required(VERSION 3.21)
project(DCC_WearPlast)

set(CMAKE_CXX_STANDARD 17)

add_executable(DCC_WearPlast Main_WearPlast.cpp src/DCCProcessing/DCCProcessing.h src/DCCProcessing/Processing_Functions.h src/DCCKinetic/DCCKinetic.h src/DCCKinetic/Kinetic_Functions.h src/DCCCharacterisation/StructureCharacterisation.h src/DCCCharacterisation/TJsLab.h src/DCC_SupportFunctions.h src/DCCCharacterisation/QPsLab.h src/DCCCharacterisation/DislocationsLab.h)