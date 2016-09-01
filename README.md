# colors
Boot sector program that displays all color modes

# Assemble and Run

nasm colors.asm -f bin -o colors.bin
qemu-system-i386 colors.bin
