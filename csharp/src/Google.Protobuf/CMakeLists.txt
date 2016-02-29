cmake_minimum_required(VERSION 2.8)

set(PROJ_NAME Google.Protobuf)

execute_process(
            COMMAND  "${CMAKE_CURRENT_SOURCE_DIR}/NuGet.exe" "install" "${CMAKE_CURRENT_SOURCE_DIR}/packages.config"
            )
execute_process(COMMAND echo "bbbbbbb")
include(dsn.ext.csharp.cmake)