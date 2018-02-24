# learn_nv

bat commands build hello world:

cl.exe  /I %UVROOT%\include helloworld.c   /link user32.lib advapi32.lib iphlpapi.lib psapi.lib  userenv.lib  ws2_32.lib  %UVROOT%\Debug\lib\libuv.lib /DEFAULTLIB:LIBCMTD
