cmake_minimum_required(VERSION 3.16)

add_library(game_enderalse SHARED)
mo2_configure_plugin(game_enderalse
    WARNINGS OFF
    PRIVATE_DEPENDS creation)
mo2_install_target(game_enderalse)
