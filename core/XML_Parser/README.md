============================================================
=============Adding the Library to Your Project=============

============================================================
Include the "asm-xml.h" file in your source file.
============================================================

Link your project with the AsmXml object file.
 ~ ~ ~ ~
Here are some tips to use it with various configurations:
  MSVC 6: Add the \ms-coff\asm-xml.obj file to your project.
  MinGW: Link your project with \ms-coff\asm-xml.obj.
  Linux: Link your project with /elf/asm-xml.o.
  Mac OS X: Link your project with /mach-o/asm-xml.o.
  
============================================================