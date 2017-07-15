cmake_minimum_required(VERSION 2.6)
project(FATDISK C)

add_definitions(-DVERSION="1.0.0-beta")

add_executable(fatdisk
  backtrace.c
  command.c
  dir.c
  disk.c
  fat.c
  file.c
  log.c
  main.c
  ptrcheck.c
  string.c
  tree.c
  util.c
)

