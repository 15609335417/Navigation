cmake_minimum_required(VERSION 3.24)
project(Navigation)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Navigation
        Config.cpp
        Config.h
        CONST.h
        Coor.h
        CoordinateTransformation.cpp
        Decode.h
        DecodeNovOem7.cpp
        ErrorCorrection.cpp
        ErrorCorrection.h
        lambda.cpp
        lambda.h
        main.cpp
        Matrix.cpp
        Matrix.h
        OutFile.cpp
        OutFile.h
        OutType.hpp
        RTK.cpp
        RTK.h
        SatellitePostion.cpp
        SatellitePostion.h
        Serial.cpp
        Serial.h
        sockets.cpp
        sockets.h
        Spp.h
        SPP_SPV.cpp
        Time.h
        TimeConversion.cpp
        Vector.cpp
        Vector.h)
