# python-open-
文件.read() 





f=open("C:/Users/dell/Desktop/word.txt","r",encoding="UTF-8")#U can not use"\"
print(type(f))
print(f"{f}")

# --------------myway review
#print(f.read(10))
#print(f.read())
# print(f.readline())
# print(f.readlines())
# a=f.read()
# print(a)
# print(type(a))
# a=f.read()
# print(a)
# print(len(a))
# if a== {}:
#     print("true")
# else:print("false")

# #--------------------------way 1
# a=f.readline()
# print(a)
# c=len(a)
# count=0
# while  (c!=0):                 #u cannot use "len(a=f.readline()”there is "a="
#     b=a.split(" ")
#     i=0
#     while (i<len(b)):
#         if ((b[i]=='itheima')or(b[i]=='itheima\n')):
#
#             count+=1
#         i+=1
#     a=f.readline()
#     print(a)
#     c=len(a)
# print(f"count {count}")
# f.close()



# #----------------------way2    count
# a=f.read()
# num=a.count("itheima")
# print(num)


# #-------------way 3
# count=0
# for line in f:    #文本便利是每行，
#     line=line.strip() #if u dont use ,显示会有空行
#     print(line)
#     print(type(line))
#     words=line.split(" ")
#     for word in words:  #列表便利是每个，等价于【i】
#         if word=="itheima":
#             count+=1
# print(count)
# f.close()
