# Inline.class

This element extends an existing defition

Children:

* [math](#math)

true false
# id.attrib.required

Children:

* ID.datatype

# table.attlist

This element extends an existing defition

Children:

* Text.datatype
* Text.datatype
* Number.datatype
* Number.datatype

# caption

This element extends an existing defition

Children:

* [caption.attlist](#captionattlist)
* [Content.InlineTitle](#ContentInlineTitle)
* [Inline.model](#Inlinemodel)

# enum.attr.td.data-valign

# enum.attr.td.data-align

# td.attlist

This element extends an existing defition

Children:

* [enum.attr.td.data-valign](#enumattrtddata-valign)
* [enum.attr.td.data-align](#enumattrtddata-align)

# th.attlist

This element extends an existing defition

Children:

* [enum.attr.td.data-valign](#enumattrtddata-valign)
* [enum.attr.td.data-align](#enumattrtddata-align)

# enum.attr.ol.data-number-style

# enum.attr.ol.data-mark-suffix

# ol.attlist

This element extends an existing defition

Children:

* [enum.attr.ol.data-number-style](#enumattroldata-number-style)
* [enum.attr.ol.data-mark-suffix](#enumattroldata-mark-suffix)
* [enum.attr.ol.data-mark-suffix](#enumattroldata-mark-suffix)

# enum.attr.ul.data-bullet-style

# ul.attlist

This element extends an existing defition

Children:

* [enum.attr.ul.data-bullet-style](#enumattruldata-bullet-style)
* [enum.attr.ol.data-mark-suffix](#enumattroldata-mark-suffix)

# li.attlist

This element extends an existing defition

Children:

* Text.datatype
* Text.datatype
* Text.datatype

# enum.attr.img.data-media-type

# img.attlist

This element extends an existing defition

Children:

* [enum.attr.img.data-media-type](#enumattrimgdata-media-type)
* URI.datatype
* Length.datatype
* Boolean.datatype

# enum.attr.strong.data-effect

# strong.attlist

This element extends an existing defition

Children:

* [enum.attr.strong.data-effect](#enumattrstrongdata-effect)

# enum.attr.em.data-effect

# em.attlist

This element extends an existing defition

Children:

* [enum.attr.em.data-effect](#enumattremdata-effect)

# enum.attr.span.data-type

# span.attlist

This element extends an existing defition

Children:

* [enum.attr.span.data-type](#enumattrspandata-type)
* Text.datatype

# enum.attr.Heading.data-type

# Heading.attrib

This element extends an existing defition

Children:

* [enum.attr.Heading.data-type](#enumattrHeadingdata-type)

# div.attlist

This element extends an existing defition

Children:

* Text.datatype
* Text.datatype

# Content.Space

Children:

* Number.datatype
* Text.datatype

# Content.Term

Children:

* [id.attrib](#idattrib)
* [class.attrib](#classattrib)
* [Inline.model](#Inlinemodel)

# Content.Foreign

Children:

* [Inline.model](#Inlinemodel)

# Content.FootnoteNumber

Children:

* [id.attrib.required](#idattribrequired)
* URI.datatype
* Number.datatype

# Content.ImageWithThumbnail

Children:

* URI.datatype
* [img](#img)

# Content.FootnoteRefs

Children:

* [id.attrib.required](#idattribrequired)
* URI.datatype
* Number.datatype
* [Inline.model](#Inlinemodel)

# Content.Title.optional

Children:

* [Common.attrib](#Commonattrib)
* [Flow.model](#Flowmodel)

# Content.Note.attrs

Children:

* [Common.attrib](#Commonattrib)
* Text.datatype
* Text.datatype
* [Content.Title.optional](#ContentTitleoptional)

# Content.Note

Children:

* [Content.Note.attrs](#ContentNoteattrs)
* [Flow.model](#Flowmodel)

# Content.Equation

Children:

* [Content.Note.attrs](#ContentNoteattrs)
* [Flow.model](#Flowmodel)

# Content.Problem

Children:

* [Content.Note.attrs](#ContentNoteattrs)
* [Flow.model](#Flowmodel)

# Content.Solution

Children:

* [Content.Note.attrs](#ContentNoteattrs)
* [Flow.model](#Flowmodel)

# Content.Commentary

Children:

* [Content.Note.attrs](#ContentNoteattrs)
* [Flow.model](#Flowmodel)

# Content.Exercise

Children:

* [Content.Note.attrs](#ContentNoteattrs)
* [Content.Problem](#ContentProblem)
* [Content.Solution](#ContentSolution)
* [Content.Commentary](#ContentCommentary)

# Content.Example

Children:

* [Content.Note.attrs](#ContentNoteattrs)
* [Flow.model](#Flowmodel)

# Content.Newline.class

Children:

* [Content.Note.attrs](#ContentNoteattrs)
* Number.datatype
* [br](#br)

# div-span-list.attrs

Children:

* Text.datatype
* Text.datatype
* [enum.attr.ul.data-bullet-style](#enumattruldata-bullet-style)
* [enum.attr.ol.data-number-style](#enumattroldata-number-style)
* [Content.Note.attrs](#ContentNoteattrs)

# Content.DivList

Children:

* [div-span-list.attrs](#div-span-listattrs)
* [Content.DivListItem](#ContentDivListItem)

# Content.DivListItem

Children:

* [Content.Note.attrs](#ContentNoteattrs)
* [Flow.model](#Flowmodel)

# Content.SpanList

Children:

* [div-span-list.attrs](#div-span-listattrs)
* [Content.SpanListItem](#ContentSpanListItem)

# Content.SpanListItem

Children:

* [Content.Note.attrs](#ContentNoteattrs)
* [Inline.model](#Inlinemodel)

# Content.ListWithTitle

Children:

* [id.attrib.required](#idattribrequired)
* [id.attrib](#idattrib)
* [Inline.model](#Inlinemodel)
* [ul](#ul)
* [ol](#ol)
* [Content.DivList](#ContentDivList)

# Content.ParaWithTitle

Children:

* [p.attlist](#pattlist)
* [Content.InlineTitle](#ContentInlineTitle)
* [Inline.model](#Inlinemodel)

# Content.Alternates.class

Children:

* [id.attrib.required](#idattribrequired)
* Text.datatype
* [img](#img)
* [Content.ImageWithThumbnail](#ContentImageWithThumbnail)

# Content.Media.class

Children:

* [id.attrib.required](#idattribrequired)
* Text.datatype
* Text.datatype
* [img](#img)
* [iframe](#iframe)

# u

Children:

* [u.attlist](#uattlist)
* [Inline.model](#Inlinemodel)

# u.attlist

Children:

* [Common.attrib](#Commonattrib)

# ol.attlist

This element extends an existing defition

# Content.Glossary

Children:

* [dl](#dl)

# Content.InlineTitle

Children:

* [Inline.model](#Inlinemodel)

# Block.class

This element extends an existing defition

Children:

* [section](#section)
* [figure](#figure)
* [Content.Note](#ContentNote)
* [Content.Equation](#ContentEquation)
* [Content.Exercise](#ContentExercise)
* [Content.Example](#ContentExample)
* [Content.DivList](#ContentDivList)
* [Content.ListWithTitle](#ContentListWithTitle)
* [Content.ParaWithTitle](#ContentParaWithTitle)
* [Content.Media.class](#ContentMediaclass)
* [Content.Alternates.class](#ContentAlternatesclass)
* [Content.Newline.class](#ContentNewlineclass)
* [Content.FootnoteRefs](#ContentFootnoteRefs)

# Inline.class

This element extends an existing defition

Children:

* [u](#u)
* [Content.SpanList](#ContentSpanList)
* [Content.Space](#ContentSpace)
* [Content.FootnoteNumber](#ContentFootnoteNumber)
* [Content.Term](#ContentTerm)
* [Content.Foreign](#ContentForeign)
* [Content.Media.class](#ContentMediaclass)
* [Content.Alternates.class](#ContentAlternatesclass)
* [Content.Newline.class](#ContentNewlineclass)

# section

Children:

* [section.attlist](#sectionattlist)
* [Heading.class](#Headingclass)
* [Flow.model](#Flowmodel)

# section.attlist

Children:

* [Common.attrib](#Commonattrib)
* Number.datatype
* Text.datatype
* Text.datatype

# figure

Children:

* [figure.attlist](#figureattlist)
* [Content.Title.optional](#ContentTitleoptional)
* [figcaption](#figcaption)
* [Flow.model](#Flowmodel)

# figure.attlist

Children:

* [Common.attrib](#Commonattrib)
* Text.datatype

# figcaption

Children:

* [figcaption.attlist](#figcaptionattlist)
* [Content.InlineTitle](#ContentInlineTitle)
* [Flow.model](#Flowmodel)

# figcaption.attlist

Children:

* [id.attrib](#idattrib)

# cnx-pi

Children:

* [cnx-pi.attlist](#cnx-piattlist)
* cnx-pi.datatype

# cnx-pi.attlist

Children:

* Text.datatype

# Block.class

This element extends an existing defition

Children:

* [cnx-pi](#cnx-pi)
