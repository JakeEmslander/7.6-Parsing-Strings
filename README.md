# 7.6-Parsing-Strings

comma = ','
string = input('Enter input string:\n')
while string != 'q':
    if comma in string:
        first_word = string.split(',')[0]
        second_word = string.split(',')[1]
        print('First word:', first_word)
        print('Second word:'+ second_word, '\n')
    else:
        print('Error: No comma in string.')
        print()
    print('Enter input string:')
    string = input()
