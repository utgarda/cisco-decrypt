### Decoder for password encoding of Cisco VPN client. ##
Copyright (C) 2005 Maurice Massar   
Thanks to HAL-9000@evilscientists.de for decoding and posting the algorithm!

Requires libgcrypt version 1.1.90 or newer

Compile with:   
``gcc -Wall -o cisco-decrypt cisco-decrypt.c $(libgcrypt-config --libs --cflags)``

Usage:   
``./cisco-decrypt DEADBEEF...012345678 424242...7261``
