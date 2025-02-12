# Boolean Word Search Application

This application allows users to search for specific word occurrences in a text file based on a Boolean expression. The program supports logical operators, such as `AND` and `OR`, to refine search queries. It then returns the occurrences from the text where the Boolean expression is satisfied within a user-specified range of words.

## Input
- **Text file**: The text file in which to search for word occurrences.
- **Boolean expression**: A logical expression using `AND` and `OR` operators to define the search criteria.
- **Range**: A user-defined range (in characters) within which the Boolean expression must hold true.

## Output
The program will return the occurrences found in the text where the Boolean expression is satisfied within the specified range.

## Setup

1. In the `Boolean_Search/booleanEvaluator.py` file, locate the following variables and edit them as needed:

    ```python
    file = ""  # Path to your text file
    expression = ""  # Boolean expression (e.g., "word1 AND word2 OR word3")
    userDefinedLength = 150  # Range of characters to consider
    ```

## Example Usage

### Scenario
If the input text file is the *Book of Mormon* and the Boolean expression is `"Nephi AND Jesus"`, with a range set to `150`, the program will find all instances where the word "Nephi" appears within 150 characters of the word "Jesus."

### Sample Output

words:  ['jesus', 'nephi']
instances found @:  30 [859984, 1180294, 1183588, 1187637, 1199278, 1202669, 1211496, 1216227, 1223434, 1224128, 1225588, 1249571, 1254281, 1255595, 1258535, 1258721, 1265332, 1275201, 1275962, 1276228, 1276394, 1277111, 1277398, 1278902, 1282698, 1283164, 1284284, 1284446, 1286351, 1354622]
  
the prophecy is fulfilled;
therefore write the words which i shall say.

45:10 and these are the words: behold, i perceive that this very
people, the nephites, according to the spirit of revelation which is in
me, in four hundred years from the time that jesus christ shall
manifest himself unto them,
  
  
iful; and they were marveling and wondering one with
another, and were showing one to another the great and marvelous change
which had taken place. 3 nephi 11:2 and they were also conversing about
this jesus christ, of whom the sign had been given concerning his
death.

11:3 and it came to pass that 
  
  
themselves, they did cry out with one accord, saying:

11:17 hosanna! blessed be the name of the most high god! and they did
fall down at the feet of jesus, and did worship him.

11:18 and it came to pass that he spake unto nephi (for nephi was among
the multitude) and he commanded him that he should
  
  
 and the winds beat upon
them.

11:41 therefore, go forth unto this people, and declare the words which
i have spoken, unto the ends of the earth.

3 nephi chapter 12

12:1 and it came to pass that when jesus had spoken these words unto
nephi, and to those who had been called, (now the number of them
  
  
take therefore no thought for the morrow, for the morrow shall
take thought for the things of itself. sufficient is the day unto the
evil thereof.

3 nephi chapter 14

14:1 and now it came to pass that when jesus had spoken these words he
turned again to the multitude, and did open his mouth unto the
  
  
sand-

14:27 and the rain descended, and the floods came, and the winds blew,
and beat upon that house; and it fell, and great was the fall of it.

3 nephi chapter 15

15:1 and now it came to pass that when jesus had ended these sayings he
cast his eyes round about on the multitude, and said unto the
  
  
erusalem.

16:20 the lord hath made bare his holy arm in the eye of all the
nations; and all the ends of the earth shall see the salvation of god.

3 nephi chapter 17

17:1 behold, now it came to pass that when jesus had spoken these words
he looked round about again on the multitude, and he said unt
  
  
 hear, every
man for himself; and they were in number about two thousand and five
hundred souls; and they did consist of men, women, and children.

3 nephi chapter 18

18:1 and it came to pass that jesus commanded his disciples that they
should bring forth some bread and wine unto him.

18:2 and whil
  
  
y were overshadowed he departed from them, and
ascended into heaven. and the disciples saw and did bear record that he
ascended again into heaven.

3 nephi chapter 19

19:1 and now it came to pass that when jesus had ascended into heaven,
the multitude did disperse, and every man did take his wife an
  
  
ple that there were many,
yea, an exceedingly great number, did labor exceedingly all that night,
that they might be on the morrow in the place where jesus should show
himself unto the multitude.

19:4 and it came to pass that on the morrow, when the multitude was
gathered together, behold, nephi and
  
  
o them.

19:10 and when they had thus prayed they went down unto the waterâ€™s
edge, and the multitude followed them.

19:11 and it came to pass that nephi went down into the water and was
baptized.

19:12 and he came up out of the water and began to baptize. and he
baptized all those whom jesus had 
  
  
e it that ye have not written this
thing, that many saints did arise and appear unto many and did minister
unto them?

23:12 and it came to pass that nephi remembered that this thing had not
been written.

23:13 and it came to pass that jesus commanded that it should be
written; therefore it was writ
  
  
shall turn the heart of the fathers to the children, and
the heart of the children to their fathers, lest i come and smite the
earth with a curse.

3 nephi chapter 26

26:1 and now it came to pass that when jesus had told these things he
expounded them unto the multitude; and he did expound all thing
  
  
ness which is in christ, who
was before the world began.

26:6 and now there cannot be written in this book even a hundredth part
of the things which jesus did truly teach unto the people;

26:7 but behold the plates of nephi do contain the more part of the
things which he taught the people.

26:8 an
  
  
and they had
all things common among them, every man dealing justly, one with
another.

26:20 and it came to pass that they did do all things even as jesus had
commanded them.

26:21 and they who were baptized in the name of jesus were called the
church of christ.

3 nephi chapter 27

27:1 and it cam
  
  
 they who were baptized in the name of jesus were called the
church of christ.

3 nephi chapter 27

27:1 and it came to pass that as the disciples of jesus were journeying
and were preaching the things which they had both heard and seen, and
were baptizing in the name of jesus, it came to pass that t
  
  
 wide is the gate, and broad the way which leads to
death, and many there be that travel therein, until the night cometh,
wherein no man can work.

3 nephi chapter 28

28:1 and it came to pass when jesus had said these words, he spake unto
his disciples, one by one, saying unto them: what is it that 
  
  
 hand of
the lord unto the left, that he may not execute judgment unto the
fulfilling of the covenant which he hath made unto the house of israel.

3 nephi chapter 30

30:1 hearken, o ye gentiles, and hear the words of jesus christ, the
son of the living god, which he hath commanded me that i should 
  
  
ceive a remission of your sins, and be filled
with the holy ghost, that ye may be numbered with my people who are of
the house of israel.




 fourth nephi

who is the son of nephi-one of the disciples of jesus christ

an account of the people of nephi, according to his record.

4 nephi 1:1 and it ca
  
  
 his record.

4 nephi 1:1 and it came to pass that the thirty and fourth year passed
away, and also the thirty and fifth, and behold the disciples of jesus
had formed a church of christ in all the lands round about. and as many
as did come unto them, and did truly repent of their sins, were
baptized 
  
  
 a church of christ in all the lands round about. and as many
as did come unto them, and did truly repent of their sins, were
baptized in the name of jesus; and they did also receive the holy
ghost.

4 nephi 1:2 and it came to pass in the thirty and sixth year, the
people were all converted unto the 
  
  
assed
away also, and there still continued to be peace in the land.

4 nephi 1:5 and there were great and marvelous works wrought by the
disciples of jesus, insomuch that they did heal the sick, and raise the
dead, and cause the lame to walk, and the blind to receive their sight,
and the deaf to hear
  
  
e deaf to hear; and all manner of miracles did they work among
the children of men; and in nothing did they work miracles save it were
in the name of jesus.

4 nephi 1:6 and thus did the thirty and eighth year pass away, and also
the thirty and ninth, and forty and first, and the forty and second,
ye
  
  
and it came to pass that there was no contention among all
the people, in all the land; but there were mighty miracles wrought
among the disciples of jesus.

4 nephi 1:14 and it came to pass that the seventy and first year passed
away, and also the seventy and second year, yea, and in fine, till the

  
  
hrist, because of
their humility and their belief in christ; and they did despise them
because of the many miracles which were wrought among them.

4 nephi 1:30 therefore they did exercise power and authority over the
disciples of jesus who did tarry with them, and they did cast them into
prison; but
  
  
, and notwithstanding all these miracles, the
people did harden their hearts, and did seek to kill them, even as the
jews at jerusalem sought to kill jesus, according to his word.

4 nephi 1:32 and they did cast them into furnaces of fire, and they
came forth receiving no harm.

4 nephi 1:33 and they
  
  
and they were true believers in christ;
and among them there were those who were called by the
lamanites-jacobites, and josephites, and zoramites;

4 nephi 1:37 therefore the true believers in christ, and the true
worshipers of christ, (among whom were the three disciples of jesus who
should tarry) w
  
  
herefore the true believers in christ, and the true
worshipers of christ, (among whom were the three disciples of jesus who
should tarry) were called nephites, and jacobites, and josephites, and
zoramites.

4 nephi 1:38 and it came to pass that they who rejected the gospel were
called lamanites, and 
  
  
to pass that the robbers of gadianton did
spread over all the face of the land; and there were none that were
righteous save it were the disciples of jesus. and gold and silver did
they lay up in store in abundance, and did traffic in all manner of
traffic.

4 nephi 1:47 and it came to pass that afte
  
  

the flesh.

3:17 and now, as i, moroni, said i could not make a full account of
these things which are written therefore it sufficeth me to say that
jesus showed himself unto this man in the spirit, even after the manner
and in the likeness of the same body even as he showed himself unto the
nephite
  
time:  0.04480695724487305

