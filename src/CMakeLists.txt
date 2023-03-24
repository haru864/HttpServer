# CMakeのバージョンを設定
cmake_minimum_required(VERSION 3.22.1)
# プロジェクト名と使用する言語を設定
project(HttpServer CXX)
# a.outという実行ファイルをmain.cppとhello.cppから作成
add_executable(HttpServer HttpServer.cpp)
