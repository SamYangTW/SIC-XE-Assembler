# SIC-XE-Assembler

*                       SIC/XE Assembler                            
*                        Yang YaoNing                                 


支援 : 

1. 2-PASS Assembler
2. SIC/XE 全指令 support



Assembler程式編譯環境 :
windows/Dev C++ 5.6.3/C



使用方法 : 
將assembler.c 放置於source code同個資料夾中執行，
產生出SIC/XE 的OBJFILE.



注意事項 : 
1. source code 需命名為 source_code.txt。
2. 產生出的executable file的檔名為 OBJFILE.txt 
4. 內部提供幾個debug function，print_Literal Pool(印出Literal Pool)、print_LITTAB(印出LITTAB)、
    print_SYMTAB(印出SYMTAB)、print_OPTAB(印出OPTAB)、print_REGTAB(印出REGTAB)
    
    
    
