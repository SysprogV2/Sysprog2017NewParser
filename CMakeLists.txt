cmake_minimum_required(VERSION 3.5.1)
project(sysProg)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        Automat/src/Automat.cpp
        Automat/src/Automat.h
#        Automat/src/TestAutomat.cpp
        Buffer/src/Buffer.cpp
        Buffer/src/Buffer.h
#        Buffer/src/TestBuffer.cpp
        Parser/src/Node.cpp
        Parser/src/Node.h
        Parser/src/Parser.cpp
        Parser/src/Parser.h
        Parser/src/ParserTest.cpp
        Scanner/src/myListe.cpp
        Scanner/src/myListe.h
        Scanner/src/Scanner.cpp
        Scanner/src/Scanner.h
#        Scanner/src/TestScanner.cpp
        Scanner/src/Token.cpp
        Scanner/src/Token.h
        Symboltable/src/Information.cpp
        Symboltable/src/Information.h
        Symboltable/src/Symboltable.cpp
        Symboltable/src/Symboltable.h
#        Symboltable/src/TestSymboltable.cpp
        )

add_executable(sysProg ${SOURCE_FILES})