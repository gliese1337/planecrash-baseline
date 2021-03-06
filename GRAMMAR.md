Ethnography
===========

Dath ilan is an alternate-history Earth envisioned by Eliezer Yudkowsky, whose history diverges at least a couple thousand years ago from our own, and in which civilization has achieved a much higher degree of global economic coordination. Part of this increased coordination is that everyone on dath ilan speaks, at minimum, an in-universe conlang called "Baseline". Out-of-universe, Baseline did not actually exist prior to Eliezer writing stories featuring Baseline-speaking dath ilanis--but descriptions of what it is like do exist in those stories, which can be used, to the extent that they are consistent, to infer a language consistent with the stories. 

Phonology
=========

The majority of canonical evidence for Baseline phonology comes from names:

    Alis       Athpechya  Bahb
    Bahdhi     Bohob      Corun
    Derrin     Elshorm    Elzbeth
    Helorm     Illeia     Karal
    Keltham    Limyar     Merrin
    Miyalsvor  Nemamel    Petheriel
    Ranthal    Salthin    Thellim
    Verrez

Most names have two syllables; a few (5 in this list) have 3, or maybe 4. "Bahb" is the only one-syllable names, but that is likely not representative of any real name used for a dath ilani person, as it appears in a context where it is clearly meant to be transcription of the English name "Bob", as part of the set "Alis, Bahb, and Karal", standing in for "Alice, Bob, and Carol", the standard placeholder names for participants in a cryptographic protocol. "Bohob" seems to be an alternative adaptation of "Bob" that fits Baseline naming patterns better. In combination with "Bahdhi", though, the orthographic possibility of "Bahb" suggests the existence of ⟨a⟩ and ⟨ah⟩ as separate vowels. If ⟨h⟩ can only occur in onset positions, there would be minimal ambiguity introduced in the Anglicization by adopting that convention.

⟨Illeia⟩ could be a four-syllable name, and ⟨Petheriel⟩ almost certainly is if it is meant to be pronounced in the "obvious" way, but we have a negative example in that ⟨Athpechya⟩ is presented as a dath ilani equivalent for a non-Baseline 4-syllable name, which has been cut down to 3 syllables (assuming ⟨y⟩ is to be interpreted as a consonant).

Our primary informant, Keltham, [at one point says](https://glowfic.com/replies/1625693#reply-1625693)

> Two syllables is long enough that you'd be moderately unlikely to be good friends with two people with the same name, so it's what most normies like my parents use in the modern generation.  I've considered changing mine to something four-syllabled just to be Chaotic about it, but common wisdom says I should let my personality finish shaking out up to age 25 first.

Which suggests that 4-syllable names are *possible*, but rare--probably over-represented by having the single unambiguous example of ⟨Petheriel⟩ in this small sample. If we don't want to end up with *two* such names in every 22, ⟨Illeia⟩ can be resolved to a 3-syllables name if we interpret that intervocalic ⟨i⟩ as a transcriptional variant of ⟨y⟩, much like ⟨c⟩ is a transcriptional variant of ⟨k⟩, rather than as a whole extra syllable.

As a cultural note, all dath ilani are mononymic, so there is nothing to be said about the structure of family names / patronymics.

The following non-personal-name words are also attested:

dath  
ilan  
raht  
tsi-imbi  
farsheth  
kelthorkarnen

And there are the pre-canonical examples

Gora Vedev
Sinyelt
de'a'na
est
shadarak
shan
codra

from [Eliezer's April Fools' Day Confession](https://yudkowsky.tumblr.com/post/81447230971/my-april-fools-day-confession).

In terms of explicit descriptions of Baseline's phonology, this is all we have:

> For example, all the phonemes are a minimum distance away from each other that guarantees people with slightly less acute hearing can understand it when spoken under slightly adverse conditions. In-between phonemes that are possible to pronounce, but potentially difficult to hear correctly, are then reserved for constructing 'conlangs', constructed languages, many of which use 'Baseline' as a baseline but add new short words using the expanded phoneme set.

Assuming that the attested words are meant to pronounced in ways intuitive to an Anglophone audience, and that these pronunciations are recognizably accurate to the native Baseline pronunciations, that claim seems not to be super well supported by the data. For example, it appears to contain all three of s/θ/f, which are easily confusable in low-fidelity audio environments. (TODO: Include literature review on phonetic confusion.) 

However, fortunately for us, the character who speaks that paragraph is not specifically trained in linguistics, and may not know exactly what he's talking about--and there are other constraints on the design of Baseline which may conflict with that one, such that the optimal design for Baseline phonology is not one which optimizes distinctness-of-phonemes in isolation. In particular, Baseline speakers seem to have a strong sense of syllables as the most salient components of word structure, and count of syllables as the obvious way to measure utterance length; and, they value having short words and short utterances for concepts that are common in their culture. Thus, we can also expect to have a large phonemic inventory to allow for the maximum number of individual syllables, maximum information per syllable, and maximal number of short words, which is in direct conflict with keeping individual phones as far apart from each other in acoustic space as possible.

From this data, we can infer that Baseline has a 6 vowel system:

|     | Front   | Back     |
|-----|---------|----------|
| Hi  | /i/ ⟨i⟩ | /u/ ⟨u⟩  |
| Mid | /ɛ/ ⟨e⟩ | /o/ ⟨o⟩  |
| Hi  | /æ/ ⟨a⟩ | /ɑ/ ⟨ah⟩ |

with three degrees of height, a binary front-back distinction, and rounding in the back non-low vowels.

It would be more in-line with designing for maximal distinctiveness if the ⟨e⟩ vowel were a little higher, to maximize contrast with /æ/, but we have an explicit negative example where [the dath ilani Merrin struggles to pronounce the French names "Félix" and "Élie"](https://www.glowfic.com/replies/1786094#reply-1786094), which confirms that the Baseline ⟨e⟩ vowel is *not* /e/.

Note, however, that in the attested data ⟨r⟩ only occurs after ⟨e⟩, ⟨a⟩, or ⟨o⟩. In English phonology, "r" and a few other consonants trigger vowel neutralization in cod positions, resulting in a smaller vowel inventory in the environment of those codas. The lack of ⟨ir⟩ or ⟨ahr⟩
sequences in the data suggest that we can construct a reduced 3-vowel triangular system in the pre-⟨r⟩ environment, neutralizing ⟨i⟩ and ⟨e⟩ to a mid-close front vowel romanized as ⟨e⟩, a low-mid vowel romanized as ⟨a⟩, and a mid-close back vowel romanized as ⟨o⟩. This will prove numerologically useful for constructing numeric digits later, although it may be contradicted by future data.

Given that /j/ never occurs as an unambiguous coda in the canonical or pre-canonical data, we are also free to extend the vowel neutralization environment to pre-/j/ positions as well, which will also serve to assist in proper pronunciation by Anglophone readers. The strangeness of English long vowels, however, requires a special case in the romanization to suggest the proper Anglicized pronunciation--namely, that /aj/ be transcribed as ⟨ai⟩, rather than ⟨ay⟩, as the latter would be mispronounced as /ej/.

Attested consonants, based on the assumption that names are supposed to be pronounced in the most obvious possible way for an Anglophone reader, are as follows:

p - /p/  
b - /b/  
t - /t/  
d - /d/  
k/c - /k/

f - /f/  
v - /v/  
s - /s/  
z - /z/  
th - /θ/  
dh - /ð/  
sh - /ʃ/  
h - /h/

ts - /t͡s/  
ch - /t͡ʃ/

l - /L/ (for maximal distinctiveness from /j/, we assume this to be a dark/velarized l, rather than copying English's light/dark allophony; the presence of this and /v/ justify the lack of /w/)  
r - /r/ (for maximal distinctiveness from /l/, we assume this to be a tap/trill even though that's not the *most* natural reading for most Anglophones).  
y - /j/

m - /m/  
n - /n/

We interpret ⟨ts⟩ as an affricate on the basis that there are no other word-initial apparent clusters, and that the affricate ⟨ch⟩ is unambiguously attested (so the category of affricates clearly exists in Baseline's inventory).

The lack of /g/ is not typologically odd on its own, but given the fairly robust fairly robust voicing distinction for most plosives and fricatives, we can infer that there should also be \*/g/, \*/ʒ/, \*/d͡z/, and \*/d͡ʒ, phonemes, even though they happen to be missing from this dataset, on the basis that, having decided that voicing was usefully distinctive for all other obstruents, the in-world engineers of Baseline wouldn't have just left those specific place/manner combinations unused!

Now, let us consider the case of ⟨tsi-imbi⟩ a little more closely. It's the only attested word with a hyphen in it, and the only word with consecutive identical vowels if you ignore the hyphen. In fact, no attested words have consecutive vowels at all! I infer that this is to maximize the ease of syllable segmentation, and that the hyphen should in fact represent an additional marginal glottal stop (/ʔ/) phoneme (such as shows up in the English "uh-oh"), which shows up wherever vowels would otherwise be in hiatus. That also allows to resolve any possible ambiguity in the usage of ⟨ah⟩ to transcribe the low-back vowel. Something like ⟨bahob⟩ (a minimal change from the attested ⟨Bohob⟩) would have to be read as /bæ.hob/, while /baob/ would be phonetically [ba.ʔ.ob], with extra-metrical /ʔ/, and transcribed as ⟨bah-ob⟩--and /ba.hob/ would be ⟨bahhob⟩. The hyphen can also be used in Anglicization to break disambiguate Ch digraphs from C.h sequences across syllable boundaries; e.g., /a.θa/ would be written ⟨atha⟩, /aθ.ha/ would be written ⟨athha⟩, and /at.ha/ would be written ⟨at-ha⟩.

This lack of vowel length or hiatus vowels raises another potential problem with the transcription of other consonants; while we have examples of single intervocalic ⟨l⟩ and ⟨r⟩, there are also a few instance of doubled ⟨ll⟩ and ⟨rr⟩--but no other doubled consonants. And if we aren't allowing doubled vowels, having geminate continuant consonants across syllable boundaries seems like a very weird choice, completely counter to the goal of making syllabic segmentation easy and unambiguous. One could imagine heterosyllabic /l.ʔ.l/ and /r.ʔ.r/ sequences, with epenthetic glottal stops separating syllables just like they do between vowels, but in the absence of written hyphens in the attested names, I am going to assume that the doubled letters are there purely for purposes of Anglophone aesthetics, and that cross-syllable geminates do not exist in Baseline roots. (Eliminating them across morpheme boundaries is a more difficult problem, so we will not dismiss that possibility yet.)

That leads to the following consonants chart:

|             | Labial      | Dental        | Alveolar        | Palatal        | Velar       | Glottal |
|-------------|-------------|---------------|-----------------|----------------|-------------|---------|
| Plosive     | p ⟨p⟩ b ⟨b⟩ |               | t ⟨t⟩ d ⟨d⟩     |                | k ⟨k⟩ g ⟨g⟩ | (ʔ) ⟨-⟩ |
| Nasal       | m ⟨m⟩       |               | n ⟨n⟩           |                |             |         |
| Trill       |             |               | r ⟨r⟩           |                |             |         |
| Fricative   | f ⟨f⟩ v ⟨v⟩ | θ ⟨th⟩ ð ⟨dh⟩ | s ⟨s⟩ z ⟨z⟩     | ʃ ⟨sh⟩ ʒ ⟨zh⟩  |             | h ⟨h⟩   |
| Affricate   |             |               | t͡s ⟨ts⟩ d͡z ⟨dz⟩ | t͡ʃ ⟨ch⟩ d͡ʒ ⟨j⟩ |             |         |
| Approximant |             |               |                 | j ⟨y⟩          | L ⟨l⟩       |         |

The Anglicization is slightly complicated by transcribing /k/ as ⟨c⟩ instead of ⟨k⟩ when it precedes ⟨o⟩, and /j/ and ⟨i⟩ instead of ⟨y⟩ when it is between two vowels, or when it is a coda for ⟨a⟩.

The fricatives are a little bit weird; why include θ/ð alone in their column, rather than bringing in the velar fricatives x/ɣ to maximize distinctiveness and get slightly better correspondence between fricative and plosive series? But perhaps the in-world justification is that they just Wanted More Options for making more short words, and the possibility of x/h confusion pushed for pulling in the dental fricatives instead, despite the labial/dental/alveolar confusability, to allow for including h.

For the plosives, maximizing distinctiveness suggests that all of the voiceless plosives should also be secondarily aspirated--we've only got two plosive series, so we might as well make them as phonetically distinctive as possible!

Phonotactics & Syllable Structure
---------------------------------

Extrapolating from the canonical and pre-canonical evidence, we can infer the following apparent phonotactic rules:

Syllables have the form (C1)V((r|l|s|z)C2(s|z)), where:
* C1 is any consonant.
* C2 is any consonant except /h/.
* Only reduced vowels are permitted before coda /r/ or /j/.
* No pre-C2 consonants can occur before /j/.
* The optional /r/ or /l/ cannot occur before another /r/ or /l/ in the C2 slot.
* The optional coda sibilants cannot occur adjacent to another sibilant in the C2 slot or prior to a sonorant.
* /s/ cannot occur adjacent to tautosyllabic voiced stops/fricatives.
* /z/ cannot occur adjacent to tautosyllabic voiceless stops/fricatives.

Within a word:
* A syllable cannot end with the same consonant with which the next syllable starts (nor should t/d precede t͡s/d͡z or t͡ʃ/d͡ʒ, respectively).
* Vowels cannot occur in hiatus on the phonetic level, with extra-syllabic glottal stops being inserted for repair.

Making codas more complex than onsets is just weird, and there does not seem to be any clear in-world justification, but that seems to be where the available data is pointing. Maybe it is meant to allows sub-syllable-level suffixing/infixing morphology? The possibility of coda clusters with initial /l/ and /s/ is suggested only by pre-canonical data, but aside from the general weirdness of complex codas without complex onsets, it is not contradicted by any canonical data, so I have chosen to accept that pre-canonical data on the basis that it obeys the [sonority sequencing principle](https://en.wikipedia.org/wiki/Sonority_Sequencing_Principle) and helps to expand the total number of possible monosyllables.

Allophony
---------

Special attention must be paid to how pairs of phonemes are realized across morpheme and word boundaries, which interfaces allow pairing which cannot occur within a single syllable or across syllables within a root.

Vowel-initial roots and affixes may trigger resyllabification based on the maximum-onset principle when they occur after consonants in the same morphological word. Across word boundaries, a glottal stop is inserted to occupy the onset consonant position. When vowel-initial words occur after voiceless codas, this glottal stop merges with the preceding consonant to produce a phonetic ejective. This process is entirely predictable from the positions of word boundaries, indicated with a space in both the Baseline orthography and the romanization. Vowel-initial morphemes do not occur in the "basic" vocabulary, for which is it guaranteed that any sequence of phonemes have a unique interpretation, and thus resyllabification cannot be allowed.

Sonorant consonants (⟨r⟩, ⟨y⟩, ⟨l⟩) trigger the insertion of an extra-syllabic glottal stop when they occur doubled, just like hiatus vowels do. This represented in the romanization with a hyphen ⟨-⟩, to make it clear that there are two separate consonants rather than a single onset consonant written doubled for aesthetic reasons, except in the case of /aj.j/ sequences, which are written as ⟨aiy⟩.

Pairs of homorganic fricatives similarly trigger insertion of an epenthetic glottal stop, which is realized as ejectivization when the first fricative is voiceless.

Voiced stops (including nasals and plosives) are simply geminated when they are doubled across a morpheme boundary. E.g., /d.d/ -> [d:]

Voiced plosives followed by homorganic voiceless plosives are pronounced as a half-voiced geminate stop with aspirated release. E.g., /d.t/ -> [d͡tʰ]

Pairs of voiceless plosives are always pronounced separately with a distinct aspirated release. E.g., /t.t/ -> [tʰtʰ]

Similarly, pairs of affricates are always pronounced in sequence with distinct fricative releases, rather than geminated. Plosives followed by homorganic affricates are realized with geminate stops, with the stop portion taking the voicing of the original plosive and the fricated release taking the voicing of the original affricate.

Prosody
-------

Based on characters' commenting on how many syllables are required to say something in various languages, and treating syllable count as a reliable measure of how long an utterance is / how much effort it takes to express something, we can infer that the language is syllable-timed, rather than stress- or mora-timed.

Possible Syllables
------------------

Making the default assumption that the maximum onset principle for syllabification applies, the attested syllables are as follows:

a ath  
i im  
el elz  
bah bahb  
beth bi bo  
dath dhi  
far  
he hob  
ka kar kel ko  
lan le lim lis lorm  
ma me mel mi  
ne nen  
pech  
raht ral ran rez ri rin run  
sal  
sheth shorm  
thal tham the thin thor  
tsi 
ver vor 
ya yals yar 

The possible syllables are a much larger set, totalling 18,450. However, depending on morphological rules, not all of these will necessarily be available for assignment to unique lexical items.

Syntax
======

Basic Clauses
-------------

Baseline's basic unmarked word order is SXV(O) (where X stands for a finite auxiliary). Correspondingly, the language is primarily head-initial. However, additional nonfinite V(O) units acting as components of a serial verb construction or as adverbial adjuncts (two different Earth-centric analyses of the same actual phonomenon) may occur in any order, with actual order of appearance dictated by quantifier scoping relations and pragmatic information structure concerns. 

Personal & Demonstrative Pronouns
=================================

All personal pronouns are invariant for all grammatical functions.

The first person singular pronoun is ⟨mi⟩.

The second person singular pronoun is ⟨ti⟩. The plural is ⟨vi⟩.

For third person, Baseline uses a single series of personal and demonstrative pronouns. These use a common rime of ⟨-em⟩ for singular and ⟨-erm⟩ for plural, with onset consonants varying to agree alliteratively with the onset of the antecedent. There are twelve total agreement forms, as follows:

|  Form  | Agr. Classes |
|--------|--------------|
| ⟨pem⟩  |    p-, b-    |
| ⟨tem⟩  |  t-, d-, r-  | 
| ⟨kem⟩  |    k-, g-    |
| ⟨hem⟩  |    V-, h-    |
| ⟨nem⟩  |    m-, n-    | 
| ⟨vem⟩  |    f-, v-    |
| ⟨dhem⟩ |    θ-, ð-    |
| ⟨zem⟩  |    s-, z-    |
| ⟨zhem⟩ |    ʃ-, ʒ-    |
| ⟨tsem⟩ |   t͡s-, d͡z-   |
| ⟨chem⟩ |   t͡ʃ-, d͡ʒ-   |
| ⟨yem⟩  |    j-, l-    |

These forms are always endophoric; that is, that refer to some other phrase in the ongoing discourse. When used in the determiner slot of an argument phrase, the noun complement serves to further restrict what the whole determiner phrase may be referring to, giving greater specificity than the pronoun on its own. Alternately, this can be interpreted as the determiner restricting the noun to co-refer to something else in the discourse.

The prefix ⟨e-⟩ derives *exophoric* demonstratives--pronouns which rever to something in the world external to the discourse, and bring that entity into the discourse. If used with a noun, the demonstrative will always agree with the head of the noun phrase; when used in isolation, however, an exophoric demonstrative may not have any formal linguistic expression to agree with (since the thing it refers to is by definition not yet part of the discourse); for example, when asking "What is that?" In such cases, ⟨eyem⟩ serves as the default, generic demonstrative.

Baseline does not distinguish distal vs. proximal demonstratives.

First person plurals are formed by compounding the first person singular with second and third person pronouns, forming the following set of 8 pronouns:

* ⟨miti⟩ - me and you, the two of us.
* ⟨mivi⟩ - me and all of you
* ⟨miyem⟩ - me and him/her/it, but not you
* ⟨miyerm⟩ - me and them, but not you.
* ⟨mitem⟩ - the two of us and he/she/it
* ⟨miterm⟩ - the two of us and them.
* ⟨mivem⟩ - me, all of you, and he/she/it
* ⟨miverm⟩ - me, all of you, and them.

Numerals
========

Baseline digits (atomic cardinal numerals) are all single closed syllables beginning with one of seven voiceless consonants: 
⟨p⟩ ⟨sh⟩ ⟨t⟩ ⟨f⟩ ⟨k⟩ ⟨ch⟩ ⟨s⟩.

No two digits form a minimal pair; that is, all digits differ by at least two phonemes, which is accomplished by varying codas on a different frequency from onsets. Additionally, numerically-adjacent digits have onsets which differ in both place and manner of articulation

There are 21 digits constructed from 3 cycles of the seven onset consonants, paired with 7 cycles of the 3 vowels ⟨e⟩, ⟨ah⟩, and ⟨o⟩. Each cycle of vowels has a consistent coda, with groups of codas cycling through a separate set of seven consonants which are differentiated from onsets to ensure that compound numerals never have sequential identical fricatives: ⟨n⟩ ⟨dh⟩ ⟨d⟩ ⟨m⟩ ⟨g⟩ ⟨b⟩ ⟨l⟩.

| Value | Numeral | Value | Numeral | Value | Numeral |
|-------|---------|-------|---------|-------|---------|
| 0     | ⟨pen⟩   | 1     | ⟨shahn⟩ | 2     | ⟨ton⟩   |
| 3     | ⟨fedh⟩  | 4     | ⟨kahdh⟩ | 5     | ⟨chodh⟩ |
| 6     | ⟨sed⟩   | 7     | ⟨pahd⟩  | 8     | ⟨shod⟩  |
| 9     | ⟨tem⟩   | 10    | ⟨fahm⟩  | 11    | ⟨kom⟩   |
| 12    | ⟨cheg⟩  | 13    | ⟨sahg⟩  | 14    | ⟨pog⟩   |
| 15    | ⟨sheb⟩  | 16    | ⟨tahb⟩  | 17    | ⟨fob⟩   |
| 18    | ⟨kel⟩   | 19    | ⟨chahl⟩ | 20    | ⟨sol⟩   |

Sequences of consecutive digits form compound numerals which are interpreted as big-endian place-value representations of a number. By default, digit strings are interpreted in base 12, and no digit larger than 11 ⟨kom⟩ may occur in such a number. Note that any isolated digit may be used to represent its inherent value in any context; thus, while it is possible to represent, e.g., 15 as a base-12 digit string ⟨shahnfedh⟩, it would be more typical to simply say ⟨sheb⟩. When a single digit occurs more than twice in a row in a digit string, the onset consonant of alternating digits, starting with the second occurrence, is voiced, to assist with keeping track of digit positions. Thus, 26388 ("13330" in base 12) would be represented as ⟨shahnfedhvedhfedhpen⟩, not \*⟨shahnfedhfedhfedhpen⟩. This is a much more frequent occurrence when expressing numbers in smaller bases. This voicing alternation is not a waste of phonetic material as the alternate forms never appear as independent words, and so do not produce a homophone conflict with any actual independent words. Avoiding a lexical segmentation conflict just requires that those syllables not be assigned as independent words to anything which is grammatically countable.

Non-integer quantities are expressed by using the infix operator ⟨put⟩, representing a radix point, to separate the whole-number part from the fractional part of a complex numeral. Thus, 2.5 is ⟨tonput sed⟩. Leading zeroes can be omitted; thus, 0.25 is ⟨putfedh⟩, or ⟨penputfedh⟩.

Ordinal digits are formed with an infix ⟨-r-⟩, which can result in alterations in the romanization. The final 3 digits, which end in ⟨l⟩ in the cardinal form, simply replace the final ⟨l⟩ to avoid an illegal ⟨rl⟩ cluster. Thus, "first" is ⟨sharn⟩, "twelveth" is ⟨cherg⟩, "twentieth" is ⟨sor⟩, etc. Compound ordinal numerals use ordinal digits throughout. Thus, "one-hundred-fourty-fourth" is ⟨chergcherg⟩, not \*⟨chegcherg⟩ or \*⟨chergcheg⟩. This ensures that there is no ambiguity about boundaries when different numeral classes may appear in hiatus. This occurs, for example, in the expression of rational numbers, which are formed by using a cardinal numerator to quantify over an ordinal denominator, much like English. Thus, "seven eighths" is ⟨pahd shord⟩, and "thirty-seven one-hundred-fourty-fourths" is ⟨fedhshahn chergcherg⟩.

While 12 is the default base, in certain contexts digit strings may be interpreted in any other base less than 21. The simplest example of this is the use of the ⟨pernz⟩ construction. A digit with the ⟨pern-⟩ prefix and ⟨-z⟩ suffix may be preposed to any syntactic scope to alter the interpretation of digit strings within that scope. For example, placing ⟨pernsolz⟩ immediately before a digit string will cause that digit string (and any embedded digit strings within a noun phrase over which that digit string quantifies) to be interpreted in base-20. Thus, ⟨kompen⟩ is 132, but ⟨pernsolz kompen⟩ is 220. Another common construction uses the prefix ⟨tu-⟩ with ordinal derivation (using infix ⟨-r-⟩) to produce specialized base indicator which further specify that a single numeral should be interpreted in the given base, but then divided by the square of that base. Thus, ⟨tufarm⟩ translates the English "percent", while ⟨tucherg⟩ means "interpret in base 12, then divide by 144"--a base-12 equivalent of "percent". "Thirty-seven one-hundred-fourty-fourths" may thus be alternately expressed as ⟨tucherg fedhton⟩, while "52 percent" may be expressed as ⟨tufarm chodhton⟩.

Digits and digit strings can also be used in a larger construction which avoids the need to state an explicit base. An ordinal digit string compounded to a cardinal digit string with the suffix ⟨-z⟩ expresses exponentiation ("read as CAR to the ORD power times..."), and may be followed by a unit multiplier (an integer, rational, or radix-point numeral) interpreted in the base of the exponentiated cardinal digit. Note that the ⟨pernz⟩ construction described above is an extension of this pattern--it can be literally read as "X to the 0th power times...", which is otherwise functionally vacuous, as it would literally entail nothing more than multiplying by 1.

Multiple exponent constructions in sequence have their values summed. This allows easy expression of large quantities whose digit-string representations may have lots of zeroes; e.g, "one million two hundred" may be expressed as ⟨serdfahmz shahn tornfahmz ton⟩ (6 syllables), rather than ⟨pernfahmz shahnpenbenpentonpenpen⟩ (base 10, 9 syllables) or ⟨kahdhpentontemfahmpen⟩ (base 12, 6 syllables).

Note that there is no requirement that the bases of different terms in an exponential expression must be the same! However, switching radices with multiplier terms larger than 20 (thus, requiring digit string representation) is usually unnecessarily cognitively-taxing.