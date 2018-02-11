# smallLatinSuperfix

This program is a converter that allows you to superfix a set of 13 american english alphabet letters onto any of the 26 american english alphabet letters.

Only these letters can be used- aeioucdhmrtvx - meaning as long as your superfixed word has those letters in it you should have no issue.

Full set of output candidates (you can just copy and paste these)
aͣ bͣ cͣ dͣ eͣ fͣ gͣ hͣ iͣ jͣ kͣ lͣ mͣ nͣ oͣ pͣ qͣ rͣ sͣ tͣ uͣ vͣ wͣ xͣ yͣ zͣ
aͤ bͤ cͤ dͤ eͤ fͤ gͤ hͤ iͤ jͤ kͤ lͤ mͤ nͤ oͤ pͤ qͤ rͤ sͤ tͤ uͤ vͤ wͤ xͤ yͤ zͤ
aͥ bͥ cͥ dͥ eͥ fͥ gͥ hͥ iͥ jͥ kͥ lͥ mͥ nͥ oͥ pͥ qͥ rͥ sͥ tͥ uͥ vͥ wͥ xͥ yͥ zͥ
aͦ bͦ cͦ dͦ eͦ fͦ gͦ hͦ iͦ jͦ kͦ lͦ mͦ nͦ oͦ pͦ qͦ rͦ sͦ tͦ uͦ vͦ wͦ xͦ yͦ zͦ
aͧ bͧ cͧ dͧ eͧ fͧ gͧ hͧ iͧ jͧ kͧ lͧ mͧ nͧ oͧ pͧ qͧ rͧ sͧ tͧ uͧ vͧ wͧ xͧ yͧ zͧ
aͨ bͨ cͨ dͨ eͨ fͨ gͨ hͨ iͨ jͨ kͨ lͨ mͨ nͨ oͨ pͨ qͨ rͨ sͨ tͨ uͨ vͨ wͨ xͨ yͨ zͨ
aͩ bͩ cͩ dͩ eͩ fͩ gͩ hͩ iͩ jͩ kͩ lͩ mͩ nͩ oͩ pͩ qͩ rͩ sͩ tͩ uͩ vͩ wͩ xͩ yͩ zͩ
aͪ bͪ cͪ dͪ eͪ fͪ gͪ hͪ iͪ jͪ kͪ lͪ mͪ nͪ oͪ pͪ qͪ rͪ sͪ tͪ uͪ vͪ wͪ xͪ yͪ zͪ
aͫ bͫ cͫ dͫ eͫ fͫ gͫ hͫ iͫ jͫ kͫ lͫ mͫ nͫ oͫ pͫ qͫ rͫ sͫ tͫ uͫ vͫ wͫ xͫ yͫ zͫ
aͬ bͬ cͬ dͬ eͬ fͬ gͬ hͬ iͬ jͬ kͬ lͬ mͬ nͬ oͬ pͬ qͬ rͬ sͬ tͬ uͬ vͬ wͬ xͬ yͬ zͬ
 aͭ bͭ cͭ dͭ eͭ fͭ gͭ hͭ iͭ jͭ kͭ lͭ mͭ nͭ oͭ pͭ qͭ rͭ sͭ tͭ uͭ vͭ wͭ xͭ yͭ zͭ
 aͮ bͮ cͮ dͮ eͮ fͮ gͮ hͮ iͮ jͮ kͮ lͮ mͮ nͮ oͮ pͮ qͮ rͮ sͮ tͮ uͮ vͮ wͮ xͮ yͮ zͮ
aͯ bͯ cͯ dͯ eͯ fͯ gͯ hͯ iͯ jͯ kͯ lͯ mͯ nͯ oͯ pͯ qͯ rͯ sͯ tͯ uͯ vͯ wͯ xͯ yͯ zͯ

# Use Case
Using this program is easier than copying and pasting each of the letters in the chart above into place. To use it,
- Open the program
- Type in a word (to be superfixed) and press enter
- Type in the main word and press enter
- The result will be copied to your clipboard.

Here is an example of problematic output
```
input:
> dream
> memes
```
```
output:
> mͩeͬmͤeͣsͫ
```
This was successful because it has the right amount of letters and all the superfixed letters are in the set of latin characters that can be superfixed.

Here is an example of problematic output
```
input:
> hello
> goodday
```
```
output:
> gͪoͤoddͦ
```

This output is due to how only certain letters can be superfixed. The superfixed word is also shorter than the main word so not all letters will be copied.

Don't use this if you're evil.
