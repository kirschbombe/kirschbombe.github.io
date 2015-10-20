---
layout: default
title: Digital scholarly editing
---
#Digital scholarly editing: a brief tour of practices, projects, and resources.


> _…the digital “critical representation” of any work “does not accurately (so to speak) mirror its object; it consciously (so to speak) deforms its object… [opening] the doors of perception toward new opportunities and points of view.”_ --Jerome McGann (_Radiant Textuality_)

###Editorial rationales
Let's first consider a few historical approaches to scholarly editing:

  * Literal: documentary editing
  * Intentionalist (Bowers): idea of the copy-text and the eclectic text (readings drawn from multiple witnesses)
  * Genetic: more inclusive, pre-publication versions (French school), also Genette's paratext (that which sits outside the main text)
  * Social text (McGann): critical of intentionalist editing; texts are social, historically situated, as are the author's intentions (enter versioning)

In many cases, digital scholarly editing attempts to recreate the rationales of these and other editorial practices, taking advantage of the digital for certain activities, such as:  1) markup and presentation of the text structure and to tag/annotate contextual info like people, places, events, and dates;  2) to give context using links, metadata, and encoded editorial notes;  3) to make the texts interactive with hypertext, hovers and pop-ups for editorial info, and user selected views);  4) and for collation and versioning to compare and analyze texts.

_A few example projects_

* [Chymistry of Isaac Newton](http://webapp1.dlib.indiana.edu/newton/browse;jsessionid=47908DE72B75BAEFFA1E3A83BA29858D):  _Note the use of normalized vs. diplomatic transcriptions._ 
* [Lowell's "LETTER FROM A VOLUNTEER IN SALTILLO”](http://www.scholarlyediting.org/2015/editions/lowelledition_wit-Courier.html):  _Note the presentation of multiple witnesses in one eclectic text using TEI's parallel segmentation._ 
* [Shelly-Godwin Archive](http://shelleygodwinarchive.org/sc/oxford/frankenstein/notebook/a#/p11):  _Note the choice of views, Mary Shelley’s hand or Percy Shelley’s hand._ 
* [Petrus Plaoul](http://petrusplaoul.org/indexsearch/displayindexsearch.php?index=name&type=Classical&name=Anaxagoras): _Requires login, but the Index will get you access to some of the text. click on the “Paragraph Menu” at the end of a paragraph and try some of the “Comparison Tools”._ 
* [Selected Poems by the Baroness Elsa von Freytag-Loringhoven](http://digital.lib.umd.edu/transition/poem?pid=umd:55435): _Example of the Versioning Machine_ 

Beyond transferring editing practices from print to digital, we can expand our understanding of what it is to create an edition. Digital editions might highlight other aspects of a text, such as the physical characteristics of material objects or perhaps place, movement, and/or time using mapping/timeline interfaces, multi-spectral photography, and annotation of illustrations/images. Editions can also make use of the rich store of encoded data (our text is our data, after all) by visualizing contextual information, quires and gatherings, textual variation between witnesses, etc.

<iframe width="600" height="400" src="https://fontane-nb.dariah.eu/tei-conf/heb/" frameborder="0"></iframe>

* [Theodore Fontane Notebooks](https://fontane-nb.dariah.eu/tei-conf/): _Here you can view various visualizations generated from the encoded notebooks._

###Digital Scholarly Editing Activities (and related tools/resources)

Transcribing or OCRing

* [T-Pen](http://t-pen.org/TPEN/): web-based platform for transcribing manuscript material
* [Juxta Editions](http://www.juxtaeditions.com): publishing platform for digital editions, supports transcription workflow
* [Tesseract](https://code.google.com/p/tesseract-ocr/): ope source OCR engine, utilizes training files and language libraries, best for early modern texts, fraktur, etc.
* [Abbyy FineReader](http://www.abbyy.com): Commercial OCR software

Encoding and markup

* [Text Encoding Initiative](http://www.tei-c.org/index.xml) (TEI): XML schema and guidelines for encoding text
* [oXygen](http://www.oxygenxml.com): XML Editor for use with TEI
* [Juxta Editions](http://www.juxtaeditions.com): publishing platform for digital editions, supports encoding workflow
* [T-Pen](http://t-pen.org/TPEN/): can do pre-formatted encoding of texts while transcribing
* [TextGrid](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0CB4QFjAAahUKEwj86_zFhdLIAhUC1WMKHcqfAtc&url=https%3A%2F%2Ftextgrid.de%2Fen&usg=AFQjCNHkkXsDW-t5s5kUGCa5gfw4lA_3lQ): repository and collaboration tool for digital editions
* [GitHub](https://github.com): version control and collaboration; great if multiple people are working on the same files
* [Sublime Text](https://www.sublimetext.com): Dawn's text editor of choice
* [XML Editey](http://www.editey.com): web-based XML editor used with Google Drive

Collation and versioning

* [JuxtaCommons](http://juxtacommons.org): web-based collation platform (different from JuxtaEditions)
* [The Versioning Machine](http://v-machine.org): framework for publishing eclectic texts encoded with TEI parallel segmentation (undergoing an update!)

Publishing

* [TAPAS Project](http://tapasproject.org): repository and publishing platform for TEI encoded texts
* [Scholarly Editing](http://www.scholarlyediting.org): open source journal publishing small digital editions; they will work with you to publish your small edition!
* [Juxta Editions](http://www.juxtaeditions.com): publishing platform for digital editions
* [The Versioning Machine](http://v-machine.org): framework for publishing eclectic texts encoded with TEI parallel segmentation
* [GitHub](https://github.com) / [GitHub Pages](https://pages.github.com): host, collaborate on, and publish your TEI encoded texts and transformation stylesheets
