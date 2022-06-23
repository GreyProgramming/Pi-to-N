# Pi-to-N
Find PI to the Nth Digit

Creation of a new challenge and solution file for QA ltd:

Find PI to the Nth Digit - Enter a number and have the program generate PI up to that many decimal places. Keep a limit to how far the program will go.

23/06/2022

Having spent a few hours yesterday attempting merely to find a way to quickly and accurately calculate pi, I woke up today deciding to document my process:

Using PyCharm, the import function repeatedly failed to import standard packages such as numpy and pandas.

I found several different methods, and ran them against a set value of pi to 1000 places, but none of them maintained accuracy past roughly 20, 25 digits and many required re-calculating thousands of times to maintain that accuracy.

I know this because earlier this year, Emma Haruka Iwao calculated pi to 31,415,926,535,897 places and I took the first 1000 places to measure the outputs of each calculation against.

I have woken up this morning and had the thought of 'Well... If I already have the fixed value of Pi, this becomes a pre-solved issue. The output isn't to *calculate* pi to N number of places, it is to display it to that number of places.

So I downloaded Spyder(Anaconda3) last night and am now solving the problem

---Update 2 hours later:

num = int(input("How many places would you like pi to? (max 1000) "))

Anaconda has an issue with this line so I am now back in PyCharm, which is running my code just fine.
