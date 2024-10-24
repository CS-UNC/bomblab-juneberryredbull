
bomb:     file format elf64-x86-64


Disassembly of section .init:

0000000000001000 <_init>:
    1000:	f3 0f 1e fa          	endbr64 
    1004:	48 83 ec 08          	sub    $0x8,%rsp
    1008:	48 8b 05 d9 3f 00 00 	mov    0x3fd9(%rip),%rax        # 4fe8 <__gmon_start__@Base>
    100f:	48 85 c0             	test   %rax,%rax
    1012:	74 02                	je     1016 <_init+0x16>
    1014:	ff d0                	call   *%rax
    1016:	48 83 c4 08          	add    $0x8,%rsp
    101a:	c3                   	ret    

Disassembly of section .plt:

0000000000001020 <.plt>:
    1020:	ff 35 ca 3e 00 00    	push   0x3eca(%rip)        # 4ef0 <_GLOBAL_OFFSET_TABLE_+0x8>
    1026:	f2 ff 25 cb 3e 00 00 	bnd jmp *0x3ecb(%rip)        # 4ef8 <_GLOBAL_OFFSET_TABLE_+0x10>
    102d:	0f 1f 00             	nopl   (%rax)
    1030:	f3 0f 1e fa          	endbr64 
    1034:	68 00 00 00 00       	push   $0x0
    1039:	f2 e9 e1 ff ff ff    	bnd jmp 1020 <_init+0x20>
    103f:	90                   	nop
    1040:	f3 0f 1e fa          	endbr64 
    1044:	68 01 00 00 00       	push   $0x1
    1049:	f2 e9 d1 ff ff ff    	bnd jmp 1020 <_init+0x20>
    104f:	90                   	nop
    1050:	f3 0f 1e fa          	endbr64 
    1054:	68 02 00 00 00       	push   $0x2
    1059:	f2 e9 c1 ff ff ff    	bnd jmp 1020 <_init+0x20>
    105f:	90                   	nop
    1060:	f3 0f 1e fa          	endbr64 
    1064:	68 03 00 00 00       	push   $0x3
    1069:	f2 e9 b1 ff ff ff    	bnd jmp 1020 <_init+0x20>
    106f:	90                   	nop
    1070:	f3 0f 1e fa          	endbr64 
    1074:	68 04 00 00 00       	push   $0x4
    1079:	f2 e9 a1 ff ff ff    	bnd jmp 1020 <_init+0x20>
    107f:	90                   	nop
    1080:	f3 0f 1e fa          	endbr64 
    1084:	68 05 00 00 00       	push   $0x5
    1089:	f2 e9 91 ff ff ff    	bnd jmp 1020 <_init+0x20>
    108f:	90                   	nop
    1090:	f3 0f 1e fa          	endbr64 
    1094:	68 06 00 00 00       	push   $0x6
    1099:	f2 e9 81 ff ff ff    	bnd jmp 1020 <_init+0x20>
    109f:	90                   	nop
    10a0:	f3 0f 1e fa          	endbr64 
    10a4:	68 07 00 00 00       	push   $0x7
    10a9:	f2 e9 71 ff ff ff    	bnd jmp 1020 <_init+0x20>
    10af:	90                   	nop
    10b0:	f3 0f 1e fa          	endbr64 
    10b4:	68 08 00 00 00       	push   $0x8
    10b9:	f2 e9 61 ff ff ff    	bnd jmp 1020 <_init+0x20>
    10bf:	90                   	nop
    10c0:	f3 0f 1e fa          	endbr64 
    10c4:	68 09 00 00 00       	push   $0x9
    10c9:	f2 e9 51 ff ff ff    	bnd jmp 1020 <_init+0x20>
    10cf:	90                   	nop
    10d0:	f3 0f 1e fa          	endbr64 
    10d4:	68 0a 00 00 00       	push   $0xa
    10d9:	f2 e9 41 ff ff ff    	bnd jmp 1020 <_init+0x20>
    10df:	90                   	nop
    10e0:	f3 0f 1e fa          	endbr64 
    10e4:	68 0b 00 00 00       	push   $0xb
    10e9:	f2 e9 31 ff ff ff    	bnd jmp 1020 <_init+0x20>
    10ef:	90                   	nop
    10f0:	f3 0f 1e fa          	endbr64 
    10f4:	68 0c 00 00 00       	push   $0xc
    10f9:	f2 e9 21 ff ff ff    	bnd jmp 1020 <_init+0x20>
    10ff:	90                   	nop
    1100:	f3 0f 1e fa          	endbr64 
    1104:	68 0d 00 00 00       	push   $0xd
    1109:	f2 e9 11 ff ff ff    	bnd jmp 1020 <_init+0x20>
    110f:	90                   	nop
    1110:	f3 0f 1e fa          	endbr64 
    1114:	68 0e 00 00 00       	push   $0xe
    1119:	f2 e9 01 ff ff ff    	bnd jmp 1020 <_init+0x20>
    111f:	90                   	nop
    1120:	f3 0f 1e fa          	endbr64 
    1124:	68 0f 00 00 00       	push   $0xf
    1129:	f2 e9 f1 fe ff ff    	bnd jmp 1020 <_init+0x20>
    112f:	90                   	nop
    1130:	f3 0f 1e fa          	endbr64 
    1134:	68 10 00 00 00       	push   $0x10
    1139:	f2 e9 e1 fe ff ff    	bnd jmp 1020 <_init+0x20>
    113f:	90                   	nop
    1140:	f3 0f 1e fa          	endbr64 
    1144:	68 11 00 00 00       	push   $0x11
    1149:	f2 e9 d1 fe ff ff    	bnd jmp 1020 <_init+0x20>
    114f:	90                   	nop
    1150:	f3 0f 1e fa          	endbr64 
    1154:	68 12 00 00 00       	push   $0x12
    1159:	f2 e9 c1 fe ff ff    	bnd jmp 1020 <_init+0x20>
    115f:	90                   	nop
    1160:	f3 0f 1e fa          	endbr64 
    1164:	68 13 00 00 00       	push   $0x13
    1169:	f2 e9 b1 fe ff ff    	bnd jmp 1020 <_init+0x20>
    116f:	90                   	nop
    1170:	f3 0f 1e fa          	endbr64 
    1174:	68 14 00 00 00       	push   $0x14
    1179:	f2 e9 a1 fe ff ff    	bnd jmp 1020 <_init+0x20>
    117f:	90                   	nop
    1180:	f3 0f 1e fa          	endbr64 
    1184:	68 15 00 00 00       	push   $0x15
    1189:	f2 e9 91 fe ff ff    	bnd jmp 1020 <_init+0x20>
    118f:	90                   	nop
    1190:	f3 0f 1e fa          	endbr64 
    1194:	68 16 00 00 00       	push   $0x16
    1199:	f2 e9 81 fe ff ff    	bnd jmp 1020 <_init+0x20>
    119f:	90                   	nop
    11a0:	f3 0f 1e fa          	endbr64 
    11a4:	68 17 00 00 00       	push   $0x17
    11a9:	f2 e9 71 fe ff ff    	bnd jmp 1020 <_init+0x20>
    11af:	90                   	nop
    11b0:	f3 0f 1e fa          	endbr64 
    11b4:	68 18 00 00 00       	push   $0x18
    11b9:	f2 e9 61 fe ff ff    	bnd jmp 1020 <_init+0x20>
    11bf:	90                   	nop
    11c0:	f3 0f 1e fa          	endbr64 
    11c4:	68 19 00 00 00       	push   $0x19
    11c9:	f2 e9 51 fe ff ff    	bnd jmp 1020 <_init+0x20>
    11cf:	90                   	nop
    11d0:	f3 0f 1e fa          	endbr64 
    11d4:	68 1a 00 00 00       	push   $0x1a
    11d9:	f2 e9 41 fe ff ff    	bnd jmp 1020 <_init+0x20>
    11df:	90                   	nop

Disassembly of section .plt.got:

00000000000011e0 <__cxa_finalize@plt>:
    11e0:	f3 0f 1e fa          	endbr64 
    11e4:	f2 ff 25 0d 3e 00 00 	bnd jmp *0x3e0d(%rip)        # 4ff8 <__cxa_finalize@GLIBC_2.2.5>
    11eb:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

Disassembly of section .plt.sec:

00000000000011f0 <getenv@plt>:
    11f0:	f3 0f 1e fa          	endbr64 
    11f4:	f2 ff 25 05 3d 00 00 	bnd jmp *0x3d05(%rip)        # 4f00 <getenv@GLIBC_2.2.5>
    11fb:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001200 <__errno_location@plt>:
    1200:	f3 0f 1e fa          	endbr64 
    1204:	f2 ff 25 fd 3c 00 00 	bnd jmp *0x3cfd(%rip)        # 4f08 <__errno_location@GLIBC_2.2.5>
    120b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001210 <strcpy@plt>:
    1210:	f3 0f 1e fa          	endbr64 
    1214:	f2 ff 25 f5 3c 00 00 	bnd jmp *0x3cf5(%rip)        # 4f10 <strcpy@GLIBC_2.2.5>
    121b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001220 <puts@plt>:
    1220:	f3 0f 1e fa          	endbr64 
    1224:	f2 ff 25 ed 3c 00 00 	bnd jmp *0x3ced(%rip)        # 4f18 <puts@GLIBC_2.2.5>
    122b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001230 <write@plt>:
    1230:	f3 0f 1e fa          	endbr64 
    1234:	f2 ff 25 e5 3c 00 00 	bnd jmp *0x3ce5(%rip)        # 4f20 <write@GLIBC_2.2.5>
    123b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001240 <strlen@plt>:
    1240:	f3 0f 1e fa          	endbr64 
    1244:	f2 ff 25 dd 3c 00 00 	bnd jmp *0x3cdd(%rip)        # 4f28 <strlen@GLIBC_2.2.5>
    124b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001250 <__stack_chk_fail@plt>:
    1250:	f3 0f 1e fa          	endbr64 
    1254:	f2 ff 25 d5 3c 00 00 	bnd jmp *0x3cd5(%rip)        # 4f30 <__stack_chk_fail@GLIBC_2.4>
    125b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001260 <alarm@plt>:
    1260:	f3 0f 1e fa          	endbr64 
    1264:	f2 ff 25 cd 3c 00 00 	bnd jmp *0x3ccd(%rip)        # 4f38 <alarm@GLIBC_2.2.5>
    126b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001270 <close@plt>:
    1270:	f3 0f 1e fa          	endbr64 
    1274:	f2 ff 25 c5 3c 00 00 	bnd jmp *0x3cc5(%rip)        # 4f40 <close@GLIBC_2.2.5>
    127b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001280 <read@plt>:
    1280:	f3 0f 1e fa          	endbr64 
    1284:	f2 ff 25 bd 3c 00 00 	bnd jmp *0x3cbd(%rip)        # 4f48 <read@GLIBC_2.2.5>
    128b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001290 <fgets@plt>:
    1290:	f3 0f 1e fa          	endbr64 
    1294:	f2 ff 25 b5 3c 00 00 	bnd jmp *0x3cb5(%rip)        # 4f50 <fgets@GLIBC_2.2.5>
    129b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

00000000000012a0 <strcmp@plt>:
    12a0:	f3 0f 1e fa          	endbr64 
    12a4:	f2 ff 25 ad 3c 00 00 	bnd jmp *0x3cad(%rip)        # 4f58 <strcmp@GLIBC_2.2.5>
    12ab:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

00000000000012b0 <signal@plt>:
    12b0:	f3 0f 1e fa          	endbr64 
    12b4:	f2 ff 25 a5 3c 00 00 	bnd jmp *0x3ca5(%rip)        # 4f60 <signal@GLIBC_2.2.5>
    12bb:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

00000000000012c0 <gethostbyname@plt>:
    12c0:	f3 0f 1e fa          	endbr64 
    12c4:	f2 ff 25 9d 3c 00 00 	bnd jmp *0x3c9d(%rip)        # 4f68 <gethostbyname@GLIBC_2.2.5>
    12cb:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

00000000000012d0 <__memmove_chk@plt>:
    12d0:	f3 0f 1e fa          	endbr64 
    12d4:	f2 ff 25 95 3c 00 00 	bnd jmp *0x3c95(%rip)        # 4f70 <__memmove_chk@GLIBC_2.3.4>
    12db:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

00000000000012e0 <strtol@plt>:
    12e0:	f3 0f 1e fa          	endbr64 
    12e4:	f2 ff 25 8d 3c 00 00 	bnd jmp *0x3c8d(%rip)        # 4f78 <strtol@GLIBC_2.2.5>
    12eb:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

00000000000012f0 <fflush@plt>:
    12f0:	f3 0f 1e fa          	endbr64 
    12f4:	f2 ff 25 85 3c 00 00 	bnd jmp *0x3c85(%rip)        # 4f80 <fflush@GLIBC_2.2.5>
    12fb:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001300 <__isoc99_sscanf@plt>:
    1300:	f3 0f 1e fa          	endbr64 
    1304:	f2 ff 25 7d 3c 00 00 	bnd jmp *0x3c7d(%rip)        # 4f88 <__isoc99_sscanf@GLIBC_2.7>
    130b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001310 <__printf_chk@plt>:
    1310:	f3 0f 1e fa          	endbr64 
    1314:	f2 ff 25 75 3c 00 00 	bnd jmp *0x3c75(%rip)        # 4f90 <__printf_chk@GLIBC_2.3.4>
    131b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001320 <fopen@plt>:
    1320:	f3 0f 1e fa          	endbr64 
    1324:	f2 ff 25 6d 3c 00 00 	bnd jmp *0x3c6d(%rip)        # 4f98 <fopen@GLIBC_2.2.5>
    132b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001330 <exit@plt>:
    1330:	f3 0f 1e fa          	endbr64 
    1334:	f2 ff 25 65 3c 00 00 	bnd jmp *0x3c65(%rip)        # 4fa0 <exit@GLIBC_2.2.5>
    133b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001340 <connect@plt>:
    1340:	f3 0f 1e fa          	endbr64 
    1344:	f2 ff 25 5d 3c 00 00 	bnd jmp *0x3c5d(%rip)        # 4fa8 <connect@GLIBC_2.2.5>
    134b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001350 <__fprintf_chk@plt>:
    1350:	f3 0f 1e fa          	endbr64 
    1354:	f2 ff 25 55 3c 00 00 	bnd jmp *0x3c55(%rip)        # 4fb0 <__fprintf_chk@GLIBC_2.3.4>
    135b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001360 <sleep@plt>:
    1360:	f3 0f 1e fa          	endbr64 
    1364:	f2 ff 25 4d 3c 00 00 	bnd jmp *0x3c4d(%rip)        # 4fb8 <sleep@GLIBC_2.2.5>
    136b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001370 <__ctype_b_loc@plt>:
    1370:	f3 0f 1e fa          	endbr64 
    1374:	f2 ff 25 45 3c 00 00 	bnd jmp *0x3c45(%rip)        # 4fc0 <__ctype_b_loc@GLIBC_2.3>
    137b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001380 <__sprintf_chk@plt>:
    1380:	f3 0f 1e fa          	endbr64 
    1384:	f2 ff 25 3d 3c 00 00 	bnd jmp *0x3c3d(%rip)        # 4fc8 <__sprintf_chk@GLIBC_2.3.4>
    138b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001390 <socket@plt>:
    1390:	f3 0f 1e fa          	endbr64 
    1394:	f2 ff 25 35 3c 00 00 	bnd jmp *0x3c35(%rip)        # 4fd0 <socket@GLIBC_2.2.5>
    139b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

Disassembly of section .text:

00000000000013a0 <_start>:
    13a0:	f3 0f 1e fa          	endbr64 
    13a4:	31 ed                	xor    %ebp,%ebp
    13a6:	49 89 d1             	mov    %rdx,%r9
    13a9:	5e                   	pop    %rsi
    13aa:	48 89 e2             	mov    %rsp,%rdx
    13ad:	48 83 e4 f0          	and    $0xfffffffffffffff0,%rsp
    13b1:	50                   	push   %rax
    13b2:	54                   	push   %rsp
    13b3:	45 31 c0             	xor    %r8d,%r8d
    13b6:	31 c9                	xor    %ecx,%ecx
    13b8:	48 8d 3d ca 00 00 00 	lea    0xca(%rip),%rdi        # 1489 <main>
    13bf:	ff 15 13 3c 00 00    	call   *0x3c13(%rip)        # 4fd8 <__libc_start_main@GLIBC_2.34>
    13c5:	f4                   	hlt    
    13c6:	66 2e 0f 1f 84 00 00 	cs nopw 0x0(%rax,%rax,1)
    13cd:	00 00 00 

00000000000013d0 <deregister_tm_clones>:
    13d0:	48 8d 3d 89 42 00 00 	lea    0x4289(%rip),%rdi        # 5660 <stdout@GLIBC_2.2.5>
    13d7:	48 8d 05 82 42 00 00 	lea    0x4282(%rip),%rax        # 5660 <stdout@GLIBC_2.2.5>
    13de:	48 39 f8             	cmp    %rdi,%rax
    13e1:	74 15                	je     13f8 <deregister_tm_clones+0x28>
    13e3:	48 8b 05 f6 3b 00 00 	mov    0x3bf6(%rip),%rax        # 4fe0 <_ITM_deregisterTMCloneTable@Base>
    13ea:	48 85 c0             	test   %rax,%rax
    13ed:	74 09                	je     13f8 <deregister_tm_clones+0x28>
    13ef:	ff e0                	jmp    *%rax
    13f1:	0f 1f 80 00 00 00 00 	nopl   0x0(%rax)
    13f8:	c3                   	ret    
    13f9:	0f 1f 80 00 00 00 00 	nopl   0x0(%rax)

0000000000001400 <register_tm_clones>:
    1400:	48 8d 3d 59 42 00 00 	lea    0x4259(%rip),%rdi        # 5660 <stdout@GLIBC_2.2.5>
    1407:	48 8d 35 52 42 00 00 	lea    0x4252(%rip),%rsi        # 5660 <stdout@GLIBC_2.2.5>
    140e:	48 29 fe             	sub    %rdi,%rsi
    1411:	48 89 f0             	mov    %rsi,%rax
    1414:	48 c1 ee 3f          	shr    $0x3f,%rsi
    1418:	48 c1 f8 03          	sar    $0x3,%rax
    141c:	48 01 c6             	add    %rax,%rsi
    141f:	48 d1 fe             	sar    %rsi
    1422:	74 14                	je     1438 <register_tm_clones+0x38>
    1424:	48 8b 05 c5 3b 00 00 	mov    0x3bc5(%rip),%rax        # 4ff0 <_ITM_registerTMCloneTable@Base>
    142b:	48 85 c0             	test   %rax,%rax
    142e:	74 08                	je     1438 <register_tm_clones+0x38>
    1430:	ff e0                	jmp    *%rax
    1432:	66 0f 1f 44 00 00    	nopw   0x0(%rax,%rax,1)
    1438:	c3                   	ret    
    1439:	0f 1f 80 00 00 00 00 	nopl   0x0(%rax)

0000000000001440 <__do_global_dtors_aux>:
    1440:	f3 0f 1e fa          	endbr64 
    1444:	80 3d 3d 42 00 00 00 	cmpb   $0x0,0x423d(%rip)        # 5688 <completed.0>
    144b:	75 2b                	jne    1478 <__do_global_dtors_aux+0x38>
    144d:	55                   	push   %rbp
    144e:	48 83 3d a2 3b 00 00 	cmpq   $0x0,0x3ba2(%rip)        # 4ff8 <__cxa_finalize@GLIBC_2.2.5>
    1455:	00 
    1456:	48 89 e5             	mov    %rsp,%rbp
    1459:	74 0c                	je     1467 <__do_global_dtors_aux+0x27>
    145b:	48 8b 3d a6 3b 00 00 	mov    0x3ba6(%rip),%rdi        # 5008 <__dso_handle>
    1462:	e8 79 fd ff ff       	call   11e0 <__cxa_finalize@plt>
    1467:	e8 64 ff ff ff       	call   13d0 <deregister_tm_clones>
    146c:	c6 05 15 42 00 00 01 	movb   $0x1,0x4215(%rip)        # 5688 <completed.0>
    1473:	5d                   	pop    %rbp
    1474:	c3                   	ret    
    1475:	0f 1f 00             	nopl   (%rax)
    1478:	c3                   	ret    
    1479:	0f 1f 80 00 00 00 00 	nopl   0x0(%rax)

0000000000001480 <frame_dummy>:
    1480:	f3 0f 1e fa          	endbr64 
    1484:	e9 77 ff ff ff       	jmp    1400 <register_tm_clones>

0000000000001489 <main>:
    1489:	f3 0f 1e fa          	endbr64 
    148d:	53                   	push   %rbx
    148e:	83 ff 01             	cmp    $0x1,%edi
    1491:	0f 84 f8 00 00 00    	je     158f <main+0x106>
    1497:	48 89 f3             	mov    %rsi,%rbx
    149a:	83 ff 02             	cmp    $0x2,%edi
    149d:	0f 85 21 01 00 00    	jne    15c4 <main+0x13b>
    14a3:	48 8b 7e 08          	mov    0x8(%rsi),%rdi
    14a7:	48 8d 35 56 1b 00 00 	lea    0x1b56(%rip),%rsi        # 3004 <_IO_stdin_used+0x4>
    14ae:	e8 6d fe ff ff       	call   1320 <fopen@plt>
    14b3:	48 89 05 d6 41 00 00 	mov    %rax,0x41d6(%rip)        # 5690 <infile>
    14ba:	48 85 c0             	test   %rax,%rax
    14bd:	0f 84 df 00 00 00    	je     15a2 <main+0x119>
    14c3:	e8 6c 06 00 00       	call   1b34 <initialize_bomb>
    14c8:	48 8d 3d b9 1b 00 00 	lea    0x1bb9(%rip),%rdi        # 3088 <_IO_stdin_used+0x88>
    14cf:	e8 4c fd ff ff       	call   1220 <puts@plt>
    14d4:	48 8d 3d ed 1b 00 00 	lea    0x1bed(%rip),%rdi        # 30c8 <_IO_stdin_used+0xc8>
    14db:	e8 40 fd ff ff       	call   1220 <puts@plt>
    14e0:	e8 74 07 00 00       	call   1c59 <read_line>
    14e5:	48 89 c7             	mov    %rax,%rdi
    14e8:	e8 fa 00 00 00       	call   15e7 <phase_1>
    14ed:	e8 9f 08 00 00       	call   1d91 <phase_defused>
    14f2:	48 8d 3d ff 1b 00 00 	lea    0x1bff(%rip),%rdi        # 30f8 <_IO_stdin_used+0xf8>
    14f9:	e8 22 fd ff ff       	call   1220 <puts@plt>
    14fe:	e8 56 07 00 00       	call   1c59 <read_line>
    1503:	48 89 c7             	mov    %rax,%rdi
    1506:	e8 00 01 00 00       	call   160b <phase_2>
    150b:	e8 81 08 00 00       	call   1d91 <phase_defused>
    1510:	48 8d 3d 26 1b 00 00 	lea    0x1b26(%rip),%rdi        # 303d <_IO_stdin_used+0x3d>
    1517:	e8 04 fd ff ff       	call   1220 <puts@plt>
    151c:	e8 38 07 00 00       	call   1c59 <read_line>
    1521:	48 89 c7             	mov    %rax,%rdi
    1524:	e8 54 01 00 00       	call   167d <phase_3>
    1529:	e8 63 08 00 00       	call   1d91 <phase_defused>
    152e:	48 8d 3d 26 1b 00 00 	lea    0x1b26(%rip),%rdi        # 305b <_IO_stdin_used+0x5b>
    1535:	e8 e6 fc ff ff       	call   1220 <puts@plt>
    153a:	e8 1a 07 00 00       	call   1c59 <read_line>
    153f:	48 89 c7             	mov    %rax,%rdi
    1542:	e8 57 02 00 00       	call   179e <phase_4>
    1547:	e8 45 08 00 00       	call   1d91 <phase_defused>
    154c:	48 8d 3d d5 1b 00 00 	lea    0x1bd5(%rip),%rdi        # 3128 <_IO_stdin_used+0x128>
    1553:	e8 c8 fc ff ff       	call   1220 <puts@plt>
    1558:	e8 fc 06 00 00       	call   1c59 <read_line>
    155d:	48 89 c7             	mov    %rax,%rdi
    1560:	e8 ae 02 00 00       	call   1813 <phase_5>
    1565:	e8 27 08 00 00       	call   1d91 <phase_defused>
    156a:	48 8d 3d f9 1a 00 00 	lea    0x1af9(%rip),%rdi        # 306a <_IO_stdin_used+0x6a>
    1571:	e8 aa fc ff ff       	call   1220 <puts@plt>
    1576:	e8 de 06 00 00       	call   1c59 <read_line>
    157b:	48 89 c7             	mov    %rax,%rdi
    157e:	e8 dc 02 00 00       	call   185f <phase_6>
    1583:	e8 09 08 00 00       	call   1d91 <phase_defused>
    1588:	b8 00 00 00 00       	mov    $0x0,%eax
    158d:	5b                   	pop    %rbx
    158e:	c3                   	ret    
    158f:	48 8b 05 da 40 00 00 	mov    0x40da(%rip),%rax        # 5670 <stdin@GLIBC_2.2.5>
    1596:	48 89 05 f3 40 00 00 	mov    %rax,0x40f3(%rip)        # 5690 <infile>
    159d:	e9 21 ff ff ff       	jmp    14c3 <main+0x3a>
    15a2:	48 8b 4b 08          	mov    0x8(%rbx),%rcx
    15a6:	48 8b 13             	mov    (%rbx),%rdx
    15a9:	48 8d 35 56 1a 00 00 	lea    0x1a56(%rip),%rsi        # 3006 <_IO_stdin_used+0x6>
    15b0:	bf 01 00 00 00       	mov    $0x1,%edi
    15b5:	e8 56 fd ff ff       	call   1310 <__printf_chk@plt>
    15ba:	bf 08 00 00 00       	mov    $0x8,%edi
    15bf:	e8 6c fd ff ff       	call   1330 <exit@plt>
    15c4:	48 8b 16             	mov    (%rsi),%rdx
    15c7:	48 8d 35 55 1a 00 00 	lea    0x1a55(%rip),%rsi        # 3023 <_IO_stdin_used+0x23>
    15ce:	bf 01 00 00 00       	mov    $0x1,%edi
    15d3:	b8 00 00 00 00       	mov    $0x0,%eax
    15d8:	e8 33 fd ff ff       	call   1310 <__printf_chk@plt>
    15dd:	bf 08 00 00 00       	mov    $0x8,%edi
    15e2:	e8 49 fd ff ff       	call   1330 <exit@plt>

00000000000015e7 <phase_1>:
    15e7:	f3 0f 1e fa          	endbr64 
    15eb:	48 83 ec 08          	sub    $0x8,%rsp
    15ef:	48 8d 35 56 1b 00 00 	lea    0x1b56(%rip),%rsi        # 314c <_IO_stdin_used+0x14c>
    15f6:	e8 d9 04 00 00       	call   1ad4 <strings_not_equal>
    15fb:	85 c0                	test   %eax,%eax
    15fd:	75 05                	jne    1604 <phase_1+0x1d>
    15ff:	48 83 c4 08          	add    $0x8,%rsp
    1603:	c3                   	ret    
    1604:	e8 df 05 00 00       	call   1be8 <explode_bomb>
    1609:	eb f4                	jmp    15ff <phase_1+0x18>

000000000000160b <phase_2>:
    160b:	f3 0f 1e fa          	endbr64 
    160f:	55                   	push   %rbp
    1610:	53                   	push   %rbx
    1611:	48 83 ec 28          	sub    $0x28,%rsp
    1615:	64 48 8b 04 25 28 00 	mov    %fs:0x28,%rax
    161c:	00 00 
    161e:	48 89 44 24 18       	mov    %rax,0x18(%rsp)
    1623:	31 c0                	xor    %eax,%eax
    1625:	48 89 e6             	mov    %rsp,%rsi
    1628:	e8 e7 05 00 00       	call   1c14 <read_six_numbers>
    162d:	83 3c 24 00          	cmpl   $0x0,(%rsp)
    1631:	78 0a                	js     163d <phase_2+0x32>
    1633:	48 89 e5             	mov    %rsp,%rbp
    1636:	bb 01 00 00 00       	mov    $0x1,%ebx
    163b:	eb 13                	jmp    1650 <phase_2+0x45>
    163d:	e8 a6 05 00 00       	call   1be8 <explode_bomb>
    1642:	eb ef                	jmp    1633 <phase_2+0x28>
    1644:	83 c3 01             	add    $0x1,%ebx
    1647:	48 83 c5 04          	add    $0x4,%rbp
    164b:	83 fb 06             	cmp    $0x6,%ebx
    164e:	74 11                	je     1661 <phase_2+0x56>
    1650:	89 d8                	mov    %ebx,%eax
    1652:	03 45 00             	add    0x0(%rbp),%eax
    1655:	39 45 04             	cmp    %eax,0x4(%rbp)
    1658:	74 ea                	je     1644 <phase_2+0x39>
    165a:	e8 89 05 00 00       	call   1be8 <explode_bomb>
    165f:	eb e3                	jmp    1644 <phase_2+0x39>
    1661:	48 8b 44 24 18       	mov    0x18(%rsp),%rax
    1666:	64 48 2b 04 25 28 00 	sub    %fs:0x28,%rax
    166d:	00 00 
    166f:	75 07                	jne    1678 <phase_2+0x6d>
    1671:	48 83 c4 28          	add    $0x28,%rsp
    1675:	5b                   	pop    %rbx
    1676:	5d                   	pop    %rbp
    1677:	c3                   	ret    
    1678:	e8 d3 fb ff ff       	call   1250 <__stack_chk_fail@plt>

000000000000167d <phase_3>:
    167d:	f3 0f 1e fa          	endbr64 
    1681:	48 83 ec 18          	sub    $0x18,%rsp
    1685:	64 48 8b 04 25 28 00 	mov    %fs:0x28,%rax
    168c:	00 00 
    168e:	48 89 44 24 08       	mov    %rax,0x8(%rsp)
    1693:	31 c0                	xor    %eax,%eax
    1695:	48 8d 4c 24 04       	lea    0x4(%rsp),%rcx
    169a:	48 89 e2             	mov    %rsp,%rdx
    169d:	48 8d 35 73 1c 00 00 	lea    0x1c73(%rip),%rsi        # 3317 <array.0+0x177>
    16a4:	e8 57 fc ff ff       	call   1300 <__isoc99_sscanf@plt>
    16a9:	83 f8 01             	cmp    $0x1,%eax
    16ac:	7e 1e                	jle    16cc <phase_3+0x4f>
    16ae:	83 3c 24 07          	cmpl   $0x7,(%rsp)
    16b2:	0f 87 9a 00 00 00    	ja     1752 <phase_3+0xd5>
    16b8:	8b 04 24             	mov    (%rsp),%eax
    16bb:	48 8d 15 be 1a 00 00 	lea    0x1abe(%rip),%rdx        # 3180 <_IO_stdin_used+0x180>
    16c2:	48 63 04 82          	movslq (%rdx,%rax,4),%rax
    16c6:	48 01 d0             	add    %rdx,%rax
    16c9:	3e ff e0             	notrack jmp *%rax
    16cc:	e8 17 05 00 00       	call   1be8 <explode_bomb>
    16d1:	eb db                	jmp    16ae <phase_3+0x31>
    16d3:	b8 4b 00 00 00       	mov    $0x4b,%eax
    16d8:	2d ae 03 00 00       	sub    $0x3ae,%eax
    16dd:	05 2e 02 00 00       	add    $0x22e,%eax
    16e2:	2d c8 02 00 00       	sub    $0x2c8,%eax
    16e7:	05 c8 02 00 00       	add    $0x2c8,%eax
    16ec:	2d c8 02 00 00       	sub    $0x2c8,%eax
    16f1:	05 c8 02 00 00       	add    $0x2c8,%eax
    16f6:	2d c8 02 00 00       	sub    $0x2c8,%eax
    16fb:	83 3c 24 05          	cmpl   $0x5,(%rsp)
    16ff:	7f 06                	jg     1707 <phase_3+0x8a>
    1701:	39 44 24 04          	cmp    %eax,0x4(%rsp)
    1705:	74 05                	je     170c <phase_3+0x8f>
    1707:	e8 dc 04 00 00       	call   1be8 <explode_bomb>
    170c:	48 8b 44 24 08       	mov    0x8(%rsp),%rax
    1711:	64 48 2b 04 25 28 00 	sub    %fs:0x28,%rax
    1718:	00 00 
    171a:	75 42                	jne    175e <phase_3+0xe1>
    171c:	48 83 c4 18          	add    $0x18,%rsp
    1720:	c3                   	ret    
    1721:	b8 00 00 00 00       	mov    $0x0,%eax
    1726:	eb b0                	jmp    16d8 <phase_3+0x5b>
    1728:	b8 00 00 00 00       	mov    $0x0,%eax
    172d:	eb ae                	jmp    16dd <phase_3+0x60>
    172f:	b8 00 00 00 00       	mov    $0x0,%eax
    1734:	eb ac                	jmp    16e2 <phase_3+0x65>
    1736:	b8 00 00 00 00       	mov    $0x0,%eax
    173b:	eb aa                	jmp    16e7 <phase_3+0x6a>
    173d:	b8 00 00 00 00       	mov    $0x0,%eax
    1742:	eb a8                	jmp    16ec <phase_3+0x6f>
    1744:	b8 00 00 00 00       	mov    $0x0,%eax
    1749:	eb a6                	jmp    16f1 <phase_3+0x74>
    174b:	b8 00 00 00 00       	mov    $0x0,%eax
    1750:	eb a4                	jmp    16f6 <phase_3+0x79>
    1752:	e8 91 04 00 00       	call   1be8 <explode_bomb>
    1757:	b8 00 00 00 00       	mov    $0x0,%eax
    175c:	eb 9d                	jmp    16fb <phase_3+0x7e>
    175e:	e8 ed fa ff ff       	call   1250 <__stack_chk_fail@plt>

0000000000001763 <func4>:
    1763:	f3 0f 1e fa          	endbr64 
    1767:	b8 00 00 00 00       	mov    $0x0,%eax
    176c:	85 ff                	test   %edi,%edi
    176e:	7e 2d                	jle    179d <func4+0x3a>
    1770:	41 54                	push   %r12
    1772:	55                   	push   %rbp
    1773:	53                   	push   %rbx
    1774:	89 fb                	mov    %edi,%ebx
    1776:	89 f5                	mov    %esi,%ebp
    1778:	89 f0                	mov    %esi,%eax
    177a:	83 ff 01             	cmp    $0x1,%edi
    177d:	74 19                	je     1798 <func4+0x35>
    177f:	8d 7f ff             	lea    -0x1(%rdi),%edi
    1782:	e8 dc ff ff ff       	call   1763 <func4>
    1787:	44 8d 24 28          	lea    (%rax,%rbp,1),%r12d
    178b:	8d 7b fe             	lea    -0x2(%rbx),%edi
    178e:	89 ee                	mov    %ebp,%esi
    1790:	e8 ce ff ff ff       	call   1763 <func4>
    1795:	44 01 e0             	add    %r12d,%eax
    1798:	5b                   	pop    %rbx
    1799:	5d                   	pop    %rbp
    179a:	41 5c                	pop    %r12
    179c:	c3                   	ret    
    179d:	c3                   	ret    

000000000000179e <phase_4>:
    179e:	f3 0f 1e fa          	endbr64 
    17a2:	48 83 ec 18          	sub    $0x18,%rsp
    17a6:	64 48 8b 04 25 28 00 	mov    %fs:0x28,%rax
    17ad:	00 00 
    17af:	48 89 44 24 08       	mov    %rax,0x8(%rsp)
    17b4:	31 c0                	xor    %eax,%eax
    17b6:	48 89 e1             	mov    %rsp,%rcx
    17b9:	48 8d 54 24 04       	lea    0x4(%rsp),%rdx
    17be:	48 8d 35 52 1b 00 00 	lea    0x1b52(%rip),%rsi        # 3317 <array.0+0x177>
    17c5:	e8 36 fb ff ff       	call   1300 <__isoc99_sscanf@plt>
    17ca:	83 f8 02             	cmp    $0x2,%eax
    17cd:	75 0b                	jne    17da <phase_4+0x3c>
    17cf:	8b 04 24             	mov    (%rsp),%eax
    17d2:	83 e8 02             	sub    $0x2,%eax
    17d5:	83 f8 02             	cmp    $0x2,%eax
    17d8:	76 05                	jbe    17df <phase_4+0x41>
    17da:	e8 09 04 00 00       	call   1be8 <explode_bomb>
    17df:	8b 34 24             	mov    (%rsp),%esi
    17e2:	bf 09 00 00 00       	mov    $0x9,%edi
    17e7:	e8 77 ff ff ff       	call   1763 <func4>
    17ec:	39 44 24 04          	cmp    %eax,0x4(%rsp)
    17f0:	75 15                	jne    1807 <phase_4+0x69>
    17f2:	48 8b 44 24 08       	mov    0x8(%rsp),%rax
    17f7:	64 48 2b 04 25 28 00 	sub    %fs:0x28,%rax
    17fe:	00 00 
    1800:	75 0c                	jne    180e <phase_4+0x70>
    1802:	48 83 c4 18          	add    $0x18,%rsp
    1806:	c3                   	ret    
    1807:	e8 dc 03 00 00       	call   1be8 <explode_bomb>
    180c:	eb e4                	jmp    17f2 <phase_4+0x54>
    180e:	e8 3d fa ff ff       	call   1250 <__stack_chk_fail@plt>

0000000000001813 <phase_5>:
    1813:	f3 0f 1e fa          	endbr64 
    1817:	53                   	push   %rbx
    1818:	48 89 fb             	mov    %rdi,%rbx
    181b:	e8 93 02 00 00       	call   1ab3 <string_length>
    1820:	83 f8 06             	cmp    $0x6,%eax
    1823:	75 2c                	jne    1851 <phase_5+0x3e>
    1825:	48 89 d8             	mov    %rbx,%rax
    1828:	48 8d 7b 06          	lea    0x6(%rbx),%rdi
    182c:	b9 00 00 00 00       	mov    $0x0,%ecx
    1831:	48 8d 35 68 19 00 00 	lea    0x1968(%rip),%rsi        # 31a0 <array.0>
    1838:	0f b6 10             	movzbl (%rax),%edx
    183b:	83 e2 0f             	and    $0xf,%edx
    183e:	03 0c 96             	add    (%rsi,%rdx,4),%ecx
    1841:	48 83 c0 01          	add    $0x1,%rax
    1845:	48 39 f8             	cmp    %rdi,%rax
    1848:	75 ee                	jne    1838 <phase_5+0x25>
    184a:	83 f9 2a             	cmp    $0x2a,%ecx
    184d:	75 09                	jne    1858 <phase_5+0x45>
    184f:	5b                   	pop    %rbx
    1850:	c3                   	ret    
    1851:	e8 92 03 00 00       	call   1be8 <explode_bomb>
    1856:	eb cd                	jmp    1825 <phase_5+0x12>
    1858:	e8 8b 03 00 00       	call   1be8 <explode_bomb>
    185d:	eb f0                	jmp    184f <phase_5+0x3c>

000000000000185f <phase_6>:
    185f:	f3 0f 1e fa          	endbr64 
    1863:	41 56                	push   %r14
    1865:	41 55                	push   %r13
    1867:	41 54                	push   %r12
    1869:	55                   	push   %rbp
    186a:	53                   	push   %rbx
    186b:	48 83 ec 60          	sub    $0x60,%rsp
    186f:	64 48 8b 04 25 28 00 	mov    %fs:0x28,%rax
    1876:	00 00 
    1878:	48 89 44 24 58       	mov    %rax,0x58(%rsp)
    187d:	31 c0                	xor    %eax,%eax
    187f:	49 89 e5             	mov    %rsp,%r13
    1882:	4c 89 ee             	mov    %r13,%rsi
    1885:	e8 8a 03 00 00       	call   1c14 <read_six_numbers>
    188a:	41 be 01 00 00 00    	mov    $0x1,%r14d
    1890:	49 89 e4             	mov    %rsp,%r12
    1893:	eb 28                	jmp    18bd <phase_6+0x5e>
    1895:	e8 4e 03 00 00       	call   1be8 <explode_bomb>
    189a:	eb 30                	jmp    18cc <phase_6+0x6d>
    189c:	48 83 c3 01          	add    $0x1,%rbx
    18a0:	83 fb 05             	cmp    $0x5,%ebx
    18a3:	7f 10                	jg     18b5 <phase_6+0x56>
    18a5:	41 8b 04 9c          	mov    (%r12,%rbx,4),%eax
    18a9:	39 45 00             	cmp    %eax,0x0(%rbp)
    18ac:	75 ee                	jne    189c <phase_6+0x3d>
    18ae:	e8 35 03 00 00       	call   1be8 <explode_bomb>
    18b3:	eb e7                	jmp    189c <phase_6+0x3d>
    18b5:	49 83 c6 01          	add    $0x1,%r14
    18b9:	49 83 c5 04          	add    $0x4,%r13
    18bd:	4c 89 ed             	mov    %r13,%rbp
    18c0:	41 8b 45 00          	mov    0x0(%r13),%eax
    18c4:	83 e8 01             	sub    $0x1,%eax
    18c7:	83 f8 05             	cmp    $0x5,%eax
    18ca:	77 c9                	ja     1895 <phase_6+0x36>
    18cc:	41 83 fe 05          	cmp    $0x5,%r14d
    18d0:	7f 05                	jg     18d7 <phase_6+0x78>
    18d2:	4c 89 f3             	mov    %r14,%rbx
    18d5:	eb ce                	jmp    18a5 <phase_6+0x46>
    18d7:	be 00 00 00 00       	mov    $0x0,%esi
    18dc:	8b 0c b4             	mov    (%rsp,%rsi,4),%ecx
    18df:	b8 01 00 00 00       	mov    $0x1,%eax
    18e4:	48 8d 15 15 39 00 00 	lea    0x3915(%rip),%rdx        # 5200 <node1>
    18eb:	83 f9 01             	cmp    $0x1,%ecx
    18ee:	7e 0b                	jle    18fb <phase_6+0x9c>
    18f0:	48 8b 52 08          	mov    0x8(%rdx),%rdx
    18f4:	83 c0 01             	add    $0x1,%eax
    18f7:	39 c8                	cmp    %ecx,%eax
    18f9:	75 f5                	jne    18f0 <phase_6+0x91>
    18fb:	48 89 54 f4 20       	mov    %rdx,0x20(%rsp,%rsi,8)
    1900:	48 83 c6 01          	add    $0x1,%rsi
    1904:	48 83 fe 06          	cmp    $0x6,%rsi
    1908:	75 d2                	jne    18dc <phase_6+0x7d>
    190a:	48 8b 5c 24 20       	mov    0x20(%rsp),%rbx
    190f:	48 8b 44 24 28       	mov    0x28(%rsp),%rax
    1914:	48 89 43 08          	mov    %rax,0x8(%rbx)
    1918:	48 8b 54 24 30       	mov    0x30(%rsp),%rdx
    191d:	48 89 50 08          	mov    %rdx,0x8(%rax)
    1921:	48 8b 44 24 38       	mov    0x38(%rsp),%rax
    1926:	48 89 42 08          	mov    %rax,0x8(%rdx)
    192a:	48 8b 54 24 40       	mov    0x40(%rsp),%rdx
    192f:	48 89 50 08          	mov    %rdx,0x8(%rax)
    1933:	48 8b 44 24 48       	mov    0x48(%rsp),%rax
    1938:	48 89 42 08          	mov    %rax,0x8(%rdx)
    193c:	48 c7 40 08 00 00 00 	movq   $0x0,0x8(%rax)
    1943:	00 
    1944:	bd 05 00 00 00       	mov    $0x5,%ebp
    1949:	eb 09                	jmp    1954 <phase_6+0xf5>
    194b:	48 8b 5b 08          	mov    0x8(%rbx),%rbx
    194f:	83 ed 01             	sub    $0x1,%ebp
    1952:	74 11                	je     1965 <phase_6+0x106>
    1954:	48 8b 43 08          	mov    0x8(%rbx),%rax
    1958:	8b 00                	mov    (%rax),%eax
    195a:	39 03                	cmp    %eax,(%rbx)
    195c:	7d ed                	jge    194b <phase_6+0xec>
    195e:	e8 85 02 00 00       	call   1be8 <explode_bomb>
    1963:	eb e6                	jmp    194b <phase_6+0xec>
    1965:	48 8b 44 24 58       	mov    0x58(%rsp),%rax
    196a:	64 48 2b 04 25 28 00 	sub    %fs:0x28,%rax
    1971:	00 00 
    1973:	75 0d                	jne    1982 <phase_6+0x123>
    1975:	48 83 c4 60          	add    $0x60,%rsp
    1979:	5b                   	pop    %rbx
    197a:	5d                   	pop    %rbp
    197b:	41 5c                	pop    %r12
    197d:	41 5d                	pop    %r13
    197f:	41 5e                	pop    %r14
    1981:	c3                   	ret    
    1982:	e8 c9 f8 ff ff       	call   1250 <__stack_chk_fail@plt>

0000000000001987 <fun7>:
    1987:	f3 0f 1e fa          	endbr64 
    198b:	48 85 ff             	test   %rdi,%rdi
    198e:	74 32                	je     19c2 <fun7+0x3b>
    1990:	48 83 ec 08          	sub    $0x8,%rsp
    1994:	8b 17                	mov    (%rdi),%edx
    1996:	39 f2                	cmp    %esi,%edx
    1998:	7f 0c                	jg     19a6 <fun7+0x1f>
    199a:	b8 00 00 00 00       	mov    $0x0,%eax
    199f:	75 12                	jne    19b3 <fun7+0x2c>
    19a1:	48 83 c4 08          	add    $0x8,%rsp
    19a5:	c3                   	ret    
    19a6:	48 8b 7f 08          	mov    0x8(%rdi),%rdi
    19aa:	e8 d8 ff ff ff       	call   1987 <fun7>
    19af:	01 c0                	add    %eax,%eax
    19b1:	eb ee                	jmp    19a1 <fun7+0x1a>
    19b3:	48 8b 7f 10          	mov    0x10(%rdi),%rdi
    19b7:	e8 cb ff ff ff       	call   1987 <fun7>
    19bc:	8d 44 00 01          	lea    0x1(%rax,%rax,1),%eax
    19c0:	eb df                	jmp    19a1 <fun7+0x1a>
    19c2:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    19c7:	c3                   	ret    

00000000000019c8 <secret_phase>:
    19c8:	f3 0f 1e fa          	endbr64 
    19cc:	53                   	push   %rbx
    19cd:	e8 87 02 00 00       	call   1c59 <read_line>
    19d2:	48 89 c7             	mov    %rax,%rdi
    19d5:	ba 0a 00 00 00       	mov    $0xa,%edx
    19da:	be 00 00 00 00       	mov    $0x0,%esi
    19df:	e8 fc f8 ff ff       	call   12e0 <strtol@plt>
    19e4:	89 c3                	mov    %eax,%ebx
    19e6:	83 e8 01             	sub    $0x1,%eax
    19e9:	3d e8 03 00 00       	cmp    $0x3e8,%eax
    19ee:	77 26                	ja     1a16 <secret_phase+0x4e>
    19f0:	89 de                	mov    %ebx,%esi
    19f2:	48 8d 3d 27 37 00 00 	lea    0x3727(%rip),%rdi        # 5120 <n1>
    19f9:	e8 89 ff ff ff       	call   1987 <fun7>
    19fe:	83 f8 07             	cmp    $0x7,%eax
    1a01:	75 1a                	jne    1a1d <secret_phase+0x55>
    1a03:	48 8d 3d d6 17 00 00 	lea    0x17d6(%rip),%rdi        # 31e0 <array.0+0x40>
    1a0a:	e8 11 f8 ff ff       	call   1220 <puts@plt>
    1a0f:	e8 7d 03 00 00       	call   1d91 <phase_defused>
    1a14:	5b                   	pop    %rbx
    1a15:	c3                   	ret    
    1a16:	e8 cd 01 00 00       	call   1be8 <explode_bomb>
    1a1b:	eb d3                	jmp    19f0 <secret_phase+0x28>
    1a1d:	e8 c6 01 00 00       	call   1be8 <explode_bomb>
    1a22:	eb df                	jmp    1a03 <secret_phase+0x3b>

0000000000001a24 <sig_handler>:
    1a24:	f3 0f 1e fa          	endbr64 
    1a28:	50                   	push   %rax
    1a29:	58                   	pop    %rax
    1a2a:	48 83 ec 08          	sub    $0x8,%rsp
    1a2e:	48 8d 3d d3 17 00 00 	lea    0x17d3(%rip),%rdi        # 3208 <array.0+0x68>
    1a35:	e8 e6 f7 ff ff       	call   1220 <puts@plt>
    1a3a:	bf 03 00 00 00       	mov    $0x3,%edi
    1a3f:	e8 1c f9 ff ff       	call   1360 <sleep@plt>
    1a44:	48 8d 35 7f 18 00 00 	lea    0x187f(%rip),%rsi        # 32ca <array.0+0x12a>
    1a4b:	bf 01 00 00 00       	mov    $0x1,%edi
    1a50:	b8 00 00 00 00       	mov    $0x0,%eax
    1a55:	e8 b6 f8 ff ff       	call   1310 <__printf_chk@plt>
    1a5a:	48 8b 3d ff 3b 00 00 	mov    0x3bff(%rip),%rdi        # 5660 <stdout@GLIBC_2.2.5>
    1a61:	e8 8a f8 ff ff       	call   12f0 <fflush@plt>
    1a66:	bf 01 00 00 00       	mov    $0x1,%edi
    1a6b:	e8 f0 f8 ff ff       	call   1360 <sleep@plt>
    1a70:	48 8d 3d 5b 18 00 00 	lea    0x185b(%rip),%rdi        # 32d2 <array.0+0x132>
    1a77:	e8 a4 f7 ff ff       	call   1220 <puts@plt>
    1a7c:	bf 10 00 00 00       	mov    $0x10,%edi
    1a81:	e8 aa f8 ff ff       	call   1330 <exit@plt>

0000000000001a86 <invalid_phase>:
    1a86:	f3 0f 1e fa          	endbr64 
    1a8a:	50                   	push   %rax
    1a8b:	58                   	pop    %rax
    1a8c:	48 83 ec 08          	sub    $0x8,%rsp
    1a90:	48 89 fa             	mov    %rdi,%rdx
    1a93:	48 8d 35 40 18 00 00 	lea    0x1840(%rip),%rsi        # 32da <array.0+0x13a>
    1a9a:	bf 01 00 00 00       	mov    $0x1,%edi
    1a9f:	b8 00 00 00 00       	mov    $0x0,%eax
    1aa4:	e8 67 f8 ff ff       	call   1310 <__printf_chk@plt>
    1aa9:	bf 08 00 00 00       	mov    $0x8,%edi
    1aae:	e8 7d f8 ff ff       	call   1330 <exit@plt>

0000000000001ab3 <string_length>:
    1ab3:	f3 0f 1e fa          	endbr64 
    1ab7:	80 3f 00             	cmpb   $0x0,(%rdi)
    1aba:	74 12                	je     1ace <string_length+0x1b>
    1abc:	b8 00 00 00 00       	mov    $0x0,%eax
    1ac1:	48 83 c7 01          	add    $0x1,%rdi
    1ac5:	83 c0 01             	add    $0x1,%eax
    1ac8:	80 3f 00             	cmpb   $0x0,(%rdi)
    1acb:	75 f4                	jne    1ac1 <string_length+0xe>
    1acd:	c3                   	ret    
    1ace:	b8 00 00 00 00       	mov    $0x0,%eax
    1ad3:	c3                   	ret    

0000000000001ad4 <strings_not_equal>:
    1ad4:	f3 0f 1e fa          	endbr64 
    1ad8:	41 54                	push   %r12
    1ada:	55                   	push   %rbp
    1adb:	53                   	push   %rbx
    1adc:	48 89 fb             	mov    %rdi,%rbx
    1adf:	48 89 f5             	mov    %rsi,%rbp
    1ae2:	e8 cc ff ff ff       	call   1ab3 <string_length>
    1ae7:	41 89 c4             	mov    %eax,%r12d
    1aea:	48 89 ef             	mov    %rbp,%rdi
    1aed:	e8 c1 ff ff ff       	call   1ab3 <string_length>
    1af2:	89 c2                	mov    %eax,%edx
    1af4:	b8 01 00 00 00       	mov    $0x1,%eax
    1af9:	41 39 d4             	cmp    %edx,%r12d
    1afc:	75 31                	jne    1b2f <strings_not_equal+0x5b>
    1afe:	0f b6 13             	movzbl (%rbx),%edx
    1b01:	84 d2                	test   %dl,%dl
    1b03:	74 1e                	je     1b23 <strings_not_equal+0x4f>
    1b05:	b8 00 00 00 00       	mov    $0x0,%eax
    1b0a:	38 54 05 00          	cmp    %dl,0x0(%rbp,%rax,1)
    1b0e:	75 1a                	jne    1b2a <strings_not_equal+0x56>
    1b10:	48 83 c0 01          	add    $0x1,%rax
    1b14:	0f b6 14 03          	movzbl (%rbx,%rax,1),%edx
    1b18:	84 d2                	test   %dl,%dl
    1b1a:	75 ee                	jne    1b0a <strings_not_equal+0x36>
    1b1c:	b8 00 00 00 00       	mov    $0x0,%eax
    1b21:	eb 0c                	jmp    1b2f <strings_not_equal+0x5b>
    1b23:	b8 00 00 00 00       	mov    $0x0,%eax
    1b28:	eb 05                	jmp    1b2f <strings_not_equal+0x5b>
    1b2a:	b8 01 00 00 00       	mov    $0x1,%eax
    1b2f:	5b                   	pop    %rbx
    1b30:	5d                   	pop    %rbp
    1b31:	41 5c                	pop    %r12
    1b33:	c3                   	ret    

0000000000001b34 <initialize_bomb>:
    1b34:	f3 0f 1e fa          	endbr64 
    1b38:	48 83 ec 08          	sub    $0x8,%rsp
    1b3c:	48 8d 35 e1 fe ff ff 	lea    -0x11f(%rip),%rsi        # 1a24 <sig_handler>
    1b43:	bf 02 00 00 00       	mov    $0x2,%edi
    1b48:	e8 63 f7 ff ff       	call   12b0 <signal@plt>
    1b4d:	48 83 c4 08          	add    $0x8,%rsp
    1b51:	c3                   	ret    

0000000000001b52 <initialize_bomb_solve>:
    1b52:	f3 0f 1e fa          	endbr64 
    1b56:	c3                   	ret    

0000000000001b57 <blank_line>:
    1b57:	f3 0f 1e fa          	endbr64 
    1b5b:	55                   	push   %rbp
    1b5c:	53                   	push   %rbx
    1b5d:	48 83 ec 08          	sub    $0x8,%rsp
    1b61:	48 89 fd             	mov    %rdi,%rbp
    1b64:	0f b6 5d 00          	movzbl 0x0(%rbp),%ebx
    1b68:	84 db                	test   %bl,%bl
    1b6a:	74 1e                	je     1b8a <blank_line+0x33>
    1b6c:	e8 ff f7 ff ff       	call   1370 <__ctype_b_loc@plt>
    1b71:	48 83 c5 01          	add    $0x1,%rbp
    1b75:	48 0f be db          	movsbq %bl,%rbx
    1b79:	48 8b 00             	mov    (%rax),%rax
    1b7c:	f6 44 58 01 20       	testb  $0x20,0x1(%rax,%rbx,2)
    1b81:	75 e1                	jne    1b64 <blank_line+0xd>
    1b83:	b8 00 00 00 00       	mov    $0x0,%eax
    1b88:	eb 05                	jmp    1b8f <blank_line+0x38>
    1b8a:	b8 01 00 00 00       	mov    $0x1,%eax
    1b8f:	48 83 c4 08          	add    $0x8,%rsp
    1b93:	5b                   	pop    %rbx
    1b94:	5d                   	pop    %rbp
    1b95:	c3                   	ret    

0000000000001b96 <skip>:
    1b96:	f3 0f 1e fa          	endbr64 
    1b9a:	55                   	push   %rbp
    1b9b:	53                   	push   %rbx
    1b9c:	48 83 ec 08          	sub    $0x8,%rsp
    1ba0:	48 8d 2d 59 3b 00 00 	lea    0x3b59(%rip),%rbp        # 5700 <input_strings>
    1ba7:	48 63 05 42 3b 00 00 	movslq 0x3b42(%rip),%rax        # 56f0 <num_input_strings>
    1bae:	48 8d 3c 80          	lea    (%rax,%rax,4),%rdi
    1bb2:	48 c1 e7 04          	shl    $0x4,%rdi
    1bb6:	48 01 ef             	add    %rbp,%rdi
    1bb9:	48 8b 15 d0 3a 00 00 	mov    0x3ad0(%rip),%rdx        # 5690 <infile>
    1bc0:	be 50 00 00 00       	mov    $0x50,%esi
    1bc5:	e8 c6 f6 ff ff       	call   1290 <fgets@plt>
    1bca:	48 89 c3             	mov    %rax,%rbx
    1bcd:	48 85 c0             	test   %rax,%rax
    1bd0:	74 0c                	je     1bde <skip+0x48>
    1bd2:	48 89 c7             	mov    %rax,%rdi
    1bd5:	e8 7d ff ff ff       	call   1b57 <blank_line>
    1bda:	85 c0                	test   %eax,%eax
    1bdc:	75 c9                	jne    1ba7 <skip+0x11>
    1bde:	48 89 d8             	mov    %rbx,%rax
    1be1:	48 83 c4 08          	add    $0x8,%rsp
    1be5:	5b                   	pop    %rbx
    1be6:	5d                   	pop    %rbp
    1be7:	c3                   	ret    

0000000000001be8 <explode_bomb>:
    1be8:	f3 0f 1e fa          	endbr64 
    1bec:	50                   	push   %rax
    1bed:	58                   	pop    %rax
    1bee:	48 83 ec 08          	sub    $0x8,%rsp
    1bf2:	48 8d 3d f2 16 00 00 	lea    0x16f2(%rip),%rdi        # 32eb <array.0+0x14b>
    1bf9:	e8 22 f6 ff ff       	call   1220 <puts@plt>
    1bfe:	48 8d 3d ef 16 00 00 	lea    0x16ef(%rip),%rdi        # 32f4 <array.0+0x154>
    1c05:	e8 16 f6 ff ff       	call   1220 <puts@plt>
    1c0a:	bf 08 00 00 00       	mov    $0x8,%edi
    1c0f:	e8 1c f7 ff ff       	call   1330 <exit@plt>

0000000000001c14 <read_six_numbers>:
    1c14:	f3 0f 1e fa          	endbr64 
    1c18:	48 83 ec 08          	sub    $0x8,%rsp
    1c1c:	48 89 f2             	mov    %rsi,%rdx
    1c1f:	48 8d 4e 04          	lea    0x4(%rsi),%rcx
    1c23:	48 8d 46 14          	lea    0x14(%rsi),%rax
    1c27:	50                   	push   %rax
    1c28:	48 8d 46 10          	lea    0x10(%rsi),%rax
    1c2c:	50                   	push   %rax
    1c2d:	4c 8d 4e 0c          	lea    0xc(%rsi),%r9
    1c31:	4c 8d 46 08          	lea    0x8(%rsi),%r8
    1c35:	48 8d 35 cf 16 00 00 	lea    0x16cf(%rip),%rsi        # 330b <array.0+0x16b>
    1c3c:	b8 00 00 00 00       	mov    $0x0,%eax
    1c41:	e8 ba f6 ff ff       	call   1300 <__isoc99_sscanf@plt>
    1c46:	48 83 c4 10          	add    $0x10,%rsp
    1c4a:	83 f8 05             	cmp    $0x5,%eax
    1c4d:	7e 05                	jle    1c54 <read_six_numbers+0x40>
    1c4f:	48 83 c4 08          	add    $0x8,%rsp
    1c53:	c3                   	ret    
    1c54:	e8 8f ff ff ff       	call   1be8 <explode_bomb>

0000000000001c59 <read_line>:
    1c59:	f3 0f 1e fa          	endbr64 
    1c5d:	55                   	push   %rbp
    1c5e:	53                   	push   %rbx
    1c5f:	48 83 ec 08          	sub    $0x8,%rsp
    1c63:	b8 00 00 00 00       	mov    $0x0,%eax
    1c68:	e8 29 ff ff ff       	call   1b96 <skip>
    1c6d:	48 85 c0             	test   %rax,%rax
    1c70:	74 5d                	je     1ccf <read_line+0x76>
    1c72:	8b 2d 78 3a 00 00    	mov    0x3a78(%rip),%ebp        # 56f0 <num_input_strings>
    1c78:	48 63 c5             	movslq %ebp,%rax
    1c7b:	48 8d 1c 80          	lea    (%rax,%rax,4),%rbx
    1c7f:	48 c1 e3 04          	shl    $0x4,%rbx
    1c83:	48 8d 05 76 3a 00 00 	lea    0x3a76(%rip),%rax        # 5700 <input_strings>
    1c8a:	48 01 c3             	add    %rax,%rbx
    1c8d:	48 89 df             	mov    %rbx,%rdi
    1c90:	e8 ab f5 ff ff       	call   1240 <strlen@plt>
    1c95:	83 f8 4e             	cmp    $0x4e,%eax
    1c98:	0f 8f a9 00 00 00    	jg     1d47 <read_line+0xee>
    1c9e:	83 e8 01             	sub    $0x1,%eax
    1ca1:	48 98                	cltq   
    1ca3:	48 63 d5             	movslq %ebp,%rdx
    1ca6:	48 8d 0c 92          	lea    (%rdx,%rdx,4),%rcx
    1caa:	48 c1 e1 04          	shl    $0x4,%rcx
    1cae:	48 8d 15 4b 3a 00 00 	lea    0x3a4b(%rip),%rdx        # 5700 <input_strings>
    1cb5:	48 01 ca             	add    %rcx,%rdx
    1cb8:	c6 04 02 00          	movb   $0x0,(%rdx,%rax,1)
    1cbc:	83 c5 01             	add    $0x1,%ebp
    1cbf:	89 2d 2b 3a 00 00    	mov    %ebp,0x3a2b(%rip)        # 56f0 <num_input_strings>
    1cc5:	48 89 d8             	mov    %rbx,%rax
    1cc8:	48 83 c4 08          	add    $0x8,%rsp
    1ccc:	5b                   	pop    %rbx
    1ccd:	5d                   	pop    %rbp
    1cce:	c3                   	ret    
    1ccf:	48 8b 05 9a 39 00 00 	mov    0x399a(%rip),%rax        # 5670 <stdin@GLIBC_2.2.5>
    1cd6:	48 39 05 b3 39 00 00 	cmp    %rax,0x39b3(%rip)        # 5690 <infile>
    1cdd:	74 1b                	je     1cfa <read_line+0xa1>
    1cdf:	48 8d 3d 55 16 00 00 	lea    0x1655(%rip),%rdi        # 333b <array.0+0x19b>
    1ce6:	e8 05 f5 ff ff       	call   11f0 <getenv@plt>
    1ceb:	48 85 c0             	test   %rax,%rax
    1cee:	74 20                	je     1d10 <read_line+0xb7>
    1cf0:	bf 00 00 00 00       	mov    $0x0,%edi
    1cf5:	e8 36 f6 ff ff       	call   1330 <exit@plt>
    1cfa:	48 8d 3d 1c 16 00 00 	lea    0x161c(%rip),%rdi        # 331d <array.0+0x17d>
    1d01:	e8 1a f5 ff ff       	call   1220 <puts@plt>
    1d06:	bf 08 00 00 00       	mov    $0x8,%edi
    1d0b:	e8 20 f6 ff ff       	call   1330 <exit@plt>
    1d10:	48 8b 05 59 39 00 00 	mov    0x3959(%rip),%rax        # 5670 <stdin@GLIBC_2.2.5>
    1d17:	48 89 05 72 39 00 00 	mov    %rax,0x3972(%rip)        # 5690 <infile>
    1d1e:	b8 00 00 00 00       	mov    $0x0,%eax
    1d23:	e8 6e fe ff ff       	call   1b96 <skip>
    1d28:	48 85 c0             	test   %rax,%rax
    1d2b:	0f 85 41 ff ff ff    	jne    1c72 <read_line+0x19>
    1d31:	48 8d 3d e5 15 00 00 	lea    0x15e5(%rip),%rdi        # 331d <array.0+0x17d>
    1d38:	e8 e3 f4 ff ff       	call   1220 <puts@plt>
    1d3d:	bf 00 00 00 00       	mov    $0x0,%edi
    1d42:	e8 e9 f5 ff ff       	call   1330 <exit@plt>
    1d47:	48 8d 3d f8 15 00 00 	lea    0x15f8(%rip),%rdi        # 3346 <array.0+0x1a6>
    1d4e:	e8 cd f4 ff ff       	call   1220 <puts@plt>
    1d53:	8b 05 97 39 00 00    	mov    0x3997(%rip),%eax        # 56f0 <num_input_strings>
    1d59:	8d 50 01             	lea    0x1(%rax),%edx
    1d5c:	89 15 8e 39 00 00    	mov    %edx,0x398e(%rip)        # 56f0 <num_input_strings>
    1d62:	48 98                	cltq   
    1d64:	48 6b c0 50          	imul   $0x50,%rax,%rax
    1d68:	48 8d 15 91 39 00 00 	lea    0x3991(%rip),%rdx        # 5700 <input_strings>
    1d6f:	48 be 2a 2a 2a 74 72 	movabs $0x636e7572742a2a2a,%rsi
    1d76:	75 6e 63 
    1d79:	48 bf 61 74 65 64 2a 	movabs $0x2a2a2a64657461,%rdi
    1d80:	2a 2a 00 
    1d83:	48 89 34 02          	mov    %rsi,(%rdx,%rax,1)
    1d87:	48 89 7c 02 08       	mov    %rdi,0x8(%rdx,%rax,1)
    1d8c:	e8 57 fe ff ff       	call   1be8 <explode_bomb>

0000000000001d91 <phase_defused>:
    1d91:	f3 0f 1e fa          	endbr64 
    1d95:	48 83 ec 78          	sub    $0x78,%rsp
    1d99:	64 48 8b 04 25 28 00 	mov    %fs:0x28,%rax
    1da0:	00 00 
    1da2:	48 89 44 24 68       	mov    %rax,0x68(%rsp)
    1da7:	31 c0                	xor    %eax,%eax
    1da9:	83 3d 40 39 00 00 06 	cmpl   $0x6,0x3940(%rip)        # 56f0 <num_input_strings>
    1db0:	74 15                	je     1dc7 <phase_defused+0x36>
    1db2:	48 8b 44 24 68       	mov    0x68(%rsp),%rax
    1db7:	64 48 2b 04 25 28 00 	sub    %fs:0x28,%rax
    1dbe:	00 00 
    1dc0:	75 73                	jne    1e35 <phase_defused+0xa4>
    1dc2:	48 83 c4 78          	add    $0x78,%rsp
    1dc6:	c3                   	ret    
    1dc7:	48 8d 4c 24 0c       	lea    0xc(%rsp),%rcx
    1dcc:	48 8d 54 24 08       	lea    0x8(%rsp),%rdx
    1dd1:	4c 8d 44 24 10       	lea    0x10(%rsp),%r8
    1dd6:	48 8d 35 84 15 00 00 	lea    0x1584(%rip),%rsi        # 3361 <array.0+0x1c1>
    1ddd:	48 8d 3d 0c 3a 00 00 	lea    0x3a0c(%rip),%rdi        # 57f0 <input_strings+0xf0>
    1de4:	e8 17 f5 ff ff       	call   1300 <__isoc99_sscanf@plt>
    1de9:	83 f8 03             	cmp    $0x3,%eax
    1dec:	74 0e                	je     1dfc <phase_defused+0x6b>
    1dee:	48 8d 3d ab 14 00 00 	lea    0x14ab(%rip),%rdi        # 32a0 <array.0+0x100>
    1df5:	e8 26 f4 ff ff       	call   1220 <puts@plt>
    1dfa:	eb b6                	jmp    1db2 <phase_defused+0x21>
    1dfc:	48 8d 7c 24 10       	lea    0x10(%rsp),%rdi
    1e01:	48 8d 35 62 15 00 00 	lea    0x1562(%rip),%rsi        # 336a <array.0+0x1ca>
    1e08:	e8 c7 fc ff ff       	call   1ad4 <strings_not_equal>
    1e0d:	85 c0                	test   %eax,%eax
    1e0f:	75 dd                	jne    1dee <phase_defused+0x5d>
    1e11:	48 8d 3d 28 14 00 00 	lea    0x1428(%rip),%rdi        # 3240 <array.0+0xa0>
    1e18:	e8 03 f4 ff ff       	call   1220 <puts@plt>
    1e1d:	48 8d 3d 44 14 00 00 	lea    0x1444(%rip),%rdi        # 3268 <array.0+0xc8>
    1e24:	e8 f7 f3 ff ff       	call   1220 <puts@plt>
    1e29:	b8 00 00 00 00       	mov    $0x0,%eax
    1e2e:	e8 95 fb ff ff       	call   19c8 <secret_phase>
    1e33:	eb b9                	jmp    1dee <phase_defused+0x5d>
    1e35:	e8 16 f4 ff ff       	call   1250 <__stack_chk_fail@plt>

0000000000001e3a <sigalrm_handler>:
    1e3a:	f3 0f 1e fa          	endbr64 
    1e3e:	50                   	push   %rax
    1e3f:	58                   	pop    %rax
    1e40:	48 83 ec 08          	sub    $0x8,%rsp
    1e44:	b9 00 00 00 00       	mov    $0x0,%ecx
    1e49:	48 8d 15 88 15 00 00 	lea    0x1588(%rip),%rdx        # 33d8 <array.0+0x238>
    1e50:	be 01 00 00 00       	mov    $0x1,%esi
    1e55:	48 8b 3d 24 38 00 00 	mov    0x3824(%rip),%rdi        # 5680 <stderr@GLIBC_2.2.5>
    1e5c:	b8 00 00 00 00       	mov    $0x0,%eax
    1e61:	e8 ea f4 ff ff       	call   1350 <__fprintf_chk@plt>
    1e66:	bf 01 00 00 00       	mov    $0x1,%edi
    1e6b:	e8 c0 f4 ff ff       	call   1330 <exit@plt>

0000000000001e70 <rio_readlineb>:
    1e70:	41 56                	push   %r14
    1e72:	41 55                	push   %r13
    1e74:	41 54                	push   %r12
    1e76:	55                   	push   %rbp
    1e77:	53                   	push   %rbx
    1e78:	49 89 f4             	mov    %rsi,%r12
    1e7b:	48 83 fa 01          	cmp    $0x1,%rdx
    1e7f:	0f 86 92 00 00 00    	jbe    1f17 <rio_readlineb+0xa7>
    1e85:	48 89 fb             	mov    %rdi,%rbx
    1e88:	4c 8d 74 16 ff       	lea    -0x1(%rsi,%rdx,1),%r14
    1e8d:	41 bd 01 00 00 00    	mov    $0x1,%r13d
    1e93:	48 8d 6f 10          	lea    0x10(%rdi),%rbp
    1e97:	eb 56                	jmp    1eef <rio_readlineb+0x7f>
    1e99:	e8 62 f3 ff ff       	call   1200 <__errno_location@plt>
    1e9e:	83 38 04             	cmpl   $0x4,(%rax)
    1ea1:	75 55                	jne    1ef8 <rio_readlineb+0x88>
    1ea3:	ba 00 20 00 00       	mov    $0x2000,%edx
    1ea8:	48 89 ee             	mov    %rbp,%rsi
    1eab:	8b 3b                	mov    (%rbx),%edi
    1ead:	e8 ce f3 ff ff       	call   1280 <read@plt>
    1eb2:	89 c2                	mov    %eax,%edx
    1eb4:	89 43 04             	mov    %eax,0x4(%rbx)
    1eb7:	85 c0                	test   %eax,%eax
    1eb9:	78 de                	js     1e99 <rio_readlineb+0x29>
    1ebb:	85 c0                	test   %eax,%eax
    1ebd:	74 42                	je     1f01 <rio_readlineb+0x91>
    1ebf:	48 89 6b 08          	mov    %rbp,0x8(%rbx)
    1ec3:	48 8b 43 08          	mov    0x8(%rbx),%rax
    1ec7:	0f b6 08             	movzbl (%rax),%ecx
    1eca:	48 83 c0 01          	add    $0x1,%rax
    1ece:	48 89 43 08          	mov    %rax,0x8(%rbx)
    1ed2:	83 ea 01             	sub    $0x1,%edx
    1ed5:	89 53 04             	mov    %edx,0x4(%rbx)
    1ed8:	49 83 c4 01          	add    $0x1,%r12
    1edc:	41 88 4c 24 ff       	mov    %cl,-0x1(%r12)
    1ee1:	80 f9 0a             	cmp    $0xa,%cl
    1ee4:	74 3c                	je     1f22 <rio_readlineb+0xb2>
    1ee6:	41 83 c5 01          	add    $0x1,%r13d
    1eea:	4d 39 f4             	cmp    %r14,%r12
    1eed:	74 30                	je     1f1f <rio_readlineb+0xaf>
    1eef:	8b 53 04             	mov    0x4(%rbx),%edx
    1ef2:	85 d2                	test   %edx,%edx
    1ef4:	7e ad                	jle    1ea3 <rio_readlineb+0x33>
    1ef6:	eb cb                	jmp    1ec3 <rio_readlineb+0x53>
    1ef8:	48 c7 c0 ff ff ff ff 	mov    $0xffffffffffffffff,%rax
    1eff:	eb 05                	jmp    1f06 <rio_readlineb+0x96>
    1f01:	b8 00 00 00 00       	mov    $0x0,%eax
    1f06:	85 c0                	test   %eax,%eax
    1f08:	75 29                	jne    1f33 <rio_readlineb+0xc3>
    1f0a:	b8 00 00 00 00       	mov    $0x0,%eax
    1f0f:	41 83 fd 01          	cmp    $0x1,%r13d
    1f13:	75 0d                	jne    1f22 <rio_readlineb+0xb2>
    1f15:	eb 13                	jmp    1f2a <rio_readlineb+0xba>
    1f17:	41 bd 01 00 00 00    	mov    $0x1,%r13d
    1f1d:	eb 03                	jmp    1f22 <rio_readlineb+0xb2>
    1f1f:	4d 89 f4             	mov    %r14,%r12
    1f22:	41 c6 04 24 00       	movb   $0x0,(%r12)
    1f27:	49 63 c5             	movslq %r13d,%rax
    1f2a:	5b                   	pop    %rbx
    1f2b:	5d                   	pop    %rbp
    1f2c:	41 5c                	pop    %r12
    1f2e:	41 5d                	pop    %r13
    1f30:	41 5e                	pop    %r14
    1f32:	c3                   	ret    
    1f33:	48 c7 c0 ff ff ff ff 	mov    $0xffffffffffffffff,%rax
    1f3a:	eb ee                	jmp    1f2a <rio_readlineb+0xba>

0000000000001f3c <submitr>:
    1f3c:	f3 0f 1e fa          	endbr64 
    1f40:	41 57                	push   %r15
    1f42:	41 56                	push   %r14
    1f44:	41 55                	push   %r13
    1f46:	41 54                	push   %r12
    1f48:	55                   	push   %rbp
    1f49:	53                   	push   %rbx
    1f4a:	4c 8d 9c 24 00 60 ff 	lea    -0xa000(%rsp),%r11
    1f51:	ff 
    1f52:	48 81 ec 00 10 00 00 	sub    $0x1000,%rsp
    1f59:	48 83 0c 24 00       	orq    $0x0,(%rsp)
    1f5e:	4c 39 dc             	cmp    %r11,%rsp
    1f61:	75 ef                	jne    1f52 <submitr+0x16>
    1f63:	48 83 ec 78          	sub    $0x78,%rsp
    1f67:	49 89 fd             	mov    %rdi,%r13
    1f6a:	89 f5                	mov    %esi,%ebp
    1f6c:	48 89 54 24 08       	mov    %rdx,0x8(%rsp)
    1f71:	48 89 4c 24 10       	mov    %rcx,0x10(%rsp)
    1f76:	4c 89 44 24 20       	mov    %r8,0x20(%rsp)
    1f7b:	4c 89 4c 24 18       	mov    %r9,0x18(%rsp)
    1f80:	48 8b 9c 24 b0 a0 00 	mov    0xa0b0(%rsp),%rbx
    1f87:	00 
    1f88:	4c 8b bc 24 b8 a0 00 	mov    0xa0b8(%rsp),%r15
    1f8f:	00 
    1f90:	64 48 8b 04 25 28 00 	mov    %fs:0x28,%rax
    1f97:	00 00 
    1f99:	48 89 84 24 68 a0 00 	mov    %rax,0xa068(%rsp)
    1fa0:	00 
    1fa1:	31 c0                	xor    %eax,%eax
    1fa3:	c7 44 24 3c 00 00 00 	movl   $0x0,0x3c(%rsp)
    1faa:	00 
    1fab:	ba 00 00 00 00       	mov    $0x0,%edx
    1fb0:	be 01 00 00 00       	mov    $0x1,%esi
    1fb5:	bf 02 00 00 00       	mov    $0x2,%edi
    1fba:	e8 d1 f3 ff ff       	call   1390 <socket@plt>
    1fbf:	85 c0                	test   %eax,%eax
    1fc1:	0f 88 12 01 00 00    	js     20d9 <submitr+0x19d>
    1fc7:	41 89 c4             	mov    %eax,%r12d
    1fca:	4c 89 ef             	mov    %r13,%rdi
    1fcd:	e8 ee f2 ff ff       	call   12c0 <gethostbyname@plt>
    1fd2:	48 85 c0             	test   %rax,%rax
    1fd5:	0f 84 4e 01 00 00    	je     2129 <submitr+0x1ed>
    1fdb:	4c 8d 6c 24 40       	lea    0x40(%rsp),%r13
    1fe0:	48 c7 44 24 40 00 00 	movq   $0x0,0x40(%rsp)
    1fe7:	00 00 
    1fe9:	48 c7 44 24 48 00 00 	movq   $0x0,0x48(%rsp)
    1ff0:	00 00 
    1ff2:	66 c7 44 24 40 02 00 	movw   $0x2,0x40(%rsp)
    1ff9:	48 63 50 14          	movslq 0x14(%rax),%rdx
    1ffd:	48 8b 40 18          	mov    0x18(%rax),%rax
    2001:	48 8d 7c 24 44       	lea    0x44(%rsp),%rdi
    2006:	b9 0c 00 00 00       	mov    $0xc,%ecx
    200b:	48 8b 30             	mov    (%rax),%rsi
    200e:	e8 bd f2 ff ff       	call   12d0 <__memmove_chk@plt>
    2013:	66 c1 c5 08          	rol    $0x8,%bp
    2017:	66 89 6c 24 42       	mov    %bp,0x42(%rsp)
    201c:	ba 10 00 00 00       	mov    $0x10,%edx
    2021:	4c 89 ee             	mov    %r13,%rsi
    2024:	44 89 e7             	mov    %r12d,%edi
    2027:	e8 14 f3 ff ff       	call   1340 <connect@plt>
    202c:	85 c0                	test   %eax,%eax
    202e:	0f 88 60 01 00 00    	js     2194 <submitr+0x258>
    2034:	48 89 df             	mov    %rbx,%rdi
    2037:	e8 04 f2 ff ff       	call   1240 <strlen@plt>
    203c:	48 89 c5             	mov    %rax,%rbp
    203f:	48 8b 7c 24 08       	mov    0x8(%rsp),%rdi
    2044:	e8 f7 f1 ff ff       	call   1240 <strlen@plt>
    2049:	49 89 c6             	mov    %rax,%r14
    204c:	48 8b 7c 24 10       	mov    0x10(%rsp),%rdi
    2051:	e8 ea f1 ff ff       	call   1240 <strlen@plt>
    2056:	49 89 c5             	mov    %rax,%r13
    2059:	48 8b 7c 24 18       	mov    0x18(%rsp),%rdi
    205e:	e8 dd f1 ff ff       	call   1240 <strlen@plt>
    2063:	48 89 c2             	mov    %rax,%rdx
    2066:	4b 8d 84 2e 80 00 00 	lea    0x80(%r14,%r13,1),%rax
    206d:	00 
    206e:	48 01 d0             	add    %rdx,%rax
    2071:	48 8d 54 6d 00       	lea    0x0(%rbp,%rbp,2),%rdx
    2076:	48 01 d0             	add    %rdx,%rax
    2079:	48 3d 00 20 00 00    	cmp    $0x2000,%rax
    207f:	0f 87 6c 01 00 00    	ja     21f1 <submitr+0x2b5>
    2085:	48 8d 94 24 60 40 00 	lea    0x4060(%rsp),%rdx
    208c:	00 
    208d:	b9 00 04 00 00       	mov    $0x400,%ecx
    2092:	b8 00 00 00 00       	mov    $0x0,%eax
    2097:	48 89 d7             	mov    %rdx,%rdi
    209a:	f3 48 ab             	rep stos %rax,%es:(%rdi)
    209d:	48 89 df             	mov    %rbx,%rdi
    20a0:	e8 9b f1 ff ff       	call   1240 <strlen@plt>
    20a5:	85 c0                	test   %eax,%eax
    20a7:	0f 84 07 05 00 00    	je     25b4 <submitr+0x678>
    20ad:	8d 40 ff             	lea    -0x1(%rax),%eax
    20b0:	4c 8d 6c 03 01       	lea    0x1(%rbx,%rax,1),%r13
    20b5:	48 8d ac 24 60 40 00 	lea    0x4060(%rsp),%rbp
    20bc:	00 
    20bd:	48 8d 84 24 60 80 00 	lea    0x8060(%rsp),%rax
    20c4:	00 
    20c5:	48 89 44 24 28       	mov    %rax,0x28(%rsp)
    20ca:	49 be d9 ff 00 00 00 	movabs $0x2000000000ffd9,%r14
    20d1:	00 20 00 
    20d4:	e9 a6 01 00 00       	jmp    227f <submitr+0x343>
    20d9:	48 b8 45 72 72 6f 72 	movabs $0x43203a726f727245,%rax
    20e0:	3a 20 43 
    20e3:	48 ba 6c 69 65 6e 74 	movabs $0x6e7520746e65696c,%rdx
    20ea:	20 75 6e 
    20ed:	49 89 07             	mov    %rax,(%r15)
    20f0:	49 89 57 08          	mov    %rdx,0x8(%r15)
    20f4:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    20fb:	74 6f 20 
    20fe:	48 ba 63 72 65 61 74 	movabs $0x7320657461657263,%rdx
    2105:	65 20 73 
    2108:	49 89 47 10          	mov    %rax,0x10(%r15)
    210c:	49 89 57 18          	mov    %rdx,0x18(%r15)
    2110:	41 c7 47 20 6f 63 6b 	movl   $0x656b636f,0x20(%r15)
    2117:	65 
    2118:	66 41 c7 47 24 74 00 	movw   $0x74,0x24(%r15)
    211f:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    2124:	e9 03 03 00 00       	jmp    242c <submitr+0x4f0>
    2129:	48 b8 45 72 72 6f 72 	movabs $0x44203a726f727245,%rax
    2130:	3a 20 44 
    2133:	48 ba 4e 53 20 69 73 	movabs $0x6e7520736920534e,%rdx
    213a:	20 75 6e 
    213d:	49 89 07             	mov    %rax,(%r15)
    2140:	49 89 57 08          	mov    %rdx,0x8(%r15)
    2144:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    214b:	74 6f 20 
    214e:	48 ba 72 65 73 6f 6c 	movabs $0x2065766c6f736572,%rdx
    2155:	76 65 20 
    2158:	49 89 47 10          	mov    %rax,0x10(%r15)
    215c:	49 89 57 18          	mov    %rdx,0x18(%r15)
    2160:	48 b8 73 65 72 76 65 	movabs $0x6120726576726573,%rax
    2167:	72 20 61 
    216a:	49 89 47 20          	mov    %rax,0x20(%r15)
    216e:	41 c7 47 28 64 64 72 	movl   $0x65726464,0x28(%r15)
    2175:	65 
    2176:	66 41 c7 47 2c 73 73 	movw   $0x7373,0x2c(%r15)
    217d:	41 c6 47 2e 00       	movb   $0x0,0x2e(%r15)
    2182:	44 89 e7             	mov    %r12d,%edi
    2185:	e8 e6 f0 ff ff       	call   1270 <close@plt>
    218a:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    218f:	e9 98 02 00 00       	jmp    242c <submitr+0x4f0>
    2194:	48 b8 45 72 72 6f 72 	movabs $0x55203a726f727245,%rax
    219b:	3a 20 55 
    219e:	48 ba 6e 61 62 6c 65 	movabs $0x6f7420656c62616e,%rdx
    21a5:	20 74 6f 
    21a8:	49 89 07             	mov    %rax,(%r15)
    21ab:	49 89 57 08          	mov    %rdx,0x8(%r15)
    21af:	48 b8 20 63 6f 6e 6e 	movabs $0x7463656e6e6f6320,%rax
    21b6:	65 63 74 
    21b9:	48 ba 20 74 6f 20 74 	movabs $0x20656874206f7420,%rdx
    21c0:	68 65 20 
    21c3:	49 89 47 10          	mov    %rax,0x10(%r15)
    21c7:	49 89 57 18          	mov    %rdx,0x18(%r15)
    21cb:	41 c7 47 20 73 65 72 	movl   $0x76726573,0x20(%r15)
    21d2:	76 
    21d3:	66 41 c7 47 24 65 72 	movw   $0x7265,0x24(%r15)
    21da:	41 c6 47 26 00       	movb   $0x0,0x26(%r15)
    21df:	44 89 e7             	mov    %r12d,%edi
    21e2:	e8 89 f0 ff ff       	call   1270 <close@plt>
    21e7:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    21ec:	e9 3b 02 00 00       	jmp    242c <submitr+0x4f0>
    21f1:	48 b8 45 72 72 6f 72 	movabs $0x52203a726f727245,%rax
    21f8:	3a 20 52 
    21fb:	48 ba 65 73 75 6c 74 	movabs $0x747320746c757365,%rdx
    2202:	20 73 74 
    2205:	49 89 07             	mov    %rax,(%r15)
    2208:	49 89 57 08          	mov    %rdx,0x8(%r15)
    220c:	48 b8 72 69 6e 67 20 	movabs $0x6f6f7420676e6972,%rax
    2213:	74 6f 6f 
    2216:	48 ba 20 6c 61 72 67 	movabs $0x202e656772616c20,%rdx
    221d:	65 2e 20 
    2220:	49 89 47 10          	mov    %rax,0x10(%r15)
    2224:	49 89 57 18          	mov    %rdx,0x18(%r15)
    2228:	48 b8 49 6e 63 72 65 	movabs $0x6573616572636e49,%rax
    222f:	61 73 65 
    2232:	48 ba 20 53 55 42 4d 	movabs $0x5254494d42555320,%rdx
    2239:	49 54 52 
    223c:	49 89 47 20          	mov    %rax,0x20(%r15)
    2240:	49 89 57 28          	mov    %rdx,0x28(%r15)
    2244:	48 b8 5f 4d 41 58 42 	movabs $0x46554258414d5f,%rax
    224b:	55 46 00 
    224e:	49 89 47 30          	mov    %rax,0x30(%r15)
    2252:	44 89 e7             	mov    %r12d,%edi
    2255:	e8 16 f0 ff ff       	call   1270 <close@plt>
    225a:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    225f:	e9 c8 01 00 00       	jmp    242c <submitr+0x4f0>
    2264:	49 0f a3 c6          	bt     %rax,%r14
    2268:	73 21                	jae    228b <submitr+0x34f>
    226a:	44 88 45 00          	mov    %r8b,0x0(%rbp)
    226e:	48 8d 6d 01          	lea    0x1(%rbp),%rbp
    2272:	48 83 c3 01          	add    $0x1,%rbx
    2276:	4c 39 eb             	cmp    %r13,%rbx
    2279:	0f 84 35 03 00 00    	je     25b4 <submitr+0x678>
    227f:	44 0f b6 03          	movzbl (%rbx),%r8d
    2283:	41 8d 40 d6          	lea    -0x2a(%r8),%eax
    2287:	3c 35                	cmp    $0x35,%al
    2289:	76 d9                	jbe    2264 <submitr+0x328>
    228b:	44 89 c0             	mov    %r8d,%eax
    228e:	83 e0 df             	and    $0xffffffdf,%eax
    2291:	83 e8 41             	sub    $0x41,%eax
    2294:	3c 19                	cmp    $0x19,%al
    2296:	76 d2                	jbe    226a <submitr+0x32e>
    2298:	41 80 f8 20          	cmp    $0x20,%r8b
    229c:	74 60                	je     22fe <submitr+0x3c2>
    229e:	41 8d 40 e0          	lea    -0x20(%r8),%eax
    22a2:	3c 5f                	cmp    $0x5f,%al
    22a4:	76 0a                	jbe    22b0 <submitr+0x374>
    22a6:	41 80 f8 09          	cmp    $0x9,%r8b
    22aa:	0f 85 77 02 00 00    	jne    2527 <submitr+0x5eb>
    22b0:	45 0f b6 c0          	movzbl %r8b,%r8d
    22b4:	48 8d 0d f3 11 00 00 	lea    0x11f3(%rip),%rcx        # 34ae <array.0+0x30e>
    22bb:	ba 08 00 00 00       	mov    $0x8,%edx
    22c0:	be 01 00 00 00       	mov    $0x1,%esi
    22c5:	48 8b 7c 24 28       	mov    0x28(%rsp),%rdi
    22ca:	b8 00 00 00 00       	mov    $0x0,%eax
    22cf:	e8 ac f0 ff ff       	call   1380 <__sprintf_chk@plt>
    22d4:	0f b6 84 24 60 80 00 	movzbl 0x8060(%rsp),%eax
    22db:	00 
    22dc:	88 45 00             	mov    %al,0x0(%rbp)
    22df:	0f b6 84 24 61 80 00 	movzbl 0x8061(%rsp),%eax
    22e6:	00 
    22e7:	88 45 01             	mov    %al,0x1(%rbp)
    22ea:	0f b6 84 24 62 80 00 	movzbl 0x8062(%rsp),%eax
    22f1:	00 
    22f2:	88 45 02             	mov    %al,0x2(%rbp)
    22f5:	48 8d 6d 03          	lea    0x3(%rbp),%rbp
    22f9:	e9 74 ff ff ff       	jmp    2272 <submitr+0x336>
    22fe:	c6 45 00 2b          	movb   $0x2b,0x0(%rbp)
    2302:	48 8d 6d 01          	lea    0x1(%rbp),%rbp
    2306:	e9 67 ff ff ff       	jmp    2272 <submitr+0x336>
    230b:	48 01 c5             	add    %rax,%rbp
    230e:	48 29 c3             	sub    %rax,%rbx
    2311:	0f 84 08 03 00 00    	je     261f <submitr+0x6e3>
    2317:	48 89 da             	mov    %rbx,%rdx
    231a:	48 89 ee             	mov    %rbp,%rsi
    231d:	44 89 e7             	mov    %r12d,%edi
    2320:	e8 0b ef ff ff       	call   1230 <write@plt>
    2325:	48 85 c0             	test   %rax,%rax
    2328:	7f e1                	jg     230b <submitr+0x3cf>
    232a:	e8 d1 ee ff ff       	call   1200 <__errno_location@plt>
    232f:	83 38 04             	cmpl   $0x4,(%rax)
    2332:	0f 85 90 01 00 00    	jne    24c8 <submitr+0x58c>
    2338:	4c 89 e8             	mov    %r13,%rax
    233b:	eb ce                	jmp    230b <submitr+0x3cf>
    233d:	48 b8 45 72 72 6f 72 	movabs $0x43203a726f727245,%rax
    2344:	3a 20 43 
    2347:	48 ba 6c 69 65 6e 74 	movabs $0x6e7520746e65696c,%rdx
    234e:	20 75 6e 
    2351:	49 89 07             	mov    %rax,(%r15)
    2354:	49 89 57 08          	mov    %rdx,0x8(%r15)
    2358:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    235f:	74 6f 20 
    2362:	48 ba 72 65 61 64 20 	movabs $0x7269662064616572,%rdx
    2369:	66 69 72 
    236c:	49 89 47 10          	mov    %rax,0x10(%r15)
    2370:	49 89 57 18          	mov    %rdx,0x18(%r15)
    2374:	48 b8 73 74 20 68 65 	movabs $0x6564616568207473,%rax
    237b:	61 64 65 
    237e:	48 ba 72 20 66 72 6f 	movabs $0x73206d6f72662072,%rdx
    2385:	6d 20 73 
    2388:	49 89 47 20          	mov    %rax,0x20(%r15)
    238c:	49 89 57 28          	mov    %rdx,0x28(%r15)
    2390:	41 c7 47 30 65 72 76 	movl   $0x65767265,0x30(%r15)
    2397:	65 
    2398:	66 41 c7 47 34 72 00 	movw   $0x72,0x34(%r15)
    239f:	44 89 e7             	mov    %r12d,%edi
    23a2:	e8 c9 ee ff ff       	call   1270 <close@plt>
    23a7:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    23ac:	eb 7e                	jmp    242c <submitr+0x4f0>
    23ae:	4c 8d 8c 24 60 80 00 	lea    0x8060(%rsp),%r9
    23b5:	00 
    23b6:	48 8d 0d 43 10 00 00 	lea    0x1043(%rip),%rcx        # 3400 <array.0+0x260>
    23bd:	48 c7 c2 ff ff ff ff 	mov    $0xffffffffffffffff,%rdx
    23c4:	be 01 00 00 00       	mov    $0x1,%esi
    23c9:	4c 89 ff             	mov    %r15,%rdi
    23cc:	b8 00 00 00 00       	mov    $0x0,%eax
    23d1:	e8 aa ef ff ff       	call   1380 <__sprintf_chk@plt>
    23d6:	44 89 e7             	mov    %r12d,%edi
    23d9:	e8 92 ee ff ff       	call   1270 <close@plt>
    23de:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    23e3:	eb 47                	jmp    242c <submitr+0x4f0>
    23e5:	48 8d b4 24 60 20 00 	lea    0x2060(%rsp),%rsi
    23ec:	00 
    23ed:	48 8d 7c 24 50       	lea    0x50(%rsp),%rdi
    23f2:	ba 00 20 00 00       	mov    $0x2000,%edx
    23f7:	e8 74 fa ff ff       	call   1e70 <rio_readlineb>
    23fc:	48 85 c0             	test   %rax,%rax
    23ff:	7e 54                	jle    2455 <submitr+0x519>
    2401:	48 8d b4 24 60 20 00 	lea    0x2060(%rsp),%rsi
    2408:	00 
    2409:	4c 89 ff             	mov    %r15,%rdi
    240c:	e8 ff ed ff ff       	call   1210 <strcpy@plt>
    2411:	44 89 e7             	mov    %r12d,%edi
    2414:	e8 57 ee ff ff       	call   1270 <close@plt>
    2419:	48 8d 35 a9 10 00 00 	lea    0x10a9(%rip),%rsi        # 34c9 <array.0+0x329>
    2420:	4c 89 ff             	mov    %r15,%rdi
    2423:	e8 78 ee ff ff       	call   12a0 <strcmp@plt>
    2428:	f7 d8                	neg    %eax
    242a:	19 c0                	sbb    %eax,%eax
    242c:	48 8b 94 24 68 a0 00 	mov    0xa068(%rsp),%rdx
    2433:	00 
    2434:	64 48 2b 14 25 28 00 	sub    %fs:0x28,%rdx
    243b:	00 00 
    243d:	0f 85 f8 02 00 00    	jne    273b <submitr+0x7ff>
    2443:	48 81 c4 78 a0 00 00 	add    $0xa078,%rsp
    244a:	5b                   	pop    %rbx
    244b:	5d                   	pop    %rbp
    244c:	41 5c                	pop    %r12
    244e:	41 5d                	pop    %r13
    2450:	41 5e                	pop    %r14
    2452:	41 5f                	pop    %r15
    2454:	c3                   	ret    
    2455:	48 b8 45 72 72 6f 72 	movabs $0x43203a726f727245,%rax
    245c:	3a 20 43 
    245f:	48 ba 6c 69 65 6e 74 	movabs $0x6e7520746e65696c,%rdx
    2466:	20 75 6e 
    2469:	49 89 07             	mov    %rax,(%r15)
    246c:	49 89 57 08          	mov    %rdx,0x8(%r15)
    2470:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    2477:	74 6f 20 
    247a:	48 ba 72 65 61 64 20 	movabs $0x6174732064616572,%rdx
    2481:	73 74 61 
    2484:	49 89 47 10          	mov    %rax,0x10(%r15)
    2488:	49 89 57 18          	mov    %rdx,0x18(%r15)
    248c:	48 b8 74 75 73 20 6d 	movabs $0x7373656d20737574,%rax
    2493:	65 73 73 
    2496:	48 ba 61 67 65 20 66 	movabs $0x6d6f726620656761,%rdx
    249d:	72 6f 6d 
    24a0:	49 89 47 20          	mov    %rax,0x20(%r15)
    24a4:	49 89 57 28          	mov    %rdx,0x28(%r15)
    24a8:	48 b8 20 73 65 72 76 	movabs $0x72657672657320,%rax
    24af:	65 72 00 
    24b2:	49 89 47 30          	mov    %rax,0x30(%r15)
    24b6:	44 89 e7             	mov    %r12d,%edi
    24b9:	e8 b2 ed ff ff       	call   1270 <close@plt>
    24be:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    24c3:	e9 64 ff ff ff       	jmp    242c <submitr+0x4f0>
    24c8:	48 b8 45 72 72 6f 72 	movabs $0x43203a726f727245,%rax
    24cf:	3a 20 43 
    24d2:	48 ba 6c 69 65 6e 74 	movabs $0x6e7520746e65696c,%rdx
    24d9:	20 75 6e 
    24dc:	49 89 07             	mov    %rax,(%r15)
    24df:	49 89 57 08          	mov    %rdx,0x8(%r15)
    24e3:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    24ea:	74 6f 20 
    24ed:	48 ba 77 72 69 74 65 	movabs $0x6f74206574697277,%rdx
    24f4:	20 74 6f 
    24f7:	49 89 47 10          	mov    %rax,0x10(%r15)
    24fb:	49 89 57 18          	mov    %rdx,0x18(%r15)
    24ff:	48 b8 20 74 68 65 20 	movabs $0x7265732065687420,%rax
    2506:	73 65 72 
    2509:	49 89 47 20          	mov    %rax,0x20(%r15)
    250d:	41 c7 47 28 76 65 72 	movl   $0x726576,0x28(%r15)
    2514:	00 
    2515:	44 89 e7             	mov    %r12d,%edi
    2518:	e8 53 ed ff ff       	call   1270 <close@plt>
    251d:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    2522:	e9 05 ff ff ff       	jmp    242c <submitr+0x4f0>
    2527:	48 b8 45 72 72 6f 72 	movabs $0x52203a726f727245,%rax
    252e:	3a 20 52 
    2531:	48 ba 65 73 75 6c 74 	movabs $0x747320746c757365,%rdx
    2538:	20 73 74 
    253b:	49 89 07             	mov    %rax,(%r15)
    253e:	49 89 57 08          	mov    %rdx,0x8(%r15)
    2542:	48 b8 72 69 6e 67 20 	movabs $0x6e6f6320676e6972,%rax
    2549:	63 6f 6e 
    254c:	48 ba 74 61 69 6e 73 	movabs $0x6e6120736e696174,%rdx
    2553:	20 61 6e 
    2556:	49 89 47 10          	mov    %rax,0x10(%r15)
    255a:	49 89 57 18          	mov    %rdx,0x18(%r15)
    255e:	48 b8 20 69 6c 6c 65 	movabs $0x6c6167656c6c6920,%rax
    2565:	67 61 6c 
    2568:	48 ba 20 6f 72 20 75 	movabs $0x72706e7520726f20,%rdx
    256f:	6e 70 72 
    2572:	49 89 47 20          	mov    %rax,0x20(%r15)
    2576:	49 89 57 28          	mov    %rdx,0x28(%r15)
    257a:	48 b8 69 6e 74 61 62 	movabs $0x20656c6261746e69,%rax
    2581:	6c 65 20 
    2584:	48 ba 63 68 61 72 61 	movabs $0x6574636172616863,%rdx
    258b:	63 74 65 
    258e:	49 89 47 30          	mov    %rax,0x30(%r15)
    2592:	49 89 57 38          	mov    %rdx,0x38(%r15)
    2596:	66 41 c7 47 40 72 2e 	movw   $0x2e72,0x40(%r15)
    259d:	41 c6 47 42 00       	movb   $0x0,0x42(%r15)
    25a2:	44 89 e7             	mov    %r12d,%edi
    25a5:	e8 c6 ec ff ff       	call   1270 <close@plt>
    25aa:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    25af:	e9 78 fe ff ff       	jmp    242c <submitr+0x4f0>
    25b4:	48 8d 9c 24 60 20 00 	lea    0x2060(%rsp),%rbx
    25bb:	00 
    25bc:	48 83 ec 08          	sub    $0x8,%rsp
    25c0:	48 8d 84 24 68 40 00 	lea    0x4068(%rsp),%rax
    25c7:	00 
    25c8:	50                   	push   %rax
    25c9:	ff 74 24 28          	push   0x28(%rsp)
    25cd:	ff 74 24 38          	push   0x38(%rsp)
    25d1:	4c 8b 4c 24 30       	mov    0x30(%rsp),%r9
    25d6:	4c 8b 44 24 28       	mov    0x28(%rsp),%r8
    25db:	48 8d 0d 4e 0e 00 00 	lea    0xe4e(%rip),%rcx        # 3430 <array.0+0x290>
    25e2:	ba 00 20 00 00       	mov    $0x2000,%edx
    25e7:	be 01 00 00 00       	mov    $0x1,%esi
    25ec:	48 89 df             	mov    %rbx,%rdi
    25ef:	b8 00 00 00 00       	mov    $0x0,%eax
    25f4:	e8 87 ed ff ff       	call   1380 <__sprintf_chk@plt>
    25f9:	48 83 c4 20          	add    $0x20,%rsp
    25fd:	48 89 df             	mov    %rbx,%rdi
    2600:	e8 3b ec ff ff       	call   1240 <strlen@plt>
    2605:	48 89 c3             	mov    %rax,%rbx
    2608:	48 8d ac 24 60 20 00 	lea    0x2060(%rsp),%rbp
    260f:	00 
    2610:	41 bd 00 00 00 00    	mov    $0x0,%r13d
    2616:	48 85 c0             	test   %rax,%rax
    2619:	0f 85 f8 fc ff ff    	jne    2317 <submitr+0x3db>
    261f:	44 89 64 24 50       	mov    %r12d,0x50(%rsp)
    2624:	c7 44 24 54 00 00 00 	movl   $0x0,0x54(%rsp)
    262b:	00 
    262c:	48 8d 7c 24 50       	lea    0x50(%rsp),%rdi
    2631:	48 8d 44 24 60       	lea    0x60(%rsp),%rax
    2636:	48 89 44 24 58       	mov    %rax,0x58(%rsp)
    263b:	48 8d b4 24 60 20 00 	lea    0x2060(%rsp),%rsi
    2642:	00 
    2643:	ba 00 20 00 00       	mov    $0x2000,%edx
    2648:	e8 23 f8 ff ff       	call   1e70 <rio_readlineb>
    264d:	48 85 c0             	test   %rax,%rax
    2650:	0f 8e e7 fc ff ff    	jle    233d <submitr+0x401>
    2656:	48 8d 4c 24 3c       	lea    0x3c(%rsp),%rcx
    265b:	48 8d 94 24 60 60 00 	lea    0x6060(%rsp),%rdx
    2662:	00 
    2663:	48 8d bc 24 60 20 00 	lea    0x2060(%rsp),%rdi
    266a:	00 
    266b:	4c 8d 84 24 60 80 00 	lea    0x8060(%rsp),%r8
    2672:	00 
    2673:	48 8d 35 3b 0e 00 00 	lea    0xe3b(%rip),%rsi        # 34b5 <array.0+0x315>
    267a:	b8 00 00 00 00       	mov    $0x0,%eax
    267f:	e8 7c ec ff ff       	call   1300 <__isoc99_sscanf@plt>
    2684:	44 8b 44 24 3c       	mov    0x3c(%rsp),%r8d
    2689:	41 81 f8 c8 00 00 00 	cmp    $0xc8,%r8d
    2690:	0f 85 18 fd ff ff    	jne    23ae <submitr+0x472>
    2696:	48 8d 1d 29 0e 00 00 	lea    0xe29(%rip),%rbx        # 34c6 <array.0+0x326>
    269d:	48 8d bc 24 60 20 00 	lea    0x2060(%rsp),%rdi
    26a4:	00 
    26a5:	48 89 de             	mov    %rbx,%rsi
    26a8:	e8 f3 eb ff ff       	call   12a0 <strcmp@plt>
    26ad:	85 c0                	test   %eax,%eax
    26af:	0f 84 30 fd ff ff    	je     23e5 <submitr+0x4a9>
    26b5:	48 8d b4 24 60 20 00 	lea    0x2060(%rsp),%rsi
    26bc:	00 
    26bd:	48 8d 7c 24 50       	lea    0x50(%rsp),%rdi
    26c2:	ba 00 20 00 00       	mov    $0x2000,%edx
    26c7:	e8 a4 f7 ff ff       	call   1e70 <rio_readlineb>
    26cc:	48 85 c0             	test   %rax,%rax
    26cf:	7f cc                	jg     269d <submitr+0x761>
    26d1:	48 b8 45 72 72 6f 72 	movabs $0x43203a726f727245,%rax
    26d8:	3a 20 43 
    26db:	48 ba 6c 69 65 6e 74 	movabs $0x6e7520746e65696c,%rdx
    26e2:	20 75 6e 
    26e5:	49 89 07             	mov    %rax,(%r15)
    26e8:	49 89 57 08          	mov    %rdx,0x8(%r15)
    26ec:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    26f3:	74 6f 20 
    26f6:	48 ba 72 65 61 64 20 	movabs $0x6165682064616572,%rdx
    26fd:	68 65 61 
    2700:	49 89 47 10          	mov    %rax,0x10(%r15)
    2704:	49 89 57 18          	mov    %rdx,0x18(%r15)
    2708:	48 b8 64 65 72 73 20 	movabs $0x6f72662073726564,%rax
    270f:	66 72 6f 
    2712:	48 ba 6d 20 73 65 72 	movabs $0x726576726573206d,%rdx
    2719:	76 65 72 
    271c:	49 89 47 20          	mov    %rax,0x20(%r15)
    2720:	49 89 57 28          	mov    %rdx,0x28(%r15)
    2724:	41 c6 47 30 00       	movb   $0x0,0x30(%r15)
    2729:	44 89 e7             	mov    %r12d,%edi
    272c:	e8 3f eb ff ff       	call   1270 <close@plt>
    2731:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    2736:	e9 f1 fc ff ff       	jmp    242c <submitr+0x4f0>
    273b:	e8 10 eb ff ff       	call   1250 <__stack_chk_fail@plt>

0000000000002740 <init_timeout>:
    2740:	f3 0f 1e fa          	endbr64 
    2744:	85 ff                	test   %edi,%edi
    2746:	75 01                	jne    2749 <init_timeout+0x9>
    2748:	c3                   	ret    
    2749:	53                   	push   %rbx
    274a:	89 fb                	mov    %edi,%ebx
    274c:	48 8d 35 e7 f6 ff ff 	lea    -0x919(%rip),%rsi        # 1e3a <sigalrm_handler>
    2753:	bf 0e 00 00 00       	mov    $0xe,%edi
    2758:	e8 53 eb ff ff       	call   12b0 <signal@plt>
    275d:	85 db                	test   %ebx,%ebx
    275f:	b8 00 00 00 00       	mov    $0x0,%eax
    2764:	0f 49 c3             	cmovns %ebx,%eax
    2767:	89 c7                	mov    %eax,%edi
    2769:	e8 f2 ea ff ff       	call   1260 <alarm@plt>
    276e:	5b                   	pop    %rbx
    276f:	c3                   	ret    

0000000000002770 <init_driver>:
    2770:	f3 0f 1e fa          	endbr64 
    2774:	41 54                	push   %r12
    2776:	55                   	push   %rbp
    2777:	53                   	push   %rbx
    2778:	48 83 ec 20          	sub    $0x20,%rsp
    277c:	48 89 fd             	mov    %rdi,%rbp
    277f:	64 48 8b 04 25 28 00 	mov    %fs:0x28,%rax
    2786:	00 00 
    2788:	48 89 44 24 18       	mov    %rax,0x18(%rsp)
    278d:	31 c0                	xor    %eax,%eax
    278f:	be 01 00 00 00       	mov    $0x1,%esi
    2794:	bf 0d 00 00 00       	mov    $0xd,%edi
    2799:	e8 12 eb ff ff       	call   12b0 <signal@plt>
    279e:	be 01 00 00 00       	mov    $0x1,%esi
    27a3:	bf 1d 00 00 00       	mov    $0x1d,%edi
    27a8:	e8 03 eb ff ff       	call   12b0 <signal@plt>
    27ad:	be 01 00 00 00       	mov    $0x1,%esi
    27b2:	bf 1d 00 00 00       	mov    $0x1d,%edi
    27b7:	e8 f4 ea ff ff       	call   12b0 <signal@plt>
    27bc:	ba 00 00 00 00       	mov    $0x0,%edx
    27c1:	be 01 00 00 00       	mov    $0x1,%esi
    27c6:	bf 02 00 00 00       	mov    $0x2,%edi
    27cb:	e8 c0 eb ff ff       	call   1390 <socket@plt>
    27d0:	85 c0                	test   %eax,%eax
    27d2:	0f 88 9c 00 00 00    	js     2874 <init_driver+0x104>
    27d8:	89 c3                	mov    %eax,%ebx
    27da:	48 8d 3d eb 0c 00 00 	lea    0xceb(%rip),%rdi        # 34cc <array.0+0x32c>
    27e1:	e8 da ea ff ff       	call   12c0 <gethostbyname@plt>
    27e6:	48 85 c0             	test   %rax,%rax
    27e9:	0f 84 d1 00 00 00    	je     28c0 <init_driver+0x150>
    27ef:	49 89 e4             	mov    %rsp,%r12
    27f2:	48 c7 04 24 00 00 00 	movq   $0x0,(%rsp)
    27f9:	00 
    27fa:	48 c7 44 24 08 00 00 	movq   $0x0,0x8(%rsp)
    2801:	00 00 
    2803:	66 c7 04 24 02 00    	movw   $0x2,(%rsp)
    2809:	48 63 50 14          	movslq 0x14(%rax),%rdx
    280d:	48 8b 40 18          	mov    0x18(%rax),%rax
    2811:	48 8d 7c 24 04       	lea    0x4(%rsp),%rdi
    2816:	b9 0c 00 00 00       	mov    $0xc,%ecx
    281b:	48 8b 30             	mov    (%rax),%rsi
    281e:	e8 ad ea ff ff       	call   12d0 <__memmove_chk@plt>
    2823:	66 c7 44 24 02 3b 6e 	movw   $0x6e3b,0x2(%rsp)
    282a:	ba 10 00 00 00       	mov    $0x10,%edx
    282f:	4c 89 e6             	mov    %r12,%rsi
    2832:	89 df                	mov    %ebx,%edi
    2834:	e8 07 eb ff ff       	call   1340 <connect@plt>
    2839:	85 c0                	test   %eax,%eax
    283b:	0f 88 e7 00 00 00    	js     2928 <init_driver+0x1b8>
    2841:	89 df                	mov    %ebx,%edi
    2843:	e8 28 ea ff ff       	call   1270 <close@plt>
    2848:	66 c7 45 00 4f 4b    	movw   $0x4b4f,0x0(%rbp)
    284e:	c6 45 02 00          	movb   $0x0,0x2(%rbp)
    2852:	b8 00 00 00 00       	mov    $0x0,%eax
    2857:	48 8b 54 24 18       	mov    0x18(%rsp),%rdx
    285c:	64 48 2b 14 25 28 00 	sub    %fs:0x28,%rdx
    2863:	00 00 
    2865:	0f 85 f5 00 00 00    	jne    2960 <init_driver+0x1f0>
    286b:	48 83 c4 20          	add    $0x20,%rsp
    286f:	5b                   	pop    %rbx
    2870:	5d                   	pop    %rbp
    2871:	41 5c                	pop    %r12
    2873:	c3                   	ret    
    2874:	48 b8 45 72 72 6f 72 	movabs $0x43203a726f727245,%rax
    287b:	3a 20 43 
    287e:	48 ba 6c 69 65 6e 74 	movabs $0x6e7520746e65696c,%rdx
    2885:	20 75 6e 
    2888:	48 89 45 00          	mov    %rax,0x0(%rbp)
    288c:	48 89 55 08          	mov    %rdx,0x8(%rbp)
    2890:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    2897:	74 6f 20 
    289a:	48 ba 63 72 65 61 74 	movabs $0x7320657461657263,%rdx
    28a1:	65 20 73 
    28a4:	48 89 45 10          	mov    %rax,0x10(%rbp)
    28a8:	48 89 55 18          	mov    %rdx,0x18(%rbp)
    28ac:	c7 45 20 6f 63 6b 65 	movl   $0x656b636f,0x20(%rbp)
    28b3:	66 c7 45 24 74 00    	movw   $0x74,0x24(%rbp)
    28b9:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    28be:	eb 97                	jmp    2857 <init_driver+0xe7>
    28c0:	48 b8 45 72 72 6f 72 	movabs $0x44203a726f727245,%rax
    28c7:	3a 20 44 
    28ca:	48 ba 4e 53 20 69 73 	movabs $0x6e7520736920534e,%rdx
    28d1:	20 75 6e 
    28d4:	48 89 45 00          	mov    %rax,0x0(%rbp)
    28d8:	48 89 55 08          	mov    %rdx,0x8(%rbp)
    28dc:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    28e3:	74 6f 20 
    28e6:	48 ba 72 65 73 6f 6c 	movabs $0x2065766c6f736572,%rdx
    28ed:	76 65 20 
    28f0:	48 89 45 10          	mov    %rax,0x10(%rbp)
    28f4:	48 89 55 18          	mov    %rdx,0x18(%rbp)
    28f8:	48 b8 73 65 72 76 65 	movabs $0x6120726576726573,%rax
    28ff:	72 20 61 
    2902:	48 89 45 20          	mov    %rax,0x20(%rbp)
    2906:	c7 45 28 64 64 72 65 	movl   $0x65726464,0x28(%rbp)
    290d:	66 c7 45 2c 73 73    	movw   $0x7373,0x2c(%rbp)
    2913:	c6 45 2e 00          	movb   $0x0,0x2e(%rbp)
    2917:	89 df                	mov    %ebx,%edi
    2919:	e8 52 e9 ff ff       	call   1270 <close@plt>
    291e:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    2923:	e9 2f ff ff ff       	jmp    2857 <init_driver+0xe7>
    2928:	4c 8d 05 9d 0b 00 00 	lea    0xb9d(%rip),%r8        # 34cc <array.0+0x32c>
    292f:	48 8d 0d 52 0b 00 00 	lea    0xb52(%rip),%rcx        # 3488 <array.0+0x2e8>
    2936:	48 c7 c2 ff ff ff ff 	mov    $0xffffffffffffffff,%rdx
    293d:	be 01 00 00 00       	mov    $0x1,%esi
    2942:	48 89 ef             	mov    %rbp,%rdi
    2945:	b8 00 00 00 00       	mov    $0x0,%eax
    294a:	e8 31 ea ff ff       	call   1380 <__sprintf_chk@plt>
    294f:	89 df                	mov    %ebx,%edi
    2951:	e8 1a e9 ff ff       	call   1270 <close@plt>
    2956:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    295b:	e9 f7 fe ff ff       	jmp    2857 <init_driver+0xe7>
    2960:	e8 eb e8 ff ff       	call   1250 <__stack_chk_fail@plt>

0000000000002965 <driver_post>:
    2965:	f3 0f 1e fa          	endbr64 
    2969:	53                   	push   %rbx
    296a:	4c 89 c3             	mov    %r8,%rbx
    296d:	85 c9                	test   %ecx,%ecx
    296f:	75 17                	jne    2988 <driver_post+0x23>
    2971:	48 85 ff             	test   %rdi,%rdi
    2974:	74 05                	je     297b <driver_post+0x16>
    2976:	80 3f 00             	cmpb   $0x0,(%rdi)
    2979:	75 33                	jne    29ae <driver_post+0x49>
    297b:	66 c7 03 4f 4b       	movw   $0x4b4f,(%rbx)
    2980:	c6 43 02 00          	movb   $0x0,0x2(%rbx)
    2984:	89 c8                	mov    %ecx,%eax
    2986:	5b                   	pop    %rbx
    2987:	c3                   	ret    
    2988:	48 8d 35 55 0b 00 00 	lea    0xb55(%rip),%rsi        # 34e4 <array.0+0x344>
    298f:	bf 01 00 00 00       	mov    $0x1,%edi
    2994:	b8 00 00 00 00       	mov    $0x0,%eax
    2999:	e8 72 e9 ff ff       	call   1310 <__printf_chk@plt>
    299e:	66 c7 03 4f 4b       	movw   $0x4b4f,(%rbx)
    29a3:	c6 43 02 00          	movb   $0x0,0x2(%rbx)
    29a7:	b8 00 00 00 00       	mov    $0x0,%eax
    29ac:	eb d8                	jmp    2986 <driver_post+0x21>
    29ae:	41 50                	push   %r8
    29b0:	52                   	push   %rdx
    29b1:	4c 8d 0d 10 0b 00 00 	lea    0xb10(%rip),%r9        # 34c8 <array.0+0x328>
    29b8:	49 89 f0             	mov    %rsi,%r8
    29bb:	48 89 f9             	mov    %rdi,%rcx
    29be:	48 8d 15 36 0b 00 00 	lea    0xb36(%rip),%rdx        # 34fb <array.0+0x35b>
    29c5:	be 6e 3b 00 00       	mov    $0x3b6e,%esi
    29ca:	48 8d 3d fb 0a 00 00 	lea    0xafb(%rip),%rdi        # 34cc <array.0+0x32c>
    29d1:	e8 66 f5 ff ff       	call   1f3c <submitr>
    29d6:	48 83 c4 10          	add    $0x10,%rsp
    29da:	eb aa                	jmp    2986 <driver_post+0x21>

Disassembly of section .fini:

00000000000029dc <_fini>:
    29dc:	f3 0f 1e fa          	endbr64 
    29e0:	48 83 ec 08          	sub    $0x8,%rsp
    29e4:	48 83 c4 08          	add    $0x8,%rsp
    29e8:	c3                   	ret    
