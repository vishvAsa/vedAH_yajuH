+++
title = "Metrical restoration"
+++

+++(Source - https://liberalarts.utexas.edu/lrc/rigveda/RV00.php . Copied here for easy search and reference.)+++ 

The form in which the Rigveda was handed down by Indian tradition, the saṃhitā text, applied later rules of sound combination throughout that systematically destroyed the metrical form of the poems. These inappropriate combinations have to be resolved before the text can be read, and they frequently obscure meaning. For illustration of the many ways in which the later editorial process distorted and obscured the original, see section 45.1 of our online course on the language of the Rigveda, Ancient Sanskrit Online.

+++(áhann áhim ánu apás tatarda prá vakṣáṇā abhinat párvatānām. The Atharvaveda (AVP 13.6.1) repeats the verse, but replaces the plural noun vakṣáṇās with a participle, vakṣámānās. This not only destoys the metre of the line but makes no grammatical sense, and is clearly simply an error.)+++


The approach taken by van Nooten and Holland to restore the original form of the poems was exclusively systematic. A precise set of procedures was applied, which owed their origin to suggestions made by a number of nineteenth-century Rigvedic scholars, among them Kuhn, Bollensen, Oldenberg, Grassmann, and E. Vernon Arnold. These procedures were:

- **Restoration of lost syllables**. A large number of inappropriate vowel combinations are resolved, both within and between words. For example, the vocative "índraagnī" is restored for "índrāgnī" at 6.059.2b, where the metre clearly shows that the compounded name of the two deities retained the original four syllables. (Note: an alternative restoration, "índrāagnī", with dual ending to both members, is preferred by others, including Grassmann.)
- **Vocalization of the semivowel**. There are innumerable instances where the semivowels y and v in the ancient editions clearly have syllabic value, and were originally vowels. The corresponding vowel (i before y, u before v) has been inserted. This single procedure alone restores the correct syllable count to a large number of verse lines. Where the semivowel resulted from an ancient internal sandhi convention it has simply been removed and the original vowel restored: vyáñjana and abhyáñjana at 8.078.02 are restored to viáñjana and abhiáñjana.+++(5)+++
- **Marking of disyllabic long vowels**. A number of long vowels, including the diphthongs e and o, in some words always have disyllabic value. Where the origin of the dissyllable remains uncertain this is indicated by use of a tilde over the vowel. Where the origin of the dissyllable is clear the original form has been restored.
- **Vowel insertion**. The metre can frequently be restored by inserting a dropped vowel into some word forms. For example, the genitive/locative form "pitrós" should always be read "pitarós"+++(5)+++, and neuter nouns in "-man" and "-van" regularly had later syncopation applied to oblique cases by the ancient editors which is here restored. The name "índra", similarly, is often trisyllabic, "índara".+++(5)+++
- **Correction of representation of "iva"**. This is consistently given as disyllabic by the ancient editors, but frequently should read "va" in the Rigveda (see section 41.1 of Ancient Sanskrit Online).
- **Quantitative restoration**. Where metrical irregularity was consistently found in the representation of the same word or morphological form, it was clear that that word or form had suffered in the transmission of the text. For example, the word "pāvaká" is always metrically to be read "pavāká".+++(5)+++ Long vowels occurring in a number of dual forms have been revised for the same reason: "āśate" is given for "āśāte", "rāsathām" for "rāsāthām".
- Use of the rest sign (midline dot). This editorial sign was adopted to mark a pause equivalent to the length of a syllable.

A table of specific restorations can be found at the end of this introduction.

## Interpreting van Nooten and Holland's Electronic Text
Two electronic versions of the Rigveda were provided on the diskette. In addition to the metrically restored version (RV), which forms the basis for our online edition, the unrestored Aufrecht (RVA) text was also supplied. Included also were miscellaneous DOS applications -- variously dated 1986-1990 -- and some online (README) documentation.

Our first problem was identifying the character set used in the metrically restored text files. The Harvard documentation describes an "International Codepage for Sanskrit diacritics," extending the ASCII character set, which was supposedly used to transcribe the text; but the files use 20 non-ASCII characters, many with high frequency, that are not described. Later, two ASCII code points (42 and 46) were found to represent non-ASCII characters, "bolle" and "midline dot", in the metrically restored text -- though not elsewhere. (Actually, ASCII code point 42 was thus used only in the first book; in books 2-10, the non-ASCII code point 174 represents "bolle".) Finally, in the Codepage description, "r underdot acute" is listed twice, at two different code points; the first of these turned out to be unused.

Our second problem was to identify those 20 undefined characters. The "International Codepage" as described corresponds in some ways to the "CSX" and "CSX+" Sanskrit codepages that may be found on the Internet. Some of the 20 undefined characters can be matched with these codepages; however, there are numerous differences between CSX(+) and both the described Codepage and the characters that must be inferred from their context in the RV files. Ultimately, given incomplete and sometimes inaccurate documentation, we could fully decode the [inconsistent] electronic RV files only by trial and error.

Third, we faced the problem that no font then known to us (none was included on the diskette) could properly render the Rigveda text -- even if our own subsequent editing had not required the specification of yet more code points, not used by van Nooten and Holland. We decided that the only reasonable option was to convert the entire text to the Unicode (ISO/IEC 10646) character set, for which many standard fonts are available.

Our fourth problem was to identify and correct a range of errors in the electronic RV files. For example, several apparently random (transmission?) data errors were found. Several lines were found to be missing, and others were misnumbered or duplicated. Such errors, where identified, were corrected by hand.

Fifth, for publication online we selected the HTML web page format (using Unicode UTF-8) in the belief that this represents the simplest and most effective means of free, worldwide distribution. In this way, we could publish our results and simultaneously facilitate Rigveda research by others -- goals no doubt shared by van Nooten and Holland, now 14+ years ago.

Errors aside, we owe van Nooten and Holland a debt of gratitude for publishing the text in electronic form. Without their pioneering work, we would not have tackled this project.

## Editing the Metrically Restored Text
Subsequent examination of the [repaired] contents of the RV files revealed a significant number of differences between the electronic and the printed text, the electronic version appearing to represent an earlier stage of the authors' editorial process (although some errors occurring in the printed text were not found in the electronic text). Our own online text, therefore, is a significantly edited version of the electronic text as issued by Harvard. The textual alterations that we have made take the following forms:

- Corrections to errors found in both the electronic and the printed text, for example "vā́yo" for the midline vocative "vāyo" at 1.135.07a. Some of these, like "vr̥tráputra" for "vr̥tráputrā" at 1.032.09a and "ávasā ā́" for "avasā́ ā́" at 3.053.20d, derive from the process of metrical restoration. A few derive from mistakes in Aufrecht's edition, at least one of which, "te" for "té" at 7.001.04a, has been generally reproduced since.
- Corrections to errors found in the electronic version, which were already corrected in the printed text. For example, there were a number of terminal grave accents reflecting an interim stage in the metrical analysis, like "vāvr̥dhānò" at 5.002.12a.

The text has been largely brought into line with the editors' declared intentions in their Introduction and Metrical Notes. Several inconsistencies remained in the electronic version, not all of which had been corrected in the printed text.

Additionally, we have taken the liberty of overruling a traditional irregular Rigvedic sandhi, replacing all ī̀ with ī́ for clarity; van Nooten and Holland's printed text does this at 1.080.03a, but not elsewhere. We have also restored the onomatopoeic "jájhjhatīs" at 5.052.06d from the devanāgari texts.

The primary purpose of our online edition is to show the original linguistic and poetic style of the Rigveda, and to make the text accessible in this form and easy to read. In addition, as is to be expected of an innovative and highly complex piece of work, some errors remain in van Nooten and Holland's attempt. By putting the metrically restored text online we hope to facilitate its further improvement and correction by scholars; accordingly, scholars are invited to suggest further corrections using the "Send comments" e-mail link at the bottom of this or any other LRC web page, or by contacting Karen Thomson directly.

## Comparing the Restored Text with the Ancient Texts
An interlinear electronic edition, giving (a) the traditional saṃhitā text, (b) its ancient word-by-word analysis (the Pada 'word' text - but see below, 'Restoration or Conservation?'), and (c) the van Nooten and Holland metrically restored text in parallel, can be found on the TITUS website, providing a useful resource for study of the restoration process. Many of the corrections that we have made to van Nooten and Holland's text remain uncorrected on the TITUS website, and no doubt we shall have missed other errors identified by the TITUS editors. A complete list of our corrections is available upon request.

## Table of Restorations
An alphabetical table of all the changes flagged in the text by van Nooten and Holland's editorial bolle (°) follows. Many restored forms were not so marked -- the printed text makes use of italics to indicate restorations -- and we have supplemented the table by marking other restorations with our own editorial sign: +. A few additional forms that might be puzzling are also included here.

- apriṇād	 	aprīṇād
- áśvavatyā	 	áśvāvatyā
- asmábhya	 	asmábhyam
- ānayitā́	 	ānetā́
- ā́yu	 	ā́yuḥ
- āśate	 	āśāte
- ā́śathe	 	ā́śāthe
- āsate	 	āsāte
- āsathe	 	āsāthe
- āsī3t	 	āsīt
- āsī́3d	 	ā́sīd
- índara-	 	índra-
- ulok-	 	u lok-
- cakrate	 	cakrāte (Pada: iti)
- jyáyiṣṭha-	 	jyéṣṭha-
- túbhya	 	túbhyam
- trā́sithām	 	trā́sīthām
- dadhathe	 	dadhāthe
- dáyiṣṭhaḥ	 	déṣṭhaḥ
- dayiṣṇá-	 	deṣṇá-
- dr̥̄ḷhá-	 	dr̥ḷhá-
- druṇānó	 	drūṇānó
- dháyiṣṭha-	 	dhéṣṭha-
- dhyānó	 	(see hyāná-)
- nayit-	 	net-
- nr̥̄nā́m	 	nr̥nā́m
- pavāká-	 	pāvaká-
- pā́taram	 	pā́tram
- pitaró-	 	pitró-
- pipāya	 	pīpāya
- praṇayit-	 	praṇet-
- prámatī	 	prámatyā
- prayitā́ro	 	pretā́ro
- práyiṣṭha-	 	préṣṭha-
- priṇa-	 	prīṇa-
- priṇītá	 	prīṇītá
- bhriṇánti	 	bhrīṇánti
- matī́	 	matyā́
- mandaró	 	mandró
- mártia-	 	márta-
- mahinā́	 	mahnā́
- máhya	 	máhyam
- mā́ ū	 	mó (Pada: iti)
- mr̥̄ḷ-	 	mr̥ḷ-
- yáyiṣṭha-	 	yéṣṭha-
- yásmi	 	yásmin
- yuñjathām	 	yuñjāthām
- yuñjathe	 	yuñjāthe
- rāsathām	 	rāsāthām
- rudará	 	rudrá
- ródasīyoḥ	 	ródasyoḥ
- ródasoḥ	 	ródasyoḥ
- 'va	 	-iva
- vajri	 	vajrin
- vindatī3m̐	 	vindatīm̐
- ṣkr̥ṇvanti	 	kr̥ṇvanti
- śráyaṇi-	 	śréṇi-
- śráyiṣṭha-	 	śréṣṭha-
- śriṇāná-	 	śrīṇāná-
- śriṇītana	 	śrīṇītana
- śrutárṣim	 	śrutár̥ṣim
- sásmi	 	sásmin
- sáhyase	 	sáhīyase
- sumatī́	 	sumatyā́
- sumádūdhnīḥ	 	smádūdhnīḥ
- sumán	 	smán
- sumr̥̄ḷīk-	 	sumr̥ḷīk-
- svāná-	 	suvāná-
- hárīhá	 	hárī ihá (Pada: iti)
- hyāná-	 	hiyāná-

## Restoration or Conservation?
N.B. This section contains a brief discussion of some modern editorial revisions to the ancient texts, the loci of which are flagged in our text with a dagger (†) hotlinked to here.

We owe the text that we have, in its two forms, to the painstaking editorial work of Max Müller in the middle of the nineteenth century. Although fully aware that neither the Saṃhitā nor the Pada was a true representation of the original, he argued against making any changes to them.+++(5)+++ "What would a Greek scholar give, if he could say of Homer that his text was in every word, in every syllable, in every vowel, in every accent, the same as the text used by Peisistratos in the sixth century B.C.!" (Vedic Hymns, Oxford, 1891, p.xlvi). In attempting a reconstruction of the original metrical form of these ancient poems van Nooten and Holland have departed from the form of the text that we have inherited from ancient scholastic tradition, according to the systematic procedure outlined above.

In other respects, however, their edition of the Rigveda is conservative, and would meet with the approval of its primary editor. Van Nooten and Holland have not imported most of the conjectural readings of modern scholarship, with the exception of the revision throughout of the incongruous form u loká to uloká, an emendation which is based on strictly linguistic arguments. So that the reader can assess these conjectural readings (the different reading can be found in the TITUS version of the Pada text), they are briefly discussed below.

A number of the changes remain open to debate. The readings sápāti for sá pāti at 5.012.06b (after Roth) and cakrámāma for ca krámāma at 6.049.15d are possible alternatives. The change from śmaśā́ rudhat to śmaśā́ru dhat at 10.105.01b (Oldenberg) is endorsed by Manfred Mayrhofer in his recent dictionary, but not the change from áti riktam (an aorist form) to átiriktam at 8.058.03d, which creates an earlier occurrence of the past participle than is otherwise attested. The transferring of the initial r to the end of the previous word at 1.069.08b and 6.031.03d (changing rápāṃsi to ápāṃsi) seems less compelling than at 8.039.02c and 10.040.07c, where the two uniquely occurring forms of rárāvan are reassigned to árāvan; the second is followed by Geldner in his translation but not the first. The change of verb at 8.099.06c, giving śrathayanta for śnathayanta after the medieval scholar Sāyaṇa, perhaps presents problems for a text that was orally transmitted.

All scholars however agree that at 1.070.07b ca rátham is an error for carátham. This was first pointed out by the nineteenth-century scholar Benfey, and acknowledged by Max Müller, although he could not approve making the correction, nor indeed any other: "although I have no doubt that the original poet said sthātúḥ carátham, I should be loath to suppress the evidence of the mistake and alter the Pada text from ca rátham to carátham. The very mistake is instructive, as showing us the kind of misapprehension to which the collectors of the Vedic text were liable, and enabling us to judge how far the limits of conjectural criticism may safely be extended" (op. cit. p. lxxiv).+++(5)+++

## Late Additions to the Text: the Popular Rigveda
The poems of the Rigveda were produced over a considerable period of time. Although critics remain divided in their view as to the historical relation of its different parts, there is general agreement with E. Vernon Arnold's identification of passages that he categorized as "popular," which he describes as later additions to the original collection. Many of these are found in Book 10, but every book contains at least some "popular" passages.

Our online edition of the text is the first to mark these passages, which we have divided into two categories. When Arnold's assignment of passages to the Popular Rigveda is based on linguistic evidence, the passages are distinguished by both color and smaller type size; but passages that Arnold classified as "popular" for non-linguistic reasons (position, meter, supposed subject matter, repetion in later collections) are distinguished by smaller type size alone. In addition, passages in which the linguistic evidence points to their "popular" nature, but which Arnold for the same non-linguistic reasons does not mark as "popular," are also identified by smaller type size in our text.