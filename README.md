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
* [Content.InlineTitle](#contentinlinetitle)
* [Inline.model](#inlinemodel)

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

* [enum.attr.Heading.data-type](#enumattrheadingdata-type)

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
* [Inline.model](#inlinemodel)

# Content.Foreign

Children:

* [Inline.model](#inlinemodel)

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
* [Inline.model](#inlinemodel)

# Content.Title.optional

Children:

* [Common.attrib](#commonattrib)
* [Flow.model](#flowmodel)

# Content.Note.attrs

Children:

* [Common.attrib](#commonattrib)
* Text.datatype
* Text.datatype
* [Content.Title.optional](#contenttitleoptional)

# Content.Note

Children:

* [Content.Note.attrs](#contentnoteattrs)
* [Flow.model](#flowmodel)

# Content.Equation

Children:

* [Content.Note.attrs](#contentnoteattrs)
* [Flow.model](#flowmodel)

# Content.Problem

Children:

* [Content.Note.attrs](#contentnoteattrs)
* [Flow.model](#flowmodel)

# Content.Solution

Children:

* [Content.Note.attrs](#contentnoteattrs)
* [Flow.model](#flowmodel)

# Content.Commentary

Children:

* [Content.Note.attrs](#contentnoteattrs)
* [Flow.model](#flowmodel)

# Content.Exercise

Children:

* [Content.Note.attrs](#contentnoteattrs)
* [Content.Problem](#contentproblem)
* [Content.Solution](#contentsolution)
* [Content.Commentary](#contentcommentary)

# Content.Example

Children:

* [Content.Note.attrs](#contentnoteattrs)
* [Flow.model](#flowmodel)

# Content.Newline.class

Children:

* [Content.Note.attrs](#contentnoteattrs)
* Number.datatype
* [br](#br)

# div-span-list.attrs

Children:

* Text.datatype
* Text.datatype
* [enum.attr.ul.data-bullet-style](#enumattruldata-bullet-style)
* [enum.attr.ol.data-number-style](#enumattroldata-number-style)
* [Content.Note.attrs](#contentnoteattrs)

# Content.DivList

Children:

* [div-span-list.attrs](#div-span-listattrs)
* [Content.DivListItem](#contentdivlistitem)

# Content.DivListItem

Children:

* [Content.Note.attrs](#contentnoteattrs)
* [Flow.model](#flowmodel)

# Content.SpanList

Children:

* [div-span-list.attrs](#div-span-listattrs)
* [Content.SpanListItem](#contentspanlistitem)

# Content.SpanListItem

Children:

* [Content.Note.attrs](#contentnoteattrs)
* [Inline.model](#inlinemodel)

# Content.ListWithTitle

Children:

* [id.attrib.required](#idattribrequired)
* [id.attrib](#idattrib)
* [Inline.model](#inlinemodel)
* [ul](#ul)
* [ol](#ol)
* [Content.DivList](#contentdivlist)

# Content.ParaWithTitle

Children:

* [p.attlist](#pattlist)
* [Content.InlineTitle](#contentinlinetitle)
* [Inline.model](#inlinemodel)

# Content.Alternates.class

Children:

* [id.attrib.required](#idattribrequired)
* Text.datatype
* [img](#img)
* [Content.ImageWithThumbnail](#contentimagewiththumbnail)

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
* [Inline.model](#inlinemodel)

# u.attlist

Children:

* [Common.attrib](#commonattrib)

# ol.attlist

This element extends an existing defition

# Content.Glossary

Children:

* [dl](#dl)

# Content.InlineTitle

Children:

* [Inline.model](#inlinemodel)

# Block.class

This element extends an existing defition

Children:

* [section](#section)
* [figure](#figure)
* [Content.Note](#contentnote)
* [Content.Equation](#contentequation)
* [Content.Exercise](#contentexercise)
* [Content.Example](#contentexample)
* [Content.DivList](#contentdivlist)
* [Content.ListWithTitle](#contentlistwithtitle)
* [Content.ParaWithTitle](#contentparawithtitle)
* [Content.Media.class](#contentmediaclass)
* [Content.Alternates.class](#contentalternatesclass)
* [Content.Newline.class](#contentnewlineclass)
* [Content.FootnoteRefs](#contentfootnoterefs)

# Inline.class

This element extends an existing defition

Children:

* [u](#u)
* [Content.SpanList](#contentspanlist)
* [Content.Space](#contentspace)
* [Content.FootnoteNumber](#contentfootnotenumber)
* [Content.Term](#contentterm)
* [Content.Foreign](#contentforeign)
* [Content.Media.class](#contentmediaclass)
* [Content.Alternates.class](#contentalternatesclass)
* [Content.Newline.class](#contentnewlineclass)

# section

Children:

* [section.attlist](#sectionattlist)
* [Heading.class](#headingclass)
* [Flow.model](#flowmodel)

# section.attlist

Children:

* [Common.attrib](#commonattrib)
* Number.datatype
* Text.datatype
* Text.datatype

# figure

Children:

* [figure.attlist](#figureattlist)
* [Content.Title.optional](#contenttitleoptional)
* [figcaption](#figcaption)
* [Flow.model](#flowmodel)

# figure.attlist

Children:

* [Common.attrib](#commonattrib)
* Text.datatype

# figcaption

Children:

* [figcaption.attlist](#figcaptionattlist)
* [Content.InlineTitle](#contentinlinetitle)
* [Flow.model](#flowmodel)

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
