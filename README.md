Spinner
=======

Python text spinner class using NLTK and wordnet synonyms dictionary


s = spinner()

spintax = s.getSpintax('Everything in moderation, including moderation.')

spun = s.spin(spintax)

print spintax

print spun
