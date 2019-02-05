Palindrome

def is_palindrome(word):
    my_str = word.casefold()
    rev_str = reversed(my_str)
    if list(my_str) == list(rev_str):
        return True
    else:
        return False
    
print(is_palindrome('Deleveled'))
