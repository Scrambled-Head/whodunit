# Questions

## What's `stdint.h`?

contains integer types that allow the user to specify their length so that it can be recognised in all system environments

## What's the point of using `uint8_t`, `uint32_t`, `int32_t`, and `uint16_t` in a program?

To guarantee a specified amount of bits per int accross all system environments

## How many bytes is a `BYTE`, a `DWORD`, a `LONG`, and a `WORD`, respectively?

1, 4, 4, 2

## What (in ASCII, decimal, or hexadecimal) must the first two bytes of any BMP file be? Leading bytes used to identify file formats (with high probability) are generally called "magic numbers."

BM = 6677

## What's the difference between `bfSize` and `biSize`?

bfSize = full size of a bitmap file (in bytes). biSize = size of the bitmap structure (in bytes)

## What does it mean if `biHeight` is negative?

the bitmap is a top-down device-independent bitmap with the origin at the upper left corner

## What field in `BITMAPINFOHEADER` specifies the BMP's color depth (i.e., bits per pixel)?

biBitCount

## Why might `fopen` return `NULL` in lines 24 and 32 of `copy.c`?

if it can't find/open infile or outfile

## Why is the third argument to `fread` always `1` in our code?

because we always want to read 1 struct

## What value does line 63 of `copy.c` assign to `padding` if `bi.biWidth` is `3`?

3

## What does `fseek` do?

It finds a specific location within a file

## What is `SEEK_CUR`?

An integer constant which, when used as the whence argument to the fseek or fseeko functions, specifies that the offset provided is relative to the current file position
