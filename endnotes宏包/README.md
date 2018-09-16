endnotes-sty
============

base on John Lavagnino 's  endnotes.sty and Ulrich Dirr's   hyperendnotes.sty , the endnotes.sty for you to create  endnote after chapter and the link is correct.

#1. endnote{}
    add the endnote

#2. showendnotes
    insert the endnotes


#3. you can renewcommand the endnotemark and the endnotemarkback-----it is the mark style in the endnotes
\renewcommand\endnotemark{[\theenmark]}
\renewcommand\endnotemarkback{[\theenmark]}

## attention
this style file use a strange way maybe a better way to handle the endnotes-sty
because the author is not puzzled by the tex  token rule , it is really hard to understand .
now it work fine, and the link forward or backward is all work fine , the the endnotes split with the
chapter is also work fine ,
### but the endnotemark and endnotemarkback you better modify with some text
not with the tex command.
