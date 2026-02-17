# -Check-whether-a-string-is-palindrome
def rev(inputString):
    return inputString[::-1]
def isPalindrome(inputString):
    reverseString = rev(inputString)
    if inputString == reverseString:
        return True
    return False
s = input("Enter a string: ")
result = isPalindrome(s)
if result:
    print("The string is palindrome")
else:
    print("The string is not palindrome")

OUTPUT:
Enter a string: madam
The string is palindrome

