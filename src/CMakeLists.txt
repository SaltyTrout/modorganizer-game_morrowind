cmake_minimum_required(VERSION 3.16)

add_library(game_morrowind SHARED)
mo2_configure_plugin(game_morrowind
    WARNINGS OFF
    PRIVATE_DEPENDS zlib gamebryo)
mo2_install_target(game_morrowind)
