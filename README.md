# sorted-form-alphanumerically-.\
items = input("Input comma separated sequence of words:")
words = [word for word in items.split(",")]
print(",".join(sorted(list(set(words)))))


Input comma separated sequence of words:red,red,red,blue,violet,black
black,blue,red,violet

