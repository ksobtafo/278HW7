;EAX = 42h, EBX = 5h and ECX = 5h
;EAX = 42h, EBX = 5h and ECX = 10h
;EAX = 42h, EBX = 10h and ECX = 5h
INCLUDE irvine32.inc 
.code
.data
mov eax, 42h
mov ebx, 5h
mov ecx, 5h

cmp ebx, ECX 
cmovae eax, ebx ;eax will have 5h if ebx >= ecx else will have 42

mov eax, 42h
mov ebx, 5h
mov ecx, 10h

cmp ebx, ECX 
cmovae eax, ebx ;eax will have 5h if ebx >= ecx else will have 42

mov eax, 42h
mov ebx, 10h
mov ecx, 5h

cmp ebx, ECX 
cmovae eax, ebx ;eax will have 5h if ebx >= ecx else will have 42
exit
main ENDP
