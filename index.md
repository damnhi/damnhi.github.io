# My name is Damian Otto
 I study Computer Science and Artificial Intelligence at AGH Univeristy

### Projects that im working on:
 >> UnPause - fitness mobile app.
 
### Colors in Hex:

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Example Color | ![#0a192f](https://via.placeholder.com/10/0a192f?text=+) #0a192f |
| Example Color | ![#f8f8f8](https://via.placeholder.com/10/f8f8f8?text=+) #f8f8f8 |
| Example Color | ![#00b48a](https://via.placeholder.com/10/00b48a?text=+) #00b48a |
| Example Color | ![#00d1a0](https://via.placeholder.com/10/00b48a?text=+) #00d1a0 |

### This is hello world in Assembly
```
segment .data
	tekst db "Hello World!",0Dh,0Ah,"$"

segment stosik stack
	resb 64
segment .text
mov ax, .data
mov ds, ax
mov ax, stosik
mov ss, ax
mov dx, tekst
mov ah, 9
int 21h
mov ax, 4C00h
int 21h
```

### Authors

- [@damnhi](https://www.github.com/damnhi)
