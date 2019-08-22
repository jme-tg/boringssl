include_directories(../../include)
include_directories(../../third_party/lwip/contrib/ports/xilinx/include)
include_directories(../../third_party/lwip/lwip-2.1.1/src/include)
include_directories(../../third_party/lwip/lwip-2.1.1/src/include/compat/posix)

add_library(
  bio

  OBJECT

  bio.c
  bio_mem.c
  connect.c
  fd.c
  file.c
  hexdump.c
  pair.c
  printf.c
  socket.c
  socket_helper.c
)
