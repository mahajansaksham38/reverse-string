# reverse-string
program to reverse string using function
def rev_string(str):
    c=reversed(str.split())
    return ' '.join(c)
input=raw_input("Please enter the message: ")
c=rev_string(input)
print "your reversed message is: " + c
