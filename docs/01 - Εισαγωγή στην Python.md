# Python 1o Μάθημα

## Topics

- Τι είναι η Python & τι μπορούμε να κάνουμε με αυτήν;
- Εγκατάσταση της Python & setup Development Environment
- Εμφάνιση μηνυμάτων
- Συντακτικό της γλώσσας
- Πράξεις - Operations
- Σχόλια - Comments
- Μεταβλητές - Variables
- Είσοδος από τον χρήστη - input()

## Καλωσόρισμα

- Είμαι ο Σ και θα κάνουμε Python (Παρουσίαση)
- Δύο λόγια για τον Μ για ποιο λόγο είναι εδώ σε 1 πρόταση(Παρουσίαση μαθητή)
- Για ποιον είναι το μάθημα (Μαθητές, Φοιτητές, Ξεκινάει τώρα τον προγραμματισμό, κάποιον που θέλει να μάθει γρήγορα Python για άλλη χρήση)

> Σημαντικά points! Motivation (κίνητρο), Confident (αυτοπεποίθηση), Εύκολο, Reward (τελικό αποτέλεσμα), rewind

## Γιατί Python;

- Εύκολη
- Διαδεδομένη
- Χρησιμοποιείται και στην αγορά εργασίας και σε ακαδημαικό επίπεδο (έρευνα)
- Γρήγορη στην εκμάθηση

## Print - Εμφάνιση μηνυμάτων

> Σχετικά με την εντολή print. Δεξία είναι ο κώδικας και αριστερά είναι το αποτέλεσμα του κώδικα. Το shell ή αλλιώς το console.

## Syntax

> Οχι tab space

## Operations

> Είναι διαφορετικό το (2+3) με το ("2+3")
> Ότι ειναι μεσα στα " " το τυπώνει αυτολεξή, τυπώνει τους χαρακτήρες.
> Πράξεις μεταξύ int, float , str. Συγκρίσεις

## Comments

> Τα σχόλια είναι σημαντικά. Χρειάζονται για να μπορούμε να ξαναδιαβάσουμε τον κώδικα μας μετά απο καιρό ή να μπορούμε να τον δώσουμε σε άλλον να τον διαβάσει.

## Variables

- Παραδείγματα μεταβλητών με μηνύτα
  > Συνήθως, δίνουμε ονόματα μεταβλητών τα οποία μπορούμε να τα διαβάσουμε και να αναγνωρίσουμε τι παραριστάνει η μεταβλητή αυτή.

### Choosing a good name for a variable

- It is often useful to name variables according to what they are used for. For example, if the variable contains a word, the name `word` is a better choice than, say, `a`.
- There is no set limit to the length of a variable name in Python, but there are some other limitations. A variable name should begin with a letter, and it can only contain letters, numbers and underscores \_.
- Lowercase and uppercase letters are different characters. The variables `name`, `Name` and `NAME` are all different variables. While this rule has a few exceptions, we will ignore those for now.
- It is a common programming practice in Python to use only lowercase characters in variable names. If the variable name consists of multiple words, use an underscore between the words. While this rule also has a few exceptions, we will ignore those for now.

## input()

```py
name = input("What is your name? ")
print("Hi there, " + name)
```

```

```

> Παραδείγματα input με μηνύτα. Πάμε να δουμε πως μπορουμε να πάρουμε στοιχεία απο τον χρήστη
> Το int προσδιορίζει τι είδος δεδομένου θα πάρει η μεταβλητή
> Παράδειγμα με string

## Ασκήσεις

### Άσκηση 1η

Να φτιάξετε ένα πρόγραμμα το οποίο θα δέχεται ως είσοδο το Όνομα,το Επώνυμο, το email και το username κάποιου και θα εμφανίζει το εξής μήνυμα

```py
Το 'username' ανήκει στον/ην 'Όνομα' 'Επώνυμο'
To email του είναι: 'email'
```

### Άσκηση 2η

Διορθώστε το πρόγραμμα κατάλληλα έτσι ώστε να δέχεται την Ημέρα, τον Μήνα και την Χρονιά και να τυπώνεται το μήνυμα **Η ημερομηνία είναι 25-9-2022!**

```py
# Fix the code
variable = input("Δώσε μεταβλητή ")
variable = input("Δώσε μεταβλητή ")
variable = input("Δώσε μεταβλητή ")
print(variable + variable + variable)
```

## Sources - Notes

- D:\_COURSES\[TutsNode.com] - Python A-Z - Learn Python Programming By Building 5 Projects
- Helsinki

- https://www.faceprep.in/python/hello-world-in-python/
- https://stackoverflow.blog/2017/09/06/incredible-growth-python/
- https://www.statista.com/chart/21017/most-popular-programming-languages/
- https://realpython.world/basics/python-comments.html
- https://medium.com/analytics-vidhya/5-essential-python-tricks-to-make-your-code-more-clean-readable-elegant-33db96d99e84
