import re
#No 1
def cekEmail(input):
    cocok = re.findall('[@]+[a-zA-Z]+[0-9]+[_]',input)
    if cocok:
        print('Pass')
    else:
        print('Failed')

#No 2
s = input('Teks Email :')
cocok = re.findall('[a-zA-Z0-9]+[@]+[a-zA-Z0-9]+[.]+[a-zA-Z0-9]+', s)
print(cocok)
