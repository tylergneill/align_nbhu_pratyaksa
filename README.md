# align_nbhu_pratyaksa

A paragraph-level alignment of Joshi 1986's English translation of Nyāyabhūṣaṇa Pratyakṣapariccheda to Sanskrit text (Yogīndrānanda 1968), in spreadsheet form.

# how I'm making this

I first extracted the pre-OCRed content from Joshi's 1979 dissertation PDF, obtained on Shodhganga, and gradually did manual cleaning on it with Regex etc.

Later, I myself scanned the Joshi 1986 book to PDF, manually cropped out the footnote material, and OCRed batches of pages using Google Vision via Google Drive. After cleaning, the result was not very satisfactory.

Comparing the two, I also found instances where improper editing of the 1986 book resulted in loss of potentially important information from the 1979. I therefore decided with work with both.

To adjudicate differences, I separate the content of each of the two works based on the paragraph division of 1986 book, and use the diff-like function of BBEdit to reconcile differences between the two, one paragraph at a time.

The NBhū e-text was obtained anonymously through peers. I believe it may stem from Shodo Yamakami's work, but certainly only after being filtered through the work of others, I think Ernst Prets and Sylvia Stark. I've been slowly improving this and host it now on my pramana-NLP project (see separate repo).

Once the English has been reconciled (although not perfectly proofread, so mistakes do definitely stilll remain), I compare it to the Sanskrit, highlight in bold the parts of the English that directly correspond with Sanskrit, and also record a few notes on the side (some preliminary translation material included). The spreadsheet can be sorted either according to the order of the Sanskrit or Joshi's English presentation.

Eventually, I would like to use this table, plus my dissertation work on NBhū 104–154 (the part missing in Joshi) as a basis for my own full English translation of the Pratyakṣa chapter.