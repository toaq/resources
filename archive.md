# Archive

## On names with falling tone

### 2018-07-10, #chiejio
mı Lỉq:
> "In (NAM.1) and (NAM.2), the name after mi carries a falling tone. It can also
carry any other tone. The name ends automatically when the phrase started by
the name's tone ends."
>
> I'm actually a little confused about this phrasing
>
> oh, phrase means something very specific, right

mı Hỏemāı
> %miu mi4 bu7

mı Nủogāı
> (mỉ bũ)
> {λ𝑋 chua(‹bũ›, 𝑋)}().

mı Hỏemāı
> %miu mi4 neo6 ni2

mı Nủogāı
> (mỉ {no ní})
> {λ𝑋 chua(‹no ní›, 𝑋)}().

mı Hỏemāı
> So here the names are "bũ" and "nèo ní"
>
> An adverbial phrase and a prepositional phrase
>
> the prepositional phrase ends with its noun complement (which itself ends once
> its serial verb is over and once there aren't any attached relative clauses
> anymore)
>
> And then the name is automatically over

mı Lỉmēq
> %miu mỉ mỏq

mı Nủogāı
> syntax error :1.7: want [bB], [cC], [dD], [fF], [gG], [hH], [jJ], [kK], [lL], [mM], [nN], [pP], [rR], [sS], or [tT]; got EOF

mı Lỉq
> so, if my name is Lı̉q, that tone is part of the name? as in, mi Líq and mi Lĩq are different persons

mı Hỏemāı
> Unless you also go by those names

mı Lỉq
> right

mı Hủaqchī
> That’s the difference between Ms. Being a female, Ms. A Female and Ms. Femininely
> 
> roughly
>
> zo’orei

### 2019-03-07, #general
mı Sẻaqtāq
> Anyhow normally you will find a name in the fourth tone

### 2019-03-08, #general
mı Nỉucūq
> m̂, fragments of terms and serial predicates also can be taken as a name/phrase by mi/shu

### Summary
Names can have any tone, but the most common one is the fourth tone.
Two names with the same word, but different tones are technically different names (mı Lỉq <> mı Líq <> mı Lĩq).

## On frames and signatures 

This file contains most of the common frames.    
[frames-list.txt](https://github.com/acotis/serial-predicate-engine/blob/master/code/dict/frame-list.txt)

### 2019-03-08, #general
mı Hỏaqgīo
> As for frames-list.txt...
> Since there are only a few common types in the type system 
>     (c, 0, 1, and 2),
> and since each word has usually only one or two slots, it happens that a lot of
> words have the same signature as each other.
> 
> (This is bolstered by the fact that Toaq tries to build patterns into the
> vocabulary, so many words that deal with similar concepts are given them same
> signature on purpose.
> -- see the triplet 
>     (dua, chi, miu) 
> or 
>     (jui, jao, leaq, poe, cuao) )
> 
> A frame is just a common signature that lots of words fit into.
> For example, the LEO frame is the signature
>     [(c) (c 1)] -- 
> predicates whose 1-ary meaning takes just a concrete object and whose 2-ary
> meaning takes a concrete object and a property (a proposition with one open
> slot)
> 
> Math stuff here, don't look if you're already feeling overwhelmed :smiley: : There's also the special case of the JEO frame, which has the signature [(0) (c 1)] and the special requirement that, for a predicate P to be in the JEO frame, it must satisfy the equivalence P(x, y) = P(jeo(x, y)).  We also have the MAO frame, which is defined as predicates which have a signature of [(0) (c 1)] but which don't satisfy that equality, which is named the "JEO-frame Equivalence"

## On ternary predicates

### 2019-03-13, #general

mi Hỏaqgīo
> % cutaq

nuogaiBOT
> 1–1/1 — cutaq + — <▯1, ▯2> are such that <x1, x2, x1> satisfy ternary relation ▯/3; ▯ does/is ▯/3 to themselves.

mi Hỏaqgīo
> Here's one that was added recently
>
> It's the first one I know of though
>
> 2-ary properties are useful for words like mia (___ satisfies property ___ with many things) and jeq (___ and ___ satisfy property ___ with the same thing)
> 3-ary properties aren't useful for much, as far as we've discovered


## On the low tone

### 2019-03-13, #general
mi Hỏaqgīo
> Here's how :t6: works:
> Both :t6: and :t7: serve to create adverbials. An adverbial is a part of a sentence that makes a claim about the sentence itself (not its text, but its content).
>
> Everything in Toaq is done with predicates, and adverbials are no different. Ultimately an adverbial always does its thing by taking the entire Toaq sentence, pretending is has a :t5: tone (that generates propositions) and sticking it into the first place of a predicate.
>
> For example:
>
> "Shie jí rào kôi hó"
>
> Here, the rao with the :t6: grabs the entire rest of the sentence, throws it into a :t5: clause, then passes it as the x1 place to the predicate rao.  :t6: also has the effect of taking the following noun and passing it to the predicate as the x2 place.
>
> Thus the sentence is equivalent to:
>
> "Rao (shîe jí na) kôi hó"
>
> With the originally top-level claim in parentheses
>
> It means "I am awake while he/she is walking"

## On the necessity of the tones

### 2019-03-13, #general
mi Hỏaqgīo
> :t6: and :t7: can be excluded without too much difficulty
>
> :t3: might be possible to get rid of, but it would take some work to prove that. It doesn't just expand to something else like those other two tones do
>
> :t1:, :t2:, :t4:, :t5:, and :t8: are all 100% necessary

## On implications

### 2019-03-14, #general

mi seaqtaq
> Those are lojban words
>
> rinka=ca
>
> nibli=lica
>
> krinu≈mu kui (edited)

mi brunofrancosalamin
> thanks!

mi seaqtaq
> jum [vietoaq]

[...]

mi seaqtaq
> oh woops lica was supposed to be luca
> i always mix those up

## On ordinal compounds

### 2019-03-14, #general


mi Hỏemāı
> I have written a possible lesson 2.
>
> Also I need to add the ordinal compounds to the official dictionary.

You make ordinal compounds by concatenating the number name with the (ko) predicate:

> shiko
>
> guko
>
> saqko
>
> ...

## On laughter and the lambda quantifier (ja)

### 2019-03-16, #general

mi Heutijeqtua
> jajajaja

mi 🍵
> hahahaha*
>
> we’re in Toaqistan, sir

mi Heutijeqtua
> sorry, my spanish showed XD

mi 🍵
> you don’t necessarily want to laugh with the lambda variable quantifier
>
> unless it’s ja dó ja dó ja dó ja dó

mi Heutijeqtua
> would that mean XXXX?

mi 🍵
> it would
>
> kind of
>

mi 🍵
> although each of the X’s would be distinct
>
> and the whole wouldn’t really mean anything without context
>

BREAK [...]

mi Heutijeqtua
> O.O, I didn't realize that each ja do would represent a different variable

mi 🍵
> it always does
>
> so, how do you differentiate between their values? by position?

mi 🍵
> ?cheon subjir lit seam ja pob ja pob
>

mi nuogaiBOT
> chẻo súqjī lî sẻaq ja póq ja póq

mi 🍵
> = we are reciprocal in relation λxy. x has sex with y
>
> = we have sex with each other
>
> ?= cheon seam subjir
>

mi nuogaiBOT
> = chẻo sẻaq súqjī

mi 🍵
> ja binds variables
>

mi Heutijeqtua
> oooh, I see! and the variables are predicates?
>
> like poq and do?
>

mi 🍵
> no
>
> I mean, yes
>
> but poq isn’t a variable predicate
>
> if you say ja póq, then poq won’t refer to that
>
> but ja dó will make do refer to the lambda variable
>

mi Heutijeqtua
> oh, its the lambda calculus
>
> ok, the first ja means the x, the second ja means the y
>
> ja
>
> I don't understand what ja do/ refers to
>

mi 🍵
> do doesn’t mean anything until it’s bound by a quantifier
>

mi Hỏemāı
> %miu lẻo jí lî nủo ja dó
>

mi nuogaiBOT
> (lẻo {jí [lî <nủo (ja dó)>]})
>
> [℩𝐽 : ji(𝐽)] leo(𝐽, {λ𝑋 nuo(𝑋)}).
>

mi 🍵
> %miu lẻo jí lî nủo ja póq
>

mi nuogaiBOT
> (lẻo {jí [lî <nủo (ja póq)>]})
>
> [℩𝐽 : ji(𝐽)] leo(𝐽, {[λ𝑃 : poq(𝑃)] nuo(𝑃)}).
>

## On Transitive and intransitive verbs
### 2019-03-16, #general

mi Heutijeqtua
> why are there two different words for "gather", one transitive (tua tijeq) and the other intransitive?
>
> wait, I think I misunderstood the idea. is it the tua that makes tijeq transitive?
>
mi Hỏaqgīo
> Intransitive is used like "The marbles all gathered together at the bottom of the bucket"
>
> Transitive is used as "I gathered together some firewood"
>
> The second kind has a place for a person making the things gather
>
> And yes, it's tua that makes it so
>

mi Heutijeqtua
> I see, thanks!
>
> could you use the intransitive tijeq in a toaq sentence?
>

mi Hỏaqgīo
> Sure!
>
> "Tijēq sa róai deo ní da"
>
> Would you like me to give the translation or do you want to work it out?
>

[...]

mi seaqtaq
> It would be better with sho tijeq
>

mi Hỏemāı
> tıjēq only means "to be in the same place", not "to gather" (which would be sho tỉjēq). But also, note that there is a root for "gather" (kueq)
>

mi Hỏaqgīo
> Oh
>
> Then let me try again
>
> "Kueq sa róai deo ní da."
>
> Also, bear in mind that kueq and deo both have a :t4:, i just can't type it
>
> The translation is: "Eight children gather here."
>
