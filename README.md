# Calculate-Noah-s-Score

In a recent quiz, there were three problems valued at 1, 2, and 4 points each. Three students - Mia, Liam, and Noah - took the quiz. Mia scored A points, and Liam scored B points. Noah’s approach was unique: He solved every problem that was attempted by either Mia or Liam and didn’t attempt any problem that both Mia and Liam skipped. What was Noah’s score? Under the given conditions, Noah’s score is uniquely determined.

# Input
A, B = map(int, input().split())

# Noah's score is the bitwise OR of A and B
noah_score = A | B

# Output
print(noah_score)
