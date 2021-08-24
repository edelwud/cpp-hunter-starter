cmake_minimum_required(VERSION 3.10)

set(CMAKE_INSTALL_PREFIX "/install")

include(cmake/main.cmake)

set(CMAKE_CXX_STANDARD 17)

project(${ADDON_APP}
        VERSION 0.0.1
        DESCRIPTION "High performance FTP server"
        HOMEPAGE_URL "https://github.com/edelwud/hpftp"
        LANGUAGES CXX)

initialize_project()
