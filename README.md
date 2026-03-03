📊 Word Frequency Counter in Python

This Python program counts how many times each word appears in a given sentence.

📌 Features

Takes sentence input from user

Case-insensitive word counting

Uses dictionary for storing frequency

Beginner-friendly

Interview-ready implementation

💻 Technology Used

Python 3

🚀 How It Works

The program takes a sentence as input.

Converts the sentence to lowercase (to avoid case mismatch).

Splits the sentence into words using split().

Uses a dictionary to store word counts.

Prints each word along with its frequency.

📝 Code
sentence = input("Enter a sentence: ")

sentence = sentence.lower()

words = sentence.split()

word_count = {}

for word in words:
    if word in word_count:
        word_count[word] += 1
    else:
        word_count[word] = 1

print("Word Frequency:")
for word, count in word_count.items():
    print(word, ":", count)
▶️ Example

Input:

Python is easy and Python is powerful

Output:

python : 2
is : 2
easy : 1
and : 1
powerful : 1


🎯 Learning Concepts

String manipulation

split() function

Dictionary data structure

Looping and conditional statements

