# Pig-Latin
# Pig Latin form of an English word the initial consonant sound is transposed to the end of  the word and an ay is affixed

word = raw_input('What\'s your word? ').lower()
vowels = 'aeiou'

pig = 'ay'

first = word[0]

if first in vowels:
    new = word + way
else:
    new = word[1:] + first + pig

print new
